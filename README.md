# build-computer
## HDL Language
HDL stands for Hardware Description Language. It's used to model the structure, design, and operation of digital logic circuits, allowing for the simulation and synthesis of digital systems before they are physically built.
## Using NAND gates
Using NAND gates to create various logic circuits is rooted in a fundamental concept in digital electronics known as functional completeness. NAND gates are functionally complete, which means that any boolean function or logic circuit can be constructed using only NAND gates.

![image](https://github.com/marouene-djabbar/build-computer/assets/165311266/564334e6-f763-4ac4-9c98-1006f0d0fa15)


![image](https://github.com/marouene-djabbar/build-computer/assets/165311266/85e2341c-2234-4b3e-a79b-92c74f11c7aa)

In tearms of transistors:

![image](https://github.com/marouene-djabbar/build-computer/assets/165311266/6f52fce6-8b1b-41f0-aff4-012dea48cfc6)

When both inputs A and B are ‘on’, the current flows through both transistors (Q1 and Q2), grounding the output node, making the output 0.
When either A or B is 'off', the corresponding transistor is off, which means it does not conduct, and the current cannot flow completely to ground. Instead, the pull-up resistor (R) pulls the output node up to a high voltage, making the output 1.

https://www.geeksforgeeks.org/what-is-nand-gate/

![image](https://github.com/marouene-djabbar/build-computer/assets/165311266/fd75691f-d697-4462-977c-d15946e13d0d)

https://en.wikipedia.org/wiki/NAND_gate

## Examples of NAND implimentatons:

### Implementation of AND Gate from NAND Gate

![image](https://github.com/marouene-djabbar/build-computer/assets/165311266/24a5c105-d0f1-4f0d-af8a-934d02353a3c)

https://www.tutorialspoint.com/implementation-of-and-gate-from-nand-gate

### Implementation of NOT Gate using NAND Gate

![image](https://github.com/marouene-djabbar/build-computer/assets/165311266/32c3bcaa-e743-41e8-a13d-f75a670aa866)

https://www.tutorialspoint.com/implementation-of-not-gate-using-nand-gate

### Implementation of XOR Gate from NAND Gate

![image](https://github.com/marouene-djabbar/build-computer/assets/165311266/9be158c0-8aae-40cc-a1fb-3c3f13a1e981)

https://www.tutorialspoint.com/implementation-of-xor-gate-from-nand-gate

### Implementation of OR Gate from NAND Gate


![image](https://github.com/marouene-djabbar/build-computer/assets/165311266/c98fb604-53e6-44b0-8e29-d492adbc81c5)

https://www.tutorialspoint.com/implementation-of-or-gate-from-nand-gate









