.. sip:method-description::
    :status: todo
    :pysig: ace6ae5d193c9782b7a2d252a83f13ec
    :realsig: (QHelpEngineCore*,QObject*)
    :digest: 7e61f57d35c802563055063ac74d72e9

Constructs a new search engine with the given *parent*. The search engine uses the given *helpEngine* to access the documentation that needs to be indexed. The :sip:ref:`~PyQt5.QtHelp.QHelpEngine`'s setupFinished() signal is automatically connected to the :sip:ref:`~PyQt5.QtHelp.QHelpSearchEngine`'s indexing function, so that new documentation will be indexed after the signal is emitted.
