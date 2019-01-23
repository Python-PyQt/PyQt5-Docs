.. sip:method-description::
    :status: todo
    :pysig: 7a3358e95d4f145bda830cea88a83ba4
    :realsig: (QResizeEvent*)
    :digest: f7d163acb960eb8e06c065a86e3f9c53

Override this to handle resize events (\ *ev*).

The resize event is called whenever the window is resized in the windowing system, either directly through the windowing system acknowledging a :sip:ref:`~PyQt5.QtGui.QWindow.setGeometry` or :sip:ref:`~PyQt5.QtGui.QWindow.resize` request, or indirectly through the user resizing the window manually.
