.. sip:class-description::
    :status: todo
    :brief: Contains meta-information about Qt objects
    :digest: 123773653fb08ed980adb6f8d39a2ed1

The :sip:ref:`~PyQt5.QtCore.QMetaObject` class contains meta-information about Qt objects.

The Qt `Meta-Object System <https://doc.qt.io/qt-5/metaobjects.html>`_ in Qt is responsible for the signals and slots inter-object communication mechanism, runtime type information, and the Qt property system. A single :sip:ref:`~PyQt5.QtCore.QMetaObject` instance is created for each :sip:ref:`~PyQt5.QtCore.QObject` subclass that is used in an application, and this instance stores all the meta-information for the :sip:ref:`~PyQt5.QtCore.QObject` subclass. This object is available as :sip:ref:`~PyQt5.QtCore.QObject.metaObject`.

This class is not normally required for application programming, but it is useful if you write meta-applications, such as scripting engines or GUI builders.

The functions you are most likely to find useful are these:

* :sip:ref:`~PyQt5.QtCore.QMetaObject.className` returns the name of a class.

* :sip:ref:`~PyQt5.QtCore.QMetaObject.superClass` returns the superclass's meta-object.

* :sip:ref:`~PyQt5.QtCore.QMetaObject.method` and :sip:ref:`~PyQt5.QtCore.QMetaObject.methodCount` provide information about a class's meta-methods (signals, slots and other invokable member functions).

* :sip:ref:`~PyQt5.QtCore.QMetaObject.enumerator` and :sip:ref:`~PyQt5.QtCore.QMetaObject.enumeratorCount` and provide information about a class's enumerators.

* :sip:ref:`~PyQt5.QtCore.QMetaObject.propertyCount` and :sip:ref:`~PyQt5.QtCore.QMetaObject.property` provide information about a class's properties.

* :sip:ref:`~PyQt5.QtCore.QMetaObject.constructor` and :sip:ref:`~PyQt5.QtCore.QMetaObject.constructorCount` provide information about a class's meta-constructors.

The index functions :sip:ref:`~PyQt5.QtCore.QMetaObject.indexOfConstructor`, :sip:ref:`~PyQt5.QtCore.QMetaObject.indexOfMethod`, :sip:ref:`~PyQt5.QtCore.QMetaObject.indexOfEnumerator`, and :sip:ref:`~PyQt5.QtCore.QMetaObject.indexOfProperty` map names of constructors, member functions, enumerators, or properties to indexes in the meta-object. For example, Qt uses :sip:ref:`~PyQt5.QtCore.QMetaObject.indexOfMethod` internally when you connect a signal to a slot.

Classes can also have a list of *name*--\ *value* pairs of additional class information, stored in :sip:ref:`~PyQt5.QtCore.QMetaClassInfo` objects. The number of pairs is returned by :sip:ref:`~PyQt5.QtCore.QMetaObject.classInfoCount`, single pairs are returned by :sip:ref:`~PyQt5.QtCore.QMetaObject.classInfo`, and you can search for pairs with :sip:ref:`~PyQt5.QtCore.QMetaObject.indexOfClassInfo`.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QMetaClassInfo`, :sip:ref:`~PyQt5.QtCore.QMetaEnum`, :sip:ref:`~PyQt5.QtCore.QMetaMethod`, :sip:ref:`~PyQt5.QtCore.QMetaProperty`, :sip:ref:`~PyQt5.QtCore.QMetaType`, `Meta-Object System <https://doc.qt.io/qt-5/metaobjects.html>`_.
