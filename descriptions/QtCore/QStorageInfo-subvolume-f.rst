.. sip:method-description::
    :status: todo
    :pysig: 6359afdf86b9ec14316ea3f79e266b65
    :realsig: () const
    :digest: 70d62e9b6a6b5bf0ed4b8a586bc67b0d

Returns the subvolume name for this volume.

Some filesystem types allow multiple subvolumes inside one device, which may be mounted in different paths. If the subvolume could be detected, it is returned here. The format of the subvolume name is specific to each filesystem type.

If this volume was not mounted from a subvolume of a larger filesystem or if the subvolume could not be detected, this function returns an empty byte array.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QStorageInfo.device`.
