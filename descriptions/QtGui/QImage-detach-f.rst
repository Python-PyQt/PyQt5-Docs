.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 445a1b9553547610171200b421591891

If multiple images share common data, this image makes a copy of the data and detaches itself from the sharing mechanism, making sure that this image is the only one referring to the data.

Nothing is done if there is just a single reference.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImage.copy`, `Implicit Data Sharing <https://doc.qt.io/qt-5/implicit-sharing.html>`_.
