.. sip:class-description::
    :status: todo
    :brief: Iterator on the results of a global match of a QRegularExpression object against a string
    :digest: 8cee006380b490e8f59c335052cf1d41

The :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator` class provides an iterator on the results of a global match of a :sip:ref:`~PyQt5.QtCore.QRegularExpression` object against a string.

A :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator` object is a forward only Java-like iterator; it can be obtained by calling the :sip:ref:`~PyQt5.QtCore.QRegularExpression.globalMatch` function. A new :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator` will be positioned before the first result. You can then call the :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator.hasNext` function to check if there are more results available; if so, the :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator.next` function will return the next result and advance the iterator.

Each result is a :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch` object holding all the information for that result (including captured substrings).

For instance:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 344-351

Moreover, :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator` offers a :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator.peekNext` function to get the next result *without* advancing the iterator.

You can retrieve the :sip:ref:`~PyQt5.QtCore.QRegularExpression` object the subject string was matched against by calling the :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator.regularExpression` function; the match type and the match options are available as well by calling the :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator.matchType` and the :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator.matchOptions` respectively.

Please refer to the :sip:ref:`~PyQt5.QtCore.QRegularExpression` documentation for more information about the Qt regular expression classes.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QRegularExpression`, :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch`.
