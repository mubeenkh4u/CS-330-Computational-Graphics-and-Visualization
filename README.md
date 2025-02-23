# CS-330-Computational-Graphics-and-Visualization

## 3D Graphics Final Project

### Overview

This project is developed as part of the CS 330 - Computational Graphics and Visualization course at SNHU. The focus is on creating a structured and interactive 3D scene using OpenGL, incorporating custom geometry, realistic textures, dynamic lighting, and camera controls. The project demonstrates proficiency in computational graphics techniques, shader programming, and scene management.

### Features

* Custom 3D Shapes: Implemented HalfTorus (for cup handle) and SemiSphere (for lid elements) to create realistic scene objects.
* Scene Management: Modular architecture to load, manage, and render 3D objects efficiently.
* Texture Mapping: Applied textures to objects for enhanced realism.
* Lighting Effects: Configured multiple light sources including point lights, directional light, and a spotlight attached to the camera.
* Camera System: Interactive navigation via keyboard and mouse, with toggleable Orthographic and Perspective views.
* Modular Code Structure: Organized implementation using reusable functions and shader management.

### Controls

  * W, A, S, D: Move the camera forward, left, backward, and right.
  * Q, E: Move the camera up and down.
  * Mouse Movement: Rotate camera view.
  * Scroll Wheel: Adjust camera movement speed.
  * O / P: Toggle between Orthographic and Perspective projections.
  * ESC: Exit the application.

### File Structure

* ViewManager.h / ViewManager.cpp – Handles camera movement, input processing, and projection toggling.
* SceneManager.h / SceneManager.cpp – Manages scene rendering, textures, and lighting.
* ShapeMeshes.h / ShapeMeshes.cpp – Contains custom and predefined 3D object meshes.
* ShaderManager.cpp – Handles shader programs and uniform values.

### Installation & Setup

* Requirements
  * Visual Studio 2022
  * OpenGL 4.1+
  * GLFW for window management
  * GLM for mathematical operations
  * stb_image for texture loading

* Steps
  * Clone the repository:
  `git clone https://github.com/yourusername/CS330-3D-Graphics-Project.git
  cd CS330-3D-Graphics-Project`

* Ensure dependencies are installed.

  * Compile the project using a compatible C++ compiler.
  * Run the executable to explore the 3D scene.

* Future Enhancements
  * Animation & Interaction: Adding object animations and interactive elements.
  * Enhanced Materials: Experimenting with physically based rendering (PBR).
  * Optimizations: Implementing frustum culling and LOD techniques for performance improvements.

### Author

Mubeen Ahmed Khan
Final Year CS Student | SNHU | Data Analytics Concentration
