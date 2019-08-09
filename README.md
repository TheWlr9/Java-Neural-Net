# Java-Neural-Net
A Java version of a nice and easy neural network module, ready to be implemented anywhere you want for all your AI needs!

## How To Use
* First, give a neural network to all members of the population.

**GENERATION START**
* Then during the execution/update functions of the members, you must call the update method on it's neural network by giving it the updated input values. It will return the output values.
* Then have them act accordingly to the outputs of the neural network.

**GENERATION END**

* Then set the fitness levels of the corresponding genomes in the genetic algorithm to the fitness of the neural network (for each member).
* Then run the epoch function and set the old population of genomes to the newly returned population of genomes from the epoch function.
* Lastly, reset all fitness scores back to 0.

**GOTO GENERATION START** (for as many generations as you desire)

## Rules
* Input values given to the input neurons of the neural network can be any integer.
* The output values are from range [0, 1].
