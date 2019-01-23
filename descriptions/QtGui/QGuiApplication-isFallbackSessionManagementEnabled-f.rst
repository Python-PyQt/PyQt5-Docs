.. sip:method-description::
    :status: todo
    :pysig: 01111d32dddd979ac6254452ab6fef9b
    :realsig: ()
    :digest: 34d7f2657f75e93968ae34a2b29472f1

Returns whether :sip:ref:`~PyQt5.QtGui.QGuiApplication` will use fallback session management.

The default is ``true``.

If this is ``true`` and the session manager allows user interaction, :sip:ref:`~PyQt5.QtGui.QGuiApplication` will try to close toplevel windows after :sip:ref:`~PyQt5.QtGui.QGuiApplication.commitDataRequest` has been emitted. If a window cannot be closed, session shutdown will be canceled and the application will keep running.

Fallback session management only benefits applications that have an "are you sure you want to close this window?" feature or other logic that prevents closing a toplevel window depending on certain conditions, and that do nothing to explicitly implement session management. In applications that *do* implement session management using the proper session management API, fallback session management interferes and may break session management logic.

**Warning:** If all windows *are* closed due to fallback session management and :sip:ref:`~PyQt5.QtGui.QGuiApplication.quitOnLastWindowClosed` is ``true``, the application will quit before it is explicitly instructed to quit through the platform's session management protocol. That violation of protocol may prevent the platform session manager from saving application state.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QGuiApplication.setFallbackSessionManagementEnabled`, :sip:ref:`~PyQt5.QtGui.QSessionManager.allowsInteraction`, :sip:ref:`~PyQt5.QtGui.QGuiApplication.saveStateRequest`, :sip:ref:`~PyQt5.QtGui.QGuiApplication.commitDataRequest`.
