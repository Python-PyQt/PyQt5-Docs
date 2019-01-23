:orphan:

.. sip:class:: PyQt5.QtLocation.QPlaceReply
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtLocation/QPlaceReply-c.rst

    .. sip:enum:: PyQt5.QtLocation.QPlaceReply.Error
        :description: QtLocation/QPlaceReply-Error-e.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Error.BadArgumentError
            :description: QtLocation/QPlaceReply-Error-BadArgumentError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Error.CancelError
            :description: QtLocation/QPlaceReply-Error-CancelError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Error.CategoryDoesNotExistError
            :description: QtLocation/QPlaceReply-Error-CategoryDoesNotExistError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Error.CommunicationError
            :description: QtLocation/QPlaceReply-Error-CommunicationError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Error.NoError
            :description: QtLocation/QPlaceReply-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Error.ParseError
            :description: QtLocation/QPlaceReply-Error-ParseError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Error.PermissionsError
            :description: QtLocation/QPlaceReply-Error-PermissionsError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Error.PlaceDoesNotExistError
            :description: QtLocation/QPlaceReply-Error-PlaceDoesNotExistError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Error.UnknownError
            :description: QtLocation/QPlaceReply-Error-UnknownError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Error.UnsupportedError
            :description: QtLocation/QPlaceReply-Error-UnsupportedError-v.rst

    .. sip:enum:: PyQt5.QtLocation.QPlaceReply.Type
        :description: QtLocation/QPlaceReply-Type-e.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Type.ContentReply
            :description: QtLocation/QPlaceReply-Type-ContentReply-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Type.DetailsReply
            :description: QtLocation/QPlaceReply-Type-DetailsReply-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Type.IdReply
            :description: QtLocation/QPlaceReply-Type-IdReply-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Type.MatchReply
            :description: QtLocation/QPlaceReply-Type-MatchReply-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Type.Reply
            :description: QtLocation/QPlaceReply-Type-Reply-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Type.SearchReply
            :description: QtLocation/QPlaceReply-Type-SearchReply-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QPlaceReply.Type.SearchSuggestionReply
            :description: QtLocation/QPlaceReply-Type-SearchSuggestionReply-v.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceReply.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtLocation/QPlaceReply-__init__-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceReply.abort
        :description: QtLocation/QPlaceReply-abort-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceReply.error
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceReply.Error`
        :description: QtLocation/QPlaceReply-error-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceReply.errorString
        :returns:
            str
        :description: QtLocation/QPlaceReply-errorString-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceReply.isFinished
        :returns:
            bool
        :description: QtLocation/QPlaceReply-isFinished-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceReply.setError
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceReply.Error`
            str
        :description: QtLocation/QPlaceReply-setError-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceReply.setFinished
        :args:
            bool
        :description: QtLocation/QPlaceReply-setFinished-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceReply.type
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceReply.Type`
        :description: QtLocation/QPlaceReply-type-f.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceReply.aborted
        :description: QtLocation/QPlaceReply-aborted-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceReply.contentUpdated
        :description: QtLocation/QPlaceReply-contentUpdated-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceReply.error
        :description: QtLocation/QPlaceReply-error-f-1.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceReply.error
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceReply.Error`
            errorString: str = ''
        :description: QtLocation/QPlaceReply-error-f-2.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceReply.finished
        :description: QtLocation/QPlaceReply-finished-s.rst
