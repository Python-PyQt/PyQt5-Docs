.. sip:method-description::
    :status: todo
    :pysig: ebb6ca28dbb3c347e045d9f9ae65d112
    :realsig: (QUrl::ComponentFormattingOptions) const
    :digest: 82d59e668dc7836dd051ec8ad380ff2d

Returns the user info of the URL, or an empty string if the user info is undefined.

This function returns an unambiguous value, which may contain that characters still percent-encoded, plus some control sequences not representable in decoded form in QString.

The *options* argument controls how to format the user info component. The value of :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.FullyDecoded` is not permitted in this function. If you need to obtain fully decoded data, call :sip:ref:`~PyQt5.QtCore.QUrl.userName` and :sip:ref:`~PyQt5.QtCore.QUrl.password` individually.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QUrl.setUserInfo`, :sip:ref:`~PyQt5.QtCore.QUrl.userName`, :sip:ref:`~PyQt5.QtCore.QUrl.password`, :sip:ref:`~PyQt5.QtCore.QUrl.authority`.
