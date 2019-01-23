.. sip:method-description::
    :status: todo
    :pysig: 0a4930f766b1cc290b03b805c13d02be
    :realsig: (QUrl::ComponentFormattingOptions) const
    :digest: 31c344f8a1f56ef8e6ceceb6c0a534bc

Returns the password of the URL if it is defined; otherwise an empty string is returned.

The *options* argument controls how to format the user name component. All values produce an unambiguous result. With :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.FullyDecoded`, all percent-encoded sequences are decoded; otherwise, the returned value may contain some percent-encoded sequences for some control sequences not representable in decoded form in QString.

Note that :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.FullyDecoded` may cause data loss if those non-representable sequences are present. It is recommended to use that value when the result will be used in a non-URL context, such as setting in :sip:ref:`~PyQt5.QtNetwork.QAuthenticator` or negotiating a login.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QUrl.setPassword`.
