---
name: "Vedabahu’s Raylib Apollonian Gasket"
description: "An experimental recursive geometry visualizer built with Raylib and compiled natively to WebAssembly using Emscripten."
date: 2026-05-11

cover: "./images/apollonian-gasket.png"
coverAlt: "Recursive Apollonian gasket rendered with Raylib in WebAssembly"

logo:
  image: "./images/apollonian-gasket.png"
  fallback:
    text: "A"
    bgColor: "bg-neutral-800"

caseStudy:
  challenge: "Explore advanced C++ rendering workflows, recursive geometry generation, and browser-native graphics using WebAssembly."

  solution: "Built an interactive Apollonian gasket visualizer using Raylib, recursive Descartes circle theorem generation, modern C++20 features, and Emscripten-based WebAssembly deployment."

  results:
    - "Recursive fractal circle generation"
    - "Interactive real-time parameter manipulation"
    - "Browser-native C++ graphics rendering"
    - "Responsive WebAssembly deployment"
    - "Advanced geometry computation using complex numbers"
    - "Modern C++20 ranges and algorithm usage"

  links:
    - text: "Live Demo"
      url: "/projs/raylib-apollonian-gasket"

---

## Project Overview

Vedabahu’s Raylib Apollonian Gasket is an experimental mathematical visualization project focused on recursive fractal geometry generation using modern C++ and Raylib.

The project generates Apollonian gasket structures by recursively computing tangent circles using Descartes’ theorem and complex-number-based geometric calculations. The visualization runs natively inside the browser through WebAssembly compiled using Emscripten.

The project also serves as a deeper exploration into advanced graphics programming workflows, browser-native C++ rendering, and interactive procedural geometry systems.

## Features

- Recursive Apollonian gasket generation
- Real-time fractal regeneration
- Adjustable recursion depth
- Interactive minimum and maximum seed radius controls
- Deterministic random seed generation
- Browser-native rendering through WebAssembly
- Responsive rendering pipeline for desktop and mobile browsers
- MSAA-enabled rendering pipeline
- Immediate mode debug-style UI using raygui

## Technical Stack

- Raylib
- raygui
- C++20
- WebAssembly (WASM)
- Emscripten
- CMake

## Technical Details

The project heavily uses recursive geometry generation and mathematical circle packing techniques.

Circle generation is implemented using:

- Descartes circle theorem
- Complex-number-based center calculations
- Recursive tangent circle generation
- Floating-point tolerance validation
- Tangency validation checks
- Duplicate-circle rejection systems

The rendering and interaction pipeline was designed to remain lightweight while supporting live regeneration of the fractal structure whenever parameters are modified.

The project also explores modern C++ techniques including:

- `std::ranges`
- structured bindings
- constexpr validation helpers
- templated random generation utilities
- recursive procedural generation systems
- complex-number geometry computation

## Purpose

This project was created as part of a broader effort to learn advanced C++, mathematical visualization techniques, procedural graphics generation, and browser-native rendering using WebAssembly.

The goal was not only to generate visually interesting fractals, but also to understand how native rendering pipelines, recursive algorithms, and modern C++ abstractions behave when deployed directly inside the browser.
