.. sip:method-description::
    :status: todo
    :pysig: eeb7da0d6e67a3b967fb3719b03f0feb
    :realsig: (const QByteArray&,bool)
    :digest: 7802d7cd165c796cd52f2907c9ee6b50

This function reads the XML file from *data* and tries to recognize the encoding. It converts the raw data *data* into a QString and returns it. It tries its best to get the correct encoding for the XML file.

If *beginning* is true, this function assumes that the data starts at the beginning of a new XML document and looks for an encoding declaration. If *beginning* is false, it converts the raw data using the encoding determined from prior calls.
