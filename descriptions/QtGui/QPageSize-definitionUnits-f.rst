.. sip:method-description::
    :status: todo
    :pysig: 94e4ac8eb1a4a7466033a877ca7f073a
    :realsig: () const
    :digest: 96aa3c1b367cf1b5e277f6bb3e43e5a7

Returns the definition units of the page size.

For a standard page size this will be the units as defined in the relevant standard, i.e. ISO A4 will be defined in millimeters while ANSI Letter will be defined in inches.

For a custom page size this will be the original units used to create the page size object.

If the :sip:ref:`~PyQt5.QtGui.QPageSize` is invalid then the :sip:ref:`~PyQt5.QtGui.QPageSize.Unit` will be invalid.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPageSize.definitionSize`.
