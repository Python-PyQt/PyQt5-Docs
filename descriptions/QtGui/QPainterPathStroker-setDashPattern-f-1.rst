.. sip:method-description::
    :status: todo
    :pysig: 13ab3c5e77307569196120fd7ddfef82
    :realsig: (const QVector<qreal>&)
    :digest: 1389b1f8c220152cd269fae37546cc4a

This is an overloaded function.

Sets the dash pattern for the generated outlines to *dashPattern*. This function makes it possible to specify custom dash patterns.

Each element in the vector contains the lengths of the dashes and spaces in the stroke, beginning with the first dash in the first element, the first space in the second element, and alternating between dashes and spaces for each following pair of elements.

The vector can contain an odd number of elements, in which case the last element will be extended by the length of the first element when the pattern repeats.
