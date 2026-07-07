# Racing Track Rendering
**Computer Graphics – Final Project**

**Group 12**

---

# 1. Introduction

## 1.1 Motivation

The objective of this project is to develop an interactive 3D racing track using modern WebGL technologies. The application demonstrates fundamental concepts in computer graphics, including 3D modeling, animation, lighting, camera control, and real-time rendering within a web browser.

The project combines assets created in Blender with WebGL rendering through Three.js to create an interactive racing environment.

---

# 2. Project Objectives

The project aims to implement the following features:

- Load a complete racing track scene into a WebGL environment.
- Add a car model with running animations.
- Allow users to control the car speed using the keyboard.
- Implement spotlights capable of casting shadows.
- Support switching between Day and Night themes.
- Add additional environmental objects to enrich the scene.

---

# 3. 3D Modeling

## 3.1 Model Creation

The racing environment was created using Blender.

The scene includes:

- Racing track
- Car model
- Ferris wheel
- Decorative environmental objects
- Lighting setup
- Materials and textures

Several external models were customized and integrated into the final scene.

---

# 4. Resources

The project utilizes publicly available 3D assets from Sketchfab.

### Racing Track

https://sketchfab.com/3d-models/isometric-race-track-daily-render-27-257cbed7fefb43b88663fc1763dbf233

### Ferris Wheel

https://sketchfab.com/3d-models/isometric-ferris-wheel-daily-render-29-03685bda9cb843d88f550a1f7f393184

The imported models were modified by changing materials while preserving the original geometry, textures, and animations.

---

# 5. Blender Scene Creation

The complete environment was assembled inside Blender.

This process involved:

- Importing 3D assets
- Positioning scene objects
- Creating animations
- Assigning materials
- Exporting the final scene as a GLB file for WebGL rendering

---

# 6. WebGL Rendering

The exported Blender scene was loaded into a Three.js application.

The rendering pipeline includes:

- GLB model loading
- Camera setup
- Scene initialization
- Lighting configuration
- Animation updates
- Shadow rendering
- User interaction

---

# 7. Development Tools

## 7.1 Vite.js

Vite is used as the frontend build tool.

Its advantages include:

- Fast development server
- Native ES module support
- Efficient hot module replacement
- Optimized production builds using Rollup

---

## 7.2 Three.js

Three.js is the primary graphics library used in this project.

Its responsibilities include:

- WebGL rendering
- Scene management
- Camera control
- Lighting
- Shadow generation
- Animation playback
- Model loading
- Material management

---

# 8. System Architecture

The application consists of several major components.

## Scene Initialization

- Create renderer
- Create scene
- Configure camera
- Set renderer size

## Model Loading

- Load GLB files
- Extract objects
- Load animations

## Lighting

- Ambient light
- Directional light
- Spotlight
- Shadow configuration

## Environment

- Racing track
- Decorative objects
- Room/environment

## Camera

- Perspective camera
- Orbit controls

## Theme

- Day mode
- Night mode

## Animation

- Animation mixer
- Render loop
- Timing control

---

# 9. Model Loading

GLB models are imported into Three.js.

The loading process includes:

- Reading GLB files
- Adding meshes to the scene
- Applying materials
- Configuring object hierarchy

---

# 10. Animation

Animations created in Blender are imported together with the GLB model.

The animation system controls:

- Car movement
- Wheel rotation
- Environmental animations

Three.js AnimationMixer is used to play and manage these animations.

---

# 11. Lighting

The lighting system consists of:

- Ambient lighting
- Spotlights
- Shadow casting

Lighting significantly improves scene realism while supporting both Day and Night modes.

---

# 12. Keyboard Controls

The application supports interactive keyboard controls.

| Key | Function |
|------|----------|
| Right Arrow | Increase car speed |
| Left Arrow | Decrease car speed |
| Space | Stop the car |
| R | Reset speed |

---

# 13. Building Animations in Blender

Animations were created inside Blender before exporting to GLB.

The animation workflow includes:

1. Model preparation
2. Keyframe creation
3. Animation testing
4. GLB export
5. Import into Three.js

---

# 14. Day/Night Theme

The application supports two visual themes.

## Day Mode

- Bright ambient lighting
- Natural environment

## Night Mode

- Dark environment
- Strong spotlight effects
- Enhanced shadow visibility

Users can switch between these themes during runtime.

---

# 15. Demonstration

The completed application demonstrates:

- Interactive racing track
- Animated car
- Real-time rendering
- Keyboard interaction
- Dynamic lighting
- Day/Night switching
- Shadow effects

---

# 16. References

## 3D Models

Race Track

https://sketchfab.com/3d-models/isometric-race-track-daily-render-27-257cbed7fefb43b88663fc1763dbf233

Ferris Wheel

https://sketchfab.com/3d-models/isometric-ferris-wheel-daily-render-29-03685bda9cb843d88f550a1f7f393184

The project uses the original models, textures, and animations while modifying certain object materials.

---

## Textures

The USTH SVG logo was used to create a custom 3D logo model.

---

## Code Reference

Project folder structure for importing GLB models:

https://www.youtube.com/watch?v=rxTb9ys834w

---

# 17. Conclusion

This project demonstrates the implementation of an interactive WebGL racing environment using Blender and Three.js.

The final application successfully integrates:

- 3D modeling
- Animation
- Real-time rendering
- Dynamic lighting
- Shadow mapping
- User interaction
- Theme switching

The project showcases practical applications of modern computer graphics techniques for web-based 3D visualization.

---

# Thank You

**Group 12**