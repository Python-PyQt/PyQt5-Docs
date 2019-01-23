:orphan:

.. sip:class:: PyQt5.QtCore.QMimeDatabase
    :description: QtCore/QMimeDatabase-c.rst

    .. sip:enum:: PyQt5.QtCore.QMimeDatabase.MatchMode
        :description: QtCore/QMimeDatabase-MatchMode-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QMimeDatabase.MatchMode.MatchContent
            :description: QtCore/QMimeDatabase-MatchMode-MatchContent-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QMimeDatabase.MatchMode.MatchDefault
            :description: QtCore/QMimeDatabase-MatchMode-MatchDefault-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QMimeDatabase.MatchMode.MatchExtension
            :description: QtCore/QMimeDatabase-MatchMode-MatchExtension-v.rst

    .. sip:method:: PyQt5.QtCore.QMimeDatabase.__init__
        :description: QtCore/QMimeDatabase-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QMimeDatabase.allMimeTypes
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QMimeType`]
        :description: QtCore/QMimeDatabase-allMimeTypes-f.rst

    .. sip:method:: PyQt5.QtCore.QMimeDatabase.mimeTypeForData
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMimeType`
        :description: QtCore/QMimeDatabase-mimeTypeForData-f.rst

    .. sip:method:: PyQt5.QtCore.QMimeDatabase.mimeTypeForData
        :args:
            :sip:ref:`~PyQt5.QtCore.QIODevice`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMimeType`
        :description: QtCore/QMimeDatabase-mimeTypeForData-f-1.rst

    .. sip:method:: PyQt5.QtCore.QMimeDatabase.mimeTypeForFile
        :args:
            str
            mode: :sip:ref:`~PyQt5.QtCore.QMimeDatabase.MatchMode` = :sip:ref:`~PyQt5.QtCore.QMimeDatabase.MatchMode.MatchDefault`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMimeType`
        :description: QtCore/QMimeDatabase-mimeTypeForFile-f.rst

    .. sip:method:: PyQt5.QtCore.QMimeDatabase.mimeTypeForFile
        :args:
            :sip:ref:`~PyQt5.QtCore.QFileInfo`
            mode: :sip:ref:`~PyQt5.QtCore.QMimeDatabase.MatchMode` = :sip:ref:`~PyQt5.QtCore.QMimeDatabase.MatchMode.MatchDefault`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMimeType`
        :description: QtCore/QMimeDatabase-mimeTypeForFile-f-1.rst

    .. sip:method:: PyQt5.QtCore.QMimeDatabase.mimeTypeForFileNameAndData
        :args:
            str
            :sip:ref:`~PyQt5.QtCore.QIODevice`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMimeType`
        :description: QtCore/QMimeDatabase-mimeTypeForFileNameAndData-f.rst

    .. sip:method:: PyQt5.QtCore.QMimeDatabase.mimeTypeForFileNameAndData
        :args:
            str
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMimeType`
        :description: QtCore/QMimeDatabase-mimeTypeForFileNameAndData-f-1.rst

    .. sip:method:: PyQt5.QtCore.QMimeDatabase.mimeTypeForName
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMimeType`
        :description: QtCore/QMimeDatabase-mimeTypeForName-f.rst

    .. sip:method:: PyQt5.QtCore.QMimeDatabase.mimeTypeForUrl
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMimeType`
        :description: QtCore/QMimeDatabase-mimeTypeForUrl-f.rst

    .. sip:method:: PyQt5.QtCore.QMimeDatabase.mimeTypesForFileName
        :args:
            str
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QMimeType`]
        :description: QtCore/QMimeDatabase-mimeTypesForFileName-f.rst

    .. sip:method:: PyQt5.QtCore.QMimeDatabase.suffixForFileName
        :args:
            str
        :returns:
            str
        :description: QtCore/QMimeDatabase-suffixForFileName-f.rst
