# [CCObj2opengl](https://github.com/ccworld1000/CCObj2opengl)

script to convert 3D models of OBJ files to OC/C/C++ float arrays (vertices, faces, texture) compatible with OpenGL ES glDrawArrays compatible with iPhone/iPad/macOS

### CCObj2opengl come frome obj2opengl

obj2opengl -->It will not be updated for a long time. This script will be slightly adjusted later

### Convert 3D models of OBJ file

```sh
CC # ls
CCObj2opengl.pl	CCTest.obj	CCTestObj.png	CCTestRun.png	LICENSE		README.md
CC # ./CCObj2opengl.pl CCTest.obj
Input file     : ./CCTest.obj
Output file    : ./CCTest.h
Object name    : CCTest
Center         : <0, 0, 0>
Scale by       : 0.5
----------------
Vertices       : 8
Faces          : 12
Texture Coords : 14
Normals        : 6
CC # ls
CCObj2opengl.pl	CCTest.h	CCTest.obj	CCTestObj.png	CCTestRun.png	LICENSE		README.md
CC #
```



### Test OBJ file

![CCTestObj.png](https://raw.github.com/ccworld1000/CCObj2opengl/main/CCTestObj.png)



![CCSphere1.png](https://raw.github.com/ccworld1000/CCObj2opengl/main/CCSphere1.png)



### Test OBJ file run iPhone

![CCCTestRun.png](https://raw.github.com/ccworld1000/CCObj2opengl/main/CCTestRun.png)

![CCSphere2.png](https://raw.github.com/ccworld1000/CCObj2opengl/main/CCSphere2.png)

