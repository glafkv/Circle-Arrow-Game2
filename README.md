# Circle-Arrow-Game2
Part 2 of the circle arrow game.
{

PROJECT 2
Author: Gabi Appel

 Due Date: 2/18/19

 Class: CS4500 Sec. 1

 Program description: The point of this game is to follow arrows
 and make sure all the circles are checked. It will take in a file
 that has the number of circles, number of total arrows, and the the
 to and from arrows, it will then "set up" the game. To fully play the game, the
 circles must be strongly connected, which means you can get to every circle from
 the arrows we have. If it's not strongly connected, it prints a detailed message
 about why it didn't work. If it is strongly connected, it will run 10 times, resetting
 each time, then print out stats. It will print out the average amount of checks
 in one game, max amount of checks in one game, and min amount of checks in one
 game. It also prints the average amount of checks per circle, max and min checks
 per circle.

 Central data structures: I used arrays as my main data structures.
 The first one is an array of boolean values that I used to see if a
 circle had an out arrow. The second array is an array of the record oneCircle.
 I used a record so I can have elements of different types for my array. I used
 a recursive procedure to keep track of what circles were strongly connected and
 what was not.

 Potential issue: I could not figure out how to catch if the input file wasn't
 formatted correctly} 
