:orphan:

.. sip:class:: PyQt5.QtWebEngineCore.QWebEngineUrlRequestJob
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtWebEngineCore/QWebEngineUrlRequestJob-c.rst

    .. sip:enum:: PyQt5.QtWebEngineCore.QWebEngineUrlRequestJob.Error
        :description: QtWebEngineCore/QWebEngineUrlRequestJob-Error-e.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlRequestJob.Error.NoError
            :description: QtWebEngineCore/QWebEngineUrlRequestJob-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlRequestJob.Error.RequestAborted
            :description: QtWebEngineCore/QWebEngineUrlRequestJob-Error-RequestAborted-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlRequestJob.Error.RequestDenied
            :description: QtWebEngineCore/QWebEngineUrlRequestJob-Error-RequestDenied-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlRequestJob.Error.RequestFailed
            :description: QtWebEngineCore/QWebEngineUrlRequestJob-Error-RequestFailed-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlRequestJob.Error.UrlInvalid
            :description: QtWebEngineCore/QWebEngineUrlRequestJob-Error-UrlInvalid-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlRequestJob.Error.UrlNotFound
            :description: QtWebEngineCore/QWebEngineUrlRequestJob-Error-UrlNotFound-v.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlRequestJob.fail
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlRequestJob.Error`
        :description: QtWebEngineCore/QWebEngineUrlRequestJob-fail-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlRequestJob.initiator
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtWebEngineCore/QWebEngineUrlRequestJob-initiator-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlRequestJob.redirect
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtWebEngineCore/QWebEngineUrlRequestJob-redirect-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlRequestJob.reply
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            :sip:ref:`~PyQt5.QtCore.QIODevice`
        :description: QtWebEngineCore/QWebEngineUrlRequestJob-reply-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlRequestJob.requestHeaders
        :returns:
            Dict[:sip:ref:`~PyQt5.QtCore.QByteArray`, :sip:ref:`~PyQt5.QtCore.QByteArray`]
        :description: QtWebEngineCore/QWebEngineUrlRequestJob-requestHeaders-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlRequestJob.requestMethod
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtWebEngineCore/QWebEngineUrlRequestJob-requestMethod-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlRequestJob.requestUrl
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtWebEngineCore/QWebEngineUrlRequestJob-requestUrl-f.rst
