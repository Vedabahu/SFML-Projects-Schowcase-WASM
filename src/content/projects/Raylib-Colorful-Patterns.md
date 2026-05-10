---
name: "Vedabahu's Random Raylib Graphics - 1"
description: "Experimental Raylib graphics rendered natively in WebAssembly."
date: 2026-05-26

cover: "./images/raylib-main-showcase.png"
coverAlt: "Colorful circular patterns rendered with Raylib and Shaders (GLSL)"

logo:
  image: "./images/raylib-main-showcase.png"
  fallback:
    text: "V"
    bgColor: "bg-orange-500"

caseStudy:
  challenge: "To learn how Vertex Shaders and Fragment Shaders work and to produce interesting things with them."

  solution: "Built a browser-based rendering experiment using Raylib, Vertex Shaders, Emscripten, and WebAssembly."

  results:
    - "Native Raylib rendering in the browser"
    - "WebAssembly graphics pipeline"
    - "Real-time illusionary fractal like rendering"
    - "Cross-platform browser deployment"

  links:
    - text: "Live Demo"
      url: "/projs/raylib-patterns"

---

## Project Overview

Vedabahu's Random Raylub Graphics - 1 is an experimental rendering showcase built using Raylib and compiled to WebAssembly using Emscripten.

The project focuses on rendering colorful fractal like things directly in the browser through a native C++ rendering pipeline.

## Technical Stack

- Raylib
- GPU Shaders (GLSL)
- WebAssembly (WASM)
- Emscripten
- CMake

## Purpose

This project was created to explore advanced C++ workflows, browser-based native rendering, and WebAssembly deployment using Raylib. Also, I wanted to learn, in detail about GPU shaders for fun.

## Inspiration

The inspiration was from [ShaderToy](https://www.shadertoy.com/view/mtyGWy) and the user [Kishimisu](https://www.shadertoy.com/view/mtyGWy). He made a very nice pattern which I ported over to Raylib with slight modifications in color and rendering.
