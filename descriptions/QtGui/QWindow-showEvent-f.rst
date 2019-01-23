.. sip:method-description::
    :status: todo
    :pysig: 6bcb2ebd68db77cdeb88424932ddb791
    :realsig: (QShowEvent*)
    :digest: 08930fd564af14fe566c14d27567dfd6

Override this to handle show events (\ *ev*).

The function is called when the window has requested becoming visible.

If the window is successfully shown by the windowing system, this will be followed by a resize and an expose event.
