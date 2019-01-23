:orphan:

.. sip:class:: PyQt5.QtWidgets.QUndoStack
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtWidgets/QUndoStack-c.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtWidgets/QUndoStack-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.beginMacro
        :args:
            str
        :description: QtWidgets/QUndoStack-beginMacro-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.canRedo
        :returns:
            bool
        :description: QtWidgets/QUndoStack-canRedo-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.canUndo
        :returns:
            bool
        :description: QtWidgets/QUndoStack-canUndo-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.cleanIndex
        :returns:
            int
        :description: QtWidgets/QUndoStack-cleanIndex-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.clear
        :description: QtWidgets/QUndoStack-clear-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.command
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QUndoCommand`
        :description: QtWidgets/QUndoStack-command-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.count
        :returns:
            int
        :description: QtWidgets/QUndoStack-count-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.createRedoAction
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
            prefix: str = ''
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QUndoStack-createRedoAction-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.createUndoAction
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
            prefix: str = ''
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QUndoStack-createUndoAction-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.endMacro
        :description: QtWidgets/QUndoStack-endMacro-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.index
        :returns:
            int
        :description: QtWidgets/QUndoStack-index-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.isActive
        :returns:
            bool
        :description: QtWidgets/QUndoStack-isActive-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.isClean
        :returns:
            bool
        :description: QtWidgets/QUndoStack-isClean-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.__len__
        :returns:
            int
        :description: QtWidgets/QUndoStack-__len__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.push
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QUndoCommand`
        :description: QtWidgets/QUndoStack-push-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.redo
        :description: QtWidgets/QUndoStack-redo-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.redoText
        :returns:
            str
        :description: QtWidgets/QUndoStack-redoText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.resetClean
        :description: QtWidgets/QUndoStack-resetClean-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.setActive
        :args:
            active: bool = True
        :description: QtWidgets/QUndoStack-setActive-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.setClean
        :description: QtWidgets/QUndoStack-setClean-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.setIndex
        :args:
            int
        :description: QtWidgets/QUndoStack-setIndex-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.setUndoLimit
        :args:
            int
        :description: QtWidgets/QUndoStack-setUndoLimit-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.text
        :args:
            int
        :returns:
            str
        :description: QtWidgets/QUndoStack-text-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.undo
        :description: QtWidgets/QUndoStack-undo-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.undoLimit
        :returns:
            int
        :description: QtWidgets/QUndoStack-undoLimit-f.rst

    .. sip:method:: PyQt5.QtWidgets.QUndoStack.undoText
        :returns:
            str
        :description: QtWidgets/QUndoStack-undoText-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QUndoStack.canRedoChanged
        :args:
            bool
        :description: QtWidgets/QUndoStack-canRedoChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QUndoStack.canUndoChanged
        :args:
            bool
        :description: QtWidgets/QUndoStack-canUndoChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QUndoStack.cleanChanged
        :args:
            bool
        :description: QtWidgets/QUndoStack-cleanChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QUndoStack.indexChanged
        :args:
            int
        :description: QtWidgets/QUndoStack-indexChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QUndoStack.redoTextChanged
        :args:
            str
        :description: QtWidgets/QUndoStack-redoTextChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QUndoStack.undoTextChanged
        :args:
            str
        :description: QtWidgets/QUndoStack-undoTextChanged-s.rst
