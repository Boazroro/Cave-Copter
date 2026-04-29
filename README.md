# Cave Copter 🚁

## Overview
Cave Copter is a 2D arcade-style game built entirely from scratch in the **Jack programming language**. 
It was developed as a final project for the Digital Systems course, designed to run on a simulated 16-bit computer architecture (Hack platform / Nand to Tetris).

Unlike modern game development, this project was built without the use of high-level game engines, external graphics libraries, or built-in physics engines. Every pixel, movement, and collision was explicitly programmed to work within strict hardware and memory constraints.

## The Engineering Challenge
Developing in Jack for a 16-bit virtual machine required a deep understanding of low-level computer science principles:
* **Object-Oriented Programming under constraints:** Implementing complex OOP structures in a minimalist, primitive language.
* **Custom Game Loop:** Managing the game state, frame updates, and user inputs manually.
* **Physics & Collision Detection:** Writing raw algorithms to handle gravity, acceleration, and hitboxes without external dependencies.
* **Direct Memory & Screen Management:** Interacting directly with the simulated memory map to render graphics to the screen efficiently.

## Technologies Used
* **Language:** Jack (A simple, Java-like object-oriented language)
* **Architecture:** 16-bit Hack Computer platform
* **Concepts:** OOP, Low-level Memory Management, Algorithmic Game Logic

## How to Run
*(Note: To run this project, you need the VM Emulator from the Nand to Tetris software suite.)*
1. Open the VM Emulator.
2. Load the compiled `.vm` files from this repository.
3. Set the animation speed to 'Fast' and run the program.

## Credits
Developed collaboratively by Boaz Roro as part of the Digital Systems course (December 2025).
