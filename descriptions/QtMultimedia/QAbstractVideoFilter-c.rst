.. sip:class-description::
    :status: todo
    :brief: Represents a filter that is applied to the video frames received by a VideoOutput type
    :digest: 23ec06a7025b44175d5c73a2d830ba78

The :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoFilter` class represents a filter that is applied to the video frames received by a `VideoOutput <https://doc.qt.io/qt-5/qml-qtmultimedia-videooutput.html>`_ type.

:sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoFilter` provides a convenient way for applications to run image processing, computer vision algorithms or any generic transformation or calculation on the output of a `VideoOutput <https://doc.qt.io/qt-5/qml-qtmultimedia-videooutput.html>`_ type, regardless of the source (video or camera). By providing a simple interface it allows applications and third parties to easily develop QML types that provide image processing algorithms using popular frameworks like OpenCV. Due to the close integration with the final stages of the Qt Multimedia video pipeline, accelerated and possibly zero-copy solutions are feasible too: for instance, a plugin providing OpenCL-based algorithms can use OpenCL's OpenGL interop to use the OpenGL textures created by a hardware accelerated video decoder, without additional readbacks and copies.

**Note:** :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoFilter` is not always the best choice. To apply effects or transformations using OpenGL shaders to the image shown on screen, the standard Qt Quick approach of using `ShaderEffect <https://doc.qt.io/qt-5/qml-qtquick-shadereffect.html>`_ items in combination with `VideoOutput <https://doc.qt.io/qt-5/qml-qtmultimedia-videooutput.html>`_ should be used. VideoFilter is not a replacement for this. It is rather targeted for performing computations (that do not necessarily change the image shown on screen) and computer vision algorithms provided by external frameworks.

:sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoFilter` is meant to be subclassed. The subclasses are then registered to the QML engine, so they can be used as a QML type. The list of filters are assigned to a `VideoOutput <https://doc.qt.io/qt-5/qml-qtmultimedia-videooutput.html>`_ type via its `filters <https://doc.qt.io/qt-5/qml-qtmultimedia-videooutput.html#filters-prop>`_ property.

A single filter represents one transformation or processing step on a video frame. The output is a modified video frame, some arbitrary data or both. For example, image transformations will result in a different image, whereas an algorithm for detecting objects on an image will likely provide a list of rectangles.

Arbitrary data can be represented as properties on the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoFilter` subclass and on the :sip:ref:`~PyQt5.QtCore.QObject` or QJSValue instances passed to its signals. What exactly these properties and signals are, is up to the individual video filters. Completion of the operations can be indicated by signals. Computations that do not result in a modified image will pass the input image through so that subsequent filters can be placed after them.

Properties set on :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoFilter` serve as input to the computation, similarly to how uniform values are specified in `ShaderEffect <https://doc.qt.io/qt-5/qml-qtquick-shadereffect.html>`_ types. The changed property values are taken into use when the next video frame is processed.

The typical usage is to subclass :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoFilter` and :sip:ref:`~PyQt5.QtMultimedia.QVideoFilterRunnable`:

::

    class MyFilterRunnable : public QVideoFilterRunnable {
    public:
        QVideoFrame run(QVideoFrame *input, const QVideoSurfaceFormat &surfaceFormat, RunFlags flags) { ... }
    };

    class MyFilter : public QAbstractVideoFilter {
    public:
        QVideoFilterRunnable *createFilterRunnable() { return new MyFilterRunnable; }
    signals:
        void finished(QObject *result);
    };

    int main(int argc, char **argv) {
        ...
        qmlRegisterType<MyFilter>("my.uri", 1, 0, "MyFilter");
        ...
    }

MyFilter is thus accessible from QML:

::

    import my.uri 1.0

    Camera {
        id: camera
    }
    MyFilter {
        id: filter
        // set properties, they can also be animated
        onFinished: console.log("results of the computation: " + result)
    }
    VideoOutput {
        source: camera
        filters: [ filter ]
        anchors.fill: parent
    }

This also allows providing filters in QML plugins, separately from the application.

.. seealso:: `VideoOutput <https://doc.qt.io/qt-5/qml-qtmultimedia-videooutput.html>`_, `Camera <https://doc.qt.io/qt-5/qml-multimedia.html#camera>`_, `MediaPlayer <https://doc.qt.io/qt-5/qml-qtmultimedia-mediaplayer.html>`_, :sip:ref:`~PyQt5.QtMultimedia.QVideoFilterRunnable`.
