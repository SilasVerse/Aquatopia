🐟 Aquatopia: An Animated Underwater Scene
===========================================
📘 Abstract
============
Aquatopia is an interactive OpenGL-based animation that simulates a lively underwater scene featuring multiple fish, plants, bubbles, and a swimming shark.
This project demonstrates the use of 2D computer graphics, animation, and interactive user input using C++ and OpenGL/GLUT.

The animation showcases:

- Realistic movement of fish following sine-wave patterns

- A controllable green fish that moves toward the mouse click

- Dynamic bubble generation and rising motion

- Flowing aquatic plants and a moving shark

- A beautiful background gradient mimicking underwater lighting

🧠 Project Overview
====================
The program consists of two main stages:

1. Intro Screen – Displays the project title, member names, and supervisor information.

   - The animation starts when the user presses any key.

2. Main Animation – Displays a complete underwater ecosystem.

   - Fish move in natural patterns.

   - Clicking the mouse moves the user-controlled fish toward that point.

   - The shark glides across the screen, and bubbles rise dynamically.

💻 Technologies Used
=====================

Language: C++

Libraries:

- OpenGL (GL)

- GLUT (OpenGL Utility Toolkit)

- GLU (OpenGL Utility Library)

Platform: Windows


🧩 Features
============

✅ Animated Sea Life

- Multiple species of fish with different colors, speeds, and swimming patterns

- Sine-wave motion for natural swimming

✅ Interactive Movement

- Click anywhere in the window to move the fish in that direction

✅ Environmental Details

- Rising bubbles and moving sea plants (Coontail plants)

- Smooth background gradient resembling ocean depth

✅ Introductory Screen

- Displays team details and starts animation on any key press

🧰 Prerequisites
================
- C++ compiler (e.g., MinGW, Visual Studio, or Code::Blocks)

- OpenGL and GLUT development libraries: glut.h, gl.h, glu.h

🖱️ Controls
============
| Action                 | Description                                                   |
| ---------------------- | ------------------------------------------------------------- |
| **Any Key**            | Starts the animation                                          |
| **Left Mouse Click**   | Moves the controllable green fish toward the clicked location |
| **Esc / Close Window** | Exit the program                                              |

🎬 Demonstrated Concepts
========================
- OpenGL transformations: glTranslatef, glScalef, glRotatef

- 2D animation using trigonometric functions (sin and cos)

- Dynamic rendering via glutPostRedisplay() and glutTimerFunc()

- Hierarchical modeling and modular function-based drawing

- Event-driven programming (keyboard and mouse input)

✍️ Note from the Authors
========================
This is our first project using OpenGL, created through continuous learning from various tutorials and online resources.
While some visual elements (such as fish shapes) may resemble other OpenGL projects found online, the internal logic, animation flow, and implementation details in this project were developed independently through our own understanding and experimentation.

Unlike many similar projects that use a free coordinate range, this implementation operates strictly within the standard OpenGL range of -1 to 1 for both the X and Y axes.
This constraint helped maintain a consistent coordinate system and made it easier to understand fundamental OpenGL transformations such as translation, rotation, and scaling.

The goal of this project is purely educational, focusing on learning and demonstrating core computer graphics concepts including:

- Coordinate system management

- Object modeling

- Animation and timing

- User interactivity

HL & NSH
========
