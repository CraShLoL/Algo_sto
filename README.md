# Algo_sto

Repository containing some practical exercises carried out during my first year of master's degree.
You can find the instructions (in french) for each exercises here :   
https://github.com/CraShLoL/Algo_sto/blob/main/tp5.pdf  

## Table of content:
* [List of exercices](#List-of-exercices)
* [Simulated annealing](#Simulated-annealing)
* [Genetic](#Genetic)

## List of exercices

* [Traveling salesman : TP 5 ex 1 commerce.ipynb](https://github.com/CraShLoL/Algo_sto/blob/main/TP%205%20ex%201%20commerce.ipynb)
* [Continuous optimization : Tp 5 ex 2 Optimisation.ipynb](https://github.com/CraShLoL/Algo_sto/blob/main/Tp%205%20ex%202%20Optimisation.ipynb)
* [backpack problem : Tp 5 ex 3 Génétique.ipynb](https://github.com/CraShLoL/Algo_sto/blob/main/Tp%205%20ex%203%20G%C3%A9n%C3%A9tique.ipynb)

## Simulated annealing

"Simulated annealing (SA) is a probabilistic technique for approximating the global optimum of a given function. [...] The name of the algorithm comes from annealing in metallurgy, a technique involving heating and controlled cooling of a material to increase the size of its crystals and reduce their defects. Both are attributes of the material that depend on their thermodynamic free energy. Heating and cooling the material affects both the temperature and the thermodynamic free energy or Gibbs energy. Simulated annealing can be used for very hard computational optimization problems where exact algorithms fail; even though it usually achieves an approximate solution to the global minimum, it could be enough for many practical problems.

This notion of slow cooling implemented in the simulated annealing algorithm is interpreted as a slow decrease in the probability of accepting worse solutions as the solution space is explored. Accepting worse solutions allows for a more extensive search for the global optimal solution. In general, simulated annealing algorithms work as follows. The temperature progressively decreases from an initial positive value to zero. At each time step, the algorithm randomly selects a solution close to the current one, measures its quality, and moves to it according to the temperature-dependent probabilities of selecting better or worse solutions, which during the search respectively remain at 1 (or positive) and decrease towards zero."  
Source : https://en.wikipedia.org/wiki/Simulated_annealing

## Genetic

Genetic algorithms inspired by natural selections came way before simulated annealing. The main idea stay the same, we need to maximize a fitness function.
For the Backpack problem we are trying to maximise the sum of items under the constraint of a maximum weight.

