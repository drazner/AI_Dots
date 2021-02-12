# AI_Dots

This project serves as a demonstration to learn about the genetic algorithm with regards to artificial intelligence. 

I created a model of a population of dots that must reach a goal point with an obstacle in the way. The first 
generation of dots are initialized with completely randomized movement. A scoring algorithm is then used to 
detect how fit each dot was based on how close they came to the goal and how many steps it took them. Dots with
higher fitness scores are more likely to reproduce. Fitness probability is then used in conjunction with random
mutations to create a new generation of dots that learn from their predecessors. 
