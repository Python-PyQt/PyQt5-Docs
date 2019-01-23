.. sip:method-description::
    :status: todo
    :pysig: d7eb8f2a66339e995244a3835a72b4b1
    :realsig: (int,int) const
    :digest: 0667d830cf8463f33a6bf490eac9ada2

Reimplement this function to pass certain key events to the ActiveX control. *message* is the Window message identifier specifying the message type (ie. WM_KEYDOWN), and *keycode* is the virtual keycode (ie. VK_TAB).

If the function returns true the key event is passed on to the ActiveX control, which then either processes the event or passes the event on to Qt.

If the function returns false the processing of the key event is ignored by `ActiveQt <https://doc.qt.io/qt-5/activeqt-index.html>`_, ie. the ActiveX control might handle it or not.

The default implementation returns true for the following cases:

+---------------+-------------+----------------------------------------------------------------------------------------------+
| WM_SYSKEYDOWN | WM_SYSKEYUP | WM_KEYDOWN                                                                                   |
+===============+=============+==============================================================================================+
| All keycodes  | VK_MENU     | VK_TAB, VK_DELETE and all non-arrow-keys in combination with VK_SHIFT, VK_CONTROL or VK_MENU |
+---------------+-------------+----------------------------------------------------------------------------------------------+

This table is the result of experimenting with popular ActiveX controls, ie. Internet Explorer and Microsoft Office applications, but for some controls it might require modification.
