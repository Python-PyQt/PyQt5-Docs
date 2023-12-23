Installing PyQt5
================

Both the GPL and commercial versions of PyQt5 can be built from sdists or
installed from binary wheels.  Although this section concentrates on PyQt5
itself it applies equally to the add-on projects (e.g. PyQt3D, PyQtNetworkAuth
etc.).


Understanding the Correct Version to Install
--------------------------------------------

People sometimes mistakenly believe that support for a particular version of Qt
requires a matching version of PyQt.

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
extension modules such as PyQt5.  Wheels are provide for 32- and 64-bit
Windows, 64-bit macOS (Intel and ARM) and 64-bit Linux.  These correspond with
the platforms for which The Qt Company provide binary installers.

Wheels are installed using the :program:`pip` program.


Installing the GPL Version
..........................

To install the wheel for the GPL version of PyQt5, run::

    pip install PyQt5

This will install the wheel for your platform and your version of Python
(assuming both are supported).  The wheel will be automatically downloaded from
`PyPI <https://pypi.org/project/PyQt5/>`__.

You may find that :program:`pip` doesn't download a wheel but instead downloads
the sdist and tries to build PyQt5 from source.  If it does then the build will
probably fail with a cryptic error message.  There are a number of reasons for
this:

- there is no wheel available for your platform and version of Python
- your version of Python is unsupported (e.g. v3.7)
- your version of :program:`pip` is too old and doesn't support the current
  standards for naming wheels
- in order for :program:`pip` to build from source additional options must be
  specified.

When using :program:`pip` to build from source then a command line similar to
the following should be used::

    pip -v install --config-settings --confirm-license= --config-settings --qmake=/path/to/qmake PyQt5

The ``-v`` option is not required but is recommended. The :program:`qmake`
location does not need to specified if it is on :envvar:`PATH`.

:program:`pip` will also automatically install any dependencies that are
required.  In the case of PyQt5 itself this will be the PyQt5-Qt5 and PyQt5-sip
projects.  The PyQt5-Qt5 project contains the parts of a standard LGPL Qt
installation required by PyQt5.  The PyQt5-sip project contains the
:sip:ref:`~PyQt5.sip` module.

.. note::
    If you want PyQt5 to use a copy of Qt that you already have installed then
    you need to build it from source.

To uninstall the GPL version, run::

    pip uninstall PyQt5

. note::
    The Qt libraries in the Linux wheel of the PyQt5-Qt5 project require
    OpenSSL v1.1 however some Linux distributions (specifically Ubuntu 22.04 at
    the time of writing) include the incompatible OpenSSL v3.

    The required version of OpenSSL can be downloaded from the Ubuntu 20.04
    repository by clicking `here
    <http://security.ubuntu.com/ubuntu/pool/main/o/openssl/libssl1.1_1.1.1f-1ubuntu2.16_amd64.deb>`__.

    The downloaded ``.deb`` file can then be installed by running::

        sudo apt install /path/to/libssl1.1_1.1.1f-1ubuntu2.16_amd64.deb


Installing the Commercial Version
.................................

Wheels are also provided for the commercial version of PyQt5 but they must be
downloaded from your account on the Riverbank Computing website.  Before you
install the downloaded wheel using :program:`pip` you must ensure you have an
appropriate Qt license and have decided how you want to distribute your PyQt5
wheels to your developers.

By default, installing the commercial PyQt5 wheel will do the same as
installing the GPL wheel, i.e. it will automatically download and install the
required parts of a standard LGPL Qt installation from PyPI.  There are a
number of reasons why you might not want to do this:

- you have a commercial Qt license and need to make sure that is used with
  PyQt5
- you don't allow your developers access to PyPI
- you want to minimise the number of wheels you need to distribute to your
  developers.

.. note::
    Some Qt libraries are licensed under the GPL rather than the LGPL.  If your
    own application license is compatibile with the LGPL but is incompatible
    with the GPL then you must make sure you do not use the corresponding PyQt
    modules (even though you have a commercial PyQt license).

The solution to all these issues is to use the :program:`pyqt-bundle` program
to bundle a copy of your own Qt installation with your commercial PyQt5.  This
will produce a new wheel that you can distribute easily to your developers.

:program:`pyqt-bundle` is part of `PyQt-builder
<https://pypi.org/project/PyQt-builder/>`__.  To install it, run::

    pip install PyQt-builder

The documentation can be found `here
<https://www.riverbankcomputing.com/static/Docs/PyQt-builder/pyqtbundle.html>`__.

To uninstall the commercial version, run::

    pip uninstall PyQt5-commercial


Building and Installing from Source
-----------------------------------

As described above :program:`pip` can be used to download, build and
install the GPL source packages from the `PyQt5
<https://pypi.org/project/PyQt5/>`__ project at PyPI.  However doing so is not
recommended as it is not easy to configure the installation or diagnose any
problems.

PyQt5 is built using `PyQt-builder <https://pypi.org/project/PyQt-builder/>`__.
To install it, run::

    pip install PyQt-builder

PyQt-builder is an extension to the `SIP <https://pypi.org/project/sip/>`__
bindings generator which will be installed automatically.

The rest of these instructions assume that you have downloaded the PyQt5 sdist
from `PyPI <https://pypi.org/project/PyQt5/>`__ and will used SIP's
:program:`sip-install` command line tool to do the build and installation.

If you are using the commercial version of PyQt6 then you should use the
download instructions which were sent to you when you made your purchase.  You
must also download your :file:`pyqt-commercial.sip` license file.

PyQt-builder extends the build system by adding `options
<https://www.riverbankcomputing.com//static/Docs/PyQt-builder/command_line_tools.html>`__
to SIP's `command line tools
<https://www.riverbankcomputing.com/static/Docs/sip/command_line_tools.html>`__.

PyQt5 further extends the build system by adding the following options to SIP's
command line tools.

.. option:: --confirm-license

    Using this confirms that you accept the terms of the PyQt license.  If it
    is omitted then you will be asked for confirmation during configuration.

.. option:: --dbus DIR

    The directory containing the :file:`dbus/dbus-python.h` header file of the
    dbus-python package can be found in the directory ``DIR``.

.. option:: --license-dir DIR

    The :file:`pyqt-commercial,sip` license file needed by the commercial
    version of PyQt5 can be found in the directory ``DIR``.  By default it is
    assumed that you have copied it to the :file:`sip` sub-directory of the 
    unpacked sdist.

.. option:: --no-dbus-python

    The Qt support for the dbus-python package will not be built.

.. option:: --no-designer-plugin

    The Qt Designer plugin will not be built.

.. option:: --no-qml-plugin

    The :program:`qmlscene` plugin will not be built.

.. option:: --no-tools

    The :program:`pyuic5`, :program:`pyrcc5` and :program:`pylupdate5` tools
    will not be built.

.. option:: --qt-shared

    Normally Qt is checked to see if it has been built as shared libraries.
    Some Linux distributions configure their Qt builds to make this check
    unreliable.  This option ignores the result of the check and assumes that
    Qt has been built as shared libraries.


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

Once you have downloaded the sdist from PyPI, unpack it and change
directory to its top level directory (i.e. the one containing the
:file:`pyproject.toml` file.

If you are building the commercial version of PyQt5 then copy the
:file:`pyqt-commercial.sip` license file to the :file:`sip` sub-directory.

To build and install PyQt5, run::

    sip-install

In order to see all the available command line options, run::

    sip-install -h

If you want to run :program:`make` seperately then instead run::

    sip-build --no-make
    make
    make install


Building PyQt5 Add-on Projects
..............................

The additional PyQt5 projects (i.e. PyQtNetworkAuth, PyQtWebEngine, PyQt3D,
PyQtChart, PyQtDataVisualization and PyQtPurchasing) are built and installed in
exactly the same way as PyQt5 itself.  PyQt5 must be built and installed first.
