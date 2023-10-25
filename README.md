# 3D Skybox

This is a simple JavaScript code for creating a 3D skybox using the Three.js library. A skybox is a textured cube that surrounds a 3D scene, providing the illusion of a distant background. In this example, a cocoa-themed skybox is created and rendered within a web application.

## Description

This code initializes a 3D scene with a cocoa-themed skybox and allows you to view and navigate around it. The skybox is made of a cube with cocoa-themed textures on each of its faces. You can control the camera's position and rotation using the mouse for a 360-degree view of the skybox.

## How to Use

To use this code in your project, follow these steps:

1. Ensure you have the Three.js library included in your project.

2. Create an HTML file and include the Three.js library.

3. Add this JavaScript code to your HTML file.

4. Make sure to have the cocoa-themed texture images (cocoa_ft.jpg, cocoa_bk.jpg, cocoa_up.jpg, cocoa_dn.jpg, cocoa_rt.jpg, cocoa_lf.jpg) in the same directory as your HTML file.

5. Initialize your project by calling the `init()` function.

## Code Explanation

- The `init()` function initializes the 3D scene, camera, and renderer. It sets up the camera's position, creates a renderer, and adds an orbit control for camera movement.

- Six textures (front, back, up, down, right, left) are loaded and used to create the skybox's materials.

- A cube geometry is created for the skybox with a size of 10,000 units on each side.

- The skybox is constructed from the cube geometry and the materials and added to the scene.

- The `animate()` function repeatedly renders the scene, creating an animation loop.

## Sample Usage

Here is a sample code snippet to get you started:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>3D Skybox Example</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
  </head>
  <body>
    <script src="your-script.js"></script>
  </body>
</html>
```

Replace `"your-script.js"` with the filename containing the provided JavaScript code.

Have fun exploring your 3D cocoa-themed skybox!