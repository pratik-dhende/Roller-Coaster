# Roller Coaster
- A roller coaster simulation using OpenGL
- The roller coaster is created with Catmull Rom spline and the track is made to extend out along the path of spline
- The camera is also made to follow along the spline with physically based movement

**Note**: The code is not disclosed as it was implemented as a part of CSCI 420 Computer Graphics course at the University of Southern California.

## Technological Stack
`C++ • OpenGL • GLSL`

## Features
- Spline
  - Used Catmull Rom splines
  - Used Recursive subdivision algorithm for splines
  - Used Sloan method for generating Spline normals
- Phong shading
  - Ambient lighting
  - Diffused lighting
  - Specular lighting
- Physically based dynamic camera movement along the roller coaster
- Phong shading to the ground with Normal maps using Tangent, Binormal, Normal space transformations
- Skybox
- Back face culling
- Anti-aliasing

## Features Demo
The application runs at 60 FPS but the below animation is shown at 15 FPS created from recorded screenshots.

[![rollerCoaster](https://github.com/user-attachments/assets/a6a073e2-c2dd-4235-967d-cc6ab46288b1)
](https://drive.google.com/file/d/15gYGRMzlxD52I-ksMdT0jsy8GMdRkLhE/view?usp=sharing)
