# 2D_Predator_Prey_Simulator
This was a project that I made for my CS162 course (Intro to Computer Science II) at Oregon State

(This was created when I was still new to C++, so there is a lot of room to improve efficiency and readability. However it works nonetheless!)

# Overview

This assignment is based off of the Lotka-Volterra equations which describe the change in populations of predators and prey over time. 
In this case, we use "Ants" as prey and "DoodleBugs" as predators (The names were chosen by the professor, I personally would've went
with something cooler than DoodleBugs...)

The program consists with a 20x20 grid randomly populated with 100 ants and 5 doodlebugs. The simulation then follows these rules:

1. DoodleBugs will favor a move to a tile that contains an ant
2. If a DoodleBug collides with an ant, it "eats" the ant
3. If an ant goes three steps without dying, it "breeds"
4. If a DoodleBug goes eight steps without dying, it "breeds"
5. If a DoodleBug goes three steps without eating, it "dies"
