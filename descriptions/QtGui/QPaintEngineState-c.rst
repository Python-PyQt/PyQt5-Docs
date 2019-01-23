.. sip:class-description::
    :status: todo
    :brief: Information about the active paint engine's current state
    :digest: ff3d990c3f2a0dbc7489b204136b0680

The :sip:ref:`~PyQt5.QtGui.QPaintEngineState` class provides information about the active paint engine's current state.

:sip:ref:`~PyQt5.QtGui.QPaintEngineState` records which properties that have changed since the last time the paint engine was updated, as well as their current value.

Which properties that have changed can at any time be retrieved using the :sip:ref:`~PyQt5.QtGui.QPaintEngineState.state` function. This function returns an instance of the QPaintEngine::DirtyFlags type which stores an OR combination of :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag` values. The :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag` enum defines whether a property has changed since the last update or not.

If a property is marked with a dirty flag, its current value can be retrieved using the corresponding get function:

.. _qpaintenginestate-getfunction:

+----------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------+
| Property Flag                                                                                                                    | Current Property Value                                    |
+==================================================================================================================================+===========================================================+
| :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyBackground`                                                                   | :sip:ref:`~PyQt5.QtGui.QPaintEngineState.backgroundBrush` |
+----------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------+
| :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyBackgroundMode`                                                               | :sip:ref:`~PyQt5.QtGui.QPaintEngineState.backgroundMode`  |
+----------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------+
| :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyBrush`                                                                        | :sip:ref:`~PyQt5.QtGui.QPaintEngineState.brush`           |
+----------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------+
| :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyBrushOrigin`                                                                  | :sip:ref:`~PyQt5.QtGui.QPaintEngineState.brushOrigin`     |
+----------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------+
| :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyClipRegion` *or* :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyClipPath` | :sip:ref:`~PyQt5.QtGui.QPaintEngineState.clipOperation`   |
+----------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------+
| :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyClipPath`                                                                     | :sip:ref:`~PyQt5.QtGui.QPaintEngineState.clipPath`        |
+----------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------+
| :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyClipRegion`                                                                   | :sip:ref:`~PyQt5.QtGui.QPaintEngineState.clipRegion`      |
+----------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------+
| :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyCompositionMode`                                                              | :sip:ref:`~PyQt5.QtGui.QPaintEngineState.compositionMode` |
+----------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------+
| :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyFont`                                                                         | :sip:ref:`~PyQt5.QtGui.QPaintEngineState.font`            |
+----------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------+
| :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyTransform`                                                                    | :sip:ref:`~PyQt5.QtGui.QPaintEngineState.transform`       |
+----------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------+
| :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyClipEnabled`                                                                  | :sip:ref:`~PyQt5.QtGui.QPaintEngineState.isClipEnabled`   |
+----------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------+
| :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyPen`                                                                          | :sip:ref:`~PyQt5.QtGui.QPaintEngineState.pen`             |
+----------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------+
| :sip:ref:`~PyQt5.QtGui.QPaintEngine.DirtyFlag.DirtyHints`                                                                        | :sip:ref:`~PyQt5.QtGui.QPaintEngineState.renderHints`     |
+----------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------+

The :sip:ref:`~PyQt5.QtGui.QPaintEngineState` class also provide the :sip:ref:`~PyQt5.QtGui.QPaintEngineState.painter` function which returns a pointer to the painter that is currently updating the paint engine.

An instance of this class, representing the current state of the active paint engine, is passed as argument to the :sip:ref:`~PyQt5.QtGui.QPaintEngine.updateState` function. The only situation in which you will have to use this class directly is when implementing your own paint engine.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPaintEngine`.
