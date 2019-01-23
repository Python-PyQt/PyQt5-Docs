.. sip:class-description::
    :status: todo
    :brief: Default implementation of the phong lighting effect where the diffuse and specular light components are read from texture maps
    :realname: Qt3DExtras::QDiffuseSpecularMapMaterial
    :digest: 18c381d5382643a5c37b3baf3c403e9b

The :sip:ref:`~PyQt5.Qt3DExtras.QDiffuseSpecularMapMaterial` provides a default implementation of the phong lighting effect where the diffuse and specular light components are read from texture maps.

This class is deprecated; use :sip:ref:`~PyQt5.Qt3DExtras.QDiffuseSpecularMaterial` instead.

The specular lighting effect is based on the combination of 3 lighting components ambient, diffuse and specular. The relative strengths of these components are controlled by means of their reflectivity coefficients which are modelled as RGB triplets:

* Ambient is the color that is emitted by an object without any other light source.

* Diffuse is the color that is emitted for rought surface reflections with the lights.

* Specular is the color emitted for shiny surface reflections with the lights.

* The shininess of a surface is controlled by a float property.

This material uses an effect with a single render pass approach and performs per fragment lighting. Techniques are provided for OpenGL 2, OpenGL 3 or above as well as OpenGL ES 2.
