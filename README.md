This project is a command-line-based simulation of the classic "Water Jug Problem," which involves using two jugs with different capacities to measure a specific amount of water. The program allows the user to simulate different operations on the jugs to achieve the target amount of water, either in one of the jugs.

Key Features and Functionality:

User Input:
The user is prompted to input the capacities of two jugs and the target amount of water they want to measure.

Validation:
The program checks if the target amount can be measured using the two jugs. If the target is larger than both jugs' capacities or if the target is not a multiple of the greatest common divisor (gcd) of the two jug capacities, it informs the user that the measurement is impossible.

GCD Calculation:
The program calculates the greatest common divisor (gcd) of the two jugs' capacities using the Euclidean algorithm. The target can only be measured if it's a multiple of the gcd.

Gameplay Loop:
The program enters an interactive loop where the user can input various commands to manipulate the water in the jugs:

fill1: Fills the first jug to its capacity.

fill2: Fills the second jug to its capacity.

empty1: Empties the first jug.

empty2: Empties the second jug.

pour1to2: Pours water from the first jug into the second jug until the second jug is full or the first jug is empty.

pour2to1: Pours water from the second jug into the first jug until the first jug is full or the second jug is empty.

exit: Exits the program.
