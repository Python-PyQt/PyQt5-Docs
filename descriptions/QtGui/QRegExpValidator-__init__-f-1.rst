.. sip:method-description::
    :status: todo
    :pysig: da8bd06e18c8d53d8b645e103fdcfea4
    :realsig: (const QRegExp&,QObject*)
    :digest: 1b6b4e6ab26edb0458ae5950fb3f950b

Constructs a validator with a *parent* object that accepts all strings that match the regular expression *rx*.

The match is made against the entire string; e.g. if the regexp is **[A-Fa-f0-9]+** it will be treated as **^[A-Fa-f0-9]+$**.
