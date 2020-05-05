Installing PyQt5
================

Both the GPL and commercial versions of PyQt5 can be built from source packages
or installed from binary wheels.  Although this section concentrates on PyQt5
itself it applies equally to the related projects (i.e. PyQtWebEngine, PyQt3D,
PyQtChart, PyQtDataVisualization and PyQtPurchasing).


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

With PyQt5 the version number of PyQt5 is tied, to a certain extent, to the
version of Qt v5 so that:

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

- The patch versions of PyQt5 and Qt v5 are entirely unrelated to each other.

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

Wheels are installed using the :program:`pip` program that is included with
current versions of Python.


Installing the GPL Version
..........................

To install the wheel for the GPL version of PyQt5, run::

    pip install PyQt5

This will install the wheel for your platform and your version of Python
(assuming both are supported).  The wheel will be automatically downloaded from
PyPI.

If you get an error message saying that no downloads could be found that
satisfy the rquirement then you are probably using an unsupported version of
Python.

The PyQt5 wheel includes the necessary parts of the LGPL version of Qt.  There
is no need to install Qt yourself.  You can use the :program:`pyqt-bundle`
program to create a new wheel with a different version of Qt bundled.  See
:ref:`ref-pyqt-bundle` for the full details of how to do this.

The :sip:ref:`~PyQt5.sip` module is packaged as a separate wheel which will be
downloaded and installed automatically.

To uninstall the GPL version, run::

    pip uninstall PyQt5

.. note::
   Qt's support for TLS/SSL will not work on Windows when installing wheels
   that contain Qt v5.12.4 (or later) with Python v3.7.0 to v3.7.3.  This is
   because of incompatibilities between the different versions of OpenSSL that
   these versions require.  All other version combinations should be fine.


Installing the Commercial Version
.................................

It is not possible to provide wheels for the commercial version in the same way
they are provided for the GPL version as it is not possible to distribute a
copy of the commercial version of Qt.  Therefore the :program:`pyqt-bundle`
program must be used to bundle your own copy of Qt with the provided commercial
wheels.

.. note::

    The old Riverbank Computing website provided *unlicensed* commercial wheels
    that required you to download and run the :program:`pyqtlicense` program in
    order to create a *licensed* wheel.  The new Riverbank Computing website
    provides pre-licensed wheels and there is no need to run
    :program:`pyqtlicense`.

To uninstall the commercial version, run::

    pip uninstall PyQt5-commercial


Building and Installing from Source
-----------------------------------

Starting with PyQt5 v5.14.0 :program:`pip` can be used to download, build and
install the GPL source packages from the `PyQt5
<https://pypi.org/project/PyQt5/>`__ project at PyPI.  For this to work your
:envvar:`PATH` environment variable must contain your Qt installation's ``bin``
directory.  If you do not do this then you will get a cryptic error message
from :program:`pip`.

However using :program:`pip` to install from the source package is not
recommended as it is not possible to configure the installation or to easily
diagnose any problems.  The rest of these instructions assume that you have
downloaded the source package from PyPI and will used SIP's
:program:`sip-install` command line tool to do the build and installation.

If you are using the commercial version of PyQt5 then you should use the
download instructions which were sent to you when you made your purchase.  You
must also download your ``pyqt-commercial.sip`` license file.


Installing Prerequisites
........................

`PyQt-builder <https://pypi.org/project/PyQt-builder/>`__ extends the SIP build
system and can be installed from PyPI by running::

    pip install PyQt-builder

This will also automatically install SIP if required.

`PyQt-builder <https://pypi.org/project/PyQt-builder/>`__ and PyQt5 itself add
the following options to SIP's command line tools.

.. option:: --confirm-license

    Using this confirms that you accept the terms of the PyQt5 license.  If it
    is omitted then you will be asked for confirmation during configuration.

.. option:: --dbus DIR

    The directory containing the :file:`dbus/dbus-python.h` header file of the
    dbus-python package can be found in the directory ``DIR``.

.. option:: --license-dir DIR

    The license files needed by the commercial version of PyQt5 can be found in
    the directory ``DIR``.

.. option:: --link-full-dll

    On Windows the full Python API and the limited API (as used by PyQt5) are
    implemented in different DLLs.  Normally the limited DLL is linked (unless
    a debug version of the Python interpreter is being used.  This option
    forces the full API DLL to be linked instead.

.. option:: --no-dbus-python

    The Qt support for the dbus-python package will not be built.

.. option:: --no-designer-plugin

    The Qt Designer plugin will not be built.

.. option:: --no-make

    Do not automatically invoke :program:`make` or :program:`nmake`.
    (:program:`sip-build` only.)

.. option:: --no-qml-plugin

    The :program:`qmlscene` plugin will not be built.

.. option:: --no-tools

    The :program:`pyuic5`, :program:`pyrcc5` and :program:`pylupdate5` tools
    will not be built.

.. option:: --qmake FILE

    Qt's :program:`qmake` program is used to determine how your Qt installation
    is laid out.  Normally :program:`qmake` is found on your :envvar:`PATH`.
    This option can be used to specify a particular instance of
    :program:`qmake` to use.

.. option:: --qmake-settings 'NAME += VALUE'

    The setting will be added to any :program:`qmake` :file:`.pro` file that is
    created.  This option may be given any number of times.

.. option:: --qml-debug

    Enable the QML debugging infrastructure.  This should not be enabled in a
    production environment.

.. option:: --qt-shared

    Normally Qt is checked to see if it has been built as shared libraries.
    Some Linux distributions configure their Qt builds to make this check
    unreliable.  This option ignores the result of the check and assumes that
    Qt has been built as shared libraries.

.. option:: --spec SPEC

    The argument ``-spec SPEC`` will be passed to :program:`qmake`.  The
    default behaviour is platform specific.  On Windows
    the value that is chosen is correct for the version of Python that is
    being used.  (However if you have built Python yourself then you may need
    to explicitly specify ``SPEC``.)  On macOS ``macx-xcode`` will be avoided
    if possible.

The Mercurial repository containing the latest development version of
PyQt-builder can be found `here
<https://www.riverbankcomputing.com/hg/PyQt-builder/>`__.


Building the :sip:ref:`~PyQt5.sip` Module
.........................................

It is not necessary to install the :sip:ref:`PyQt5.sip` module before building
PyQt5 but it must be installed before PyQt5 can be used.  

The module is built using :py:mod:`setuptools` and is available from the
`PyQt5-sip <https://pypi.org/project/PyQt5-sip/>`__ project at PyPI.  It uses
:py:mod:`setuptools` as its build system and can be installed by :program:`pip`
or you can also unpack the sdist and install it by running its
:program:`setup.py` script.


Building PyQt5
..............

Once you have downloaded the source package from PyPI, unpack it and change
directory to its top level directory (i.e. the one containing the
:file:`pyproject.toml` file.  To build and install PyQt5, run::

    sip-install

In order to see all the available command line options, run::

    sip-install -h

If you want to run :program:`make` seperately then instead run::

    sip-build --no-make
    make
    make install


Building PyQt5-related Projects
...............................

The additional PyQt5 projects (i.e. PyQtWebEngine, PyQt3D, PyQtChart,
PyQtDataVisualization and PyQtPurchasing) are built and installed in exactly
the same way as PyQt5 itself.  PyQt5 must be built and installed first.


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
copy.  You can also use it to produce a stripped down version of PyQt that
contains only those modules you actually want to use.  :program:`pyqt-bundle`
is part of `PyQt-builder <https://pypi.org/project/PyQt-builder/>`__.

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

.. option:: --exclude NAME

    The ``NAME`` bindings are excluded from the wheel.  This option may be
    specified multiple times.

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
