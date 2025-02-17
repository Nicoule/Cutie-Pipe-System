# Cutie-Pipe-System
We have a pipe system represented by a 2D rectangular grid of cells. There are three different types of objects located in cells in the grid, with each cell having either 0 objects or 1 object:

Source: There is 1 source in the system. It is represented by the asterisk character '*'.

Sinks: There are an arbitrary number of sinks in the system. They are each represented by a different uppercase letter ('A', 'B', 'C', etc.).

Pipes: There are 10 different shapes of pipes, represented by the following characters: '═', '║', '╔', '╗', '╚', '╝', '╠', '╣', '╦', '╩'.

Note that each pipe has openings on 2 or 3 sides of its cell.

Two adjacent cells are connected if both have a pipe opening at their shared edge.

For example, the two cells '╩ ╦' are connected to each other through their shared edge. The two cells '╩ ╔' are not connected to each other through their shared edge, but they could possibly still be connected via a path through other cells around them.

Treat the source and sinks as having pipe openings at all of their edges. For example, the two cells 'A ╦' are connected through their shared edge, but the two cells 'B ╔' are not directly connected through their shared edge.

A sink may be connected to the source through another sink. For example, in the simple pipe system '* ╦ X Y ═ Z', all three sinks are connected to the source.

Your objective is to write a function that determines which sinks are connected to the source in a given pipe system.


<img width="108" alt="image" src="https://github.com/Nicoule/Cutie-Pipe-System/assets/130537195/6517458d-2af8-4b62-b351-bcdce2e27605">


Example: This pipe System connects the Sourse with two Sinks "A" and "B". The input used is as follows.


<img width="60" alt="image" src="https://github.com/Nicoule/Cutie-Pipe-System/assets/130537195/26e8568e-555c-47e4-ad3b-003facd98b3b">


Now, please download the pipe_input.txt and test your code. It's a more complicated pipe system. The output should be like ['A', 'B', 'C']. Wish you luck!
