[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23095094&assignment_repo_type=AssignmentRepo)
# GAMR1530 Coursework 2026
You are to build a ray tracer in JavaScript which uses the Phong Lighting model.
This repo will be your submission.
# GAMR1530 – JavaScript Ray Tracer

This project is a simple ray tracer built for the GAMR1530 Maths and Computer Systems module.  
It renders a 3D scene of spheres using ray–sphere intersection, a basic camera model,  
Phong lighting (ambient, diffuse, specular), and simple shadow casting.

## How to Run
Open `index.html` in any modern browser.  
The scene renders automatically on the HTML canvas.

## Features
- Ray generation from a virtual camera (Lecture 5.2)
- Ray–sphere intersection using the quadratic formula
- Full Phong lighting: ambient, diffuse, specular
- Directional light with shadow rays
- Gradient sky background
- Multiple spheres including a ground plane
- Bird’s‑eye camera angle for clearer scene presentation

## Shadows
A secondary ray is cast from the hit point toward the light.  
If it intersects another sphere, the point is in shadow and only ambient light is applied.

## Scene
- Red sphere (centre)
- Blue sphere (above)
- Large green ground sphere
- Light angled to cast shadows slightly to the left

## Enhancements
- Tuned lighting for clearer shading and shadow visibility

