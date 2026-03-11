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