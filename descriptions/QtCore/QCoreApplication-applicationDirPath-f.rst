.. sip:method-description::
    :status: todo
    :pysig: 49cd6c4846645627c7c8750fdcfb2bfd
    :realsig: ()
    :digest: 0077bf2232c2e8aac94bc7b1997730aa

Returns the directory that contains the application executable.

For example, if you have installed Qt in the ``C:\Qt`` directory, and you run the ``regexp`` example, this function will return "C:/Qt/examples/tools/regexp".

On `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ and iOS this will point to the directory actually containing the executable, which may be inside an application bundle (if the application is bundled).

**Warning:** On Linux, this function will try to get the path from the ``/proc`` file system. If that fails, it assumes that ``argv[0]`` contains the absolute file name of the executable. The function also assumes that the current directory has not been changed by the application.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QCoreApplication.applicationFilePath`.
