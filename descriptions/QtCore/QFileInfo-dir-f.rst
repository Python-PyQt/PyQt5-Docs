.. sip:method-description::
    :status: todo
    :pysig: 4c38a33d71bcf2a0254d0a4f65cb1002
    :realsig: () const
    :digest: ca114f4d09d0f22fb84f4025a13626ef

Returns the path of the object's parent directory as a :sip:ref:`~PyQt5.QtCore.QDir` object.

**Note:** The :sip:ref:`~PyQt5.QtCore.QDir` returned always corresponds to the object's parent directory, even if the :sip:ref:`~PyQt5.QtCore.QFileInfo` represents a directory.

For each of the following,  returns the :sip:ref:`~PyQt5.QtCore.QDir` ``"~/examples/191697"``.

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-fileinfo-main.py
    :lines: 66-68

For each of the following,  returns the :sip:ref:`~PyQt5.QtCore.QDir` ``"."``.

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-fileinfo-main.py
    :lines: 71-73

.. seealso:: :sip:ref:`~PyQt5.QtCore.QFileInfo.absolutePath`, :sip:ref:`~PyQt5.QtCore.QFileInfo.filePath`, :sip:ref:`~PyQt5.QtCore.QFileInfo.fileName`, :sip:ref:`~PyQt5.QtCore.QFileInfo.isRelative`, :sip:ref:`~PyQt5.QtCore.QFileInfo.absoluteDir`.
