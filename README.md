## The ant problem

Matthieu Hanania

This repository is the resolution of the exercice proposed in the [Graduate Data Scientist](https://optiver.com/working-at-optiver/career-opportunities/6902907002/) offer of Optiver.

### Problem :

> An ant leaves its anthill in order to forage for food. It moves with the speed of 10cm per second, but it doesn’t know where to go, therefore every second it moves randomly 10cm directly north, south, east or west with equal probability.

For our simulation, we create a anthill of 10000 ants, and every ant have a maximum of 10000 seconds to reach the food

#### __Question 1:__

> If the food is located on east-west lines 20cm to the north and 20cm to the south, as well as on north-south lines 20cm to the east and 20cm to the west from the anthill, how long will it take the ant to reach it on average?

According to our simulation, it takes an ant 3.5 seconds to reach the food with this condition.

#### __Question 2:__

> What is the average time the ant will reach food if it is located only on a diagonal line passing through (10cm, 0cm) and (0cm, 10cm) points?

According to our simulation, it takes an ant 137.7 seconds to reach the food with this condition.


#### __Question 3:__

> Can you write a program that comes up with an estimate of average time to find food for any closed boundary around the anthill? What would be the answer if food is located outside an area defined by ( (x – 2.5cm) / 30cm )2 + ( (y – 2.5cm) / 40cm )2 < 1 in coordinate system where the anthill is located at (x = 0cm, y = 0cm)?

According to our simulation, it takes an ant 13.0 seconds to reach the food with this condition.

