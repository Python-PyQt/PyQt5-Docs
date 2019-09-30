.. sip:module-description::
    :status:    done
    :brief:     Classes for handling the files created by Qt Designer

The :sip:ref:`~PyQt5.uic` module contains classes for handling the ``.ui``
files created by Qt Designer that describe the whole or part of a graphical
user interface.  It includes classes that load a ``.ui`` file and render it
directly, and classes that generate Python code from a ``.ui`` file for later
execution.


.. data:: widgetPluginPath

    The list of the directories that are searched for widget plugins.
    Initially it contains the name of the directory that contains the widget
    plugins included with PyQt5.

.. function:: compileUi(uifile, pyfile, execute=False, indent=4, from_imports=False, resource_suffix='_rc', import_from='.')

    Generate a Python module that will create a user interface from a Qt
    Designer :file:`.ui` file.

    :param str uifile:
        the file name or file-like object containing the :file:`.ui` file.
    :param file pyfile:
        the file-like object to which the generated Python code will be written
        to.
    :param bool execute:
        is optionally set if a small amount of additional code is to be
        generated that will display the user interface if the code is run as a
        standalone application.
    :param int indent:
        the optional number of spaces used for indentation in the generated
        code.  If it is zero then a tab character is used instead.
    :param bool from_imports:
        is optionally set to generate relative import statements.  At the
        moment this only applies to the import of resource modules.
    :param str resource_suffix:
        is the suffix appended to the basename of any resource file specified
        in the :file:`.ui` file to create the name of the Python module
        generated from the resource file by :program:`pyrcc5`.  The default is
        ``'_rc'``, i.e. if the :file:`.ui` file specified a resource file
        called :file:`foo.qrc` then the corresponding Python module is
        ``foo_rc``.
    :param str import_from:
        is optionally set to the package used for relative import statements.
        The default is ``'.'``.


.. function:: compileUiDir(dir, recurse=False, map=None, \*\*compileUi_args)

    Create Python modules from Qt Designer :file:`.ui` files in a directory or
    directory tree.

    :param str dir:
        the name of the directory to scan for files whose name ends with
        :file`.ui`.  By default the generated Python module is created in the
        same directory ending with :file:`.py`.
    :param bool recurse:
        is optionally set if any sub-directories should be scanned.
    :param callable map:
        an optional callable that is passed the name of the directory
        containing the :file:`.ui` file and the name of the Python module that
        will be created.  The callable should return a tuple of the name of the
        directory in which the Python module will be created and the (possibly
        modified) name of the module.
    :param compileUi_args:
        are any additional keyword arguments that are passed to
        :func:`~PyQt5.uic.compileUi` that is called to create each Python
        module.


.. function:: loadUiType(uifile, from_imports=False, resource_suffix='_rc', import_from='.')

    Load a Qt Designer :file:`.ui` file and return a tuple of the generated
    *form class* and the *Qt base class*.  These can then be used to
    create any number of instances of the user interface without having to
    parse the :file:`.ui` file more than once.

    :param str uifile:
        the file name or file-like object containing the :file:`.ui` file.
    :param bool from_imports:
        is optionally set to generate relative import statements.  At the
        moment this only applies to the import of resource modules.
    :param str resource_suffix:
        is the suffix appended to the basename of any resource file specified
        in the :file`.ui` file to create the name of the Python module
        generated from the resource file by :program:`pyrcc5`.  The default is
        ``'_rc'``, i.e. if the :file:`.ui` file specified a resource file
        called :file:`foo.qrc` then the corresponding Python module is
        ``foo_rc``.
    :param str import_from:
        is optionally set to the package used for relative import statements.
        The default is ``'.'``.
    :return:
        the *form class* and the *Qt base class*.


.. function:: loadUi(uifile, baseinstance=None, package='', resource_suffix='_rc')

    Load a Qt Designer :file:`.ui` file and returns an instance of the user
    interface.

    :param str uifile:
        the file name or file-like object containing the :file:`.ui` file.
    :param baseinstance:
        the optional instance of the *Qt base class*.  If specified then the
        user interface is created in it.  Otherwise a new instance of the base
        class is automatically created.
    :param str package:
        the optional package that is the base package for any relative imports
        of custom widgets.
    :param str resource_suffix:
        is the suffix appended to the basename of any resource file specified
        in the :file:`.ui` file to create the name of the Python module
        generated from the resource file by :program:`pyrcc5`.  The default is
        ``'_rc'``, i.e. if the :file:`.ui` file specified a resource file
        called :file:`foo.qrc` then the corresponding Python module is
        ``foo_rc``.
    :return:
        the :sip:ref:`~PyQt5.QtWidgets.QWidget` sub-class that implements the
        user interface.
