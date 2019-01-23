.. sip:class-description::
    :status: todo
    :brief: System-independent file information
    :digest: e0d47c35502a7fa54fa237bc05d5b78f

The :sip:ref:`~PyQt5.QtCore.QFileInfo` class provides system-independent file information.

:sip:ref:`~PyQt5.QtCore.QFileInfo` provides information about a file's name and position (path) in the file system, its access rights and whether it is a directory or symbolic link, etc. The file's size and last modified/read times are also available. :sip:ref:`~PyQt5.QtCore.QFileInfo` can also be used to obtain information about a Qt `resource <https://doc.qt.io/qt-5/resources.html>`_.

A :sip:ref:`~PyQt5.QtCore.QFileInfo` can point to a file with either a relative or an absolute file path. Absolute file paths begin with the directory separator "/" (or with a drive specification on Windows). Relative file names begin with a directory name or a file name and specify a path relative to the current working directory. An example of an absolute path is the string "/tmp/quartz". A relative path might look like "src/fatlib". You can use the function :sip:ref:`~PyQt5.QtCore.QFileInfo.isRelative` to check whether a :sip:ref:`~PyQt5.QtCore.QFileInfo` is using a relative or an absolute file path. You can call the function :sip:ref:`~PyQt5.QtCore.QFileInfo.makeAbsolute` to convert a relative :sip:ref:`~PyQt5.QtCore.QFileInfo`'s path to an absolute path.

The file that the :sip:ref:`~PyQt5.QtCore.QFileInfo` works on is set in the constructor or later with :sip:ref:`~PyQt5.QtCore.QFileInfo.setFile`. Use :sip:ref:`~PyQt5.QtCore.QFileInfo.exists` to see if the file exists and :sip:ref:`~PyQt5.QtCore.QFileInfo.size` to get its size.

The file's type is obtained with :sip:ref:`~PyQt5.QtCore.QFileInfo.isFile`, :sip:ref:`~PyQt5.QtCore.QFileInfo.isDir` and :sip:ref:`~PyQt5.QtCore.QFileInfo.isSymLink`. The :sip:ref:`~PyQt5.QtCore.QFileInfo.symLinkTarget` function provides the name of the file the symlink points to.

On Unix (including `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ and iOS), the symlink has the same :sip:ref:`~PyQt5.QtCore.QFileInfo.size` has the file it points to, because Unix handles symlinks transparently; similarly, opening a symlink using :sip:ref:`~PyQt5.QtCore.QFile` effectively opens the link's target. For example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qfileinfo.py
    :lines: 59-72

On Windows, symlinks (shortcuts) are ``.lnk`` files. The reported :sip:ref:`~PyQt5.QtCore.QFileInfo.size` is that of the symlink (not the link's target), and opening a symlink using :sip:ref:`~PyQt5.QtCore.QFile` opens the ``.lnk`` file. For example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qfileinfo.py
    :lines: 77-90

Elements of the file's name can be extracted with :sip:ref:`~PyQt5.QtCore.QFileInfo.path` and :sip:ref:`~PyQt5.QtCore.QFileInfo.fileName`. The :sip:ref:`~PyQt5.QtCore.QFileInfo.fileName`'s parts can be extracted with :sip:ref:`~PyQt5.QtCore.QFileInfo.baseName`, :sip:ref:`~PyQt5.QtCore.QFileInfo.suffix` or :sip:ref:`~PyQt5.QtCore.QFileInfo.completeSuffix`. :sip:ref:`~PyQt5.QtCore.QFileInfo` objects to directories created by Qt classes will not have a trailing file separator. If you wish to use trailing separators in your own file info objects, just append one to the file name given to the constructors or :sip:ref:`~PyQt5.QtCore.QFileInfo.setFile`.

The file's dates are returned by :sip:ref:`~PyQt5.QtCore.QFileInfo.created`, :sip:ref:`~PyQt5.QtCore.QFileInfo.lastModified`, :sip:ref:`~PyQt5.QtCore.QFileInfo.lastRead` and fileTime(). Information about the file's access permissions is obtained with :sip:ref:`~PyQt5.QtCore.QFileInfo.isReadable`, :sip:ref:`~PyQt5.QtCore.QFileInfo.isWritable` and :sip:ref:`~PyQt5.QtCore.QFileInfo.isExecutable`. The file's ownership is available from :sip:ref:`~PyQt5.QtCore.QFileInfo.owner`, :sip:ref:`~PyQt5.QtCore.QFileInfo.ownerId`, :sip:ref:`~PyQt5.QtCore.QFileInfo.group` and :sip:ref:`~PyQt5.QtCore.QFileInfo.groupId`. You can examine a file's permissions and ownership in a single statement using the :sip:ref:`~PyQt5.QtCore.QFileInfo.permission` function.

.. _qfileinfo-ntfs-permissions:

**Note:** On NTFS file systems, ownership and permissions checking is disabled by default for performance reasons. To enable it, include the following line:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-ntfsp.py
    :lines: 55-55

Permission checking is then turned on and off by incrementing and decrementing ``qt_ntfs_permission_lookup`` by 1.

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-ntfsp.py
    :lines: 59-60

.. _qfileinfo-performance-issues:

Performance Issues
------------------

Some of :sip:ref:`~PyQt5.QtCore.QFileInfo`'s functions query the file system, but for performance reasons, some functions only operate on the file name itself. For example: To return the absolute path of a relative file name, :sip:ref:`~PyQt5.QtCore.QFileInfo.absolutePath` has to query the file system. The :sip:ref:`~PyQt5.QtCore.QFileInfo.path` function, however, can work on the file name directly, and so it is faster.

**Note:** To speed up performance, :sip:ref:`~PyQt5.QtCore.QFileInfo` caches information about the file.

Because files can be changed by other users or programs, or even by other parts of the same program, there is a function that refreshes the file information: :sip:ref:`~PyQt5.QtCore.QFileInfo.refresh`. If you want to switch off a :sip:ref:`~PyQt5.QtCore.QFileInfo`'s caching and force it to access the file system every time you request information from it call :sip:ref:`~PyQt5.QtCore.QFileInfo.setCaching`\ (false).

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDir`, :sip:ref:`~PyQt5.QtCore.QFile`.
