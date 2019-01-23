.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: (int)
    :digest: c75522ea8fd035adeabe6bcd19cc413b

Sets the base of integers to *base*, both for reading and for generating numbers. *base* can be either 2 (binary), 8 (octal), 10 (decimal) or 16 (hexadecimal). If *base* is 0, :sip:ref:`~PyQt5.QtCore.QTextStream` will attempt to detect the base by inspecting the data on the stream. When generating numbers, :sip:ref:`~PyQt5.QtCore.QTextStream` assumes base is 10 unless the base has been set explicitly.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTextStream.integerBase`, :sip:ref:`~PyQt5.QtCore.QTextStream.setNumberFlags`.
