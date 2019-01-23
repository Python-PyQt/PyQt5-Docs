:orphan:

.. sip:class:: PyQt5.QtWidgets.QFileIconProvider
    :description: QtWidgets/QFileIconProvider-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QFileIconProvider.IconType
        :description: QtWidgets/QFileIconProvider-IconType-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFileIconProvider.IconType.Computer
            :description: QtWidgets/QFileIconProvider-IconType-Computer-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFileIconProvider.IconType.Desktop
            :description: QtWidgets/QFileIconProvider-IconType-Desktop-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFileIconProvider.IconType.Drive
            :description: QtWidgets/QFileIconProvider-IconType-Drive-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFileIconProvider.IconType.File
            :description: QtWidgets/QFileIconProvider-IconType-File-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFileIconProvider.IconType.Folder
            :description: QtWidgets/QFileIconProvider-IconType-Folder-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFileIconProvider.IconType.Network
            :description: QtWidgets/QFileIconProvider-IconType-Network-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFileIconProvider.IconType.Trashcan
            :description: QtWidgets/QFileIconProvider-IconType-Trashcan-v.rst

    .. sip:enum:: PyQt5.QtWidgets.QFileIconProvider.Option
        :description: QtWidgets/QFileIconProvider-Option-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFileIconProvider.Option.DontUseCustomDirectoryIcons
            :description: QtWidgets/QFileIconProvider-Option-DontUseCustomDirectoryIcons-v.rst

    .. sip:method:: PyQt5.QtWidgets.QFileIconProvider.__init__
        :description: QtWidgets/QFileIconProvider-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileIconProvider.icon
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QFileIconProvider.IconType`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QIcon`
        :description: QtWidgets/QFileIconProvider-icon-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileIconProvider.icon
        :args:
            :sip:ref:`~PyQt5.QtCore.QFileInfo`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QIcon`
        :description: QtWidgets/QFileIconProvider-icon-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QFileIconProvider.options
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QFileIconProvider.Options`
        :description: QtWidgets/QFileIconProvider-options-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileIconProvider.setOptions
        :args:
            Union[:sip:ref:`~PyQt5.QtWidgets.QFileIconProvider.Options`, :sip:ref:`~PyQt5.QtWidgets.QFileIconProvider.Option`]
        :description: QtWidgets/QFileIconProvider-setOptions-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFileIconProvider.type
        :args:
            :sip:ref:`~PyQt5.QtCore.QFileInfo`
        :returns:
            str
        :description: QtWidgets/QFileIconProvider-type-f.rst
