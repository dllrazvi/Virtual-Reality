# Virtual Reality – Final Project and Lab Work

## Overview

This repository contains both the laboratory exercises and the final project developed for the Virtual Reality course at UBB. The course combined theoretical and practical aspects of 3D geometry, graphics rendering, and immersive game design using Unity. The focus was on implementing a custom ray tracer and creating a thematic interactive environment based on a personal psychological theme.

---

## Laboratory Work – Custom Raytracer

The lab section includes a complete ray tracing engine built from scratch in C#, covering:

- **Custom vector and geometry math**: Defined 3D vector operations, planes, spheres, ellipsoids, intersections, and more (`Vector.cs`, `Geometry.cs`, `Ellipsoid.cs`, etc.).
- **Ray-object intersection logic**: Implemented intersection detection between rays and scene objects, computing hit points and normals.
- **Light and materials**: Simulated ambient, diffuse, and specular reflections using Phong shading (`Material.cs`, `Light.cs`).
- **Camera and rendering**: Built a full camera system with image projection and pixel coloring logic (`Camera.cs`, `Image.cs`, `RayTracer.cs`).
- **Volume rendering**: Used CT scan data from a `.raw` file (`walnut.raw`, `RawCTMask.cs`) to experiment with voxel visualization.
- **Output generation**: Final image exported as bitmap using a custom format.

The raytracer provides a deep understanding of how 3D scenes are constructed and rendered at the pixel level.

---

## Final Project – Unity VR Experience: "The Fear Maze"

For understanding the project easier, you might check the screenshots section.

### Concept

The final project is an interactive 3D VR-like experience developed in Unity, where the main theme revolves around **facing personal fears**. The player must navigate through a symbolic maze and complete challenges that metaphorically represent different fears.

### Mechanics & Elements

- **Lava Room Challenge**: Walk on narrow wooden paths above lava to symbolize fear of failure or danger.
- **Narrow Stairs & Bridges**: Balance across moving stairs and rope bridges, targeting acrophobia (fear of heights).
- **City Navigation**: Move across rooftops and urban obstacles to depict anxiety from overwhelming environments.
- **Labyrinth**: A symbolic maze representing confusion, indecision, or being lost.
- **Sphere Collection**: Collect golden spheres to progress — a metaphor for gaining courage through confronting fears.

### Features

- Developed using **Unity 2020.3 LTS**
- Custom terrain, materials, and lighting
- Animated objects and environmental feedback
- Structured in modular scenes to represent each challenge
- Final scene merges all prior areas into a cohesive city-like setting

---

## Project Structure

- `Raytracer/` – Contains all source files related to the custom rendering engine (labs)
- `UnityProject/` – Contains the Unity assets, scripts, scenes, and prefabs for the final fear-based VR maze

---

## Technologies Used

- Unity (C#)
- .NET Core (C#) for raytracer
- Shader-based rendering techniques
- Custom mathematical modeling of 3D objects


