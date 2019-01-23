.. sip:enum-member-description::
    :status: todo
    :value: 0
    :digest: e4199774f8528e9503a27e3694e8ed11

This attribute is no longer fully supported in Qt 5. It ensures that widgets are created as soon as they are constructed. By default, resources for widgets are allocated on demand to improve efficiency and minimize resource usage. Setting or clearing this attribute affects widgets constructed after the change. Setting it tells Qt to create toplevel windows immediately. Therefore, if it is important to minimize resource consumption, do not set this attribute.
