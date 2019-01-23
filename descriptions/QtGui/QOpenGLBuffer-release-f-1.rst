.. sip:method-description::
    :status: todo
    :pysig: b1cafad4793834893d5e4cd628353cc6
    :realsig: (QOpenGLBuffer::Type)
    :digest: 1dc218c3796c15707f62c9edc4966b1a

Releases the buffer associated with *type* in the current :sip:ref:`~PyQt5.QtGui.QOpenGLContext`.

This function is a direct call to ``glBindBuffer(type, 0)`` for use when the caller does not know which :sip:ref:`~PyQt5.QtGui.QOpenGLBuffer` has been bound to the context but wants to make sure that it is released.

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_opengl_qopenglbuffer.py
    :lines: 50-50
