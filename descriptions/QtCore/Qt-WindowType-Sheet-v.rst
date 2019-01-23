.. sip:enum-member-description::
    :status: todo
    :value: 0x00000004 | Window
    :digest: 26b901c8f8b997e67f9041da49eb821c

Indicates that the window is a sheet on `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_. Since using a sheet implies window modality, the recommended way is to use :sip:ref:`~PyQt5.QtWidgets.QWidget.setWindowModality`, or QDialog::open(), instead.
