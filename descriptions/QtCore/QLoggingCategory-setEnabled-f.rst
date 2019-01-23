.. sip:method-description::
    :status: todo
    :pysig: 0d86759cfe78611c078e8ac72aa79f8b
    :realsig: (QtMsgType,bool)
    :digest: 71a5d8475b2ad784203728c0e2d960b5

Changes the message type *type* for the category to *enable*.

This method is meant to be used only from inside a filter installed by installFilter(). See :ref:`qloggingcategory-configuring-categories` for an overview on how to configure categories globally.

**Note:** ``QtFatalMsg`` cannot be changed. It will always remain ``true``.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QLoggingCategory.isEnabled`.
