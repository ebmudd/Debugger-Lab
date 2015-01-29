### Answers to Debugger Lab

**Question 1:** `Cutoff` is not a parameter because it is assigned as a
parameter in the `PigGame` class, so it is not needed in `playTurn` method. 

**Question 2:** This line of code would print the average number of turns it
took to reach the goal value, which in this case is 100, however because of
its location in the code it would return 0 because the score was just reset.

**Question 3:** `numBusts` could be moved to `numTurns` because it would tell
you how many of the turns that were taken were a bust. 

**Question 4:** There could be a problem in when to start a new score sheet/new
game so in the `playGame` method. The `PigGame`appears to be sound at the moment. 

**Question 5:** 
Keeps running in scoreSheet and reseting to 0 every time the 
`pigGame` method is called, so it is not keeping track of the score after each
turn. 

Something appears to be wrong with the die because it busts every time. If this
is happening

One problem found was a formatting error in the Die.java
`upValue = (int) (Math.random() * 6) + 1;`

With change we get the correct values returned for the original cutoff of 18.
102
13
7.85
**Question 6:** 
Cutoff Value   Average Number of Turns  
10                6.0
15                8.5
20                10.02, ran another time and got 7.36
25                16.83, ran a couple more times and got 7.21,12.75, 10.1, 7.21