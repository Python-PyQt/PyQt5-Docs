.. sip:method-description::
    :status: todo
    :pysig: 706b6094f305008096863a45e92da902
    :realsig: (QUrl::FormattingOptions) const
    :digest: b3c64a78c705af8ce17d8dda0c711c42

Returns a string representation of the URL. The output can be customized by passing flags with *options*. The option :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.FullyDecoded` is not permitted in this function since it would generate ambiguous data.

The resulting QString can be passed back to a :sip:ref:`~PyQt5.QtCore.QUrl` later on.

Synonym for :sip:ref:`~PyQt5.QtCore.QUrl.toString`\ (options).

.. seealso:: FormattingOptions, :sip:ref:`~PyQt5.QtCore.QUrl.toEncoded`, :sip:ref:`~PyQt5.QtCore.QUrl.toString`.
