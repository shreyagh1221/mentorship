#Randomizer Algorithm
## INPUTS:
- names of all the people
- desired amount of groups

## OUTPUTS:
- names seperated into random groups (of desired amount)
- People per group

## ALGORITHM:
- count how many people there are
- divide by desired amount of groups (THIS IS # of people in group)
- IDEAS:
  - COUNTER: random number generator (randrang()) will produce number. This number will count on the list till it reaches a name. This name goes into first group and is off the list. Repeat till no more names on list
  - RANDOM.SHUFFLE(): shuffles the list of names. Then, split into groups starting from top
