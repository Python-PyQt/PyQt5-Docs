.. sip:class-description::
    :status: todo
    :brief: Common base class for media service implementations
    :digest: e0d20508bf6ce9a2e7f5dcaf297d7ee0

The :sip:ref:`~PyQt5.QtMultimedia.QMediaService` class provides a common base class for media service implementations.

Media services provide implementations of the functionality promised by media objects, and allow multiple providers to implement a :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`.

To provide the functionality of a :sip:ref:`~PyQt5.QtMultimedia.QMediaObject` media services implement :sip:ref:`~PyQt5.QtMultimedia.QMediaControl` interfaces. Services typically implement one core media control which provides the core feature of a media object, and some number of additional controls which provide either optional features of the media object, or features of a secondary media object or peripheral object.

A pointer to media service's :sip:ref:`~PyQt5.QtMultimedia.QMediaControl` implementation can be obtained by passing the control's interface name to the :sip:ref:`~PyQt5.QtMultimedia.QMediaService.requestControl` function.

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-media.py
    :lines: 104-105

Media objects can use services loaded dynamically from plug-ins or implemented statically within an applications. Plug-in based services should also implement the QMediaServiceProviderPlugin interface. Static services should implement the QMediaServiceProvider interface. In general, implementing a :sip:ref:`~PyQt5.QtMultimedia.QMediaService` is outside of the scope of this documentation and support on the relevant mailing lists or IRC channels should be sought.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QMediaObject`, :sip:ref:`~PyQt5.QtMultimedia.QMediaControl`.
