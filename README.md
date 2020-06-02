# varchday
A virtual arch for elementary school kids to celebrate the end of their school year at hom. There are so many rituals, traditions, and rites of passage that couldn't happen this year.  Live site is [here](https://cruble.github.io/varchday). Best viewed on your mobile device. 

Since kids can't get to the arch. This project was a way of bringing the arch to them. But this project is also a template for anyone who wants to bring in a 3D model into a simple, clean, web-based 3D viewer with AR capabilities. Even though I didn't use animations here, the component supports it. 

# model-viewer

This project relies heavily on Google's [model-viewer](https://github.com/google/model-viewer) web component.  Much of the styling is from their [example](https://model-viewer.glitch.me/). The most comprehensive resource for the component can be found at [modelviewer.dev](https://modelviewer.dev/).   

# models 

The component works with specific .glb and .glTF 3D file formats. Those can be exported directly from Blender and most 3D modelling software. This arch was modelled in Blender. In order for the module to work on iOS devices, you need a .usdz file. The easiest way I found to convert a .glb to a .usdz was with [Apple's Reality Converter tool](https://developer.apple.com/news/?id=01132020a) (currently in beta). I had some funky results the first time I used it, but that was due to my normals being off on some of the surfaces. Interestingly, that didn't effect the .glb file on the Android Chrome viewer. Both of the models are in the assets file. If you are forking this project for your own use, you will want to change the path in the index.html file. 

	src="https://cruble.github.io/varchday/assets/varch-3-1.glb" 
	ios-src="https://varch.s3.amazonaws.com/varch-3-1.usdz" 



