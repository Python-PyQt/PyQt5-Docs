.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: (bool)
    :digest: a8cdc824cd6c698d17494118080b5dc3

Sets whether swizzling is enabled for the red and blue color channels to *swizzle*. An BGRA to RGBA conversion (occurring in the shader on the GPU, instead of a slow CPU-side transformation) can be useful when the source texture contains data from a :sip:ref:`~PyQt5.QtGui.QImage` with a format like :sip:ref:`~PyQt5.QtGui.QImage.Format.Format_ARGB32` which maps to BGRA on little endian systems.

By default the red-blue swizzle is disabled since this is what a texture attached to an framebuffer object or a texture based on a byte ordered :sip:ref:`~PyQt5.QtGui.QImage` format (like QImage::Format_RGBA8888) needs.
