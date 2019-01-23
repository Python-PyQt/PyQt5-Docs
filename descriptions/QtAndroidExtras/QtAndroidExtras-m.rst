.. sip:module-description::
    :status:    done
    :brief:     Additional classes specific to Android
    :platform:  Android

The :sip:ref:`~PyQt5.QtAndroidExtras` module contains additional classes that
are specific to Android.
    
Only a sub-set of the :sip:ref:`~PyQt5.QtAndroidExtras.QAndroidJniObject` class
is implemented.  In particular only the
:sip:ref:`~PyQt5.QtAndroidExtras.QAndroidJniObject.callMethod` and
:sip:ref:`~PyQt5.QtAndroidExtras.QAndroidJniObject.callStaticMethod` methods
can be called to invoke a method on a Java class.  In addition only Java
methods that take no arguments and return an ``int`` may be invoked.  This
restricts the usefulness to Java classes where you have control of the Java API
and can design it to take account of these limitations.
