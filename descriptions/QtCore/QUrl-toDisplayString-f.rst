.. sip:method-description::
    :status: todo
    :pysig: 706b6094f305008096863a45e92da902
    :realsig: (QUrl::FormattingOptions) const
    :digest: c64f3e7e5dfb8418a9fbfbdb9d7ba5de

Returns a human-displayable string representation of the URL. The output can be customized by passing flags with *options*. The option :sip:ref:`~PyQt5.QtCore.QUrl.UrlFormattingOption.RemovePassword` is always enabled, since passwords should never be shown back to users.

With the default options, the resulting QString can be passed back to a :sip:ref:`~PyQt5.QtCore.QUrl` later on, but any password that was present initially will be lost.

.. seealso:: FormattingOptions, :sip:ref:`~PyQt5.QtCore.QUrl.toEncoded`, :sip:ref:`~PyQt5.QtCore.QUrl.toString`.
