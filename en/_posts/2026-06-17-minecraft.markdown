---
layout: default
modal-id: 4
date: 2026-06-17
img: minecraft.png
alt: Minecraft project logo
project-date: 2026
client: Personal project
category: Game Development / C# Godot
github_url: https://github.com/barnabas47/minecraft
description: |
  [Minecraft Clone](https://github.com/barnabas47/minecraft) is a voxel-based 3D sandbox game built completely from scratch in Godot Engine 4 using C# and .NET 8.0. The goal of this project is to implement the core gameplay mechanics of Minecraft along with asynchronous multithreaded world loading.

  **Main features:**
  - **Asynchronous World Loading**: Heavy terrain generation, tree placement, and 3D mesh building are executed entirely on separate background threads (`Task.Run`), ensuring smooth player movement and stutter-free chunk loads (stable 60 FPS).
  - **Procedural Terrain**: Simplex noise (FastNoiseLite) based terrain with hills and depth-dependent ores (coal, iron, gold, diamond).
  - **Item Drops with Physics**: Mined blocks fall as 3D physical entities, collide with the terrain, float, and are magnetically attracted to the player when nearby.
  - **Full Inventory & Hotbar**: Interactive UI for storing, moving, and stacking blocks and tools, along with hotbar slot selection.
  - **Crafting & Smelting**:
    - *Crafting Table*: Crafting interface with recipes for tools and ingredients.
    - *Furnace*: Cooking interface with fuel consumption (coal, wood, sticks), smelting time, and progress bars.
  - **Physics & Memory Optimization**: Cylinder-shaped player collision to prevent diagonal clipping and static Material Cache to eliminate redundant disk texture loads.

  **Technologies:**
  - Game Engine: Godot Engine 4.x (Mono/C#)
  - Runtime: C# (.NET 8.0)
  - Noise Generation: FastNoiseLite
  - Rendering: Custom voxel mesh generation using SurfaceTool
  - Multithreading: Thread locks, reentrant locks, and CallDeferred scheduling

  **How to run:**
  - Open the project directory and run it from the Godot Editor, or compile and run from command line: `dotnet build`
---
