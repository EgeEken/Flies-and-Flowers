# Flies and Flowers

I made this project for my Java class in Sorbonne University in 2022, the objects that affect the simulation are:

- Flies, which fly around randomly unless theres nectar on the screen, in which case they will use a simple pathfinding algorithm to move towards it

- Flowers, which include two sub abstract classes, Flowers that sleep, Flowers that don't sleep. Flowers that sleep are Cereus Blooms, which will open up and close depending on their randomly generated sleeping cycles, and venus flytraps, which follow the same system, but can also eat flies that move over them while they're awake. Flowers that don't sleep are tulips, which don't have any special properties besides secreting nectar at the start of every day like all other plants do.

The simulation will be terminated when/if all of the flies are eaten by the flytraps. 
