.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: ()
    :digest: f651e962810d020c32022d818f3f952d

Leaves the array or map whose items were being processed and positions the decoder at the next item after the end of the container. Returns true if leaving the container succeeded, false otherwise (usually, a parsing error). Each call to  must be paired with a call to .

This function may only be called if  has returned false and  is not zero. Calling it in any other condition is an error.

.. seealso:: enterContainer()parentContainerType()containerDepth().
