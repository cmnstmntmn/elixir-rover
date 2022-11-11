# Rover

> [Mars Rover Kata](https://kata-log.rocks/mars-rover-kata) A simulator of a simple rover that receives commands to move around the planet (Mars, in this case). The rover receives the commands in the form of characters and returns its position according to the execution of the commands.

## Details

* You are given the initial starting point (x,y) of a rover and the direction (N,S,E,W) it is facing.
* The rover receives a character array of commands.
* Implement commands that move the rover forward/backward (f,b).
* Implement commands that turn the rover left/right (l,r).
* Implement wrapping at edges. But be careful, planets are spheres.
* Implement obstacle detection before each move to a new square. If a given sequence of commands encounters an obstacle, the rover moves up to the last possible point, aborts the sequence and reports the obstacle.