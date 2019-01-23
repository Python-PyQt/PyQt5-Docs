.. sip:class-description::
    :status: todo
    :brief: Allows drawing of custom text objects in QTextDocuments
    :digest: 8532a3b0164b3e4dbf80a17f7d6a3274

The :sip:ref:`~PyQt5.QtGui.QTextObjectInterface` class allows drawing of custom text objects in :sip:ref:`~PyQt5.QtGui.QTextDocument`\ s.

A text object describes the structure of one or more elements in a text document; for instance, images imported from HTML are implemented using text objects. A text object knows how to lay out and draw its elements when a document is being rendered.

Qt allows custom text objects to be inserted into a document by registering a custom object type with :sip:ref:`~PyQt5.QtGui.QTextCharFormat`. A :sip:ref:`~PyQt5.QtGui.QTextObjectInterface` must also be implemented for this type and be :sip:ref:`~PyQt5.QtGui.QAbstractTextDocumentLayout.registerHandler` with the :sip:ref:`~PyQt5.QtGui.QAbstractTextDocumentLayout` of the document. When the object type is encountered while rendering a :sip:ref:`~PyQt5.QtGui.QTextDocument`, the :sip:ref:`~PyQt5.QtGui.QTextObjectInterface.intrinsicSize` and :sip:ref:`~PyQt5.QtGui.QTextObjectInterface.drawObject` functions of the interface are called.

The following list explains the required steps of inserting a custom text object into a document:

* Choose an *objectType*. The *objectType* is an integer with a value greater or equal to :sip:ref:`~PyQt5.QtGui.QTextFormat.ObjectTypes.UserObject`.

* Create a :sip:ref:`~PyQt5.QtGui.QTextCharFormat` object and set the object type to the chosen type using the setObjectType() function.

* Implement the :sip:ref:`~PyQt5.QtGui.QTextObjectInterface` class.

* Call :sip:ref:`~PyQt5.QtGui.QAbstractTextDocumentLayout.registerHandler` with an instance of your :sip:ref:`~PyQt5.QtGui.QTextObjectInterface` subclass to register your object type.

* Insert QChar::ObjectReplacementCharacter with the aforementioned :sip:ref:`~PyQt5.QtGui.QTextCharFormat` of the chosen object type into the document. As mentioned, the functions of :sip:ref:`~PyQt5.QtGui.QTextObjectInterface` :sip:ref:`~PyQt5.QtGui.QTextObjectInterface.intrinsicSize` and :sip:ref:`~PyQt5.QtGui.QTextObjectInterface.drawObject` will then be called with the :sip:ref:`~PyQt5.QtGui.QTextFormat` as parameter whenever the replacement character is encountered.

A class implementing a text object needs to inherit both :sip:ref:`~PyQt5.QtCore.QObject` and :sip:ref:`~PyQt5.QtGui.QTextObjectInterface`. :sip:ref:`~PyQt5.QtCore.QObject` must be the first class inherited. For instance:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-qtextobject-textobjectinterface.py
    :lines: 54-57

The data of a text object is usually stored in the :sip:ref:`~PyQt5.QtGui.QTextCharFormat` using QTextCharFormat::setProperty(), and then retrieved with QTextCharFormat::property().

**Warning:** Copy and Paste operations ignore custom text objects.

.. seealso:: `Text Object Example <https://doc.qt.io/qt-5/qtsvg-richtext-textobject-example.html>`_, :sip:ref:`~PyQt5.QtGui.QTextCharFormat`, :sip:ref:`~PyQt5.QtGui.QTextLayout`.
