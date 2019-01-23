.. sip:enum-member-description::
    :status: todo
    :value: TODO
    :digest: 54a3589fad5ee8d8d340fa87d26c2b18

Fail if the file to be opened already exists. Create and open the file only if it does not exist. There is a guarantee from the operating system that you are the only one creating and opening the file. Note that this mode implies , and combining it with  is allowed. This flag currently only affects :sip:ref:`~PyQt5.QtCore.QFile`. Other classes might use this flag in the future, but until then using this flag with any classes other than :sip:ref:`~PyQt5.QtCore.QFile` may result in undefined behavior. (since Qt 5.11)
