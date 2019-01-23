.. sip:method-description::
    :status: todo
    :pysig: 49cd6c4846645627c7c8750fdcfb2bfd
    :realsig: (const QString&)
    :digest: dd6086191e69d9d37deb330151ea7264

Configures which categories and message types should be enabled through a a set of *rules*.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-qloggingcategory-main.py

**Note:** The rules might be ignored if a custom category filter is installed with installFilter(), or if the user defined ``QT_LOGGING_CONF`` or ``QT_LOGGING_RULES`` environment variable.
