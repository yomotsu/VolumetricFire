VolumetricFire is a JS lib ported from [Alfred Fuller's Real-time Procedural Volumetric Fire Demo](http://webgl-fire.appspot.com/html/fire.html) to Mesh class for three.js.

![](capture.gif)

VolumetricFire does not use particle system. Because maximum `pointSize` of particles( a.k.a. VTF ) is limited and uncontrollable. Therefore, VolumetricFire is not limited by maximum size.

You can use fire meshes of VolumetricFire provides with `position.set()`, `rotate.set()`, `scale.set()` and other THREE.Mesh features.

- [example1: basic usage](http://yomotsu.github.io/VolumetricFire/examples/example1.html)
- [example2](http://yomotsu.github.io/VolumetricFire/examples/example2.html)
