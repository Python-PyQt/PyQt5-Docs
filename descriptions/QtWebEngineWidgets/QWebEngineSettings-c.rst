.. sip:class-description::
    :status: todo
    :brief: Object to store the settings used by QWebEnginePage
    :digest: f8c0763f99988aa85405b48b48f9eec4

The :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEngineSettings` class provides an object to store the settings used by :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEnginePage`.

:sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEngineSettings` allows configuration of browser properties, such as font sizes and families, the location of a custom style sheet, and generic attributes, such as JavaScript support. Individual attributes are set using the :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEngineSettings.setAttribute` function. The :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEngineSettings.WebAttribute` enum further describes each attribute.

Each :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEnginePage` object has its own :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEngineSettings` object, which configures the settings for that page. If a setting is not configured for a web engine page, it is looked up in the settings of the profile the page belongs to.

.. seealso:: :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEnginePage.settings`.
