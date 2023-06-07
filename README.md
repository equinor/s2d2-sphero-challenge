# Sphero BOLT maze challenge

Welcome to the awesome S2D2 Sphero challenge! You will solve this in groups of
5-6 people. The challenge is to get your Sphero to the end of the maze as
quickly as possible. 

## Getting started
Find the name written on the front of your Sphero (Starts with SB-) and run the
example:
```bash
python example.py <spero_name>
```

## Rules of the game

* The Sphero has to complete the maze autonomously. No human interaction is
  allowed.
* You will be able to do a mapping stage for up to 5 minutes before the timer
  starts. After the mapping is done the Sphero will be placed at the beginning
  of the maze. You will be allowed to touch the computer after the mapping
  stage to initiate the race sequence.
* There will be bonus points for style. Each point takes 1 second off you time.
* The timer will start when the Sphero starts moving through the maze.
  Connection time and compass calibration is not included.

## About the maze
* All paths in the maze are in north-south or east-west direction.
* Each intersection is covered by a roof.
* The distance between the intersections all the same length.
* The beginning and end of the maze are both "dead ends". Neither is covered by
  a roof.

Bonus: If you think you can solve this challenge in a randomly oriented maze,
without roofs at the intersections, let me know and I will set one up. Bonus
points will be given for this, but the official time will still be the one from
the first maze.
