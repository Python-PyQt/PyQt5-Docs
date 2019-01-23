.. sip:method-description::
    :status: todo
    :pysig: dc31d73e9f66487df226a55affb800eb
    :realsig: (const QString&,QObject*,const char*)
    :digest: e11623dd789165f7b73c5477d077d269

Sets the handler for the given *scheme* to be the handler *method* provided by the *receiver* object.

This function provides a way to customize the behavior of :sip:ref:`~PyQt5.QtGui.QDesktopServices.openUrl`. If :sip:ref:`~PyQt5.QtGui.QDesktopServices.openUrl` is called with a URL with the specified *scheme* then the given *method* on the *receiver* object is called instead of :sip:ref:`~PyQt5.QtGui.QDesktopServices` launching an external application.

The provided method must be implemented as a slot that only accepts a single :sip:ref:`~PyQt5.QtCore.QUrl` argument.

To use this function for receiving data from other apps on iOS you also need to add the custom scheme to the ``CFBundleURLSchemes`` list in your Info.plist file:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_util_qdesktopservices.py
    :lines: 82-90

For more information, see the Apple Developer Documentation for Communicating with Other Apps Using Custom URLs.

If  is used to set a new handler for a scheme which already has a handler, the existing handler is simply replaced with the new one. Since :sip:ref:`~PyQt5.QtGui.QDesktopServices` does not take ownership of handlers, no objects are deleted when a handler is replaced.

Note that the handler will always be called from within the same thread that calls :sip:ref:`~PyQt5.QtGui.QDesktopServices.openUrl`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QDesktopServices.openUrl`, :sip:ref:`~PyQt5.QtGui.QDesktopServices.unsetUrlHandler`.
