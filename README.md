# QOSF

The task I chose to do was Task #2. This was the is_rectangle function.

This task proved to be rewarding in the facet of the elegance of it's solution.

I have been exposed to qiskit before, though this project did help my further my coding skills in the domain.

The basic jist:

-We first need to define 6 circuits for the different possible configurations of the rectangle sides (AB,AC,AD,BC,BD,CD)

-We then convert the integer values of A, B, C and D to states using basis encoding

-Afterwards, we use a swap gate (2 Hadamard gates and a Fredkin gate) to see how similar the states are (it returns 1 if the values are the same, with some uncertainty)

-We then see how many 1s we got. IFF there were 2 1s returned, we say valid rectangle.
