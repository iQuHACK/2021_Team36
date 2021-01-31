# Rock Paper Scissors 
Joseph Oronto-Pratt, Victoria Outkin, Jayden Sansom, Oliver VandeWater

## Abstract
We tested a quantum computer vs. a classical computer at playing rock paper scissors.  We wanted to see if the completely random values generated by the quantum computer would beat those of a classical computer, which has patterns in its "random"  algorithm.  We applied Hadamard gates to 2 qubits, and then saw that the probabilities of the outputs were equal.  Then we put the values into a program,  only taking in 3 of the equal probabilities, and ignoring the remaining one.  After that we made the classical computer input a random number corresponding to rock, paper, or scissors.  We ran rock paper scissors games many times,  and recorded the amount of times classical computers won, quantum computers won, and how many ties there were. 

## Introduction
Why is random better than preplanned? It turns out the answer to this question reveals a striking, profound beauty in perfect uncertainty that at times is practically superior to ordered heuristics that may fail at times. While the scope of our project wasn't concerned with the philosophy and more concerned with this application of quantum advantage, consider the following:
Imagine playing a game of rock paper scissors,  and somehow all your actions were completely random, and there was no pattern,  just like a perfect quantum computer would have.   Your friend is playing with you, and is purposefully going after patterns, trying to win.   Because there are no patterns to find,  your friend is creating a pattern themselves,   which puts them at a disadvantage.  Creating a pattern vs. random makes your friend more prone to losing since they make their inputs based on something that doesn’t exist, while you are doing it at random.     
When quantum computers go against normal classical computers it's as though the normal computers are “trying to predict” what the quantum computer will do.  Normal computers have a pattern, because their random output is generated by a deterministic algorithm.  Normal computers are “trying to predict” a pattern that's not there against a quantum computer putting themselves at a disadvantage.   
    There are certain extreme cases where this would not be true,  such as if a classical computer decided to play only “Rock” and the quantum computer would play randomly.   Then both sides have an equal probability of winning, since the quantum computer is not playing against values that change and because its frequency of Rock/Paper/Scissors is ⅓ each .  Once the computer outputs other values in a pattern, as if  trying to predict the quantum computer, it puts itself at a disadvantage.  Even though the classical computer in our code is not trying to beat the quantum computer,  if we imagined it was, and leaving patterns(because normal computers have a deterministic algorithm) it can be seen that after many trials the classical computer would be at a disadvantage.  The randomness of quantum computers make them supreme to regular computers.  
 
 
If we have 2 qubits, and they have a Hadamard gate applied to them then there are 4 equally possible values which the qubits can have.   The qubits can be 000, 001, 011, and 010.  The Hadamard gate gives each qubit the same probability of being in state 1 and 0.  
When we have these 4 outcomes, that in a perfect world occur with equal probabilities, we can use these values to play in a game of rock paper and scissors.  For example,  010 can be "Rock",  000 can be "Paper",  and 011 can be “Scissors”.    What happens to the other value,  001?  We skip it each time, it is reached and only use 000, 010, 011 to represent rock paper and scissors.   When the qubits are measured,  the values received are random, because until they were measured they could not have been guessed.  Therefore the sequence generated by the quantum computer is random.  A classical computer uses a deterministic algorithm , and can not be completely random. The classical result that is outputted can be interpreted as pre planned.

When we have found the values of the quibits that correspond with either Rock, Paper, Or Scissors we match the results against a classical computers result.  The classical computer uses its "random" algorithm to determine if it chooses Rock Paper or Scissors by inputing random number from 0-2.   The results are compared with each other, and after repeating the calculations an output of how many times the classical computer vs.  the quantum computer is outputed. 

The last step, was to have the user play rock paper scissors against the quantum computer! Once the computers were done playing with each other, we told the user to choose Rock Paper or Scissors.  The quantum computer measured the quibits, and used the real quantum computer for the result.   The way we choose rock paper and scissors depends on if we get 000, 010, and 011.  From that, it doesn't matter if we get a completely different value (because quantum computers still have errors), becuase we only take in certain values.   The values are assigned rock paper or scissors,  and then the result of who won is outputed. 


## Motivation and Goals
A great deal of our motivation to create this project arose from a fundamental principle taught in The Coding School's QxQ course (sponsored by IBM Quantum) that quantum measurement is inherently probabilistic. Naturally we saw that applying this idea to a fundamental game such as Rock Paper Scissors would be the best way to put this idea to the test and see it in practical usage. The course's initial emphasis on quantum computing vs. classical computing also inspired us to put both quantum and classical implementations of the game head-to-head where we compare the results of classic computer algorithms for random number generation (0 = rock, 1 = paper, 2 = scissors) versus the intrinsic randomness of various quantum algorithm outcomes.


## Project Elements and Usage
The project contains both a regular Python RPS program from Jupiter Notebooks and a quantum gate-based RPS program. Both can be standalone, but for the purposes of this project, we ran them against each other multiple times to draw conclusions about the different natures of the two. 

## Demonstration
We tested the output of a classical computer, vs the outputs of chosing quibit states. 

## Future Work
Future work would include making the code's loop loop many times, and then save the values outputed in a string to make the program faster.  Future work would also include testing the Computer vs. Quantum on a quantum computer, and outputing many values at once.  The classical computer could be trying to beat the quantum computer, having a premade algorithm to try and guess what the quantum comptuter would output.  There are so many different possibilities to explore in the future!    

## This and the stuff below will be deleted after the project is completed!
Check out some info in the [event's repository](https://github.com/iQuHACK/2021) to get started.

Having a README in your team's repository facilitates judging. A good README contains:
* a clear title for your project,
* a short abstract,
* the motivation/goals for your project,
* a description of the work you did, and
* proposals for future work.

You can find a potential README template in [one of last year's projects](https://github.com/iQuHACK/QuhacMan).

Feel free to contact the staff with questions over our [event's slack](https://iquhack.slack.com), or via iquhack@mit.edu.

Good luck!
