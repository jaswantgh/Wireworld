## Final Assignment - Wireworld Simulation
**Score Achieved: 100 %**
This repository contains the final project for my Unix and C Programming course - a visualization of the Wireworld cellular automaton simulation, implemented in C.

### Project Overview:
This task was the second and more challenging component of the final assessment. It involved writing a program to visualize a cellular automaton simulation known as Wireworld. The Wireworld simulation is a non-interactive system that operates on a 2D square grid (akin to a 2D array) where each individual element, or "cell", can exist in one of four possible states.

### Detailed Specifications:

1. **Shell Script Functionality:** The project includes a Shell script that works seamlessly with the main program.

2. **Makefile Construction:** A well-crafted makefile is included with the appropriate flags and prerequisites for a smooth build process.

3. **Code Structure:** The code is organized into multiple `.c` files for enhanced readability and efficient structure, with corresponding header files that have appropriate header guards.

4. **C89 Coding Standard Compliance:** The project strictly follows the C89 coding standards, ensured by compiling with the `-Wall -ansi -pedantic` flags.

5. **Memory Management:** The project showcases effective memory management using the `malloc/calloc` functions for dynamic allocation, resulting in a program free of memory leaks.

6. **Command Line Argument Verification:** The program verifies and validates command line arguments, handling errors such as file opening failures with appropriate error messages and program termination.

7. **File Reading:** The program successfully reads from a text file to establish the simulation parameters. It dynamically allocates the 2D array for the cell grid based on the text file's specifications.

8. **Screen Management:** The program correctly manages screen refreshes and sleep durations for each simulation cycle, concluding when the predetermined number of steps is reached.

9. **Cell Grid Display:** The cell grid display uses double space characters and proper background color to accurately represent the state of each cell.

10. **Cell Grid Update:** Cell grids are updated according to the Wireworld simulation rules, effectively demonstrating the transitions between states in each simulation cycle.

This final Wireworld simulation project was an intensive task that allowed me to demonstrate my expertise in Unix and C Programming, memory management, and adherence to strict coding standards.
