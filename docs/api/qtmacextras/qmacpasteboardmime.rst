:orphan:

.. sip:class:: PyQt5.QtMacExtras.QMacPasteboardMime
    :description: QtMacExtras/QMacPasteboardMime-c.rst

    .. sip:enum:: PyQt5.QtMacExtras.QMacPasteboardMime.QMacPasteboardMimeType
        :description: QtMacExtras/QMacPasteboardMime-QMacPasteboardMimeType-e.rst

        .. sip:enum-member:: PyQt5.QtMacExtras.QMacPasteboardMime.QMacPasteboardMimeType.MIME_ALL
            :description: QtMacExtras/QMacPasteboardMime-QMacPasteboardMimeType-MIME_ALL-v.rst

        .. sip:enum-member:: PyQt5.QtMacExtras.QMacPasteboardMime.QMacPasteboardMimeType.MIME_CLIP
            :description: QtMacExtras/QMacPasteboardMime-QMacPasteboardMimeType-MIME_CLIP-v.rst

        .. sip:enum-member:: PyQt5.QtMacExtras.QMacPasteboardMime.QMacPasteboardMimeType.MIME_DND
            :description: QtMacExtras/QMacPasteboardMime-QMacPasteboardMimeType-MIME_DND-v.rst

        .. sip:enum-member:: PyQt5.QtMacExtras.QMacPasteboardMime.QMacPasteboardMimeType.MIME_QT3_CONVERTOR
            :description: QtMacExtras/QMacPasteboardMime-QMacPasteboardMimeType-MIME_QT3_CONVERTOR-v.rst

        .. sip:enum-member:: PyQt5.QtMacExtras.QMacPasteboardMime.QMacPasteboardMimeType.MIME_QT_CONVERTOR
            :description: QtMacExtras/QMacPasteboardMime-QMacPasteboardMimeType-MIME_QT_CONVERTOR-v.rst

    .. sip:method:: PyQt5.QtMacExtras.QMacPasteboardMime.__init__
        :args:
            int
        :description: QtMacExtras/QMacPasteboardMime-__init__-f.rst

    .. sip:method:: PyQt5.QtMacExtras.QMacPasteboardMime.__init__
        :args:
            :sip:ref:`~PyQt5.QtMacExtras.QMacPasteboardMime`
        :description: QtMacExtras/QMacPasteboardMime-__init__-f-1.rst

    .. sip:method:: PyQt5.QtMacExtras.QMacPasteboardMime.canConvert
        :args:
            str
            str
        :returns:
            bool
        :description: QtMacExtras/QMacPasteboardMime-canConvert-f.rst

    .. sip:method:: PyQt5.QtMacExtras.QMacPasteboardMime.convertFromMime
        :args:
            str
            Any
            str
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QByteArray`]
        :description: QtMacExtras/QMacPasteboardMime-convertFromMime-f.rst

    .. sip:method:: PyQt5.QtMacExtras.QMacPasteboardMime.convertorName
        :returns:
            str
        :description: QtMacExtras/QMacPasteboardMime-convertorName-f.rst

    .. sip:method:: PyQt5.QtMacExtras.QMacPasteboardMime.convertToMime
        :args:
            str
            Iterable[Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]]
            str
        :returns:
            Any
        :description: QtMacExtras/QMacPasteboardMime-convertToMime-f.rst

    .. sip:method:: PyQt5.QtMacExtras.QMacPasteboardMime.count
        :args:
            :sip:ref:`~PyQt5.QtCore.QMimeData`
        :returns:
            int
        :description: QtMacExtras/QMacPasteboardMime-count-f.rst

    .. sip:method:: PyQt5.QtMacExtras.QMacPasteboardMime.flavorFor
        :args:
            str
        :returns:
            str
        :description: QtMacExtras/QMacPasteboardMime-flavorFor-f.rst

    .. sip:method:: PyQt5.QtMacExtras.QMacPasteboardMime.mimeFor
        :args:
            str
        :returns:
            str
        :description: QtMacExtras/QMacPasteboardMime-mimeFor-f.rst
