.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const QString&)
    :digest: 1071e566a4f8987d55b0a71526bb10b1

Starts the search process using the given search phrase *searchInput*.

The phrase may consist of several words. By default, the search engine returns the list of documents that contain all the specified words. The phrase may contain any combination of the logical operators AND, OR, and NOT. The operator must be written in all capital letters, otherwise it will be considered a part of the search phrase.

If double quotation marks are used to group the words, the search engine will search for an exact match of the quoted phrase.

For more information about the text query syntax, see SQLite FTS5 Extension.
