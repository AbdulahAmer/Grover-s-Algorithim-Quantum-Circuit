# Grover-s-Algorithim-Quantum-Circuit
A basic example for a Grover's search for N=4 state, with '01' (in big endian) as the target state.

We make use of Qiskit to implement this Circuit. I got to learn something new working on this, using a general multicontrolled gate we can create any "black box" function we 
may need to 'find' a target state. The black box has a control state of '01', note in little endian which is the encoding Qiskit uses, this is '10'. This control state is in fact the target state. 

I hope to talk more and expand upon implementations of Grover's search and take a look at how tweaks of this circuit can lead to perfmormance speed ups. 
As well we cans tart to ask questions like, " what happends when I look for a state in a larger system?" we should be able to see the square root of N states speed up that comes up in the theory. 

For any questions or anything realted to Quantum Computing please reach out! 
