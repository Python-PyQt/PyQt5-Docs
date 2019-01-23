.. sip:method-description::
    :status: todo
    :pysig: 2959872364c7b497ae5baab9d50a0314
    :realsig: ()
    :digest: c96e597e1ebffe59ebae6362cccea8b2

Returns the list of command-line arguments.

Usually .at(0) is the program name, .at(1) is the first argument, and .last() is the last argument. See the note below about Windows.

Calling this function is slow - you should store the result in a variable when parsing the command line.

**Warning:** On Unix, this list is built from the argc and argv parameters passed to the constructor in the main() function. The string-data in argv is interpreted using QString::fromLocal8Bit(); hence it is not possible to pass, for example, Japanese command line arguments on a system that runs in a Latin1 locale. Most modern Unix systems do not have this limitation, as they are Unicode-based.

On Windows, the list is built from the argc and argv parameters only if modified argv/argc parameters are passed to the constructor. In that case, encoding problems might occur.

Otherwise, the  are constructed from the return value of GetCommandLine(). As a result of this, the string given by .at(0) might not be the program name on Windows, depending on how the application was started.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QCoreApplication.applicationFilePath`, :sip:ref:`~PyQt5.QtCore.QCommandLineParser`.
