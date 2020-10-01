Assignment 1

Authors (alphabetical order): Linard Büchler, Eric Buffle, Basil Peterhans

Exercise description:

Adapted the Cylinder.cpp to implement the intersection function. A quadratic equation system for a ray intersection on an infinite cylinder was derrived (see TheoryExercise.pdf). The possible solutions got checked if they are in front of the observer and if they lie on the finite cylinder, depending on its height.

In Plane.cpp the intersection function was implementet as well. Before the intersection was calculatet the dot product of the ray and planes norm was investigated in order to abort in case of a parralel ray to the plane (to avoid division by 0).

cylinders.tga show the result of rendered cylinders and a plane.

