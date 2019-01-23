.. sip:enum-member-description::
    :status: todo
    :value: 0x00000002
    :digest: ceaa962d011235b8c233ec0c76176081

Network sessions and their sockets can be bound to a particular network interface. Any packet that passes through the socket goes to the specified network interface and thus disregards standard routing table entries. This may be useful when two interfaces can reach overlapping IP ranges or an application has specific needs in regards to target networks. This option is platform specific and may not always be available.
