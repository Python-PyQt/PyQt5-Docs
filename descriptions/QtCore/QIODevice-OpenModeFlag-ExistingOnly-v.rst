.. sip:enum-member-description::
    :status: todo
    :value: TODO
    :digest: 1d9b12cb03d7df03b43bd36272f846d3

Fail if the file to be opened does not exist. This flag must be specified alongside , , or . Note that using this flag with  alone is redundant, as  already fails when the file does not exist. This flag currently only affects :sip:ref:`~PyQt5.QtCore.QFile`. Other classes might use this flag in the future, but until then using this flag with any classes other than :sip:ref:`~PyQt5.QtCore.QFile` may result in undefined behavior. (since Qt 5.11)
