.. sip:method-description::
    :status: todo
    :pysig: 627ac1e41dfcc75a9a02f0669131d228
    :realsig: (WId,int,int,int,int)
    :digest: 020a581eb4fa9840be117f0fabc1a628

Creates and returns a pixmap constructed by grabbing the contents of the given *window* restricted by :sip:ref:`~PyQt5.QtCore.QRect`\ (\ *x*, *y*, *width*, *height*).

The arguments (\ *x*, *y*) specify the offset in the window, whereas (\ *width*, *height*) specify the area to be copied. If *width* is negative, the function copies everything to the right border of the window. If *height* is negative, the function copies everything to the bottom of the window.

The window system identifier (``WId``) can be retrieved using the :sip:ref:`~PyQt5.QtWidgets.QWidget.winId` function. The rationale for using a window identifier and not a :sip:ref:`~PyQt5.QtWidgets.QWidget`, is to enable grabbing of windows that are not part of the application, window system frames, and so on.

**Warning:** Grabbing windows that are not part of the application is not supported on systems such as iOS, where sandboxing/security prevents reading pixels of windows not owned by the application.

The  function grabs pixels from the screen, not from the window, i.e. if there is another window partially or entirely over the one you grab, you get pixels from the overlying window, too. The mouse cursor is generally not grabbed.

Note on X11 that if the given *window* doesn't have the same depth as the root window, and another window partially or entirely obscures the one you grab, you will *not* get pixels from the overlying window. The contents of the obscured areas in the pixmap will be undefined and uninitialized.

On Windows Vista and above grabbing a layered window, which is created by setting the :sip:ref:`~PyQt5.QtCore.Qt.WidgetAttribute.WA_TranslucentBackground` attribute, will not work. Instead grabbing the desktop widget should work.

**Warning:** In general, grabbing an area outside the screen is not safe. This depends on the underlying window system.
