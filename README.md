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

### How Do I Approach Designing Software?

**New Design Skills Acquired**

Working on this project has helped me refine my skills in modular software design, focusing on structuring code in reusable and maintainable ways. I gained experience in scene hierarchy design, effectively managing multiple objects and their relationships in a structured way.

**Design Process Followed**

I approached the project with an iterative design process, beginning with conceptual sketches of the scene layout, followed by incremental development of models, textures, and lighting setups. Each milestone involved testing and refining individual components to ensure they worked cohesively.

**Future Applications**

The structured design approach used in this project can be applied in game development, simulation software, and interactive 3D applications. Using modular components and iterative refinement ensures scalability and adaptability in future projects.

### How Do I Approach Developing Programs?

**Development Strategies Used**

One of the key strategies I implemented was incremental testing, where each new component was tested individually before being integrated into the scene. Additionally, I focused on code optimization techniques, such as reducing redundant calculations in shader operations and efficiently managing memory allocation for 3D models.

**The Role of Iteration**

Iteration was essential in achieving a polished final product. I often had to refine lighting configurations, texture scaling, and model positioning to create a visually cohesive scene. Through multiple iterations, I was able to improve the realism and interactivity of the environment.

**Evolution of Development Approach**

Over the course of the project milestones, I transitioned from a trial-and-error approach to a more structured debugging process, utilizing OpenGL debugging tools and performance profiling to identify bottlenecks. This evolution allowed me to write more efficient and scalable code.

### How Can Computer Science Help Me in Reaching My Goals?

**Educational Pathway**

This project introduced me to computational graphics principles, which will be invaluable in fields like computer vision, AI-driven visualizations, and augmented reality. Understanding shader programming, matrix transformations, and lighting models has expanded my technical skill set for future coursework.

**Professional Pathway**

The skills gained in 3D graphics, scene rendering, and physics simulation are directly applicable to careers in game development, real-time simulation, and AR/VR technologies. This experience has strengthened my ability to create optimized, visually appealing, and interactive 3D environments, which are critical skills in industries such as gaming, simulation, and architectural visualization.

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
  `git clone https://github.com/mubeenkh4u/CS330-3D-Graphics-Project.git
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
