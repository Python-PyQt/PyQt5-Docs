.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 1f2d608c6432adc2d0ec2932f3316f20

Instructs the session to permanently accept the new access point. Once this function has been called the session may not return to the old access point.

The old access point may be closed in the process if there are no other network sessions for it. Therefore any open socket that still uses the old access point may become unusable and should be closed before completing the migration.
