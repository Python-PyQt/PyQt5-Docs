.. sip:class-description::
    :status: todo
    :brief: Base interface for media service controls
    :digest: 85cf132111ddde9921088024b1e1c021

The :sip:ref:`~PyQt5.QtMultimedia.QMediaControl` class provides a base interface for media service controls.

Media controls provide an interface to individual features provided by a media service. Most services implement a principal control which exposes the core functionality of the service and a number of optional controls which expose any additional functionality.

A pointer to a control implemented by a media service can be obtained using the :sip:ref:`~PyQt5.QtMultimedia.QMediaService.requestControl` member of :sip:ref:`~PyQt5.QtMultimedia.QMediaService`. If the service doesn't implement a control it will instead return a null pointer.

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-media.py
    :lines: 104-105

Alternatively if the IId of the control has been declared using Q_MEDIA_DECLARE_CONTROL the template version of :sip:ref:`~PyQt5.QtMultimedia.QMediaService.requestControl` can be used to request the service without explicitly passing the IId or using .

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-media.py
    :lines: 112-112

Most application code will not interface directly with a media service's controls, instead the :sip:ref:`~PyQt5.QtMultimedia.QMediaObject` which owns the service acts as an intermediary between one or more controls and the application.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QMediaService`, :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`.
