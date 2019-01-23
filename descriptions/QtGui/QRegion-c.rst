.. sip:class-description::
    :status: todo
    :brief: Specifies a clip region for a painter
    :digest: 023402ef10798b04f542ff4398ce7378

The :sip:ref:`~PyQt5.QtGui.QRegion` class specifies a clip region for a painter.

:sip:ref:`~PyQt5.QtGui.QRegion` is used with :sip:ref:`~PyQt5.QtGui.QPainter.setClipRegion` to limit the paint area to what needs to be painted. There is also a :sip:ref:`~PyQt5.QtWidgets.QWidget.repaint` function that takes a :sip:ref:`~PyQt5.QtGui.QRegion` parameter. :sip:ref:`~PyQt5.QtGui.QRegion` is the best tool for minimizing the amount of screen area to be updated by a repaint.

This class is not suitable for constructing shapes for rendering, especially as outlines. Use :sip:ref:`~PyQt5.QtGui.QPainterPath` to create paths and shapes for use with :sip:ref:`~PyQt5.QtGui.QPainter`.

:sip:ref:`~PyQt5.QtGui.QRegion` is an `implicitly shared <https://doc.qt.io/qt-5/implicit-sharing.html>`_ class.

.. _qregion-creating-and-using-regions:

Creating and Using Regions
--------------------------

A region can be created from a rectangle, an ellipse, a polygon or a bitmap. Complex regions may be created by combining simple regions using :sip:ref:`~PyQt5.QtGui.QRegion.united`, :sip:ref:`~PyQt5.QtGui.QRegion.intersected`, :sip:ref:`~PyQt5.QtGui.QRegion.subtracted`, or :sip:ref:`~PyQt5.QtGui.QRegion.xored` (exclusive or). You can move a region using :sip:ref:`~PyQt5.QtGui.QRegion.translate`.

You can test whether a region :sip:ref:`~PyQt5.QtGui.QRegion.isEmpty` or if it :sip:ref:`~PyQt5.QtGui.QRegion.contains` a :sip:ref:`~PyQt5.QtCore.QPoint` or :sip:ref:`~PyQt5.QtCore.QRect`. The bounding rectangle can be found with :sip:ref:`~PyQt5.QtGui.QRegion.boundingRect`.

Iteration over the region (with begin(), end(), or C++11 ranged-for loops) gives a decomposition of the region into rectangles.

Example of using complex regions:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_painting_qregion.py
    :lines: 54-64

.. _qregion-additional-license-information:

Additional License Information
------------------------------

On Embedded Linux and X11 platforms, parts of this class rely on code obtained under the following licenses:

.. container:: legalese

    Copyright (c) 1987 X Consortium

    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE X CONSORTIUM BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

    Except as contained in this notice, the name of the X Consortium shall not be used in advertising or otherwise to promote the sale, use or other dealings in this Software without prior written authorization from the X Consortium.

.. container:: legalese

    Copyright 1987 by Digital Equipment Corporation, Maynard, Massachusetts.

    All Rights Reserved

    Permission to use, copy, modify, and distribute this software and its documentation for any purpose and without fee is hereby granted, provided that the above copyright notice appear in all copies and that both that copyright notice and this permission notice appear in supporting documentation, and that the name of Digital not be used in advertising or publicity pertaining to distribution of the software without specific, written prior permission.

    DIGITAL DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE, INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS, IN NO EVENT SHALL DIGITAL BE LIABLE FOR ANY SPECIAL, INDIRECT OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPainter.setClipRegion`, :sip:ref:`~PyQt5.QtGui.QPainter.setClipRect`, :sip:ref:`~PyQt5.QtGui.QPainterPath`.
