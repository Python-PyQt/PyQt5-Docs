.. sip:module-description::
    :status:    done
    :brief:     A Chromium based web browser

The :sip:ref:`~PyQt5.QtWebEngineWidgets` module contains classes for a Chromium
based implementation of a web browser.  This supercedes the
:sip:ref:`~PyQt5.QtWebKit` module and provides better and up-to-date support
for HTML, CSS and JavaScript features.  However it also consumes more resources
and doesn't give direct access to the network stack and the HTML document via
Python APIs.

.. note::

    :sip:ref:`~PyQt5.QtWebEngineWidgets` is not normally available under
    Windows using versions of Python earlier than v3.5 because of compiler
    incompatibilities.
