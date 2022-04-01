# Assignment 1 of Fundamentals of Computer Graphics: Display of 3D Model

<p align="center">
  <img src="https://github.com/kevinpruvost/OpenImages/blob/miscellaneous/images/1200px-Tsinghua_University_Logo.svg.png" width=250/><br/><br/>
</p>

## Introduction

For this assignment, the main theme was `Display of 3D Model`.

The objectives here were:

- 1) Loading a 3D mesh model and display it on the screen
- 2) Four modes are supported: wireframe mode, vertex mode, face mode, face and edge mode.  Mode is switched by keyboard. Under the face mode, the color of each face is different.
- 3) Rotate and translate the model by keyboard
- 4) Change color of wireframes under wireframe mode by keyboard.

## Compilation

This project and all of my CG projects will be compiled with CMake, if you open the project directly with Visual Studio, you should be able to directly compile it.
Though, as CMake permits it, you will be easily able to compile on other platforms.

## Demonstration

### Content

For my Assignment, I got all these points covered:

- 3D Object Rendering:
    - Vertex Mode
    - Wireframe Mode
    - Face Mode
    - Wireframe/Face Mode
    - Wireframe Color Change (both on Wireframe Mode & Wireframe/Face Mode)
- Bonus:
    - Camera Movement + Rotation (can be enabled/disabled)
    - Background Collor change
    - 3D Object Movement + Rotation + Scaling
    - Auto-Rotation (can be disabled)

### How to use it

<p align="center">
  <img src="https://github.com/kevinpruvost/ComputerGraphics_Assignment1/blob/main/docs/html/recording.gif" width=900/><br/><br/>
</p>

You can launch the `Assignment1.exe`directly, if you already have Visual C++ Redistribuable.

The program was compiled in Release mode.

As it is displayed in the program, here are the controls by order of priority for the assignment:

### Controls

- Object View Mode Switch: C
- Wireframe Color Change: P
- Object Movement/Rotation:
    - Movement on X axis: ⬅️ ➡️
    - Rotation on X axis: ⬆️ ⬇️
- Camera/Cursor Lock: L
- Camera Movement:
    - Forward: W (or Z on AZERTY layout)
    - Backward: S
    - Left: A (or Q on AZERTY layout)
    - Right: D
    - Up: Space
    - Down: Left CTRL

### Additional Interactions

- You can change the background color by clicking in the square next to `Background Color`.
- As DearImgui library allows it, you can move the `Object Properties` window, I locked the `Read me !`window so that it’s less bothering.
- You can modify Position, Rotation & Scaling with sliders on the X,Y,Z axis.
- You can enable/disable automatic Auto-Rotation.

## Code Architecture

Check the Documentation (made with Doxygen) directly [here](https://kevinpruvost.github.io/ComputerGraphics_Assignment1/).
