Installing PyQt5
================

Both the GPL and commercial versions of PyQt5 can be built from source packages
or installed from binary wheels.


Understanding the Correct Version to Install
--------------------------------------------

Historically the version number of PyQt bears no relation to the version of Qt
supported.  For example it wasn't even true that PyQt4 required Qt v4 as it
would also build against Qt v5.  People sometimes mistakenly believe that, for
example, PyQt5 v5.13 is needed when building against Qt v5.13.

Qt uses `semantic versioning <https://semver.org/spec/v2.0.0.html>`__ when
deciding on the version number of a release.  In summary the major version is
increased when a release includes incompatible changes, the minor version is
increased when a release includes compatible changes, and the patch version is
increased when a release includes no user-visible changes.

Starting with PyQt5 the version number of PyQt5 is tied, to a certain extent,
to the version of Qt v5 so that:

- The major version will always be **5**.

- For a particular minor version *n* it will build against any version of Qt
  v5, but will not support any new features introduced in Qt v5.\ *n+1* or
  later.

- It will support all the features of supported modules of Qt v5.\ *n* or
  earlier.

- Support for new modules may be added to PyQt5 at any time.  This would result
  in a change of patch version only.

- The major and minor versions of the latest release of PyQt5 will be the same
  as the latest release of Qt v5.

- The maintenance numbers of PyQt5 and Qt v5 are entirely unrelated to each
  other.

So, for example, PyQt5 v5.1 will build against Qt v5.2 but will not support any
new features introduced in Qt v5.2.  PyQt5 v5.1 will support all the features
of supported modules of Qt v5.0 and those new features introduced in Qt v5.1.

In summary, you should always try and use the latest version of PyQt5 no matter
what version of Qt v5 you are using.


Installing from Wheels
----------------------

Wheels are the standard Python packaging format for pure Python or binary
extension modules such as PyQt5.  Only Python v3.5 and later are supported.
Wheels are provide for 32- and 64-bit Windows, 64-bit macOS and 64-bit Linux.
These correspond with the platforms for which The Qt Company provide binary
installers.

Wheels are installed using the :program:`pip3` program that is included with
current versions of Python.


Installing the GPL Version
..........................

To install the wheel for the GPL version of PyQt5, run::

    pip3 install pyqt5

This will install the wheel for your platform and your version of Python
(assuming both are supported).  The wheel will be automatically downloaded from
the Python Package Index.

If you get an error message saying that no downloads could be found that
satisfy the rquirement then you are probably using an unsupported version of
Python.

The PyQt5 wheel includes the necessary parts of the LGPL version of Qt.  There
is no need to install Qt yourself.

SIP is packaged as a separate wheel which will be downloaded and installed
automatically.

To uninstall the GPL version, run::

    pip3 uninstall pyqt5

.. note::

   Qt's support for TLS/SSL will not work on Windows when installing wheels
   that contain Qt v5.12.4 (or later) with Python v3.7.0 to v3.7.3.  This is
   because of incompatibilities between the different versions of OpenSSL that
   these versions require.  All other version combinations should be fine.


Installing the Commercial Version
.................................

.. program:: pyqtlicense

It is not possible to provide wheels for the commercial version in the same way
they are provided for the GPL version:

- the user's license information has to be applied

- it is not possible to distribute a copy of the commercial version of Qt.

Instead *unlicensed* wheels are provided which do not include a copy of Qt.
The program :program:`pyqtlicense` is provided which takes the unlicensed
wheel, the ``pyqt-commercial.sip`` license file and the location of the Qt
installation and generates a *licensed* wheel.  The licensed wheel contains a
copy of the necessary parts of Qt and can be installed using :program:`pip3`.

:program:`pyqtlicense` assumes that the Qt installation has been created from
one of the LGPL or commercial binary installers provided by The Qt Company.  It
may also work with a Qt installation built from source but this is unsupported.

On Windows the binary installer for MSVC 2015 or MSVC 2017 must be used.

The following describes the command line options of :program:`pyqtlicense`.

.. cmdoption:: -h, --help

    Display a help message and exit.

.. cmdoption:: -V, --version

    Display the version number and exit.

.. cmdoption:: --build-tag TAG

    This specifies that ``TAG`` should be used as the build tag in the name of
    the generated wheel.  If ``TAG`` is an empty string then the build tag is
    omitted.

.. cmdoption:: --license FILE

    This specifies that ``FILE`` is the license file.

.. cmdoption:: --no-msvc-runtime

    The unlicensed wheels for 32- and 64-bit Python includes ``msvcp140.dll``
    (part of the MSVC2015 C++ runtime).  This specifies that the DLL should be
    omitted from the licensed wheel.

.. cmdoption:: --no-openssl

    The unlicensed wheels for 32- and 64-bit Python includes the OpenSSL DLLs.
    This specifies that the DLLs should be omitted from the licensed wheel.

.. cmdoption:: --openssl DIR

    This specifies that the OpenSSL DLLs included in the unlicensed wheels for
    32- and 64-bit Python should be replaced by the DLLs in the directory
    ``DIR``.  Qt v5.12.4 and later are configured for OpenSSL v1.1.1.  Earlier
    versions of Qt are configured for OpenSSL v1.0.2.

.. cmdoption:: --output DIR

    This specifies that the licensed wheel will be written to the directory
    ``DIR``.

.. cmdoption:: --qt DIR

    This specifies that ``DIR`` contains the LGPL or commercial Qt installation
    to be included in the licensed wheel.  The directory is what Qt refers to
    as the *prefix* directory, i.e. the architecture specific directory
    containing the ``bin``, ``lib`` etc. directories.  It must be specified.

.. cmdoption:: --qt-version VERSION

    This specifies the 3-part version number of the Qt installation.  If it is
    not specified then it will be extracted from the value specified by the
    :option:`--qt` option.

.. cmdoption:: --quiet

    This specifies that all progress messages should be suppressed.

.. cmdoption:: --wheel-qt-version VERSION

    This specifies the 3-part version number of the Qt installation that the
    wheel was built against.  If it is not specified then it will be extracted
    from the build tag of the wheel file.

.. cmdoption:: --verbose

    This specifies that additional progress messages should be displayed.

The remaining argument is the name of the unlicensed wheel file to license.

To uninstall the commercial version, run::

    pip3 uninstall pyqt5-commercial


Building and Installing from Source
-----------------------------------

.. program:: configure.py

Downloading SIP
...............

SIP must be installed before building and using PyQt5.  You can get the latest
release of the SIP source code from
https://www.riverbankcomputing.com/software/sip/download.

The SIP installation instructions can be found at
https://www.riverbankcomputing.com/static/Docs/sip/installation.html.

.. note::

    When building PyQt5 v5.11 or later you must configure SIP to create a
    private copy of the ``sip`` module using a command line similar to the
    following::

        python configure.py --sip-module PyQt5.sip

    If you already have SIP installed and you just want to build and install
    the private copy of the module then add the ``--no-tools`` option.


Downloading PyQt5
.................

You can get the latest release of the GPL version of the PyQt5 source code from
https://www.riverbankcomputing.com/software/pyqt/download5.

If you are using the commercial version of PyQt5 then you should use the
download instructions which were sent to you when you made your purchase.  You
must also download your ``pyqt-commercial.sip`` license file.


Configuring PyQt5
.................

After unpacking the source package (either a ``.tar.gz`` or a ``.zip`` file
depending on your platform) you should then check for any :file:`README` files
that relate to your platform.

If you are using the commercial version of PyQt5 then you must copy your
``pyqt-commercial.sip`` license file to the :file:`sip` directory, or to the
directory specified by the :option:`--license-dir <configure.py --license-dir>`
option of :program:`configure.py`.

You need to make sure your environment variables are set properly for your
development environment.

In order to configure the build of PyQt5 you need to run the
:program:`configure.py` script as follows::

    python3 configure.py

This assumes that the Python interpreter is on your path.  Something like the
following may be appropriate on Windows::

    c:\Python38\python configure.py

If you have multiple versions of Python installed then make sure you use the
interpreter for which you wish to build PyQt5 for.

The full set of command line options is:

.. cmdoption:: -h, --help

    Display a help message and exit.

.. cmdoption:: --abi-version <VERSION>

    .. versionadded:: 5.12.3

    The ``sip`` module implements a versioned ABI and PyQt5 must be built to
    use a combatible version.  The ABI version has a major number and a minor
    number separated by ``.``.  The ABI version used by PyQt5 must have the
    same major number and a minor number no larger than the minor number
    implemented by the ``sip`` module.  By default PyQt5 will use the latest
    ABI version.  The option is ignored unless :program:`sip5` is being used.

.. cmdoption:: --allow-sip-warnings

    .. versionadded:: 5.9.1

    Normally any warning message generated by :program:`sip` is treated as an
    error.  This option causes warning messages to be considered non-fatal.  It
    is normally only required if a later version of :program:`sip` is being
    used that has deprecated a feature used by this version of PyQt5.

.. cmdoption:: --assume-shared

    Normally Qt is checked to see if it has been built as shared libraries.
    Some Linux distributions configure their Qt builds to make this check
    unreliable.  This option ignores the result of the check and assumes that
    Qt has been built as shared libraries.

.. cmdoption:: --bindir <DIR>

    The :program:`pyuic5`, :program:`pyrcc5` and :program:`pylupdate5`
    utilities will be installed in the directory ``<DIR>``.

.. cmdoption:: --concatenate

    The C++ source files for a Python module will be concatenated.  This
    results in significantly reduced compilation times.  Most, but not all,
    C++ compilers can handle the large files that result.  See also the
    :option:`--concatenate-split` option.

.. cmdoption:: --concatenate-split <N>

    If the :option:`--concatenate` option is used to concatenate the C++ source
    files then this option determines how many files are created.  The default
    is 1.

.. cmdoption:: --configuration <FILE>

    ``<FILE>`` contains the configuration of the PyQt5 build to be used instead
    of dynamically introspecting the system and is typically used when
    cross-compiling.  See :ref:`ref-configuration-files`.

.. cmdoption:: --confirm-license

    Using this confirms that you accept the terms of the PyQt5 license.  If it
    is omitted then you will be asked for confirmation during configuration.

.. cmdoption:: --dbus <DIR>

    The :file:`dbus-python.h` header file of the dbus-python package can be
    found in the directory ``<DIR>/dbus``.

.. cmdoption:: --debug

    The PyQt5 modules will be built with debugging symbols.  On Windows
    :program:`configure.py` must be run using a debug version of Python.

.. cmdoption:: --designer-plugindir <DIR>

    The Python plugin for Qt Designer will be installed in the directory
    ``<DIR>``.

.. cmdoption:: --destdir <DIR>

    The PyQt5 Python package will be installed in the directory ``<DIR>``.  The
    default is the Python installation's :file:`site-packages` directory.  If
    you use this option then the :envvar:`PYTHONPATH` environment variable must
    include ``<DIR>``.

.. cmdoption:: --disable <MODULE>

    .. versionadded:: 5.5.1

    Normally all PyQt5 modules are enabled and are built if the corresponding
    Qt library can be found.  This option will suppress the check for
    ``<MODULE>>``.  The option may be specified any number of times.

.. cmdoption:: --disable-feature <FEATURE>

    .. versionadded:: 5.10.1

    A PyQt5 module may be configured differently depending on the corresponding
    Qt configuration.  This takes the form of a set of features that may be
    disabled.  Normally this is determined automatically.  This option will
    explicitly disable the ``<FEATURE>>`` feature.  The option may be specified
    any number of times.

.. cmdoption:: --enable <MODULE>

    Normally all PyQt5 modules are enabled and are built if the corresponding
    Qt library can be found.  Using this option only those modules specifically
    enabled will be built.  The option may be specified any number of times.
    Note that using this option suppresses the checks that are normally made to
    determine how the module should be configured, i.e. which features should
    be disabled.

.. cmdoption:: --license-dir <DIR>

    The license files needed by the commercial version of PyQt5 can be found in
    the directory ``<DIR>``.

.. cmdoption:: --link-full-dll

    .. versionadded:: 5.8

    On Windows the full Python API and the limited API (as used by PyQt) are
    implemented in different DLLs.  Normally the limited DLL is linked (unless
    a debug version of the Python interpreter is being used to run 
    :program:`configure.py`).  This option forces the full API DLL to be linked
    instead.

.. cmdoption:: --no-designer-plugin

    The Qt Designer plugin will not be built.

.. cmdoption:: --no-dist-info

    .. versionadded:: 5.11

    This disables the creation of the PEP 376 ``.dist-info`` directory.
    Starting with this version a ``.dist-info`` directory is created.  This
    contains meta-data about the installation including version information for
    dependent packages.  It also means that ``pip`` can be used to uninstall
    the package.

.. cmdoption:: --no-docstrings

    The PyQt5 modules will not contain automatically generated docstrings.

.. cmdoption:: --no-python-dbus

    The Qt support for the standard Python DBus bindings is disabled.

.. cmdoption:: --no-qml-plugin

    The :program:`qmlscene` plugin will not be built.

.. cmdoption:: --no-qsci-api

    The :file:`PyQt5.api` QScintilla API file is not installed even if
    QScintilla does appear to be installed.

.. cmdoption:: --no-sip-files

    The ``.sip`` files for the PyQt5 modules will not be installed.

.. cmdoption:: --no-stubs

    .. versionadded:: 5.6

    The PEP 484 type hint stub files for the PyQt5 modules will not be
    installed.  This option is ignored (and the stub files are not installed)
    for versions of Python earlier than v3.5.

.. cmdoption:: --no-tools

    .. versionadded:: 5.3

    The ``pyuic5``, ``pyrcc5`` and ``pylupdate5`` tools will not be built.

.. cmdoption:: --no-timestamp

    Normally the header comments of each generated C/C++ source file includes
    a timestamp corresponding to when the file was generated.  This option
    suppresses the inclusion of the timestamp.

.. cmdoption:: --protected-is-public

    On certain platforms the size of PyQt5 modules can be significantly reduced
    by redefining the C++ ``protected`` keyword as ``public`` during
    compilation.  This option enables this behaviour and is the default on
    Linux and macOS.

.. cmdoption:: --protected-not-public

    The default redefinition of ``protected`` to ``public`` during compilation
    on Linux and macOS is disabled.

.. cmdoption:: --pyuic5-interpreter <FILE>

    ``<FILE>`` is the name of the Python interpreter used in the pyuic5
    wrapper.  The default is platform dependent.

.. cmdoption:: --qmake <FILE>

    Qt's :program:`qmake` program is used to determine how your Qt installation
    is laid out.  Normally :program:`qmake` is found on your :envvar:`PATH`.
    This option can be used to specify a particular instance of
    :program:`qmake` to use.

.. cmdoption:: --qml-debug

    .. versionadded:: 5.8

    Enable the QML debugging infrastructure.  This should not be enabled in a
    production environment.

.. cmdoption:: --qml-plugindir <DIR>

    The Python plugin for :program:`qmlscene` will be installed in the
    directory ``<DIR>``.

.. cmdoption:: --qsci-api

    The :file:`PyQt5.api` QScintilla API file is installed even if QScintilla
    does not appear to be installed.  This option is implied if the
    :option:`--qsci-api-destdir` option is specified.

.. cmdoption:: --qsci-api-destdir <DIR>

    The QScintilla API file will be installed in the :file:`python`
    subdirectory of the :file:`api` subdirectory of the directory ``<DIR>``.

.. cmdoption:: --qtconf-prefix <DIR>

    .. versionadded:: 5.6

    A ``qt.conf`` file is embedded in the :sip:ref:`PyQt5.QtCore` module with
    ``Prefix`` set to ``<DIR>`` which is assumed to be relative to the
    directory that the :sip:ref:`PyQt5.QtCore` module will be installed in.

.. cmdoption:: --sip <FILE>

    The :program:`sip` program is used to generate PyQt5's C++ source code.
    Normally :program:`sip` is found on your :envvar:`PATH`.  This option can
    be used to specify a particular instance of :program:`sip` to use.

.. cmdoption:: --sip-incdir <DIR>

    The ``sip.h`` header file can be found in the directory ``<DIR>``.

.. cmdoption:: --sipdir <DIR>

    The ``.sip`` files for the PyQt5 modules will be installed in the directory
    ``<DIR>``.

.. cmdoption:: --spec <SPEC>

    The argument ``-spec SPEC`` will be passed to :program:`qmake`.  The
    default behaviour is platform specific.  On Windows :program:`configure.py`
    will choose the value that is correct for the version of Python that is
    being used.  (However if you have built Python yourself then you may need
    to explicitly specify ``<SPEC>``.)  On macOS :program:`configure.py` will
    try and avoid ``macx-xcode`` if possible.)

.. cmdoption:: --static

    The PyQt5 modules will be built as static libraries.  This is useful when
    building a custom interpreter with the PyQt5 modules built in to the
    interpreter.

.. cmdoption:: --stubsdir <DIR>

    .. versionadded:: 5.6

    The PEP 484 type hint stub files for the PyQt5 modules will be installed in
    the directory ``<DIR>``.  By default they will be stored in the same
    directory where (by default) the corresponding extension modules would be
    installed.  This option is ignored (and the stub files are not installed)
    for versions of Python earlier than v3.5.

.. cmdoption:: --sysroot <DIR>

    .. versionadded:: 5.3

    ``<DIR>`` is the name of an optional directory that replaces ``sys.prefix``
    in the names of other directories (specifically those specifying where the
    various PyQt5 components will be installed and where the Python include and
    library directories can be found).  It is typically used when
    cross-compiling or when building a static version of PyQt5.  See
    :ref:`ref-configuration-files`.

.. cmdoption:: --target-py-version <VERSION>

    .. versionadded:: 5.3

    ``<VERSION>`` is the major and minor version (e.g. ``3.4``) of the version
    of Python being targetted.  By default the version of Python being used to
    run the :program:`configure.py` script is used.  It is typically used when
    cross-compiling.  See :ref:`ref-configuration-files`.

.. cmdoption:: --trace

    The generated PyQt5 modules contain additional tracing code that is enabled
    using SIP's :func:`sip.settracemask` function.

.. cmdoption:: --verbose

    Compiler commands and any output issued during configuration is displayed
    instead of being suppressed.  Use this if :program:`configure.py` is having
    problems to see what exactly is going wrong.

.. cmdoption:: --version

    Display the version number and exit.

Any remaining command line arguments are expected to be in the form
``name=value`` or ``name+=value``.  Such arguments are added to any
:program:`qmake` ``.pro`` file created by :program:`configure.py`.


Building PyQt5
..............

The next step is to build PyQt5 by running your platform's :program:`make`
command.  For example::

    make

The final step is to install PyQt5 by running the following command::

    make install

(Depending on your system you may require root or administrator privileges.)

This will install the various PyQt5 components.


Installing PyQt3D, PyQtChart, PyQtDataVisualization and PyQtPurchasing
----------------------------------------------------------------------

These additional packages are built and installed in exactly the same way as
PyQt5 itself.  In other words the source packages contain a ``configure.py``
script and binary wheels can be installed from PyPI.


.. _ref-pyqt-bundle:

Bundling Qt Using :program:`pyqt-bundle`
----------------------------------------

The wheels of the GPL version of PyQt5 on PyPI bundle a copy of the relevant
parts of Qt.  This is done so that users can install a complete PyQt
environment with a single :program:`pip` install.  A new release of Qt does not
require a new release of PyQt but does require an update of the wheels to
include the updated Qt.  Only the wheels for the PyQt version with the same
minor version number as the Qt version are updated.  In other words when a new
release of Qt v5.*n* is made, only the wheels for PyQt v5.*n* are updated.

However, given the ABI guarantees made by Qt (i.e. that a later version or Qt
should be able to replace an earlier version without having to re-compile an
application) then it should be perfectly possible to bundle a later version of
Qt that has a later minor version number with a version of PyQt that has an
earlier minor version number.  For example it should be possible to bundle Qt
v5.12.5 with PyQt v5.9.0.  The other use case is when you want to bundle a
development version of Qt with a version of PyQt so that the development
version can be tested in a Python environment.

The wheels of the commercial version of PyQt do not have a copy of Qt bundled
because it is not possible to distribute a copy of the commercial version of
Qt.  Therefore a commercial user must bundle their own copy of Qt to create a
complete wheel.

The :program:`pyqt-bundle` program is provided as a means of bundling the
relevant parts of a local Qt installation with a wheel, replacing any existing
copy.  It is part of `PyQt-builder <https://pypi.org/project/PyQt-builder/>`__
which can be installed by running::

    pip install PyQt-builder

:program:`pyqt-bundle` assumes that the Qt installation has been created from
one of the LGPL or commercial binary installers provided by The Qt Company.  It
may also work with a Qt installation built from source but this is unsupported.

On Linux you must have the :program:`chrpath` program installed.

On macOS you must have the :program:`install_name_tool` program installed.
This is a part of Xcode.

On Windows the binary installer for MSVC 2015 or MSVC 2017 must be used.  Also
on Windows :program:`pyqt-bundle` also handles the MSVC runtime DLLs and the
OpenSSL DLLs.

.. note::
    The ABI guarantees made by Qt do not apply to the
    :sip:ref:`~PyQt5.QAxContainer` module.  This is only guaranteed to work if
    the version of Qt being bundled is exactly the same as the version of Qt
    that PyQt was built against.

The syntax of the :program:`pyqt-bundle` command line is::

    pyqt-bundle [options] wheel

The full set of command line options is:

.. program:: pyqt-bundle

.. option:: -h, --help

    Display a help message and exit.

.. option:: -V, --version

    Display the version number and exit.

.. option:: --build-tag-suffix SUFFIX

    ``SUFFIX`` is appended to the build tag in the name of the updated wheel.
    The build tag is the version number of the copy of Qt being bundled.

.. option:: --no-msvc-runtime

    On Windows the :file:`msvcp140.dll`, :file:`concrt140.dll` and
    :file:`vcruntime140.dll` MSVC runtime DLLs will not be included in the
    wheel.

.. option:: --no-openssl

    On Windows the OpenSSL DLLs (included with :program:`pyqt-bundle`) will not
    be included in the wheel.

.. option:: --openssl-dir DIR

    On Windows the OpenSSL DLLs included in the wheels are taken from ``DIR``
    instead of the DLLs included with :program:`pyqt-bundle`.  (Qt v5.12.4 and
    later are configured for OpenSSL v1.1.1.  Earlier versions of Qt are
    configured for OpenSSL v1.0.2.)

.. option:: --qt-dir DIR

    ``DIR`` contains the LGPL or commercial Qt installation to be bundled.  The
    directory is what Qt refers to as the *prefix* directory, i.e. the
    architecture specific directory containing the ``bin``, ``lib`` etc.
    directories.  This option must be specified.

By convention a wheel (e.g. a commercial wheel) without a copy of Qt bundled
does not have a build tag.  A wheel with a copy of Qt bundled has a build tag
corresponding to the version of Qt.
