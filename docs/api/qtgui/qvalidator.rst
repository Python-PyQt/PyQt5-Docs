:orphan:

.. sip:class:: PyQt5.QtGui.QValidator
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtGui/QValidator-c.rst

    .. sip:enum:: PyQt5.QtGui.QValidator.State
        :description: QtGui/QValidator-State-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QValidator.State.Acceptable
            :description: QtGui/QValidator-State-Acceptable-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QValidator.State.Intermediate
            :description: QtGui/QValidator-State-Intermediate-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QValidator.State.Invalid
            :description: QtGui/QValidator-State-Invalid-v.rst

    .. sip:method:: PyQt5.QtGui.QValidator.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtGui/QValidator-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QValidator.fixup
        :args:
            str
        :returns:
            str
        :description: QtGui/QValidator-fixup-f.rst

    .. sip:method:: PyQt5.QtGui.QValidator.locale
        :returns:
            :sip:ref:`~PyQt5.QtCore.QLocale`
        :description: QtGui/QValidator-locale-f.rst

    .. sip:method:: PyQt5.QtGui.QValidator.setLocale
        :args:
            :sip:ref:`~PyQt5.QtCore.QLocale`
        :description: QtGui/QValidator-setLocale-f.rst

    .. sip:method:: PyQt5.QtGui.QValidator.validate
        :args:
            str
            int
        :returns:
            :sip:ref:`~PyQt5.QtGui.QValidator.State`
            str
            int
        :description: QtGui/QValidator-validate-f.rst

    .. sip:signal:: PyQt5.QtGui.QValidator.changed
        :description: QtGui/QValidator-changed-s.rst
