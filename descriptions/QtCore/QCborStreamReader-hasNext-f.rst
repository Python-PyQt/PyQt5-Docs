.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: () const
    :digest: 6277c8f7b200b8d1a70e06a901a4811d

Returns true if there are more items to be decoded in the current container or false of we've reached its end. If we're parsing the root element,  returning false indicates the parsing is complete; otherwise, if the container depth is non-zero, then the outer code needs to call .

.. seealso:: parentContainerType()containerDepth()leaveContainer().
