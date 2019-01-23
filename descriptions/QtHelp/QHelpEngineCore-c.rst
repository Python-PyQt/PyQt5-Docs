.. sip:class-description::
    :status: todo
    :brief: The core functionality of the help system
    :digest: 7cec64135d72ec34ee373480bbeef2e8

The :sip:ref:`~PyQt5.QtHelp.QHelpEngineCore` class provides the core functionality of the help system.

Before the help engine can be used, it must be initialized by calling :sip:ref:`~PyQt5.QtHelp.QHelpEngineCore.setupData`. At the beginning of the setup process the signal :sip:ref:`~PyQt5.QtHelp.QHelpEngineCore.setupStarted` is emitted. From this point on until the signal :sip:ref:`~PyQt5.QtHelp.QHelpEngineCore.setupFinished` is emitted, is the help data in an undefined meaning unusable state.

The core help engine can be used to perform different tasks. By calling :sip:ref:`~PyQt5.QtHelp.QHelpEngineCore.linksForIdentifier` the engine returns URLs specifying the file locations inside the help system. The actual file data can then be retrived by calling :sip:ref:`~PyQt5.QtHelp.QHelpEngineCore.fileData`. In contrast to all other functions in this class, :sip:ref:`~PyQt5.QtHelp.QHelpEngineCore.linksForIdentifier` depends on the currently set custom filter. Depending on the filter, the function may return different results.

Every help engine can contain any number of custom filters. A custom filter is defined by a name and set of filter attributes and can be added to the help engine by calling :sip:ref:`~PyQt5.QtHelp.QHelpEngineCore.addCustomFilter`. Analogous, it is removed by calling :sip:ref:`~PyQt5.QtHelp.QHelpEngineCore.removeCustomFilter`. :sip:ref:`~PyQt5.QtHelp.QHelpEngineCore.customFilters` returns all defined filters.

The help engine also offers the possibility to set and read values in a persistant way comparable to ini files or Windows registry entries. For more information see setValue() or value().

This class does not offer any GUI components or functionality for indices or contents. If you need one of those use :sip:ref:`~PyQt5.QtHelp.QHelpEngine` instead.

When creating a custom help viewer the viewer can be configured by writing a custom collection file which could contain various keywords to be used to configure the help engine. These keywords and values and their meaning can be found in the help information for creating a custom help collection file for Assistant.
