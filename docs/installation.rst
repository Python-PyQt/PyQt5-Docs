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
they are provided for the GPL version:

- it is not possible to distribute a copy of the commercial version of Qt

- the user's license information has to be applied.

The :program:`pyqt-bundle` program must be used to bundle your copy of Qt with
the provided commercial wheels.

The provided commercial PyQt5 wheel is *unlicensed* and will not run if it is
installed.  First the :program:`pyqtlicense` program must be run to create a
*licensed* wheel from your :file:`pyqt-commercial.sip` license file.

The other provided commercial wheels (for PyQtWebEngine, PyQt3D etc.) do not
need to be licensed but do need to have the relevant parts of Qt bundled.

The syntax of the :program:`pyqtlicense` command line is::

    pyqtlicense [options] unlicensed-wheel

The full set of command line options is:

.. program:: pyqtlicense

.. option:: -h, --help

    Display a help message and exit.

.. option:: -V, --version

    Display the version number and exit.

.. option:: --license FILE

    This specifies that ``FILE`` is the license file.

.. option:: --output DIR

    This specifies that the licensed wheel will be written to the directory
    ``DIR``.

To uninstall the commercial version, run::

    pip uninstall PyQt5-commercial


Building and Installing from Source
-----------------------------------

Building the :sip:ref:`~PyQt5.sip` Module
.........................................

Like any other, the :sip:ref:`~PyQt5.sip` module sdist can be built and
installed by :program:`pip`.  As it uses :py:mod:`setuptools` as its build
system you can also unpack the sdist and install it by running its
:program:`setup.py` script.


Building PyQt5
..............

:program:`pip` can also be used to build and install PyQt5 from its sdist.
However you must make sure that your Qt installation's :program:`qmake` program
can be found on :envvar:`PATH`.  If you do not do this then you will get a
cryptic error message from :program:`pip`.

The recommended method of building PyQt5 from source is to unpack the sdist and
use SIP's :program:`sip-install` program.  You must first install `PyQt-builder
<https://pypi.org/project/PyQt-builder/>`__ by running::

    pip install PyQt-builder

This will automatically install :program:`sip-install` if necessary.


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
copy.  It is part of `PyQt-builder <https://pypi.org/project/PyQt-builder/>`__.

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
