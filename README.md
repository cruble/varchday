# varchday
A virtual arch for elementary school kids to celebrate the end of their school year at hom. There are so many rituals, traditions, and rites of passage that couldn't happen this year.  

Since kids can't get to the arch. This project was a way of bringing the arch to them. 

# <model-viewer>

This project relies heavily on Google's [model-viewer](https://github.com/google/model-viewer) web component. And uses much of the styling from this [example](https://model-viewer.glitch.me/). The most comprehensive resource for the project can be found at [modelviewer.dev](https://modelviewer.dev/). 

# Notes 

<model-viewer> works with specific 3D file formats. Blender exports .glb and .gltf files. In order for the module to work on iOS devices, you need a .usdz file. The easiest way I found to convert a .glb to a .usdz was with [Apple's Reality Converter tool](https://developer.apple.com/news/?id=01132020a) (currently in beta). I had some funky results, but that was because my normals were out of whack. That didn't effect the .glb file on the Android Chrome viewer. 

I included my models in this repository, but they are hosted on a public URL on Amazon S3. <model-viewer> seems to need access to models on a public URL. There might be some other workarounds for this, but getting them up on an S3 instance was easy and inexpensive enough. 

# models 

The low-poly models were created in Blender 2.8. The arch decorations are flat surfaces textured with a single color.  


![Archday Pre-Covid](./assets/charles_archday.jpg =250x)



![Archday Post-Covid](./assets/elsie_varch.jpg =250x)

