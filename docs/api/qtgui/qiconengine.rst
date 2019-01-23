:orphan:

.. sip:class:: PyQt5.QtGui.QIconEngine
    :description: QtGui/QIconEngine-c.rst

    .. sip:enum:: PyQt5.QtGui.QIconEngine.IconEngineHook
        :description: QtGui/QIconEngine-IconEngineHook-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QIconEngine.IconEngineHook.AvailableSizesHook
            :description: QtGui/QIconEngine-IconEngineHook-AvailableSizesHook-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QIconEngine.IconEngineHook.IconNameHook
            :description: QtGui/QIconEngine-IconEngineHook-IconNameHook-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QIconEngine.IconEngineHook.IsNullHook
            :description: QtGui/QIconEngine-IconEngineHook-IsNullHook-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QIconEngine.IconEngineHook.ScaledPixmapHook
            :description: QtGui/QIconEngine-IconEngineHook-ScaledPixmapHook-v.rst

    .. sip:method:: PyQt5.QtGui.QIconEngine.__init__
        :description: QtGui/QIconEngine-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QIconEngine.__init__
        :args:
            :sip:ref:`~PyQt5.QtGui.QIconEngine`
        :description: QtGui/QIconEngine-__init__-f-1.rst

    .. sip:method:: PyQt5.QtGui.QIconEngine.actualSize
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
            :sip:ref:`~PyQt5.QtGui.QIcon.Mode`
            :sip:ref:`~PyQt5.QtGui.QIcon.State`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QIconEngine-actualSize-f.rst

    .. sip:method:: PyQt5.QtGui.QIconEngine.addFile
        :args:
            str
            :sip:ref:`~PyQt5.QtCore.QSize`
            :sip:ref:`~PyQt5.QtGui.QIcon.Mode`
            :sip:ref:`~PyQt5.QtGui.QIcon.State`
        :description: QtGui/QIconEngine-addFile-f.rst

    .. sip:method:: PyQt5.QtGui.QIconEngine.addPixmap
        :args:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
            :sip:ref:`~PyQt5.QtGui.QIcon.Mode`
            :sip:ref:`~PyQt5.QtGui.QIcon.State`
        :description: QtGui/QIconEngine-addPixmap-f.rst

    .. sip:method:: PyQt5.QtGui.QIconEngine.availableSizes
        :args:
            mode: :sip:ref:`~PyQt5.QtGui.QIcon.Mode` = :sip:ref:`~PyQt5.QtGui.QIcon.Mode.Normal`
            state: :sip:ref:`~PyQt5.QtGui.QIcon.State` = :sip:ref:`~PyQt5.QtGui.QIcon.State.Off`
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QSize`]
        :description: QtGui/QIconEngine-availableSizes-f.rst

    .. sip:method:: PyQt5.QtGui.QIconEngine.clone
        :returns:
            :sip:ref:`~PyQt5.QtGui.QIconEngine`
        :description: QtGui/QIconEngine-clone-f.rst

    .. sip:method:: PyQt5.QtGui.QIconEngine.iconName
        :returns:
            str
        :description: QtGui/QIconEngine-iconName-f.rst

    .. sip:method:: PyQt5.QtGui.QIconEngine.isNull
        :returns:
            bool
        :description: QtGui/QIconEngine-isNull-f.rst

    .. sip:method:: PyQt5.QtGui.QIconEngine.key
        :returns:
            str
        :description: QtGui/QIconEngine-key-f.rst

    .. sip:method:: PyQt5.QtGui.QIconEngine.paint
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainter`
            :sip:ref:`~PyQt5.QtCore.QRect`
            :sip:ref:`~PyQt5.QtGui.QIcon.Mode`
            :sip:ref:`~PyQt5.QtGui.QIcon.State`
        :description: QtGui/QIconEngine-paint-f.rst

    .. sip:method:: PyQt5.QtGui.QIconEngine.pixmap
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
            :sip:ref:`~PyQt5.QtGui.QIcon.Mode`
            :sip:ref:`~PyQt5.QtGui.QIcon.State`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
        :description: QtGui/QIconEngine-pixmap-f.rst

    .. sip:method:: PyQt5.QtGui.QIconEngine.read
        :args:
            :sip:ref:`~PyQt5.QtCore.QDataStream`
        :returns:
            bool
        :description: QtGui/QIconEngine-read-f.rst

    .. sip:method:: PyQt5.QtGui.QIconEngine.scaledPixmap
        :args:
            :sip:ref:`~PyQt5.QtCore.QSize`
            :sip:ref:`~PyQt5.QtGui.QIcon.Mode`
            :sip:ref:`~PyQt5.QtGui.QIcon.State`
            float
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
        :description: QtGui/QIconEngine-scaledPixmap-f.rst

    .. sip:method:: PyQt5.QtGui.QIconEngine.write
        :args:
            :sip:ref:`~PyQt5.QtCore.QDataStream`
        :returns:
            bool
        :description: QtGui/QIconEngine-write-f.rst
