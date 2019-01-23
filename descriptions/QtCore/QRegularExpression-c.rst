.. sip:class-description::
    :status: todo
    :brief: Pattern matching using regular expressions
    :digest: 40fb553390f9dcb0d821ccbb478ca7ad

The :sip:ref:`~PyQt5.QtCore.QRegularExpression` class provides pattern matching using regular expressions.

Regular expressions, or *regexps*, are a very powerful tool to handle strings and texts. This is useful in many contexts, e.g.,

+--------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Validation         | A regexp can test whether a substring meets some criteria, e.g. is an integer or contains no whitespace.                                                                                                                  |
+--------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Searching          | A regexp provides more powerful pattern matching than simple substring matching, e.g., match one of the words *mail*, *letter* or *correspondence*, but none of the words *email*, *mailman*, *mailer*, *letterbox*, etc. |
+--------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Search and Replace | A regexp can replace all occurrences of a substring with a different substring, e.g., replace all occurrences of *&* with *&amp;* except where the *&* is already followed by an *amp;*.                                  |
+--------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| String Splitting   | A regexp can be used to identify where a string should be split apart, e.g. splitting tab-delimited strings.                                                                                                              |
+--------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

This document is by no means a complete reference to pattern matching using regular expressions, and the following parts will require the reader to have some basic knowledge about Perl-like regular expressions and their pattern syntax.

Good references about regular expressions include:

* *Mastering Regular Expressions* (Third Edition) by Jeffrey E. F. Friedl, ISBN 0-596-52812-4;

* the pcrepattern(3) man page, describing the pattern syntax supported by PCRE (the reference implementation of Perl-compatible regular expressions);

* the Perl's regular expression documentation and the Perl's regular expression tutorial.

.. _qregularexpression-introduction:

Introduction
------------

:sip:ref:`~PyQt5.QtCore.QRegularExpression` implements Perl-compatible regular expressions. It fully supports Unicode. For an overview of the regular expression syntax supported by :sip:ref:`~PyQt5.QtCore.QRegularExpression`, please refer to the aforementioned pcrepattern(3) man page. A regular expression is made up of two things: a **pattern string** and a set of **pattern options** that change the meaning of the pattern string.

You can set the pattern string by passing a string to the :sip:ref:`~PyQt5.QtCore.QRegularExpression` constructor:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 63-63

This sets the pattern string to ``a pattern``. You can also use the :sip:ref:`~PyQt5.QtCore.QRegularExpression.setPattern` function to set a pattern on an existing :sip:ref:`~PyQt5.QtCore.QRegularExpression` object:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 69-70

Note that due to C++ literal strings rules, you must escape all backslashes inside the pattern string with another backslash:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 76-80

The pattern() function returns the pattern that is currently set for a :sip:ref:`~PyQt5.QtCore.QRegularExpression` object:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 86-87

.. _qregularexpression-pattern-options:

Pattern Options
---------------

The meaning of the pattern string can be modified by setting one or more *pattern options*. For instance, it is possible to set a pattern to match case insensitively by setting the :sip:ref:`~PyQt5.QtCore.QRegularExpression.PatternOption.CaseInsensitiveOption`.

You can set the options by passing them to the :sip:ref:`~PyQt5.QtCore.QRegularExpression` constructor, as in:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 93-94

Alternatively, you can use the :sip:ref:`~PyQt5.QtCore.QRegularExpression.setPatternOptions` function on an existing QRegularExpressionObject:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 100-102

It is possible to get the pattern options currently set on a :sip:ref:`~PyQt5.QtCore.QRegularExpression` object by using the :sip:ref:`~PyQt5.QtCore.QRegularExpression.patternOptions` function:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 108-112

Please refer to the :sip:ref:`~PyQt5.QtCore.QRegularExpression.PatternOption` enum documentation for more information about each pattern option.

.. _qregularexpression-match-type-and-match-options:

Match Type and Match Options
----------------------------

The last two arguments of the :sip:ref:`~PyQt5.QtCore.QRegularExpression.match` and the :sip:ref:`~PyQt5.QtCore.QRegularExpression.globalMatch` functions set the match type and the match options. The match type is a value of the :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchType` enum; the "traditional" matching algorithm is chosen by using the :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchType.NormalMatch` match type (the default). It is also possible to enable partial matching of the regular expression against a subject string: see the :ref:`partial matching<qregularexpression-partial-matching>` section for more details.

The match options are a set of one or more :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchOption` values. They change the way a specific match of a regular expression against a subject string is done. Please refer to the :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchOption` enum documentation for more details.

.. _qregularexpression-normal-matching:

Normal Matching
---------------

In order to perform a match you can simply invoke the :sip:ref:`~PyQt5.QtCore.QRegularExpression.match` function passing a string to match against. We refer to this string as the *subject string*. The result of the :sip:ref:`~PyQt5.QtCore.QRegularExpression.match` function is a :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch` object that can be used to inspect the results of the match. For instance:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 118-121

If a match is successful, the (implicit) capturing group number 0 can be used to retrieve the substring matched by the entire pattern (see also the section about :ref:`extracting captured substrings<qregularexpression-extracting-captured-substrings>`):

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 127-132

It's also possible to start a match at an arbitrary offset inside the subject string by passing the offset as an argument of the :sip:ref:`~PyQt5.QtCore.QRegularExpression.match` function. In the following example ``"12 abc"`` is not matched because the match is started at offset 1:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 138-143

.. _qregularexpression-extracting-captured-substrings:

Extracting captured substrings
..............................

The :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch` object contains also information about the substrings captured by the capturing groups in the pattern string. The :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch.captured` function will return the string captured by the n-th capturing group:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 149-156

Capturing groups in the pattern are numbered starting from 1, and the implicit capturing group 0 is used to capture the substring that matched the entire pattern.

It's also possible to retrieve the starting and the ending offsets (inside the subject string) of each captured substring, by using the :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch.capturedStart` and the :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch.capturedEnd` functions:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 162-168

All of these functions have an overload taking a QString as a parameter in order to extract *named* captured substrings. For instance:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 174-180

.. _qregularexpression-global-matching:

Global Matching
---------------

*Global matching* is useful to find all the occurrences of a given regular expression inside a subject string. Suppose that we want to extract all the words from a given string, where a word is a substring matching the pattern ``\w+``.

:sip:ref:`~PyQt5.QtCore.QRegularExpression.globalMatch` returns a :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator`, which is a Java-like forward iterator that can be used to iterate over the results. For instance:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 186-187

Since it's a Java-like iterator, the :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator` will point immediately before the first result. Every result is returned as a :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch` object. The :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator.hasNext` function will return true if there's at least one more result, and :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator.next` will return the next result and advance the iterator. Continuing from the previous example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 191-197

You can also use :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator.peekNext` to get the next result without advancing the iterator.

It is possible to pass a starting offset and one or more match options to the :sip:ref:`~PyQt5.QtCore.QRegularExpression.globalMatch` function, exactly like normal matching with :sip:ref:`~PyQt5.QtCore.QRegularExpression.match`.

.. _qregularexpression-partial-matching:

Partial Matching
----------------

A *partial match* is obtained when the end of the subject string is reached, but more characters are needed to successfully complete the match. Note that a partial match is usually much more inefficient than a normal match because many optimizations of the matching algorithm cannot be employed.

A partial match must be explicitly requested by specifying a match type of :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchType.PartialPreferCompleteMatch` or :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchType.PartialPreferFirstMatch` when calling :sip:ref:`~PyQt5.QtCore.QRegularExpression.match` or :sip:ref:`~PyQt5.QtCore.QRegularExpression.globalMatch`. If a partial match is found, then calling the :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch.hasMatch` function on the :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch` object returned by :sip:ref:`~PyQt5.QtCore.QRegularExpression.match` will return ``false``, but :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch.hasPartialMatch` will return ``true``.

When a partial match is found, no captured substrings are returned, and the (implicit) capturing group 0 corresponding to the whole match captures the partially matched substring of the subject string.

Note that asking for a partial match can still lead to a complete match, if one is found; in this case, :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch.hasMatch` will return ``true`` and :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch.hasPartialMatch` ``false``. It never happens that a :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch` reports both a partial and a complete match.

Partial matching is mainly useful in two scenarios: validating user input in real time and incremental/multi-segment matching.

.. _qregularexpression-validating-user-input:

Validating user input
.....................

Suppose that we would like the user to input a date in a specific format, for instance "MMM dd, yyyy". We can check the input validity with a pattern like:

``^(Jan|Feb|Mar|Apr|May|Jun|Jul|Aug|Sep|Oct|Nov|Dec) \d\d?, \d\d\d\d$``

(This pattern doesn't catch invalid days, but let's keep it for the example's purposes).

We would like to validate the input with this regular expression *while* the user is typing it, so that we can report an error in the input as soon as it is committed (for instance, the user typed the wrong key). In order to do so we must distinguish three cases:

* the input cannot possibly match the regular expression;

* the input does match the regular expression;

* the input does not match the regular expression right now, but it will if more characters will be added to it.

Note that these three cases represent exactly the possible states of a :sip:ref:`~PyQt5.QtGui.QValidator` (see the :sip:ref:`~PyQt5.QtGui.QValidator.State` enum).

In particular, in the last case we want the regular expression engine to report a partial match: we are successfully matching the pattern against the subject string but the matching cannot continue because the end of the subject is encountered. Notice, however, that the matching algorithm should continue and try all possibilities, and in case a complete (non-partial) match is found, then this one should be reported, and the input string accepted as fully valid.

This behaviour is implemented by the :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchType.PartialPreferCompleteMatch` match type. For instance:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 203-209

If matching the same regular expression against the subject string leads to a complete match, it is reported as usual:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 217-220

Another example with a different pattern, showing the behaviour of preferring a complete match over a partial one:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 226-230

In this case, the subpattern ``abc\\w+X`` partially matches the subject string; however, the subpattern ``def`` matches the subject string completely, and therefore a complete match is reported.

If multiple partial matches are found when matching (but no complete match), then the :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch` object will report the first one that is found. For instance:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 236-240

.. _qregularexpression-incremental-multi-segment-matching:

Incremental/multi-segment matching
..................................

Incremental matching is another use case of partial matching. Suppose that we want to find the occurrences of a regular expression inside a large text (that is, substrings matching the regular expression). In order to do so we would like to "feed" the large text to the regular expression engines in smaller chunks. The obvious problem is what happens if the substring that matches the regular expression spans across two or more chunks.

In this case, the regular expression engine should report a partial match, so that we can match again adding new data and (eventually) get a complete match. This implies that the regular expression engine may assume that there are other characters *beyond the end* of the subject string. This is not to be taken literally -- the engine will never try to access any character after the last one in the subject.

:sip:ref:`~PyQt5.QtCore.QRegularExpression` implements this behaviour when using the :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchType.PartialPreferFirstMatch` match type. This match type reports a partial match as soon as it is found, and other match alternatives are not tried (even if they could lead to a complete match). For instance:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 246-249

This happens because when matching the first branch of the alternation operator a partial match is found, and therefore matching stops, without trying the second branch. Another example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 255-258

This shows what could seem a counterintuitve behaviour of quantifiers: since ``?`` is greedy, then the engine tries first to continue the match after having matched ``"abc"``; but then the matching reaches the end of the subject string, and therefore a partial match is reported. This is even more surprising in the following example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 264-267

It's easy to understand this behaviour if we remember that the engine expects the subject string to be only a substring of the whole text we're looking for a match into (that is, how we said before, that the engine assumes that there are other characters beyond the end of the subject string).

Since the ``\*`` quantifier is greedy, then reporting a complete match could be an error, because after the current subject ``"abc"`` there may be other occurrences of ``"abc"``. For instance, the complete text could have been "abcabcX", and therefore the *right* match to report (in the complete text) would have been ``"abcabc"``; by matching only against the leading ``"abc"`` we instead get a partial match.

.. _qregularexpression-error-handling:

Error Handling
--------------

It is possible for a :sip:ref:`~PyQt5.QtCore.QRegularExpression` object to be invalid because of syntax errors in the pattern string. The :sip:ref:`~PyQt5.QtCore.QRegularExpression.isValid` function will return true if the regular expression is valid, or false otherwise:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 273-274

You can get more information about the specific error by calling the :sip:ref:`~PyQt5.QtCore.QRegularExpression.errorString` function; moreover, the :sip:ref:`~PyQt5.QtCore.QRegularExpression.patternErrorOffset` function will return the offset inside the pattern string

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 280-285

If a match is attempted with an invalid :sip:ref:`~PyQt5.QtCore.QRegularExpression`, then the returned :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch` object will be invalid as well (that is, its :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch.isValid` function will return false). The same applies for attempting a global match.

.. _qregularexpression-unsupported-perl-compatible-regular-expressions-features:

Unsupported Perl-compatible Regular Expressions Features
--------------------------------------------------------

:sip:ref:`~PyQt5.QtCore.QRegularExpression` does not support all the features available in Perl-compatible regular expressions. The most notable one is the fact that duplicated names for capturing groups are not supported, and using them can lead to undefined behaviour.

This may change in a future version of Qt.

.. _qregularexpression-notes-for-qregexp-users:

Notes for QRegExp Users
-----------------------

The :sip:ref:`~PyQt5.QtCore.QRegularExpression` class introduced in Qt 5 is a big improvement upon :sip:ref:`~PyQt5.QtCore.QRegExp`, in terms of APIs offered, supported pattern syntax and speed of execution. The biggest difference is that :sip:ref:`~PyQt5.QtCore.QRegularExpression` simply holds a regular expression, and it's *not* modified when a match is requested. Instead, a :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch` object is returned, in order to check the result of a match and extract the captured substring. The same applies with global matching and :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator`.

Other differences are outlined below.

.. _qregularexpression-porting-from-qregexp-exactmatch:

Porting from QRegExp::exactMatch()
..................................

:sip:ref:`~PyQt5.QtCore.QRegExp.exactMatch` in Qt 4 served two purposes: it exactly matched a regular expression against a subject string, and it implemented partial matching.

.. _qregularexpression-porting-from-qregexp-s-exact-matching:

Porting from QRegExp's Exact Matching
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Exact matching indicates whether the regular expression matches the entire subject string. For example, the classes yield on the subject string ``"abc123"``:

+------------------+---------------------------------------------+-----------------------------------------------------------+
|                  | :sip:ref:`~PyQt5.QtCore.QRegExp.exactMatch` | :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch.hasMatch` |
+==================+=============================================+===========================================================+
| ``"\\d+"``       | **false**                                   | **true**                                                  |
+------------------+---------------------------------------------+-----------------------------------------------------------+
| ``"[a-z]+\\d+"`` | **true**                                    | **true**                                                  |
+------------------+---------------------------------------------+-----------------------------------------------------------+

Exact matching is not reflected in :sip:ref:`~PyQt5.QtCore.QRegularExpression`. If you want to be sure that the subject string matches the regular expression exactly, you can wrap the pattern between a couple of anchoring expressions. Simply putting the pattern between the ``^`` and the ``$`` anchors is enough in most cases:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 291-291

However, remember that the ``$`` anchor not only matches at the end of the string, but also at a newline character right before the end of the string; that is, the previous pattern matches against the string "this pattern must match exactly\\n". Also, the behaviour of both the ``^`` and the ``$`` anchors changes if the MultiLineOption is set either explicitly (as a pattern option) or implicitly (as a directive inside the pattern string).

Therefore, in the most general case, you should wrap the pattern between the ``\A`` and the ``\z`` anchors:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregularexpression.py
    :lines: 297-298

Note the usage of the non-capturing group in order to preserve the meaning of the branch operator inside the pattern.

The :sip:ref:`~PyQt5.QtCore.QRegularExpression.anchoredPattern` helper method does exactly that for you.

.. _qregularexpression-porting-from-qregexp-s-partial-matching:

Porting from QRegExp's Partial Matching
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

When using :sip:ref:`~PyQt5.QtCore.QRegExp.exactMatch`, if an exact match was not found, one could still find out how much of the subject string was matched by the regular expression by calling :sip:ref:`~PyQt5.QtCore.QRegExp.matchedLength`. If the returned length was equal to the subject string's length, then one could conclude that a partial match was found.

:sip:ref:`~PyQt5.QtCore.QRegularExpression` supports partial matching explicitly by means of the appropriate :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchType.MatchType`.

Global matching
...............

Due to limitations of the :sip:ref:`~PyQt5.QtCore.QRegExp` API it was impossible to implement global matching correctly (that is, like Perl does). In particular, patterns that can match 0 characters (like ``"a\*"``) are problematic.

:sip:ref:`~PyQt5.QtCore.QRegularExpression.globalMatch` implements Perl global match correctly, and the returned iterator can be used to examine each result.

.. _qregularexpression-unicode-properties-support:

Unicode properties support
..........................

When using :sip:ref:`~PyQt5.QtCore.QRegExp`, character classes such as ``\w``, ``\d``, etc. match characters with the corresponding Unicode property: for instance, ``\d`` matches any character with the Unicode Nd (decimal digit) property.

Those character classes only match ASCII characters by default when using :sip:ref:`~PyQt5.QtCore.QRegularExpression`: for instance, ``\d`` matches exactly a character in the ``0-9`` ASCII range. It is possible to change this behaviour by using the :sip:ref:`~PyQt5.QtCore.QRegularExpression.PatternOption.UseUnicodePropertiesOption` pattern option.

.. _qregularexpression-wildcard-matching:

Wildcard matching
.................

There is no direct way to do wildcard matching in :sip:ref:`~PyQt5.QtCore.QRegularExpression`. However, the :sip:ref:`~PyQt5.QtCore.QRegularExpression.wildcardToRegularExpression` method is provided to translate glob patterns into a Perl-compatible regular expression that can be used for that purpose.

.. _qregularexpression-other-pattern-syntaxes:

Other pattern syntaxes
......................

:sip:ref:`~PyQt5.QtCore.QRegularExpression` supports only Perl-compatible regular expressions.

.. _qregularexpression-minimal-matching:

Minimal matching
................

:sip:ref:`~PyQt5.QtCore.QRegExp.setMinimal` implemented minimal matching by simply reversing the greediness of the quantifiers (\ :sip:ref:`~PyQt5.QtCore.QRegExp` did not support lazy quantifiers, like ``\*?``, ``+?``, etc.). :sip:ref:`~PyQt5.QtCore.QRegularExpression` instead does support greedy, lazy and possessive quantifiers. The :sip:ref:`~PyQt5.QtCore.QRegularExpression.PatternOption.InvertedGreedinessOption` pattern option can be useful to emulate the effects of :sip:ref:`~PyQt5.QtCore.QRegExp.setMinimal`: if enabled, it inverts the greediness of quantifiers (greedy ones become lazy and vice versa).

.. _qregularexpression-caret-modes:

Caret modes
...........

The :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchOption.AnchoredMatchOption` match option can be used to emulate the :sip:ref:`~PyQt5.QtCore.QRegExp.CaretMode.CaretAtOffset` behaviour. There is no equivalent for the other :sip:ref:`~PyQt5.QtCore.QRegExp.CaretMode` modes.

.. _qregularexpression-debugging-code-that-uses-qregularexpression:

Debugging Code that Uses QRegularExpression
-------------------------------------------

:sip:ref:`~PyQt5.QtCore.QRegularExpression` internally uses a just in time compiler (JIT) to optimize the execution of the matching algorithm. The JIT makes extensive usage of self-modifying code, which can lead debugging tools such as Valgrind to crash. You must enable all checks for self-modifying code if you want to debug programs using :sip:ref:`~PyQt5.QtCore.QRegularExpression` (f.i., see Valgrind's ``--smc-check`` command line option). The downside of enabling such checks is that your program will run considerably slower.

To avoid that, the JIT is disabled by default if you compile Qt in debug mode. It is possible to override the default and enable or disable the JIT usage (both in debug or release mode) by setting the ``QT_ENABLE_REGEXP_JIT`` environment variable to a non-zero or zero value respectively.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QRegularExpression.anchoredPattern`, :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch`, :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator`.
