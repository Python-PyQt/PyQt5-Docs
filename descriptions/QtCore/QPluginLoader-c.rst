.. sip:class-description::
    :status: todo
    :brief: Loads a plugin at run-time
    :digest: cda24b604b1f9d3b2de1eb9e4962bf23

The :sip:ref:`~PyQt5.QtCore.QPluginLoader` class loads a plugin at run-time.

:sip:ref:`~PyQt5.QtCore.QPluginLoader` provides access to a Qt plugin. A Qt plugin is stored in a shared library (a DLL) and offers these benefits over shared libraries accessed using :sip:ref:`~PyQt5.QtCore.QLibrary`:

* :sip:ref:`~PyQt5.QtCore.QPluginLoader` checks that a plugin is linked against the same version of Qt as the application.

* :sip:ref:`~PyQt5.QtCore.QPluginLoader` provides direct access to a root component object (instance()), instead of forcing you to resolve a C function manually.

An instance of a :sip:ref:`~PyQt5.QtCore.QPluginLoader` object operates on a single shared library file, which we call a plugin. It provides access to the functionality in the plugin in a platform-independent way. To specify which plugin to load, either pass a file name in the constructor or set it with setFileName().

The most important functions are load() to dynamically load the plugin file, isLoaded() to check whether loading was successful, and instance() to access the root component in the plugin. The instance() function implicitly tries to load the plugin if it has not been loaded yet. Multiple instances of :sip:ref:`~PyQt5.QtCore.QPluginLoader` can be used to access the same physical plugin.

Once loaded, plugins remain in memory until all instances of :sip:ref:`~PyQt5.QtCore.QPluginLoader` has been unloaded, or until the application terminates. You can attempt to unload a plugin using unload(), but if other instances of :sip:ref:`~PyQt5.QtCore.QPluginLoader` are using the same library, the call will fail, and unloading will only happen when every instance has called unload(). Right before the unloading happen, the root component will also be deleted.

See How to Create Qt Plugins for more information about how to make your application extensible through plugins.

Note that the :sip:ref:`~PyQt5.QtCore.QPluginLoader` cannot be used if your application is statically linked against Qt. In this case, you will also have to link to plugins statically. You can use :sip:ref:`~PyQt5.QtCore.QLibrary` if you need to load dynamic libraries in a statically linked application.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QLibrary`, `Plug & Paint Example <https://doc.qt.io/qt-5/qtwidgets-tools-plugandpaint-app-example.html>`_.
