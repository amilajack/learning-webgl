# learning-webgl

### Links
* https://webglfundamentals.org
* https://codepen.io/rachsmith/post/beginning-with-3d-webgl-pt-1-the-scene
* https://www.awwwards.com/awwwards/collections/shaders-are-easy/
* https://threejs.org/docs/#manual/introduction/Useful-links
* http://blog.cjgammon.com/
* https://tympanus.net/codrops/2016/04/26/the-aviator-animating-basic-3d-scene-threejs/
* [Shaders](https://aerotwist.com/tutorials/an-introduction-to-shaders-part-1/)
* http://www.gabrielgambetta.com/computer-graphics-from-scratch/table-of-contents.html
* Blender
    * https://www.creativebloq.com/3d-tips/blender-tutorials-1232739
### Books
* The Book of Shaders
* [WebGL Insights](http://www.webglinsights.com)
### Tutorials
* https://tympanus.net/codrops/2016/04/26/the-aviator-animating-basic-3d-scene-threejs/
### Videos
### Repos
### Books

## VR
* [aframe registry](https://aframe.io/aframe-registry/)

### FFT
* https://www.ibiblio.org/e-notes/webgl/gpu/contents.htm
* https://github.com/jbouny/fft-ocean

## Three.js Examples
* http://stemkoski.github.io/Three.js/

### Playgrounds
* http://jessevdk.github.io/webgl-play/
* [thebookofshaders editor](http://editor.thebookofshaders.com/)


### Modeling
* Practice Models
    * My bedroom
        * Maybe later I can turn this into some kind of VR experience

### Notes
* Three.js
    * Three.js always requires the following:
        * Camera, material, perspective 
    * Materials
        * Describe the apperance of something
        * Shaders can be passed to materials
    * Geometry
        * Mesh is an object that takes a Geometry and applies a Material to it
        * This is the "skeleton" of objects
    * Mesh
        * Composed of a geometry and a material
        * This is the "skin" of objects
    * Object3D
    * Shaders
        * Vertex Shaders
            * They draw vertices
        * Fragment Shaders
            * They fill in colors in shapes
        * Data Types
            * `float`, `vec2`, `vec3`, `vec4`, `mat2`, `mat3`, `mat4`
            * (currently reading [this](http://blog.cjgammon.com/threejs-custom-shader-material))
            * vectors can be accessed as objects
            * https://www.youtube.com/watch?v=JYj6e-72RDs
        * Variable types
            * `uniform`
                * Defines which properties can be created and modified from outside the shaders (by javascript)
            * `varying`
                * Defines what the frag shader can access from vertex shader
                * This is similar to scoping (?) Defines visibility of variables to frag shader
                * Each shader has its own `gl_FragColor` so this is an example of a `varying`
            * `attribute`
                * Per pixel properties defined only in vertex shader
    * Models
        * Models come in certain formats:
            * obj
            * fbx
            * etc
        * They can be created using blender


### 3D Recosntruction
* https://github.com/cdcseacave/openMVS
* https://github.com/cdcseacave/openMVS/wiki/Usage

#### Game Development
* https://80.lv/articles/star-wars-scene-production-in-ue4/
* https://blog.openbloc.fr/gamedev-with-three-js-on-the-modern-web/

#### Misc
* [Generative Art](https://inconvergent.net/generative/)

![hierarchy](https://amilajack.com/content/images/2018/06/hierarchy.png)
