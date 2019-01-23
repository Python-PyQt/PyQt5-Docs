.. sip:module-description::
    :status:    done
    :brief:     A consolidation of other modules

The :sip:ref:`~PyQt5.Qt` module consolidates the contents of most of the other
modules into a single module.  (Excluded are the Qt3D, Chart, Data
Visualization and Purchasing modules).  This has the advantage that you don't
have to worry about which underlying module contains a particular class.  It
has the disadvantage that it loads the whole of the Qt framework, thereby
significantly increasing the memory footprint of an application.  Whether you
use this consolidated module, or the individual component modules is down to
personal taste.
