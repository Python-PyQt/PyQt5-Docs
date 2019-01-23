.. sip:class-description::
    :status: todo
    :brief: Pattern matching using regular expressions
    :digest: ce6912bb9c1295f6f0c3a35a0edb4bef

The :sip:ref:`~PyQt5.QtCore.QRegExp` class provides pattern matching using regular expressions.

A regular expression, or "regexp", is a pattern for matching substrings in a text. This is useful in many contexts, e.g.,

+--------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Validation         | A regexp can test whether a substring meets some criteria, e.g. is an integer or contains no whitespace.                                                                                                                  |
+--------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Searching          | A regexp provides more powerful pattern matching than simple substring matching, e.g., match one of the words *mail*, *letter* or *correspondence*, but none of the words *email*, *mailman*, *mailer*, *letterbox*, etc. |
+--------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Search and Replace | A regexp can replace all occurrences of a substring with a different substring, e.g., replace all occurrences of *&* with *&amp;* except where the *&* is already followed by an *amp;*.                                  |
+--------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| String Splitting   | A regexp can be used to identify where a string should be split apart, e.g. splitting tab-delimited strings.                                                                                                              |
+--------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

A brief introduction to regexps is presented, a description of Qt's regexp language, some examples, and the function documentation itself. :sip:ref:`~PyQt5.QtCore.QRegExp` is modeled on Perl's regexp language. It fully supports Unicode. :sip:ref:`~PyQt5.QtCore.QRegExp` can also be used in a simpler, *wildcard mode* that is similar to the functionality found in command shells. The syntax rules used by :sip:ref:`~PyQt5.QtCore.QRegExp` can be changed with :sip:ref:`~PyQt5.QtCore.QRegExp.setPatternSyntax`. In particular, the pattern syntax can be set to :sip:ref:`~PyQt5.QtCore.QRegExp.PatternSyntax.FixedString`, which means the pattern to be matched is interpreted as a plain string, i.e., special characters (e.g., backslash) are not escaped.

A good text on regexps is *Mastering Regular Expressions* (Third Edition) by Jeffrey E. F. Friedl, ISBN 0-596-52812-4.

**Note:** In Qt 5, the new :sip:ref:`~PyQt5.QtCore.QRegularExpression` class provides a Perl compatible implementation of regular expressions and is recommended in place of :sip:ref:`~PyQt5.QtCore.QRegExp`.

.. _qregexp-introduction:

Introduction
------------

Regexps are built up from expressions, quantifiers, and assertions. The simplest expression is a character, e.g. **x** or **5**. An expression can also be a set of characters enclosed in square brackets. **[ABCD]** will match an **A** or a **B** or a **C** or a **D**. We can write this same expression as **[A-D]**, and an expression to match any capital letter in the English alphabet is written as **[A-Z]**.

A quantifier specifies the number of occurrences of an expression that must be matched. **x{1,1}** means match one and only one **x**. **x{1,5}** means match a sequence of **x** characters that contains at least one **x** but no more than five.

Note that in general regexps cannot be used to check for balanced brackets or tags. For example, a regexp can be written to match an opening html ``<b>`` and its closing ``</b>``, if the ``<b>`` tags are not nested, but if the ``<b>`` tags are nested, that same regexp will match an opening ``<b>`` tag with the wrong closing ``</b>``. For the fragment ``<b>bold <b>bolder</b></b>``, the first ``<b>`` would be matched with the first ``</b>``, which is not correct. However, it is possible to write a regexp that will match nested brackets or tags correctly, but only if the number of nesting levels is fixed and known. If the number of nesting levels is not fixed and known, it is impossible to write a regexp that will not fail.

Suppose we want a regexp to match integers in the range 0 to 99. At least one digit is required, so we start with the expression **[0-9]{1,1}**, which matches a single digit exactly once. This regexp matches integers in the range 0 to 9. To match integers up to 99, increase the maximum number of occurrences to 2, so the regexp becomes **[0-9]{1,2}**. This regexp satisfies the original requirement to match integers from 0 to 99, but it will also match integers that occur in the middle of strings. If we want the matched integer to be the whole string, we must use the anchor assertions, **^** (caret) and **$** (dollar). When **^** is the first character in a regexp, it means the regexp must match from the beginning of the string. When **$** is the last character of the regexp, it means the regexp must match to the end of the string. The regexp becomes **^[0-9]{1,2}$**. Note that assertions, e.g. **^** and **$**, do not match characters but locations in the string.

If you have seen regexps described elsewhere, they may have looked different from the ones shown here. This is because some sets of characters and some quantifiers are so common that they have been given special symbols to represent them. **[0-9]** can be replaced with the symbol **\\d**. The quantifier to match exactly one occurrence, **{1,1}**, can be replaced with the expression itself, i.e. **x{1,1}** is the same as **x**. So our 0 to 99 matcher could be written as **^\\d{1,2}$**. It can also be written **^\\d\\d{0,1}$**, i.e. *From the start of the string, match a digit, followed immediately by 0 or 1 digits*. In practice, it would be written as **^\\d\\d?$**. The **?** is shorthand for the quantifier **{0,1}**, i.e. 0 or 1 occurrences. **?** makes an expression optional. The regexp **^\\d\\d?$** means *From the beginning of the string, match one digit, followed immediately by 0 or 1 more digit, followed immediately by end of string*.

To write a regexp that matches one of the words 'mail' *or* 'letter' *or* 'correspondence' but does not match words that contain these words, e.g., 'email', 'mailman', 'mailer', and 'letterbox', start with a regexp that matches 'mail'. Expressed fully, the regexp is **m{1,1}a{1,1}i{1,1}l{1,1}**, but because a character expression is automatically quantified by **{1,1}**, we can simplify the regexp to **mail**, i.e., an 'm' followed by an 'a' followed by an 'i' followed by an 'l'. Now we can use the vertical bar **|**, which means **or**, to include the other two words, so our regexp for matching any of the three words becomes **mail|letter|correspondence**. Match 'mail' **or** 'letter' **or** 'correspondence'. While this regexp will match one of the three words we want to match, it will also match words we don't want to match, e.g., 'email'. To prevent the regexp from matching unwanted words, we must tell it to begin and end the match at word boundaries. First we enclose our regexp in parentheses, **(mail|letter|correspondence)**. Parentheses group expressions together, and they identify a part of the regexp that we wish to capture. Enclosing the expression in parentheses allows us to use it as a component in more complex regexps. It also allows us to examine which of the three words was actually matched. To force the match to begin and end on word boundaries, we enclose the regexp in **\\b** *word boundary* assertions: **\\b(mail|letter|correspondence)\\b**. Now the regexp means: *Match a word boundary, followed by the regexp in parentheses, followed by a word boundary*. The **\\b** assertion matches a *position* in the regexp, not a *character*. A word boundary is any non-word character, e.g., a space, newline, or the beginning or ending of a string.

If we want to replace ampersand characters with the HTML entity **&amp;**, the regexp to match is simply **&**. But this regexp will also match ampersands that have already been converted to HTML entities. We want to replace only ampersands that are not already followed by **amp;**. For this, we need the negative lookahead assertion, **(?!**__\ **)**. The regexp can then be written as **&(?!amp;)**, i.e. *Match an ampersand that is* **not** *followed by* **amp;**.

If we want to count all the occurrences of 'Eric' and 'Eirik' in a string, two valid solutions are **\\b(Eric|Eirik)\\b** and **\\bEi?ri[ck]\\b**. The word boundary assertion '\\b' is required to avoid matching words that contain either name, e.g. 'Ericsson'. Note that the second regexp matches more spellings than we want: 'Eric', 'Erik', 'Eiric' and 'Eirik'.

Some of the examples discussed above are implemented in the code examples section.

.. _qregexp-characters-and-abbreviations-for-sets-of-characters:

Characters and Abbreviations for Sets of Characters
---------------------------------------------------

+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Element                             | Meaning                                                                                                                                                                   |
+=====================================+===========================================================================================================================================================================+
| **c**                               | A character represents itself unless it has a special regexp meaning. e.g. **c** matches the character *c*.                                                               |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\c**                             | A character that follows a backslash matches the character itself, except as specified below. e.g., To match a literal caret at the beginning of a string, write **\\^**. |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\a**                             | Matches the ASCII bell (BEL, 0x07).                                                                                                                                       |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\f**                             | Matches the ASCII form feed (FF, 0x0C).                                                                                                                                   |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\n**                             | Matches the ASCII line feed (LF, 0x0A, Unix newline).                                                                                                                     |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\r**                             | Matches the ASCII carriage return (CR, 0x0D).                                                                                                                             |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\t**                             | Matches the ASCII horizontal tab (HT, 0x09).                                                                                                                              |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\v**                             | Matches the ASCII vertical tab (VT, 0x0B).                                                                                                                                |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\x\ *hhhh***                     | Matches the Unicode character corresponding to the hexadecimal number *hhhh* (between 0x0000 and 0xFFFF).                                                                 |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\0\ *ooo*** (i.e., \\zero *ooo*) | matches the ASCII/Latin1 character for the octal number *ooo* (between 0 and 0377).                                                                                       |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **. (dot)**                         | Matches any character (including newline).                                                                                                                                |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\d**                             | Matches a digit (QChar::isDigit()).                                                                                                                                       |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\D**                             | Matches a non-digit.                                                                                                                                                      |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\s**                             | Matches a whitespace character (QChar::isSpace()).                                                                                                                        |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\S**                             | Matches a non-whitespace character.                                                                                                                                       |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\w**                             | Matches a word character (QChar::isLetterOrNumber(), QChar::isMark(), or '_').                                                                                            |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\W**                             | Matches a non-word character.                                                                                                                                             |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\\ *n***                         | The *n*-th backreference, e.g. \\1, \\2, etc.                                                                                                                             |
+-------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

**Note:** The C++ compiler transforms backslashes in strings. To include a **\\** in a regexp, enter it twice, i.e. ``\\``. To match the backslash character itself, enter it four times, i.e. ``\\\\``.

.. _qregexp-sets-of-characters:

Sets of Characters
------------------

Square brackets mean match any character contained in the square brackets. The character set abbreviations described above can appear in a character set in square brackets. Except for the character set abbreviations and the following two exceptions, characters do not have special meanings in square brackets.

+-------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **^** | The caret negates the character set if it occurs as the first character (i.e. immediately after the opening square bracket). **[abc]** matches 'a' or 'b' or 'c', but **[^abc]** matches anything *but* 'a' or 'b' or 'c'. |
+-------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **-** | The dash indicates a range of characters. **[W-Z]** matches 'W' or 'X' or 'Y' or 'Z'.                                                                                                                                      |
+-------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Using the predefined character set abbreviations is more portable than using character ranges across platforms and languages. For example, **[0-9]** matches a digit in Western alphabets but **\\d** matches a digit in *any* alphabet.

Note: In other regexp documentation, sets of characters are often called "character classes".

.. _qregexp-quantifiers:

Quantifiers
-----------

By default, an expression is automatically quantified by **{1,1}**, i.e. it should occur exactly once. In the following list, **\ *E*** stands for expression. An expression is a character, or an abbreviation for a set of characters, or a set of characters in square brackets, or an expression in parentheses.

+----------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\ *E*?**     | Matches zero or one occurrences of *E*. This quantifier means *The previous expression is optional*, because it will match whether or not the expression is found. **\ *E*?** is the same as **\ *E*{0,1}**. e.g., **dents?** matches 'dent' or 'dents'.                                                                                                                                                                                                               |
+----------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\ *E*+**     | Matches one or more occurrences of *E*. **\ *E*+** is the same as **\ *E*{1,}**. e.g., **0+** matches '0', '00', '000', etc.                                                                                                                                                                                                                                                                                                                                           |
+----------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\ *E*\***    | Matches zero or more occurrences of *E*. It is the same as **\ *E*{0,}**. The **\*** quantifier is often used in error where **+** should be used. For example, if **\\s\*$** is used in an expression to match strings that end in whitespace, it will match every string because **\\s\*$** means *Match zero or more whitespaces followed by end of string*. The correct regexp to match strings that have at least one trailing whitespace character is **\\s+$**. |
+----------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\ *E*{n}**   | Matches exactly *n* occurrences of *E*. **\ *E*{n}** is the same as repeating *E* *n* times. For example, **x{5}** is the same as **xxxxx**. It is also the same as **\ *E*{n,n}**, e.g. **x{5,5}**.                                                                                                                                                                                                                                                                   |
+----------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\ *E*{n,}**  | Matches at least *n* occurrences of *E*.                                                                                                                                                                                                                                                                                                                                                                                                                               |
+----------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\ *E*{,m}**  | Matches at most *m* occurrences of *E*. **\ *E*{,m}** is the same as **\ *E*{0,m}**.                                                                                                                                                                                                                                                                                                                                                                                   |
+----------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\ *E*{n,m}** | Matches at least *n* and at most *m* occurrences of *E*.                                                                                                                                                                                                                                                                                                                                                                                                               |
+----------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

To apply a quantifier to more than just the preceding character, use parentheses to group characters together in an expression. For example, **tag+** matches a 't' followed by an 'a' followed by at least one 'g', whereas **(tag)+** matches at least one occurrence of 'tag'.

Note: Quantifiers are normally "greedy". They always match as much text as they can. For example, **0+** matches the first zero it finds and all the consecutive zeros after the first zero. Applied to '20005', it matches '25'. Quantifiers can be made non-greedy, see :sip:ref:`~PyQt5.QtCore.QRegExp.setMinimal`.

.. _qregexp-capturing-parentheses:

.. _qregexp-backreferences:

.. _qregexp-capturing-text:

Capturing Text
--------------

Parentheses allow us to group elements together so that we can quantify and capture them. For example if we have the expression **mail|letter|correspondence** that matches a string we know that *one* of the words matched but not which one. Using parentheses allows us to "capture" whatever is matched within their bounds, so if we used **(mail|letter|correspondence)** and matched this regexp against the string "I sent you some email" we can use the :sip:ref:`~PyQt5.QtCore.QRegExp.cap` or :sip:ref:`~PyQt5.QtCore.QRegExp.capturedTexts` functions to extract the matched characters, in this case 'mail'.

We can use captured text within the regexp itself. To refer to the captured text we use *backreferences* which are indexed from 1, the same as for :sip:ref:`~PyQt5.QtCore.QRegExp.cap`. For example we could search for duplicate words in a string using **\\b(\\w+)\\W+\\1\\b** which means match a word boundary followed by one or more word characters followed by one or more non-word characters followed by the same text as the first parenthesized expression followed by a word boundary.

If we want to use parentheses purely for grouping and not for capturing we can use the non-capturing syntax, e.g. **(?:green|blue)**. Non-capturing parentheses begin '(?:' and end ')'. In this example we match either 'green' or 'blue' but we do not capture the match so we only know whether or not we matched but not which color we actually found. Using non-capturing parentheses is more efficient than using capturing parentheses since the regexp engine has to do less book-keeping.

Both capturing and non-capturing parentheses may be nested.

.. _qregexp-greedy-quantifiers:

For historical reasons, quantifiers (e.g. **\***) that apply to capturing parentheses are more "greedy" than other quantifiers. For example, **a\*(a\*)** will match "aaa" with cap(1) == "aaa". This behavior is different from what other regexp engines do (notably, Perl). To obtain a more intuitive capturing behavior, specify :sip:ref:`~PyQt5.QtCore.QRegExp.PatternSyntax.RegExp2` to the :sip:ref:`~PyQt5.QtCore.QRegExp` constructor or call :sip:ref:`~PyQt5.QtCore.QRegExp.setPatternSyntax`\ (\ :sip:ref:`~PyQt5.QtCore.QRegExp.PatternSyntax.RegExp2`).

.. _qregexp-cap-in-a-loop:

When the number of matches cannot be determined in advance, a common idiom is to use :sip:ref:`~PyQt5.QtCore.QRegExp.cap` in a loop. For example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregexp.py
    :lines: 54-63

.. _qregexp-assertions:

Assertions
----------

Assertions make some statement about the text at the point where they occur in the regexp but they do not match any characters. In the following list **\ *E*** stands for any expression.

+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **^**         | The caret signifies the beginning of the string. If you wish to match a literal ``^`` you must escape it by writing ``\\^``. For example, **^#include** will only match strings which *begin* with the characters '#include'. (When the caret is the first character of a character set it has a special meaning, see Sets of Characters.)                                                                                                |
+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **$**         | The dollar signifies the end of the string. For example **\\d\\s\*$** will match strings which end with a digit optionally followed by whitespace. If you wish to match a literal ``$`` you must escape it by writing ``\\$``.                                                                                                                                                                                                            |
+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\b**       | A word boundary. For example the regexp **\\bOK\\b** means match immediately after a word boundary (e.g. start of string or whitespace) the letter 'O' then the letter 'K' immediately before another word boundary (e.g. end of string or whitespace). But note that the assertion does not actually match any whitespace so if we write **(\\bOK\\b)** and we have a match it will only contain 'OK' even if the string is "It's  now". |
+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\\B**       | A non-word boundary. This assertion is true wherever **\\b** is false. For example if we searched for **\\Bon\\B** in "Left on" the match would fail (space and end of string aren't non-word boundaries), but it would match in "tne".                                                                                                                                                                                                   |
+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **(?=\ *E*)** | Positive lookahead. This assertion is true if the expression matches at this point in the regexp. For example, **const(?=\\s+char)** matches 'const' whenever it is followed by 'char', as in 'static  char \*'. (Compare with **const\\s+char**, which matches 'static  \*'.)                                                                                                                                                            |
+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **(?!\ *E*)** | Negative lookahead. This assertion is true if the expression does not match at this point in the regexp. For example, **const(?!\\s+char)** matches 'const' *except* when it is followed by 'char'.                                                                                                                                                                                                                                       |
+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

.. _qregexp-qregexp-wildcard-matching:

.. _qregexp-wildcard-matching:

Wildcard Matching
-----------------

Most command shells such as *bash* or *cmd.exe* support "file globbing", the ability to identify a group of files by using wildcards. The :sip:ref:`~PyQt5.QtCore.QRegExp.setPatternSyntax` function is used to switch between regexp and wildcard mode. Wildcard matching is much simpler than full regexps and has only four features:

+-----------+----------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **c**     | Any character represents itself apart from those mentioned below. Thus **c** matches the character *c*.                                                        |
+-----------+----------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **?**     | Matches any single character. It is the same as **.** in full regexps.                                                                                         |
+-----------+----------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **\***    | Matches zero or more of any characters. It is the same as **.\*** in full regexps.                                                                             |
+-----------+----------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **[...]** | Sets of characters can be represented in square brackets, similar to full regexps. Within the character class, like outside, backslash has no special meaning. |
+-----------+----------------------------------------------------------------------------------------------------------------------------------------------------------------+

In the mode Wildcard, the wildcard characters cannot be escaped. In the mode :sip:ref:`~PyQt5.QtCore.QRegExp.PatternSyntax.WildcardUnix`, the character '\\' escapes the wildcard.

For example if we are in wildcard mode and have strings which contain filenames we could identify HTML files with **\*.html**. This will match zero or more characters followed by a dot followed by 'h', 't', 'm' and 'l'.

To test a string against a wildcard expression, use :sip:ref:`~PyQt5.QtCore.QRegExp.exactMatch`. For example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregexp.py
    :lines: 68-71

.. _qregexp-perl-users:

.. _qregexp-notes-for-perl-users:

Notes for Perl Users
--------------------

Most of the character class abbreviations supported by Perl are supported by :sip:ref:`~PyQt5.QtCore.QRegExp`, see characters and abbreviations for sets of characters.

In :sip:ref:`~PyQt5.QtCore.QRegExp`, apart from within character classes, ``^`` always signifies the start of the string, so carets must always be escaped unless used for that purpose. In Perl the meaning of caret varies automagically depending on where it occurs so escaping it is rarely necessary. The same applies to ``$`` which in :sip:ref:`~PyQt5.QtCore.QRegExp` always signifies the end of the string.

:sip:ref:`~PyQt5.QtCore.QRegExp`'s quantifiers are the same as Perl's greedy quantifiers (but see the :ref:`note above<qregexp-greedy-quantifiers>`). Non-greedy matching cannot be applied to individual quantifiers, but can be applied to all the quantifiers in the pattern. For example, to match the Perl regexp **ro+?m** requires:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregexp.py
    :lines: 76-77

The equivalent of Perl's ``/i`` option is :sip:ref:`~PyQt5.QtCore.QRegExp.setCaseSensitivity`\ (\ :sip:ref:`~PyQt5.QtCore.Qt.CaseSensitivity.CaseInsensitive`).

Perl's ``/g`` option can be emulated using a :ref:`loop<qregexp-cap-in-a-loop>`.

In :sip:ref:`~PyQt5.QtCore.QRegExp` **.** matches any character, therefore all :sip:ref:`~PyQt5.QtCore.QRegExp` regexps have the equivalent of Perl's ``/s`` option. :sip:ref:`~PyQt5.QtCore.QRegExp` does not have an equivalent to Perl's ``/m`` option, but this can be emulated in various ways for example by splitting the input into lines or by looping with a regexp that searches for newlines.

Because :sip:ref:`~PyQt5.QtCore.QRegExp` is string oriented, there are no \\A, \\Z, or \\z assertions. The \\G assertion is not supported but can be emulated in a loop.

Perl's $& is cap(0) or :sip:ref:`~PyQt5.QtCore.QRegExp.capturedTexts`[0]. There are no :sip:ref:`~PyQt5.QtCore.QRegExp` equivalents for $`, $' or $+. Perl's capturing variables, $1, $2, ... correspond to cap(1) or :sip:ref:`~PyQt5.QtCore.QRegExp.capturedTexts`[1], cap(2) or :sip:ref:`~PyQt5.QtCore.QRegExp.capturedTexts`[2], etc.

To substitute a pattern use QString::replace().

Perl's extended ``/x`` syntax is not supported, nor are directives, e.g. (?i), or regexp comments, e.g. (?#comment). On the other hand, C++'s rules for literal strings can be used to achieve the same:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregexp.py
    :lines: 82-84

Both zero-width positive and zero-width negative lookahead assertions (?=pattern) and (?!pattern) are supported with the same syntax as Perl. Perl's lookbehind assertions, "independent" subexpressions and conditional expressions are not supported.

Non-capturing parentheses are also supported, with the same (?:pattern) syntax.

See QString::split() and QStringList::join() for equivalents to Perl's split and join functions.

Note: because C++ transforms \\'s they must be written *twice* in code, e.g. **\\b** must be written **\\\\b**.

.. _qregexp-code-examples:

Code Examples
-------------

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregexp.py
    :lines: 89-92

The third string matches ''. This is a simple validation regexp for integers in the range 0 to 99.

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregexp.py
    :lines: 97-99

The second string matches ''. We've used the character set abbreviation '\\S' (non-whitespace) and the anchors to match strings which contain no whitespace.

In the following example we match strings containing 'mail' or 'letter' or 'correspondence' but only match whole words i.e. not 'email'

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregexp.py
    :lines: 104-106

The second string matches "Please write the ". The word 'letter' is also captured (because of the parentheses). We can see what text we've captured like this:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregexp.py
    :lines: 111-111

This will capture the text from the first set of capturing parentheses (counting capturing left parentheses from left to right). The parentheses are counted from 1 since cap(0) is the whole matched regexp (equivalent to '&' in most regexp engines).

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregexp.py
    :lines: 116-122

Here we've passed the :sip:ref:`~PyQt5.QtCore.QRegExp` to QString's replace() function to replace the matched text with new text.

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregexp.py
    :lines: 127-138

We've used the :sip:ref:`~PyQt5.QtCore.QRegExp.indexIn` function to repeatedly match the regexp in the string. Note that instead of moving forward by one character at a time ``pos++`` we could have written ``pos += rx.matchedLength()`` to skip over the already matched string. The count will equal 3, matching 'One  another , and an Ericsson. How many Eiriks, ?'; it doesn't match 'Ericsson' or 'Eiriks' because they are not bounded by non-word boundaries.

One common use of regexps is to split lines of delimited data into their component fields.

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregexp.py
    :lines: 143-150

In this example our input lines have the format company name, web address and country. Unfortunately the regexp is rather long and not very versatile -- the code will break if we add any more fields. A simpler and better solution is to look for the separator, '\\t' in this case, and take the surrounding text. The QString::split() function can take a separator string or regexp as an argument and split a string accordingly.

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregexp.py
    :lines: 155-155

Here field[0] is the company, field[1] the web address and so on.

To imitate the matching of a shell we can use wildcard mode.

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qregexp.py
    :lines: 160-164

Wildcard matching can be convenient because of its simplicity, but any wildcard regexp can be defined using full regexps, e.g. **.\*\\.html$**. Notice that we can't match both ``.html`` and ``.htm`` files with a wildcard unless we use **\*.htm\*** which will also match 'test.html.bak'. A full regexp gives us the precision we need, **.\*\\.html?$**.

:sip:ref:`~PyQt5.QtCore.QRegExp` can match case insensitively using :sip:ref:`~PyQt5.QtCore.QRegExp.setCaseSensitivity`, and can use non-greedy matching, see :sip:ref:`~PyQt5.QtCore.QRegExp.setMinimal`. By default :sip:ref:`~PyQt5.QtCore.QRegExp` uses full regexps but this can be changed with :sip:ref:`~PyQt5.QtCore.QRegExp.setPatternSyntax`. Searching can be done forward with :sip:ref:`~PyQt5.QtCore.QRegExp.indexIn` or backward with :sip:ref:`~PyQt5.QtCore.QRegExp.lastIndexIn`. Captured text can be accessed using :sip:ref:`~PyQt5.QtCore.QRegExp.capturedTexts` which returns a string list of all captured strings, or using :sip:ref:`~PyQt5.QtCore.QRegExp.cap` which returns the captured string for the given index. The :sip:ref:`~PyQt5.QtCore.QRegExp.pos` function takes a match index and returns the position in the string where the match was made (or -1 if there was no match).

.. seealso:: QString, QStringList, :sip:ref:`~PyQt5.QtGui.QRegExpValidator`, :sip:ref:`~PyQt5.QtCore.QSortFilterProxyModel`, `Regular Expression Example <https://doc.qt.io/qt-5/qtwidgets-tools-regexp-example.html>`_.
