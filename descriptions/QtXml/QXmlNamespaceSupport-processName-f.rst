.. sip:method-description::
    :status: todo
    :pysig: 71b1bbe2c38cf5aa296b914186f4303f
    :realsig: (const QString&,bool,QString&,QString&) const
    :digest: 245aa7d40bc8e68b03979abbdfab88f8

Processes a raw XML 1.0 name in the current context by removing the prefix and looking it up among the prefixes currently declared.

*qname* is the raw XML 1.0 name to be processed. *isAttribute* is true if the name is an attribute name.

This function stores the namespace URI in *nsuri* (which will be set to an empty string if the raw name has an undeclared prefix), and stores the local name (without prefix) in *localname* (which will be set to an empty string if no namespace is in use).

Note that attribute names are processed differently than element names: an unprefixed element name gets the default namespace (if any), while an unprefixed attribute name does not.
