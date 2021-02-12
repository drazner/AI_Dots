# AI_Dots

This project serves as a demonstration to learn about the genetic algorithm with regards to artificial intelligence. 

## Summary

I created a model of a population of dots that must reach a goal point with an obstacle in the way. The first 
generation of dots are initialized with completely randomized movement. A scoring algorithm is then used to 
detect how fit each dot was based on how close they came to the goal and how many steps it took them. Dots with
higher fitness scores are more likely to reproduce. Fitness probability is then used in conjunction with random
mutations to create a new generation of dots that learn from their predecessors. 

## Examples

In the following examples, note that the black dots all start at the bottom center of the screen and their goal is to 
get to the red dot at the top of the screen. They die if they hit the borders of the screen or the blue obstacle in 
the middle. The genesis population begins with erratic, meaningless movement.


### Generation 1 
![dots_gen1](https://user-images.githubusercontent.com/25868092/107724354-4ce0b600-6ca9-11eb-9723-4e737b6d4b4f.png)

Notice how nearly all of the dots from the first generation die on the borders and blue obstacle because their movement
is random and unintelligible. A few luckky dots can be seen approaching the goal state around the end of this generation's 
lifecycle. One of them is likely to be chosen as the champion; the role model upon which the next generation will be based.

### Generation 5
![dots_gen10](https://user-images.githubusercontent.com/25868092/107724773-46067300-6caa-11eb-8fe2-496afe745e50.png)

Notice how just five generations in, most of the dots have already learned to approach the goal state. The power of the 
genetic algorithm is fascinating. The dots were capable of learning so quickly from their intiial state, comprised entirely
of random decision making. The champion of the previous generation is colored in green.

