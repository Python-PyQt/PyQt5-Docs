.. sip:class-description::
    :status: todo
    :brief: The input data for the QXmlReader subclasses
    :digest: 65dcc6b43ff1fc0eb01acd92f2d444b1

The :sip:ref:`~PyQt5.QtXml.QXmlInputSource` class provides the input data for the :sip:ref:`~PyQt5.QtXml.QXmlReader` subclasses.

All subclasses of :sip:ref:`~PyQt5.QtXml.QXmlReader` read the input XML document from this class.

This class recognizes the encoding of the data by reading the encoding declaration in the XML file if it finds one, and reading the data using the corresponding encoding. If it does not find an encoding declaration, then it assumes that the data is either in UTF-8 or UTF-16, depending on whether it can find a byte-order mark.

There are two ways to populate the input source with data: you can construct it with a :sip:ref:`~PyQt5.QtCore.QIODevice`\* so that the input source reads the data from that device. Or you can set the data explicitly with one of the :sip:ref:`~PyQt5.QtXml.QXmlInputSource.setData` functions.

Usually you either construct a :sip:ref:`~PyQt5.QtXml.QXmlInputSource` that works on a :sip:ref:`~PyQt5.QtCore.QIODevice`\* or you construct an empty :sip:ref:`~PyQt5.QtXml.QXmlInputSource` and set the data with :sip:ref:`~PyQt5.QtXml.QXmlInputSource.setData`. There are only rare occasions where you would want to mix both methods.

The :sip:ref:`~PyQt5.QtXml.QXmlReader` subclasses use the :sip:ref:`~PyQt5.QtXml.QXmlInputSource.next` function to read the input character by character. If you want to start from the beginning again, use :sip:ref:`~PyQt5.QtXml.QXmlInputSource.reset`.

The functions :sip:ref:`~PyQt5.QtXml.QXmlInputSource.data` and :sip:ref:`~PyQt5.QtXml.QXmlInputSource.fetchData` are useful if you want to do something with the data other than parsing, e.g. displaying the raw XML file. The benefit of using the QXmlInputClass in such cases is that it tries to use the correct encoding.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlReader`, :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader`.
