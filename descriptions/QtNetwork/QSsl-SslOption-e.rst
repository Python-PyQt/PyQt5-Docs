.. sip:enum-description::
    :status: todo
    :digest: 91d446c14195b7a9812832ce68f1bbca

Describes the options that can be used to control the details of SSL behaviour. These options are generally used to turn features off to work around buggy servers.

By default,  is turned on since this causes problems with a large number of servers.  is also turned on, since it introduces a security risk.  is turned on to prevent the attack publicised by CRIME. SslOptionDisableSessionPersistence is turned on to optimize memory usage. The other options are turned off.

**Note:** Availability of above options depends on the version of the SSL backend in use.
