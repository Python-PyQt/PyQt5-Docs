.. sip:class-description::
    :status: todo
    :brief: Holds the environment variables that can be passed to a program
    :digest: cfc573dc575f6bca8320f23de7d8dd26

The :sip:ref:`~PyQt5.QtCore.QProcessEnvironment` class holds the environment variables that can be passed to a program.

A process's environment is composed of a set of key=value pairs known as environment variables. The :sip:ref:`~PyQt5.QtCore.QProcessEnvironment` class wraps that concept and allows easy manipulation of those variables. It's meant to be used along with QProcess, to set the environment for child processes. It cannot be used to change the current process's environment.

The environment of the calling process can be obtained using :sip:ref:`~PyQt5.QtCore.QProcessEnvironment.systemEnvironment`.

On Unix systems, the variable names are case-sensitive. Note that the Unix environment allows both variable names and contents to contain arbitrary binary data (except for the NUL character). :sip:ref:`~PyQt5.QtCore.QProcessEnvironment` will preserve such variables, but does not support manipulating variables whose names or values cannot be encoded by the current locale settings (see :sip:ref:`~PyQt5.QtCore.QTextCodec.codecForLocale`).

On Windows, the variable names are case-insensitive, but case-preserving. :sip:ref:`~PyQt5.QtCore.QProcessEnvironment` behaves accordingly.

.. seealso:: QProcessQProcess::systemEnvironment()QProcess::setProcessEnvironment().
