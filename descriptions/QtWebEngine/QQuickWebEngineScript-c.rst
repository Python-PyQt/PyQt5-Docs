.. sip:class-description::
    :status: todo
    :brief: Enables the injection of scripts in the JavaScript engine
    :digest: 48f250a3606f25d1e1ec2bdcaaa88eff

Enables the injection of scripts in the JavaScript engine.

The :sip:ref:`~PyQt5.QtWebEngine.QQuickWebEngineScript` type enables the programmatic injection of so called *user scripts* in the JavaScript engine at different points, determined by :sip:ref:`~PyQt5.QtWebEngine.QQuickWebEngineScript.injectionPoint`, during the loading of web content.

Scripts can be executed either in the main JavaScript *world*, along with the rest of the JavaScript coming from the web contents, or in their own isolated world. While the DOM of the page can be accessed from any world, JavaScript variables of a function defined in one world are not accessible from a different one. The :sip:ref:`~PyQt5.QtWebEngine.QQuickWebEngineScript.worldId` property provides some predefined IDs for this purpose.
