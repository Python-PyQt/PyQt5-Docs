.. sip:method-description::
    :status: todo
    :pysig: 9a6a20c9149023b4c3afcea8778e38ee
    :realsig: (QXmlStreamEntityResolver*)
    :digest: dceba3217834cff4f00d7f0538115dd2

Makes *resolver* the new :sip:ref:`~PyQt5.QtCore.QXmlStreamReader.entityResolver`.

The stream reader does *not* take ownership of the resolver. It's the callers responsibility to ensure that the resolver is valid during the entire life-time of the stream reader object, or until another resolver or 0 is set.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QXmlStreamReader.entityResolver`.
