# JS-CSS-clock
2nd challenge from #JavaScript30 by Wes Bos

A simple Javascript analog clock following instructions from the Wes Bos #JavaScript30 challenge. I have made some changes to the original one:

![original clock final] (original.png)

1 - On the original all the hands have the same style. I've updated the hours hand to be shorter, and the seconds to be thinner. Also changed the colors.

2 - Added a different background

3 - In the original there was a bug that caused the second hand to glitch when reaching the 12h position by moving all the way backwards in order to start the rotation all over again.
I've fixed this in my version with an if statement that removes the transition styling when the hand reaches this position (at 90degrees), and restores it for all the other positions.