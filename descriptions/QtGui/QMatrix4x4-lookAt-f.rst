.. sip:method-description::
    :status: todo
    :pysig: f742702ab287573ff2aefabb2cadf8a1
    :realsig: (const QVector3D&,const QVector3D&,const QVector3D&)
    :digest: 87f9309dacf39ea8ffda8b0f408b7e7f

Multiplies this matrix by a viewing matrix derived from an eye point. The *center* value indicates the center of the view that the *eye* is looking at. The *up* value indicates which direction should be considered up with respect to the *eye*.

**Note:** The *up* vector must not be parallel to the line of sight from *eye* to *center*.
