# CCObj2opengl

script to convert 3D models of OBJ files to C/C++ float arrays (vertices, faces, texture) compatible with OpenGL ES glDrawArrays compatible with iPhone/iPad 

### CCObj2opengl come frome obj2opengl

obj2opengl -->It will not be updated for a long time. This script will be slightly adjusted later

### Convert 3D models of OBJ file

```sh
CC # ls
CCObj2opengl.pl	CCTest.obj	CCTestObj.png	CCTestRun.png	LICENSE		README.md
CC # ./CCObj2opengl.pl CCTest.obj
defined(@array) is deprecated at ./CCObj2opengl.pl line 156.
	(Maybe you should just omit the defined()?)
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

### Test OBJ file run iPhone

![CCCTestRun.png](https://raw.github.com/ccworld1000/CCObj2opengl/main/CCTestRun.png)