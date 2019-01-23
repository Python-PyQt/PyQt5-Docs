.. sip:method-description::
    :status: todo
    :pysig: 706b6094f305008096863a45e92da902
    :realsig: (QUrl::FormattingOptions) const
    :digest: bfbbfa06a5d5895906d4ded35d0fe5d5

Returns a string representation of the URL. The output can be customized by passing flags with *options*. The option :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.FullyDecoded` is not permitted in this function since it would generate ambiguous data.

The default formatting option is PrettyDecoded.

.. seealso:: FormattingOptions, :sip:ref:`~PyQt5.QtCore.QUrl.url`.
