:orphan:

.. sip:class:: PyQt5.QtWidgets.QUndoGroup
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtWidgets/QUndoGroup-c.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoGroup.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtWidgets/QUndoGroup-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoGroup.activeStack
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QUndoStack`
        :description: QtWidgets/QUndoGroup-activeStack-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoGroup.addStack
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QUndoStack`
        :description: QtWidgets/QUndoGroup-addStack-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoGroup.canRedo
        :returns:
            bool
        :description: QtWidgets/QUndoGroup-canRedo-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoGroup.canUndo
        :returns:
            bool
        :description: QtWidgets/QUndoGroup-canUndo-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoGroup.createRedoAction
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
            prefix: str = ''
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QUndoGroup-createRedoAction-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoGroup.createUndoAction
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
            prefix: str = ''
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QUndoGroup-createUndoAction-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoGroup.isClean
        :returns:
            bool
        :description: QtWidgets/QUndoGroup-isClean-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoGroup.redo
        :description: QtWidgets/QUndoGroup-redo-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoGroup.redoText
        :returns:
            str
        :description: QtWidgets/QUndoGroup-redoText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoGroup.removeStack
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QUndoStack`
        :description: QtWidgets/QUndoGroup-removeStack-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoGroup.setActiveStack
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QUndoStack`
        :description: QtWidgets/QUndoGroup-setActiveStack-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoGroup.stacks
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QUndoStack`]
        :description: QtWidgets/QUndoGroup-stacks-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoGroup.undo
        :description: QtWidgets/QUndoGroup-undo-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoGroup.undoText
        :returns:
            str
        :description: QtWidgets/QUndoGroup-undoText-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QUndoGroup.activeStackChanged
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QUndoStack`
        :description: QtWidgets/QUndoGroup-activeStackChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QUndoGroup.canRedoChanged
        :args:
            bool
        :description: QtWidgets/QUndoGroup-canRedoChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QUndoGroup.canUndoChanged
        :args:
            bool
        :description: QtWidgets/QUndoGroup-canUndoChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QUndoGroup.cleanChanged
        :args:
            bool
        :description: QtWidgets/QUndoGroup-cleanChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QUndoGroup.indexChanged
        :args:
            int
        :description: QtWidgets/QUndoGroup-indexChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QUndoGroup.redoTextChanged
        :args:
            str
        :description: QtWidgets/QUndoGroup-redoTextChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QUndoGroup.undoTextChanged
        :args:
            str
        :description: QtWidgets/QUndoGroup-undoTextChanged-s.rst
