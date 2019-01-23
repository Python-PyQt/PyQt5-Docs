.. sip:method-description::
    :status: todo
    :pysig: 774f2f32bc6286301c5b354ab5e50eb8
    :realsig: (QUrl::FormattingOptions) const
    :digest: a532e49322ff85c35875fd893adaa7aa

Returns an adjusted version of the URL. The output can be customized by passing flags with *options*.

The encoding options from :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption` don't make much sense for this method, nor does :sip:ref:`~PyQt5.QtCore.QUrl.UrlFormattingOption.PreferLocalFile`.

This is always equivalent to :sip:ref:`~PyQt5.QtCore.QUrl`\ (url.\ :sip:ref:`~PyQt5.QtCore.QUrl.toString`\ (options)).

.. seealso:: FormattingOptions, :sip:ref:`~PyQt5.QtCore.QUrl.toEncoded`, :sip:ref:`~PyQt5.QtCore.QUrl.toString`.
