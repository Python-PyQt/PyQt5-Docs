.. sip:class-description::
    :status: todo
    :brief: Represents an inline object in a QAbstractTextDocumentLayout and its implementations
    :digest: 03eb9fbef9bb5b5b1cf75010113707cf

The :sip:ref:`~PyQt5.QtGui.QTextInlineObject` class represents an inline object in a :sip:ref:`~PyQt5.QtGui.QAbstractTextDocumentLayout` and its implementations.

Normally, you do not need to create a :sip:ref:`~PyQt5.QtGui.QTextInlineObject`. It is used by :sip:ref:`~PyQt5.QtGui.QAbstractTextDocumentLayout` to handle inline objects when implementing a custom layout.

The inline object has various attributes that can be set, for example using, :sip:ref:`~PyQt5.QtGui.QTextInlineObject.setWidth`, :sip:ref:`~PyQt5.QtGui.QTextInlineObject.setAscent`, and :sip:ref:`~PyQt5.QtGui.QTextInlineObject.setDescent`. The rectangle it occupies is given by :sip:ref:`~PyQt5.QtGui.QTextInlineObject.rect`, and its direction by :sip:ref:`~PyQt5.QtGui.QTextInlineObject.textDirection`. Its position in the text layout is given by :sip:ref:`~PyQt5.QtGui.QTextInlineObject.textPosition`, and its format is given by :sip:ref:`~PyQt5.QtGui.QTextInlineObject.format`.
