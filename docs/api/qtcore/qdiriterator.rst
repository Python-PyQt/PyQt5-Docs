:orphan:

.. sip:class:: PyQt5.QtCore.QDirIterator
    :description: QtCore/QDirIterator-c.rst

    .. sip:enum:: PyQt5.QtCore.QDirIterator.IteratorFlag
        :description: QtCore/QDirIterator-IteratorFlag-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QDirIterator.IteratorFlag.FollowSymlinks
            :description: QtCore/QDirIterator-IteratorFlag-FollowSymlinks-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QDirIterator.IteratorFlag.NoIteratorFlags
            :description: QtCore/QDirIterator-IteratorFlag-NoIteratorFlags-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QDirIterator.IteratorFlag.Subdirectories
            :description: QtCore/QDirIterator-IteratorFlag-Subdirectories-v.rst

    .. sip:method:: PyQt5.QtCore.QDirIterator.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QDir`
            flags: :sip:ref:`~PyQt5.QtCore.QDirIterator.IteratorFlags` = :sip:ref:`~PyQt5.QtCore.QDirIterator.IteratorFlag.NoIteratorFlags`
        :description: QtCore/QDirIterator-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QDirIterator.__init__
        :args:
            str
            flags: :sip:ref:`~PyQt5.QtCore.QDirIterator.IteratorFlags` = :sip:ref:`~PyQt5.QtCore.QDirIterator.IteratorFlag.NoIteratorFlags`
        :description: QtCore/QDirIterator-__init__-f-1.rst

    .. sip:method:: PyQt5.QtCore.QDirIterator.__init__
        :args:
            str
            :sip:ref:`~PyQt5.QtCore.QDir.Filters`
            flags: :sip:ref:`~PyQt5.QtCore.QDirIterator.IteratorFlags` = :sip:ref:`~PyQt5.QtCore.QDirIterator.IteratorFlag.NoIteratorFlags`
        :description: QtCore/QDirIterator-__init__-f-2.rst

    .. sip:method:: PyQt5.QtCore.QDirIterator.__init__
        :args:
            str
            Iterable[str]
            filters: :sip:ref:`~PyQt5.QtCore.QDir.Filters` = :sip:ref:`~PyQt5.QtCore.QDir.Filter.NoFilter`
            flags: :sip:ref:`~PyQt5.QtCore.QDirIterator.IteratorFlags` = :sip:ref:`~PyQt5.QtCore.QDirIterator.IteratorFlag.NoIteratorFlags`
        :description: QtCore/QDirIterator-__init__-f-3.rst

    .. sip:method:: PyQt5.QtCore.QDirIterator.fileInfo
        :returns:
            :sip:ref:`~PyQt5.QtCore.QFileInfo`
        :description: QtCore/QDirIterator-fileInfo-f.rst

    .. sip:method:: PyQt5.QtCore.QDirIterator.fileName
        :returns:
            str
        :description: QtCore/QDirIterator-fileName-f.rst

    .. sip:method:: PyQt5.QtCore.QDirIterator.filePath
        :returns:
            str
        :description: QtCore/QDirIterator-filePath-f.rst

    .. sip:method:: PyQt5.QtCore.QDirIterator.hasNext
        :returns:
            bool
        :description: QtCore/QDirIterator-hasNext-f.rst

    .. sip:method:: PyQt5.QtCore.QDirIterator.next
        :returns:
            str
        :description: QtCore/QDirIterator-next-f.rst

    .. sip:method:: PyQt5.QtCore.QDirIterator.path
        :returns:
            str
        :description: QtCore/QDirIterator-path-f.rst
