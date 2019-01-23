.. sip:method-description::
    :status: todo
    :pysig: d737c1fed2ce4acffe846914e5836624
    :realsig: (QWindow*,bool)
    :digest: de346d3d3d2635f8cd4e71e64971fd32

Marks the specified *window* as running in the full-screen mode if *fullscreen* is true, so that the shell handles it correctly. Otherwise, removes the mark.

**Note:** You do not usually need to call this function, because the Windows taskbar always tries to determine whether a window is running in the full-screen mode.
