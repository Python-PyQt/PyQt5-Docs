.. sip:method-description::
    :status: todo
    :pysig: cccdfb46621b1d0b0daeaca92a9c6e3f
    :realsig: (const QString&,const QStringList&)
    :digest: 8cf863de98578b1b38b04c956a44591b

Finds the executable named *executableName* in the paths specified by *paths*, or the system paths if *paths* is empty.

On most operating systems the system path is determined by the PATH environment variable.

The directories where to search for the executable can be set in the *paths* argument. To search in both your own paths and the system paths, call  twice, once with *paths* set and once with *paths* empty.

Symlinks are not resolved, in order to preserve behavior for the case of executables whose behavior depends on the name they are invoked with.

**Note:** On Windows, the usual executable extensions (from the PATHEXT environment variable) are automatically appended, so that for instance ("foo") will find foo.exe or foo.bat if present.

Returns the absolute file path to the executable, or an empty string if not found.
