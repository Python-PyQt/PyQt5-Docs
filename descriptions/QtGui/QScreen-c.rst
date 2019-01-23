.. sip:class-description::
    :status: todo
    :brief: Used to query screen properties
    :digest: f90c15f20b6cfa1774fccbf670acaa67

The :sip:ref:`~PyQt5.QtGui.QScreen` class is used to query screen properties.

A note on logical vs physical dots per inch: physical DPI is based on the actual physical pixel sizes when available, and is useful for print preview and other cases where it's desirable to know the exact physical dimensions of screen displayed contents.

Logical dots per inch are used to convert font and user interface elements from point sizes to pixel sizes, and might be different from the physical dots per inch. The logical dots per inch are sometimes user-settable in the desktop environment's settings panel, to let the user globally control UI and font sizes in different applications.
