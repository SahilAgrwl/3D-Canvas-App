FEATURES OF APP ;
1. CREATE DIFFERENT TYPES OF SHAPES IN 3D.
2. VIEW SHAPE AT DIFFERENT ANGLES BY ROTATING IT WITH MOUSE.
3. ZOOM IN AND OUT VIEW OF SHAPE.
4. SAVE THE SHAPE TO LOCAL STORAGE.
5. THERE IS ALSO PLACEHOLDER API WHICH SHOWS DATA ON CHOOSING DIFFERENT SHAPES.

TECHNOLOGIES USED ; 
1. HTML
2. CSS
3. REACT.JS
4. THREE.JS
   
SCREENSHOTS OF APP;
![Screenshot (154)](https://github.com/SahilAgrwl/3D-Canvas-App/assets/110213349/c6f37e86-0b20-45f4-871d-45fd9790b805)
![Screenshot (155)](https://github.com/SahilAgrwl/3D-Canvas-App/assets/110213349/79831010-354f-4989-ae8a-f6d85856c0cf)
![Screenshot (156)](https://github.com/SahilAgrwl/3D-Canvas-App/assets/110213349/fc5c4981-0880-44c3-8d3b-eab8db3a1077)
![Screenshot (157)](https://github.com/SahilAgrwl/3D-Canvas-App/assets/110213349/217e7c64-129d-4f0a-993c-8c06330b6169)

Approach:

Setting Up the Environment: The first step is to set up the development environment with React, Three.js, and any other necessary libraries.

Creating the Canvas: Next, create a canvas element using Three.js to render 3D shapes on the web page.

Handling 3D Shapes: Implement functions to create various 3D shapes like cubes, spheres, cylinders, etc., using Three.js geometries and materials.

Camera Control: Use the OrbitControls library to enable rotating and zooming the camera to view the 3D shapes from different angles.

Shape Data and API Integration: Add a component to fetch data related to the selected shape from an external API and display it.

Saving Drawings: Implement a function to save the current state of the drawing to local storage.

Styling and Responsiveness: Apply CSS styles to enhance the visual appearance of the website and ensure responsiveness on different screen sizes.

Challenges:

Learning Three.js: Working with Three.js can be challenging for developers unfamiliar with 3D graphics and rendering concepts.

Integration with React: Integrating Three.js with React can sometimes lead to conflicts and performance issues. Using useRef to manage the canvas and the scene can help overcome these challenges.

Camera Controls: Setting up the camera controls to enable smooth rotation and zooming can be tricky.

Removing Shapes: Removing shapes from the scene and managing their memory disposal requires careful handling to prevent memory leaks.

External API Integration: Integrating an external API to fetch shape-related data might introduce network-related issues and error handling.

Styling and Responsiveness: Achieving a visually appealing and responsive layout requires thorough CSS skills and media queries for different screen sizes.

Performance Optimization: Rendering 3D graphics can be resource-intensive. Optimizing performance to ensure smooth interactions is important.

CODE EDITOR ;
VS CODE

DEPENDENCIES REQUIRED ;
THREE, ORBITCONTROLS

HOW TO RUN ;
NPM RUN DEV 
PRESS O





# REACT+ Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
