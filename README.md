# Full-Adder

In this project, I designed a Full Adder using Cadence Virtuoso, which performs the addition of two single-bit binary numbers with a carry input. The design includes the schematic, layout, and cellview for reuse and better visualization. Below is a detailed explanation of the steps involved in the process.

--> Introduction
A Full Adder is a fundamental building block of arithmetic circuits that computes the sum of two input bits (A and B) along with a carry input (Cin). It produces two outputs: Sum and Carry Out (Cout). The Full Adder is commonly used in binary arithmetic, such as in the construction of adders and subtractors in digital processors.

The Boolean equations for a Full Adder are:

Sum = A ⊕ B ⊕ Cin
Carry Out (Cout) = (A AND B) OR (B AND Cin) OR (A AND Cin)

--> Schematic Design
The Full Adder was designed at the transistor level using basic logic gates (XOR, AND, and OR gates).

Components Used: XOR gates, AND gates, OR gates.
Logic Design: The Full Adder combines two XOR gates for the sum logic, and multiple AND-OR gates for the carry-out logic.

--> Cellview Creation
To make the design more modular and reusable, I created a cellview of the Full Adder. This can be used in larger systems, such as multi-bit adders or arithmetic logic units (ALUs).

Purpose: Cellview simplifies future integration of the Full Adder into more complex circuits.
Hierarchy: The Full Adder cellview can be used in multi-bit addition circuits and integrated into larger arithmetic systems.

--> Simulation
The Full Adder was tested using various simulations to confirm the design's correctness.

DC Analysis: Verified the output voltage levels of Sum and Cout for all input combinations (A, B, Cin).
Transient Analysis: Checked the dynamic behavior of the Full Adder when the inputs change over time, ensuring proper switching and output transitions.