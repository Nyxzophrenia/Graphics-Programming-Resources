# Graphics Programming Resources

A curated collection of open-source resources, libraries, frameworks, and educational materials for graphics programming. Whether you're a beginner or advanced developer, this repository provides organized pathways to master computer graphics.

---

## Table of Contents

- [Graphics Libraries and Frameworks](#graphics-libraries-and-frameworks)
- [Educational Resources and Tutorials](#educational-resources-and-tutorials)
- [Shader and GPU Programming](#shader-and-gpu-programming)
- [Game Engines](#game-engines)
- [Communities and Discussion](#communities-and-discussion)
- [Getting Started](#getting-started)
- [Contributing](#contributing)

---

## Graphics Libraries and Frameworks

### Core Rendering APIs

#### OpenGL

| Property | Details |
|----------|---------|
| Purpose | Cross-platform API for rendering 2D and 3D graphics |
| Best For | Established projects, educational purposes, cross-platform compatibility |
| Learning Resource | LearnOpenGL - https://learnopengl.com/ |
| Language | C/C++ |
| License | N/A (API Standard) |

#### Vulkan

| Property | Details |
|----------|---------|
| Purpose | Next-generation, high-performance graphics API with lower-level control |
| Best For | High-performance applications, advanced developers |
| Learning Resource | Vulkan Tutorial - https://vulkan-tutorial.com/ |
| Language | C/C++ |
| Repository | https://github.com/KhronosGroup/Vulkan-Samples |

### Multimedia and Graphics Libraries

#### SDL2 (Simple DirectMedia Layer)

Repository: https://github.com/libsdl-org/SDL

- Purpose: Cross-platform multimedia library handling graphics, audio, and input
- Best For: 2D graphics, game prototyping, application frameworks
- Language: C
- License: Zlib

#### SFML (Simple and Fast Multimedia Library)

Website: https://www.sfml-dev.org/

- Purpose: User-friendly multimedia library for 2D graphics and applications
- Best For: Beginners, 2D game development, quick prototyping
- Language: C++
- Documentation: Extensive and beginner-friendly

#### Raylib

Repository: https://github.com/raysan5/raylib
Website: https://www.raylib.com/

- Purpose: Simple and easy-to-use library for graphics, audio, and physics
- Best For: Learning programming, 2D/3D games, rapid development
- Language: C
- Strengths: Gentle learning curve, well-maintained, active community

#### GLFW

Repository: https://github.com/glfw/glfw

- Purpose: Cross-platform library for window creation and input handling with OpenGL/Vulkan support
- Best For: Graphics application development, game engines
- Language: C
- License: Zlib

### Advanced Rendering Frameworks

#### BGFX

Repository: https://github.com/bkaradzic/bgfx

- Purpose: Cross-platform rendering library supporting multiple backends
- Supported APIs: OpenGL, Vulkan, DirectX 9/11/12, Metal, WebGPU
- Best For: Engine development, multi-platform compatibility
- Language: C++
- License: BSD

#### Magnum

Repository: https://github.com/mosra/magnum
Website: https://magnum.graphics/

- Purpose: Modern C++11/C++14 graphics engine with modular design
- Features: Multiple rendering backends, efficient API design, plugin system
- Language: C++11/C++14
- License: MIT

#### Diligent Engine

Repository: https://github.com/DiligentGraphics/DiligentEngine

- Purpose: Modern cross-platform rendering library for graphics and game applications
- Supported APIs: Direct3D, Vulkan, OpenGL, Metal
- Language: C++
- Best For: Professional game and graphics development

#### Filament

Repository: https://github.com/google/filament

- Purpose: Physically-based real-time rendering engine by Google
- Platforms: Android, iOS, Windows, Linux, macOS, WebGL2
- Language: C++
- Best For: High-quality real-time rendering, material system

#### Three.js

Repository: https://github.com/mrdoob/three.js
Website: https://threejs.org/

- Purpose: JavaScript library for 3D graphics in web browsers
- Rendering Backend: WebGL, WebGPU
- Best For: Web-based 3D applications, data visualization
- Language: JavaScript
- Documentation: Extensive examples and tutorials

### Vision and Imaging

#### OpenCV

Repository: https://github.com/opencv/opencv
Website: https://opencv.org/

- Purpose: Computer vision library for image and video analysis
- Best For: Image processing, video analysis, AI/ML applications
- Language: C++, Python bindings
- License: Apache 2.0

#### Assimp (Asset Importer Library)

Repository: https://github.com/assimp/assimp

- Purpose: Library for importing various 3D file formats
- Supported Formats: OBJ, FBX, COLLADA, glTF, and 40+ others
- Language: C++
- Best For: Game engines, 3D graphics applications

---

## Educational Resources and Tutorials

### Written Resources

| Resource | Link | Focus | Level |
|----------|------|-------|-------|
| Scratchapixel 2.0 | https://scratchapixel.com/ | Graphics fundamentals, rendering algorithms | Intermediate |
| LearnOpenGL | https://learnopengl.com/ | Modern OpenGL from basics to advanced | Beginner to Advanced |
| The Book of Shaders | https://thebookofshaders.com/ | GLSL and shader programming introduction | Beginner |
| Real-Time Rendering | https://www.realtimerendering.com/ | Comprehensive graphics resource | Advanced |
| Computer Graphics from Scratch | https://github.com/maartenbreddels/graphics_from_scratch | Software renderer implementation | Intermediate |

### YouTube Educational Channels

#### TheCherno

Channel: https://www.youtube.com/user/TheChernoProject

- Focus: C++ programming, OpenGL, graphics engine development
- Best For: Practical implementation and design patterns
- Content: Series on game engine, graphics, and performance optimization

#### Brackeys

Channel: https://www.youtube.com/@Brackeys

- Focus: Game development with emphasis on graphics
- Educational Value: Step-by-step tutorials for beginners

### Community Curated Lists

#### Awesome Graphics

Repository: https://github.com/maciejczyzewski/awesome-graphics

- Comprehensive curated list of graphics resources
- Community-maintained and regularly updated
- Covers frameworks, algorithms, books, and more

#### Awesome Graphics Libraries

Repository: https://github.com/jslee02/awesome-graphics-libraries

- Organized collection of graphics libraries
- Categorized by use case and functionality
- Links to documentation and repositories

---

## Shader and GPU Programming

### Interactive Shader Editors

#### Shadertoy

Website: https://www.shadertoy.com/

- Purpose: Experiment and share GLSL fragment shaders
- Community: Active with thousands of examples
- Best For: Learning shader programming, visualization experiments
- No account required for viewing

#### GLSL Sandbox

Website: http://glslsandbox.com/

- Purpose: Live-coding environment for GLSL fragment shaders
- Best For: Real-time feedback on shader code
- Collaborative: Share and explore community shaders

### Shader Learning Resources

#### The Book of Shaders

Website: https://thebookofshaders.com/

- Gentle introduction to GLSL
- Interactive examples and exercises
- Available in multiple languages

#### Inigo Quilez Articles

Website: https://www.iquilezles.org/

- Advanced shader techniques
- Mathematical foundations for graphics
- Production-ready code examples

---

## Game Engines

#### Godot Engine

Repository: https://github.com/godotengine/godot
Website: https://godotengine.org/

- Purpose: Open-source game engine with advanced 2D and 3D graphics
- Languages: GDScript, C#, C++
- Graphics Capabilities: Modern rendering with Vulkan and OpenGL backends
- License: MIT
- Best For: Game development with professional graphics
- Cross-Platform: Supports 10+ platforms

#### OGRE 3D

Repository: https://github.com/OGRECave/ogre

- Purpose: Object-Oriented Graphics Rendering Engine
- Supported APIs: OpenGL, Vulkan, Direct3D
- Language: C++
- Best For: Advanced 3D graphics, engine development

#### OpenSceneGraph

Repository: https://github.com/openscenegraph/OpenSceneGraph

- Purpose: Open-source 3D graphics toolkit
- Best For: Scientific visualization, virtual reality, large-scale applications
- Language: C++
- License: OpenSceneGraph Public License

---

## Communities and Discussion

### Online Communities

| Platform | Link | Focus |
|----------|------|-------|
| Graphics Programming Subreddit | https://www.reddit.com/r/graphicsprogramming/ | General graphics programming discussions |
| Stack Overflow (graphics-programming tag) | https://stackoverflow.com/questions/tagged/graphics-programming | Troubleshooting and Q&A |
| Dev.to Graphics Tag | https://dev.to/t/graphics | Articles and tutorials |
| GameDev Stack Exchange | https://gamedev.stackexchange.com/ | Game development and graphics questions |
| Computer Graphics Stack Exchange | https://computergraphics.stackexchange.com/ | Theoretical and practical graphics topics |

### Discord Communities

- Graphics Programming Discord: Active community for discussing modern graphics APIs
- Gamedev Communities: Dedicated graphics channels in major game development servers
- Shader Art Community: Channels focused on shader development and visual effects

### Official Project Communities

- Godot Community: https://discord.gg/godotengine
- Three.js Discourse: https://discourse.threejs.org/
- Khronos Vulkan Community: https://www.khronos.org/vulkan/

---

## Getting Started

### Beginner Learning Path

### Beginner Learning Path

### Fundamentals: Learn linear algebra, vectors, matrices

2D Graphics: Start with Raylib or SFML
- Create simple 2D applications
- Understand coordinate systems

Shader Basics: Study The Book of Shaders and Shadertoy
- Learn GLSL
- Practice fragment shaders

3D Graphics: Move to OpenGL with LearnOpenGL
- Understand 3D rendering pipeline
- Work with transformations and projections

Advanced Topics: Explore specialized areas
- Physics-based rendering (Filament)
- Real-time ray tracing
- Advanced shader techniques

Next-Gen APIs: Study Vulkan for high-performance graphics
- Low-level GPU programming
- Performance optimization

### Prerequisites

- Basic Programming: C/C++ or JavaScript proficiency
- Mathematics: Linear algebra and trigonometry (learned as needed)
- Patience: Graphics programming requires persistence through the learning curve

### Setting Up Your First Project

#### Using Raylib

```bash
git clone https://github.com/raysan5/raylib.git
cd raylib
mkdir build && cd build
cmake ..
make
```

#### Using SFML on Ubuntu/Debian

```bash
sudo apt-get install libsfml-dev
```

#### Using SFML on macOS

```bash
brew install sfml
```

#### Using GLFW and OpenGL

```bash
git clone https://github.com/glfw/glfw.git
cd glfw
mkdir build && cd build
cmake ..
make
```

## Resource Comparison Guide

### Library Selection by Use Case

| Use Case | Recommended Library | Reasoning |
|----------|-------------------|-----------|
| Learning 2D Graphics | Raylib, SFML | Beginner-friendly, well-documented, quick wins |
| Web 3D Graphics | Three.js | Browser-native, large community, WebGL/WebGPU support |
| Professional Game Engine | Godot | Full-featured, production-ready, extensive tools |
| High-Performance Graphics | Vulkan, BGFX | Low-level control, optimal performance, modern API |
| Cross-Platform Rendering | BGFX, OpenGL | Broad API support, established standard |
| Real-Time Rendering | Filament | Physically-based rendering, modern architecture |
| Image Processing | OpenCV | De facto standard, comprehensive functionality |
| Web Development | Three.js, Babylon.js | Browser compatibility, extensive documentation |
| Engine Development | BGFX, Magnum | Low-level control, modular design, flexibility |

### API Comparison

| API | Level | Performance | Learning Curve | Industry Use |
|-----|-------|-------------|-----------------|--------------|
| OpenGL | Mid-level | Good | Moderate | Established, widespread |
| Vulkan | Low-level | Excellent | Steep | Modern, high-performance |
| DirectX 12 | Low-level | Excellent | Steep | Windows-focused, AAA games |
| Metal | Low-level | Excellent | Steep | Apple platforms |
| WebGL | High-level | Moderate | Low | Web browsers |
| WebGPU | Mid-level | Very Good | Low | Future web standard |
