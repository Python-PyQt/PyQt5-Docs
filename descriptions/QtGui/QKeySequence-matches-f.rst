.. sip:method-description::
    :status: todo
    :pysig: a688e4ef0cca1ea6c4b8864e92d7f363
    :realsig: (const QKeySequence&) const
    :digest: b81c3a7109cbb12d8196a796423c0f85

Matches the sequence with *seq*. Returns :sip:ref:`~PyQt5.QtGui.QKeySequence.SequenceMatch.ExactMatch` if successful, :sip:ref:`~PyQt5.QtGui.QKeySequence.SequenceMatch.PartialMatch` if *seq* matches incompletely, and :sip:ref:`~PyQt5.QtGui.QKeySequence.SequenceMatch.NoMatch` if the sequences have nothing in common. Returns :sip:ref:`~PyQt5.QtGui.QKeySequence.SequenceMatch.NoMatch` if *seq* is shorter.
