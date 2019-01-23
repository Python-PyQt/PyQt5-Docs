.. sip:enum-member-description::
    :status: todo
    :value: 2
    :digest: 4e1a97c5193bbaefe3a4e5af6598dd92

Replies only, type: :sip:ref:`~PyQt5.QtCore.QMetaType.Type.QUrl` (no default) If present, it indicates that the server is redirecting the request to a different URL. The Network Access API does not by default follow redirections: the application can determine if the requested redirection should be allowed, according to its security policies, or it can set QNetworkRequest::FollowRedirectsAttribute to true (in which case the redirection will be followed and this attribute will not be present in the reply). The returned URL might be relative. Use :sip:ref:`~PyQt5.QtCore.QUrl.resolved` to create an absolute URL out of it.
