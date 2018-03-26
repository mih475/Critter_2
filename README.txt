README

Muhammad Hasan
mih475

There are two new classes (Critters) made for this project.

To store the Critters, I used the given List<Critter> population and List<Critter> babies.
babies were used during TimeStep. After TimeStep, members of babies were added to population.
And population were updated throughout the program.

The two Critters are as follows:

Critter1 acts like an animal(carnivorous). It can reproduce when it's energy is really high. 
It will only walk. It never runs. It will attack Critter2(herbivorous) and Algae even if it has 
very low energy. For other unknown creatures, it will only attack when it's energy is 80 or 
higher. Otherwise it won't fight.

Critter2 acts like an animal(herbivorous). It can reproduce when it's energy is really high.
It randomly walks or stay in the same place. It will only attack when it faces Algae or Craig.
Otherwise it won't fight but will try to escape by running.