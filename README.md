# Reaction-Diffusion Simulation
This is a **Reaction-Diffusion** simulation I made using shaders with WebGL and Three.js, you can play with the **website** at https://diegoochoaa.github.io/Reaction-Diffusion/

### How it works

It works by using two shaders that interchange themselves with a **ping-pong** system, 
each cell computes its future value by adding up its current neighbors with the weights of the **reaction-diffusion** simulation, 
and inputting them into the **reaction-diffusion** equations, with blue representing **B** and red representing **A**.

For the simulation to avoid certain areas of the website I coded it to put green in the areas it should avoid, it then multiplies the kill variable by a small amount to make the area inhospitable **AKA** make it avoid areas.

 - This is my main source of information which helped a lot with the algorithm https://www.karlsims.com/rd.html 
 - This is one that helped to set up WebGL and three.js: https://tympanus.net/codrops/2022/11/25/conways-game-of-life-cellular-automata-and-renderbuffers-in-three-js/




