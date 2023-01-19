# Solving a 3D maze with throwing a ball by an evolutionary algorithm

The evolutionary algorithms (EAs) are designed with an idea to mimic how organisms evolve over
time in nature. EA starts with the initial population. In every iteration, the new generation improves
by using crossover and mutation to explore the results space and then choosing the fittest individuals
to mimic natural selection.
EA applications are used for exploring large search spaces. This helps to reduce the computation
time and helps to find good enough solutions.
We were fascinated that an algorithm, that mimics how things work in nature, can help solving many
real-life problems. So we wanted to try out and get a better understanding of how an evolutionary
algorithm works.

## Problem
We tried to solve a problem where a ball is thrown inside a three-dimensional room, in conditions
where there is neither gravity nor friction and the materials are perfectly elastic. The goal is to throw
a ball in a direction so, that it reaches (as close as possible) to the endpoint somewhere in the room.
The closer the ball reaches the destination the better the result. There are some obstacles on its way,
which makes it harder to reach the endpoint. The ball can bounce from the room walls and obstacles.

## Objective
Our main goal is to test out if we can use an evolutionary algorithm to solve this ball-throwing problem.
