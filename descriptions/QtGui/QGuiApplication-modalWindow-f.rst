.. sip:method-description::
    :status: todo
    :pysig: 37d8abbe73970ad3c2042713396fd379
    :realsig: ()
    :digest: 06ef51f05aea68cf3c5c86f062402fdc

Returns the most recently shown modal window. If no modal windows are visible, this function returns zero.

A modal window is a window which has its :sip:ref:`~PyQt5.QtGui.QWindow.modality` property set to :sip:ref:`~PyQt5.QtCore.Qt.WindowModality.WindowModal` or :sip:ref:`~PyQt5.QtCore.Qt.WindowModality.ApplicationModal`. A modal window must be closed before the user can continue with other parts of the program.

Modal window are organized in a stack. This function returns the modal window at the top of the stack.

.. seealso:: :sip:ref:`~PyQt5.QtCore.Qt.WindowModality`, :sip:ref:`~PyQt5.QtGui.QWindow.setModality`.
