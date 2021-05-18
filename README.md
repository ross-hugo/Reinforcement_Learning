# Reinforcement_Learning
EECS 738 Machine Learning project 4 in exploring reinforcement learning methods

## Project Requirements
We do the treasure hunting and monster fighting for you
1. Set up a new git repository in your GitHub account
2. Think up a map-like environment with treasure, obstacles and opponents
3. Choose a programming language (Python, C/C++, Java)
4. Formulate ideas on how reinforcement learning can be used to find treasure efficiently while avoiding obstacles and opponents
5. Build one or more reinforcement policies to model situational assessments, actions and rewards programmatically
6. Document your process and results

Here I used one of the most advanced reinforcement learning models: Q Learning. 

With Q Learning, I decided to create a maze that represents a traveler trying to find the exit of a labyrithn type maze.
While it is purely in a numeric form, it still has the same underpinnings rather than some other more representative form of doing it.

## Future Work
- For the future, I would like to try to use some other types of reinforcement learning and see how they different tequniques compare to each other. 
- I would also like to try and fix the problem of cycles happening in my q learning implementation. At the moment, it seems when there are multiple positive values in a cyclic path, the algorithm will not stop acruing the positive points.
- Finally, I would like to try and apply a technique like Q Learning to something other than escaping a maze or labyrinth. 