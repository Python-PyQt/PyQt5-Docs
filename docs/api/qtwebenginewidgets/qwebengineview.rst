:orphan:

.. sip:class:: PyQt5.QtWebEngineWidgets.QWebEngineView
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QWidget`
    :description: QtWebEngineWidgets/QWebEngineView-c.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWebEngineWidgets/QWebEngineView-__init__-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.back
        :description: QtWebEngineWidgets/QWebEngineView-back-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.closeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QCloseEvent`
        :description: QtWebEngineWidgets/QWebEngineView-closeEvent-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.contextMenuEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QContextMenuEvent`
        :description: QtWebEngineWidgets/QWebEngineView-contextMenuEvent-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.createWindow
        :args:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEnginePage.WebWindowType`
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEngineView`
        :description: QtWebEngineWidgets/QWebEngineView-createWindow-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.dragEnterEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QDragEnterEvent`
        :description: QtWebEngineWidgets/QWebEngineView-dragEnterEvent-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.dragLeaveEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QDragLeaveEvent`
        :description: QtWebEngineWidgets/QWebEngineView-dragLeaveEvent-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.dragMoveEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QDragMoveEvent`
        :description: QtWebEngineWidgets/QWebEngineView-dragMoveEvent-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.dropEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QDropEvent`
        :description: QtWebEngineWidgets/QWebEngineView-dropEvent-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWebEngineWidgets/QWebEngineView-event-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.findText
        :args:
            str
            options: Union[:sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEnginePage.FindFlags`, :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEnginePage.FindFlag`] = QWebEnginePage.FindFlags()
            resultCallback: Callable[[bool], None] = 0
        :description: QtWebEngineWidgets/QWebEngineView-findText-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.forward
        :description: QtWebEngineWidgets/QWebEngineView-forward-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.hasSelection
        :returns:
            bool
        :description: QtWebEngineWidgets/QWebEngineView-hasSelection-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.hideEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QHideEvent`
        :description: QtWebEngineWidgets/QWebEngineView-hideEvent-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.history
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEngineHistory`
        :description: QtWebEngineWidgets/QWebEngineView-history-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.icon
        :returns:
            :sip:ref:`~PyQt5.QtGui.QIcon`
        :description: QtWebEngineWidgets/QWebEngineView-icon-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.iconUrl
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtWebEngineWidgets/QWebEngineView-iconUrl-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.load
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtWebEngineWidgets/QWebEngineView-load-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.load
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineHttpRequest`
        :description: QtWebEngineWidgets/QWebEngineView-load-f-1.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.page
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEnginePage`
        :description: QtWebEngineWidgets/QWebEngineView-page-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.pageAction
        :args:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEnginePage.WebAction`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWebEngineWidgets/QWebEngineView-pageAction-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.reload
        :description: QtWebEngineWidgets/QWebEngineView-reload-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.selectedText
        :returns:
            str
        :description: QtWebEngineWidgets/QWebEngineView-selectedText-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.setContent
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            mimeType: str = ''
            baseUrl: :sip:ref:`~PyQt5.QtCore.QUrl` = QUrl()
        :description: QtWebEngineWidgets/QWebEngineView-setContent-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.setHtml
        :args:
            str
            baseUrl: :sip:ref:`~PyQt5.QtCore.QUrl` = QUrl()
        :description: QtWebEngineWidgets/QWebEngineView-setHtml-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.setPage
        :args:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEnginePage`
        :description: QtWebEngineWidgets/QWebEngineView-setPage-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.settings
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEngineSettings`
        :description: QtWebEngineWidgets/QWebEngineView-settings-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.setUrl
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtWebEngineWidgets/QWebEngineView-setUrl-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.setZoomFactor
        :args:
            float
        :description: QtWebEngineWidgets/QWebEngineView-setZoomFactor-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.showEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QShowEvent`
        :description: QtWebEngineWidgets/QWebEngineView-showEvent-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.sizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWebEngineWidgets/QWebEngineView-sizeHint-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.stop
        :description: QtWebEngineWidgets/QWebEngineView-stop-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.title
        :returns:
            str
        :description: QtWebEngineWidgets/QWebEngineView-title-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.triggerPageAction
        :args:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEnginePage.WebAction`
            checked: bool = False
        :description: QtWebEngineWidgets/QWebEngineView-triggerPageAction-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.url
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtWebEngineWidgets/QWebEngineView-url-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineView.zoomFactor
        :returns:
            float
        :description: QtWebEngineWidgets/QWebEngineView-zoomFactor-f.rst

    .. sip:signal:: PyQt5.QtWebEngineWidgets.QWebEngineView.iconChanged
        :args:
            :sip:ref:`~PyQt5.QtGui.QIcon`
        :description: QtWebEngineWidgets/QWebEngineView-iconChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngineWidgets.QWebEngineView.iconUrlChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtWebEngineWidgets/QWebEngineView-iconUrlChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngineWidgets.QWebEngineView.loadFinished
        :args:
            bool
        :description: QtWebEngineWidgets/QWebEngineView-loadFinished-s.rst

    .. sip:signal:: PyQt5.QtWebEngineWidgets.QWebEngineView.loadProgress
        :args:
            int
        :description: QtWebEngineWidgets/QWebEngineView-loadProgress-s.rst

    .. sip:signal:: PyQt5.QtWebEngineWidgets.QWebEngineView.loadStarted
        :description: QtWebEngineWidgets/QWebEngineView-loadStarted-s.rst

    .. sip:signal:: PyQt5.QtWebEngineWidgets.QWebEngineView.renderProcessTerminated
        :args:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEnginePage.RenderProcessTerminationStatus`
            int
        :description: QtWebEngineWidgets/QWebEngineView-renderProcessTerminated-s.rst

    .. sip:signal:: PyQt5.QtWebEngineWidgets.QWebEngineView.selectionChanged
        :description: QtWebEngineWidgets/QWebEngineView-selectionChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngineWidgets.QWebEngineView.titleChanged
        :args:
            str
        :description: QtWebEngineWidgets/QWebEngineView-titleChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngineWidgets.QWebEngineView.urlChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtWebEngineWidgets/QWebEngineView-urlChanged-s.rst
