The vs_extended bundle was constructed for ease of use in the Saxion C++ 3D Rendering course.
See the MicroEngine VS2015 readme for more info on how to use this bundle.

For details on how this bundle was constructed in case you do NOT (Why god why?) want to use the bundle or want to upgrade/downgrade to a different version of a library, see below.

Bundle construction:
--------------------

1. Create basic folder vs_extended

2. Overlay GLM
--------------------------------------
Download GLM from https://github.com/g-truc/glm/releases/download/0.9.8.2/glm-0.9.8.2.zip
Copy the GLM folder at glm-0.9.8.2\glm\glm (so the deepest one) to vs_extended\include

3. Overlay GLEW
--------------------------------------
Download GLEW from http://glew.sourceforge.net/
Copy include/bin/lib to the corresponding folders with the same name in the vs_extended folder.
(Or build it from source)

4. Overlay SFML
---------------
Download http://www.sfml-dev.org/files/SFML-2.4.1-windows-vc14-32-bit.zip
Copy include/bin/lib to the corresponding folders with the same name in the vs_extended folder

