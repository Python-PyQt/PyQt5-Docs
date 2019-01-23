.. sip:class-description::
    :status: todo
    :brief: Array of bytes
    :digest: f0973d971275776d9f06fe9b06070e49

The :sip:ref:`~PyQt5.QtCore.QByteArray` class provides an array of bytes.

:sip:ref:`~PyQt5.QtCore.QByteArray` can be used to store both raw bytes (including '\\0's) and traditional 8-bit '\\0'-terminated strings. Using :sip:ref:`~PyQt5.QtCore.QByteArray` is much more convenient than using ``const char \*``. Behind the scenes, it always ensures that the data is followed by a '\\0' terminator, and uses `implicit sharing <https://doc.qt.io/qt-5/implicit-sharing.html>`_ (copy-on-write) to reduce memory usage and avoid needless copying of data.

In addition to :sip:ref:`~PyQt5.QtCore.QByteArray`, Qt also provides the QString class to store string data. For most purposes, QString is the class you want to use. It stores 16-bit Unicode characters, making it easy to store non-ASCII/non-Latin-1 characters in your application. Furthermore, QString is used throughout in the Qt API. The two main cases where :sip:ref:`~PyQt5.QtCore.QByteArray` is appropriate are when you need to store raw binary data, and when memory conservation is critical (e.g., with Qt for Embedded Linux).

One way to initialize a :sip:ref:`~PyQt5.QtCore.QByteArray` is simply to pass a ``const char \*`` to its constructor. For example, the following code creates a byte array of size 5 containing the data "Hello":

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qbytearray.py
    :lines: 58-58

Although the :sip:ref:`~PyQt5.QtCore.QByteArray.size` is 5, the byte array also maintains an extra '\\0' character at the end so that if a function is used that asks for a pointer to the underlying data (e.g. a call to :sip:ref:`~PyQt5.QtCore.QByteArray.data`), the data pointed to is guaranteed to be '\\0'-terminated.

:sip:ref:`~PyQt5.QtCore.QByteArray` makes a deep copy of the ``const char \*`` data, so you can modify it later without experiencing side effects. (If for performance reasons you don't want to take a deep copy of the character data, use QByteArray::fromRawData() instead.)

Another approach is to set the size of the array using :sip:ref:`~PyQt5.QtCore.QByteArray.resize` and to initialize the data byte per byte. :sip:ref:`~PyQt5.QtCore.QByteArray` uses 0-based indexes, just like C++ arrays. To access the byte at a particular index position, you can use operator[](). On non-const byte arrays, operator[]() returns a reference to a byte that can be used on the left side of an assignment. For example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qbytearray.py
    :lines: 63-69

For read-only access, an alternative syntax is to use :sip:ref:`~PyQt5.QtCore.QByteArray.at`:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qbytearray.py
    :lines: 74-77

:sip:ref:`~PyQt5.QtCore.QByteArray.at` can be faster than operator[](), because it never causes a `deep copy <https://doc.qt.io/qt-5/implicit-sharing.html#deep-copy>`_ to occur.

To extract many bytes at a time, use :sip:ref:`~PyQt5.QtCore.left`, :sip:ref:`~PyQt5.QtCore.right`, or :sip:ref:`~PyQt5.QtCore.QByteArray.mid`.

A :sip:ref:`~PyQt5.QtCore.QByteArray` can embed '\\0' bytes. The :sip:ref:`~PyQt5.QtCore.QByteArray.size` function always returns the size of the whole array, including embedded '\\0' bytes, but excluding the terminating '\\0' added by :sip:ref:`~PyQt5.QtCore.QByteArray`. For example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qbytearray.py
    :lines: 457-472

If you want to obtain the length of the data up to and excluding the first '\\0' character, call qstrlen() on the byte array.

After a call to :sip:ref:`~PyQt5.QtCore.QByteArray.resize`, newly allocated bytes have undefined values. To set all the bytes to a particular value, call :sip:ref:`~PyQt5.QtCore.QByteArray.fill`.

To obtain a pointer to the actual character data, call :sip:ref:`~PyQt5.QtCore.QByteArray.data` or constData(). These functions return a pointer to the beginning of the data. The pointer is guaranteed to remain valid until a non-const function is called on the :sip:ref:`~PyQt5.QtCore.QByteArray`. It is also guaranteed that the data ends with a '\\0' byte unless the :sip:ref:`~PyQt5.QtCore.QByteArray` was created from a :sip:ref:`~PyQt5.QtCore.QByteArray.fromRawData`. This '\\0' byte is automatically provided by :sip:ref:`~PyQt5.QtCore.QByteArray` and is not counted in :sip:ref:`~PyQt5.QtCore.QByteArray.size`.

:sip:ref:`~PyQt5.QtCore.QByteArray` provides the following basic functions for modifying the byte data: :sip:ref:`~PyQt5.QtCore.QByteArray.append`, :sip:ref:`~PyQt5.QtCore.QByteArray.prepend`, :sip:ref:`~PyQt5.QtCore.QByteArray.insert`, :sip:ref:`~PyQt5.QtCore.QByteArray.replace`, and :sip:ref:`~PyQt5.QtCore.QByteArray.remove`. For example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qbytearray.py
    :lines: 82-85

The :sip:ref:`~PyQt5.QtCore.QByteArray.replace` and :sip:ref:`~PyQt5.QtCore.QByteArray.remove` functions' first two arguments are the position from which to start erasing and the number of bytes that should be erased.

When you :sip:ref:`~PyQt5.QtCore.QByteArray.append` data to a non-empty array, the array will be reallocated and the new data copied to it. You can avoid this behavior by calling :sip:ref:`~PyQt5.QtCore.QByteArray.reserve`, which preallocates a certain amount of memory. You can also call :sip:ref:`~PyQt5.QtCore.QByteArray.capacity` to find out how much memory :sip:ref:`~PyQt5.QtCore.QByteArray` actually allocated. Data appended to an empty array is not copied.

A frequent requirement is to remove whitespace characters from a byte array ('\\n', '\\t', ' ', etc.). If you want to remove whitespace from both ends of a :sip:ref:`~PyQt5.QtCore.QByteArray`, use :sip:ref:`~PyQt5.QtCore.QByteArray.trimmed`. If you want to remove whitespace from both ends and replace multiple consecutive whitespaces with a single space character within the byte array, use :sip:ref:`~PyQt5.QtCore.QByteArray.simplified`.

If you want to find all occurrences of a particular character or substring in a :sip:ref:`~PyQt5.QtCore.QByteArray`, use :sip:ref:`~PyQt5.QtCore.QByteArray.indexOf` or :sip:ref:`~PyQt5.QtCore.QByteArray.lastIndexOf`. The former searches forward starting from a given index position, the latter searches backward. Both return the index position of the character or substring if they find it; otherwise, they return -1. For example, here's a typical loop that finds all occurrences of a particular substring:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qbytearray.py
    :lines: 90-95

If you simply want to check whether a :sip:ref:`~PyQt5.QtCore.QByteArray` contains a particular character or substring, use :sip:ref:`~PyQt5.QtCore.QByteArray.contains`. If you want to find out how many times a particular character or substring occurs in the byte array, use :sip:ref:`~PyQt5.QtCore.QByteArray.count`. If you want to replace all occurrences of a particular value with another, use one of the two-parameter :sip:ref:`~PyQt5.QtCore.QByteArray.replace` overloads.

:sip:ref:`~PyQt5.QtCore.QByteArray`\ s can be compared using overloaded operators such as operator<(), operator<=(), operator==(), operator>=(), and so on. The comparison is based exclusively on the numeric values of the characters and is very fast, but is not what a human would expect. QString::localeAwareCompare() is a better choice for sorting user-interface strings.

For historical reasons, :sip:ref:`~PyQt5.QtCore.QByteArray` distinguishes between a null byte array and an empty byte array. A *null* byte array is a byte array that is initialized using :sip:ref:`~PyQt5.QtCore.QByteArray`'s default constructor or by passing (const char \*)0 to the constructor. An *empty* byte array is any byte array with size 0. A null byte array is always empty, but an empty byte array isn't necessarily null:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qbytearray.py
    :lines: 100-107

All functions except :sip:ref:`~PyQt5.QtCore.QByteArray.isNull` treat null byte arrays the same as empty byte arrays. For example, :sip:ref:`~PyQt5.QtCore.QByteArray.data` returns a pointer to a '\\0' character for a null byte array (\ *not* a null pointer), and :sip:ref:`~PyQt5.QtCore.QByteArray` compares equal to :sip:ref:`~PyQt5.QtCore.QByteArray`\ (""). We recommend that you always use :sip:ref:`~PyQt5.QtCore.QByteArray.isEmpty` and avoid :sip:ref:`~PyQt5.QtCore.QByteArray.isNull`.

.. _qbytearray-notes-on-locale:

Notes on Locale
---------------

.. _qbytearray-number-string-conversions:

Number-String Conversions
.........................

Functions that perform conversions between numeric data types and strings are performed in the C locale, irrespective of the user's locale settings. Use QString to perform locale-aware conversions between numbers and strings.

.. _qbytearray-8-bit-character-comparisons:

8-bit Character Comparisons
...........................

In :sip:ref:`~PyQt5.QtCore.QByteArray`, the notion of uppercase and lowercase and of which character is greater than or less than another character is locale dependent. This affects functions that support a case insensitive option or that compare or lowercase or uppercase their arguments. Case insensitive operations and comparisons will be accurate if both strings contain only ASCII characters. (If ``$LC_CTYPE`` is set, most Unix systems do "the right thing".) Functions that this affects include :sip:ref:`~PyQt5.QtCore.QByteArray.contains`, :sip:ref:`~PyQt5.QtCore.QByteArray.indexOf`, :sip:ref:`~PyQt5.QtCore.QByteArray.lastIndexOf`, operator<(), operator<=(), operator>(), operator>=(), isLower(), isUpper(), :sip:ref:`~PyQt5.QtCore.QByteArray.toLower` and :sip:ref:`~PyQt5.QtCore.QByteArray.toUpper`.

This issue does not apply to QStrings since they represent characters using Unicode.

.. seealso:: QString, :sip:ref:`~PyQt5.QtCore.QBitArray`.
