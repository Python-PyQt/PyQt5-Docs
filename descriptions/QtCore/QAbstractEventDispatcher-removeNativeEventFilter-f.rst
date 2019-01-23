.. sip:method-description::
    :status: todo
    :pysig: 6684e489fe789d40e97ca035d533b2fc
    :realsig: (QAbstractNativeEventFilter*)
    :digest: 347332b6d44faa5b336c978af926ed39

Removes the event filter *filter* from this object. The request is ignored if such an event filter has not been installed.

All event filters for this object are automatically removed when this object is destroyed.

It is always safe to remove an event filter, even during event filter filter activation (that is, even from within the :sip:ref:`~PyQt5.QtCore.QAbstractNativeEventFilter.nativeEventFilter` function).

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractEventDispatcher.installNativeEventFilter`, :sip:ref:`~PyQt5.QtCore.QAbstractNativeEventFilter`.
