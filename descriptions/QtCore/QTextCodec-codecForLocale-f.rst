.. sip:method-description::
    :status: todo
    :pysig: cd02528b96e2954d58dc02e6307186cc
    :realsig: ()
    :digest: 4b192fae7b3aa1c40f96f3df93e58692

Returns a pointer to the codec most suitable for this locale.

On Windows, the codec will be based on a system locale. On Unix systems, the codec will might fall back to using the *iconv* library if no builtin codec for the locale can be found.

Note that in these cases the codec's name will be "System".

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTextCodec.setCodecForLocale`.
