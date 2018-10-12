Add your answers to the Algorithms exercises here.

a) For the first problem, the runtime would be O(n) linear time because as n increases the while loop has to run more times in direct proportion to the size of n.

b) the runtime would be O(n) because the outer for loop will continue running until n is reached, and the inner for loops depend on the outer one.

c) the runtime would be O(n) because the bunnyEars function will be called recursively until bunnies equals 0

**Exercise II**:
Start at floor n/2 and see if an egg dropped from this floor breaks. If yes, go to the floor that is halfway between n/2 and the ground. If no, go to the floor that is halfway between n/2 and the top. Continue until you find floor f.