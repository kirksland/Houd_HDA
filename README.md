# Houd_HDA
All my HDA tools for houdini : 


## Custom box

a simple box tools who align the box with the ground.

<image src="WIkiHoudini/customBox.jpg" width= 500>
  
  ## Breackdown tool
  
  Function to translate each piece of a mesh if their pack, with a bounding box 
  
  <image src="WIkiHoudini/breackDown.jpg" width= 500>
  
  ## File loop 
  ---

  **Tool Name:** File loop

This is a Solaris OBJ context tool for preparing USD file variations. It takes all the files inside a folder and places them at the center of the world. You can align all the meshes for a better preview, providing a perfect input for the next tool: BuildUsd.
  
  <image src="WIkiHoudini/fileLoop.jpg" width= 500>
  
  ## BuildUSD
  ---
  **Tool Name:** Build USD
  
  this is a solaris Stage context tool, it take all the mesh inside a input, set all the variation of material and geo, create an asset gallery with vignet, and save in the folder of your choise the usd geo/variation/material and asset
  
   <image src="WIkiHoudini/buildUsd.jpg" width= 500>

     
## usd converter
---

**Tool Name:** USD Converter

**Description:**
The USD Converter is a powerful and intuitive tool designed to simplify the conversion of 3D files into the USD (Universal Scene Description) format. By simply inputting the directory path containing your 3D files, this tool automates the conversion process, assigning all geometries, materials, and textures into a single consolidated USD file. Once the conversion is complete, you can save this USD file and easily add it to your asset library, streamlining the management and integration of your 3D resources into various projects.

**Features:**
- **Transformations:** Apply transformations such as global scaling, rotation, and alignment to your 3D assets.
- **Variation Management:** Handle naming variations of your assets seamlessly.
- **Texture Prefix:** Specify texture prefixes through a detailed form.
- **Automatic Conversion:** Automatically transform all 3D files in a directory into a single USD file.
- **Intelligent Assignment:** Manage geometries, materials, and textures consistently and accurately.
- **Easy Saving:** Save the generated USD file for future use.
- **Asset Management:** Integrate the USD file into your asset library for optimized organization and accessibility.

**Usage:**
1. Enter the directory path containing your 3D files.
2. Let the tool automatically assign all geometries, materials, and textures.
3. Manage naming variations and apply transformations such as rotation, global scaling, and alignment.
4. Specify texture prefixes using the detailed form.
5. Save the generated USD file.
6. Add the USD file to your asset library for future use.

This tool is ideal for 3D artists, game developers, animators, and anyone working with 3D files, significantly simplifying the workflow and enhancing efficiency.


# HDA LookDev Tool 

This Houdini Digital Asset (HDA) tool is designed to streamline the look development process by automatically adding essential elements to your scene.

## Features
- **Color Checker**: Helps in calibrating colors and maintaining consistency across renders.
- **Reference Spheres**:
  - **Metallic** sphere for reflective material reference.
  - **Matte** sphere for diffuse material reference.
- **Ground Plane with HDRI Projection**: Simulates realistic lighting environments using HDRI maps.
- **Lighting**: Adds a light source to complement the HDRI and provide flexible control over the scene's lighting.
- **Camera Constraints**: Option to lock reference elements to the camera, ensuring a consistent view for shading and lighting tests.

<image src="WIkiHoudini/lookdev_tool.png" width= 500>
