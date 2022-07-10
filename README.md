# Lightsource

This routine calculates a projection of a set of coloured light points onto a given number of arbitrarily positioned and rotated surfaces.

## live

### version 1
![Snapshot](https://necip65.github.io/lightsource/lightsource.jpg)

https://necip65.github.io/lightsource/

* The planes can be moved, please use the gizzmo.
* drawback: a set of single triangles are created.
* drawback: light points are fixed and can not be rotated.

### version 2

![Snapshot](https://necip65.github.io/lightsource/version2.jpg)
https://necip65.github.io/lightsource/version2.html

* click on one of the surfaces to start projection (can take some seconds)
* light points are now rotateable.
* only one mesh is now created for the light projections.


### version 2a

https://necip65.github.io/lightsource/version2a.html

* gizzmo: rotate, scale, pos the meshes
* click on menu "create" to start projection
* click on menu "show" to show/hide the meshes
* if the max z distances of 3 interesection points are greater than 10 the triangle are set invisible.


### version 2b

![Snapshot](https://necip65.github.io/lightsource/version2b.jpg)
https://necip65.github.io/lightsource/version2b.html

* light points have now a parent mesh which can be handled with the gizzmo


### version 2c

![Snapshot](https://necip65.github.io/lightsource/version2c.jpg)
https://necip65.github.io/lightsource/version2c.html

* gizmo now usable only for the meshBase of the light points
* menu removed. commands now via keyboard. first click on an object mesh.
** press 'o' to prOject the light or create the mesh in earlier versions
** press first 'p' (for position) then use x,y,z or X,Y,Z
** press first 'r' (for rotation) then use x,y,z or X,Y,Z

