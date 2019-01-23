.. sip:method-description::
    :status: todo
    :pysig: d6ee3e0f03ce4e4f78df9293fc450319
    :realsig: (QTextInlineObject,int,const QTextFormat&)
    :digest: d9006452baf17a95fad8d0a2da4eebfe

Sets the size of the inline object *item* corresponding to the text *format*.

*posInDocument* specifies the position of the object within the document.

The default implementation resizes the *item* to the size returned by the object handler's intrinsicSize() function. This function is called only within Qt. Subclasses can reimplement this function to customize the resizing of inline objects.
