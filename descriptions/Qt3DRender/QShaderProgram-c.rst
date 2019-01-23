.. sip:class-description::
    :status: todo
    :brief: Encapsulates a Shader Program
    :realname: Qt3DRender::QShaderProgram
    :digest: 58d6dd246872b93be0cd4f2c68d93c31

Encapsulates a Shader Program.

A shader program consists of several different shaders, such as vertex and fragment shaders.

Qt3D will automatically populate a set of default uniforms if they are encountered during the shader instrospection phase.

+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| Default Uniform                               | Associated Qt3D Parameter name | GLSL declaration                                                     |
+===============================================+================================+======================================================================+
| ModelMatrix                                   | modelMatrix                    | uniform mat4 modelMatrix;                                            |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| ViewMatrix                                    | viewMatrix                     | uniform mat4 viewMatrix;                                             |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| ProjectionMatrix                              | projectionMatrix               | uniform mat4 projectionMatrix;                                       |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| ModelViewMatrix                               | modelView                      | uniform mat4 modelView;                                              |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| ViewProjectionMatrix                          | viewProjectionMatrix           | uniform mat4 viewProjectionMatrix;                                   |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| ModelViewProjectionMatrix                     | modelViewProjection  mvp       | uniform mat4 modelViewProjection;  uniform mat4 mvp;                 |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| InverseModelMatrix                            | inverseModelMatrix             | uniform mat4 inverseModelMatrix;                                     |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| InverseViewMatrix                             | inverseViewMatrix              | uniform mat4 inverseViewMatrix;                                      |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| InverseProjectionMatrix                       | inverseProjectionMatrix        | uniform mat4 inverseProjectionMatrix;                                |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| InverseModelViewMatrix                        | inverseModelView               | uniform mat4 inverseModelView;                                       |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| InverseViewProjectionMatrix                   | inverseViewProjectionMatrix    | uniform mat4 inverseViewProjectionMatrix;                            |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| InverseModelViewProjectionMatrix              | inverseModelViewProjection     | uniform mat4 inverseModelViewProjection;                             |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| ModelNormalMatrix                             | modelNormalMatrix              | uniform mat3 modelNormalMatrix;                                      |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| ModelViewNormalMatrix                         | modelViewNormal                | uniform mat3 modelViewNormal;                                        |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| ViewportMatrix                                | viewportMatrix                 | uniform mat4 viewportMatrix;                                         |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| InverseViewportMatrix                         | inverseViewportMatrix          | uniform mat4 inverseViewportMatrix;                                  |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| AspectRatio  (surface width / surface height) | aspectRatio                    | uniform float aspectRatio;                                           |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| Exposure                                      | exposure                       | uniform float exposure;                                              |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| Gamma                                         | gamma                          | uniform float gamma;                                                 |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| Time  (in nano seconds)                       | time                           | uniform float time;                                                  |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| EyePosition                                   | eyePosition                    | uniform vec3 eyePosition;                                            |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
| SkinningPalette                               | skinningPalette[0]             | const int maxJoints = 100;  uniform mat4 skinningPalette[maxJoints]; |
+-----------------------------------------------+--------------------------------+----------------------------------------------------------------------+
