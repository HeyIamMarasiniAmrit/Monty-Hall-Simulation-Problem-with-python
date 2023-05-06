# Monty-Hall-Simulation-Problem-with-python
WTH is Monty Hall Problem ?
_Assume There are three doors, and behind one of them is a car, while behind the other two are goats. If you choose the door with the car behind it, you win the car. Now, say you choose Door 1. The host Monty Hall then opens either Door 2 or Door 3, behind which is a goat. (He knows what is behind each door, and never opens the door with the car behind it.) Monty now gives you the choice: do you want to stick with Door 1, or switch to the other door. What should you do? Or does it matter?

Now the battle lies Emotion vs Math, mathematically switching would give you a 2/3 probability of winning rather than sticking to the same door as the probabilty of winning a car among those two door would concentrate into one.

How are we going to Simulate ?
In this source code I have simulated this problem using random module to simulate the process, and supringly with enough trials the probability winning when you switch converge to 0.6666.. which is equivalent to 2/3.

Do some simulations
Once you run the application, a very simple gui similar to what shown below will pop up with an entry box, write in it no of sample to be simulated and then press enter and then program will evaluate total wins for case of same choice or switching

Monty hall’s problem comes from a famous movie where three doors are used to help you win a car. How? Each door hides something behind it–a car and two goats. Any door can have the car while the remaining two have goats. The probability to find a car is ⅓. Now, if you select Door 1 and the host opens Door 3 to find a goat, your chances just become ⅔. This program will help you solve this problem. 

Work Flow and Logic 

The following are the main points of the simulation:

As there are three doors, a random permutation of the numbers 1, 2, and 3 would be generated, with each number representing a door. This permutation contains the first two numbers that correspond to the location of goats behind the door, and the third number corresponds to a car behind the door.
Using images, the configuration is represented graphically. Every configuration has its own image.
Only the door behind which there is a goat is to be revealed after the user has chosen a door number according to the puzzle. By selecting the door behind which the car is parked, the user can then reveal either of the other two doors. If the user selects a door behind which there is a goat, only one of the two remaining doors can be revealed (since the previously selected door cannot be revealed).

