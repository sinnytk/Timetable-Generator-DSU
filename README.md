# Documentation for **Timetable Generator** *(Work in progress)*

## What is it?
An automated university timetable scheduler for *DHA Suffa University*, moderated by *Suffa Innovation Labs*


## Current state?

### Research

## Work diary
### Resources to read up on: 
- [An algorithm for constructing University timetables](https://academic.oup.com/comjnl/article-pdf/8/4/331/1121803/8-4-331.pdf) *Mary Almond*


### Concepts to research:
- ~~What are heuristic and meta-heuristic algorithms?~~
- ~~What are genetic algorithms?~~

### Discoveries:
- Conference dedicated to automated TT scheduling [*Practice and Theory of Automated Timetabling (PATAT)*](http://www.patatconference.org/)

### Research conclusions:
- What are heuristic and meta-heuristic algorithms
    ###### Tarun
    Heuristic algorithms are a class of algorithms designed to give approximate and/or efficient solutions to problems. 
    These algorithms don't neccessarily provide a completely accurate solution, however they're used in order to provide
    a cheaper or accurate enough solution which otherwise require heavy computational cost.
    In summary, heuristic is a solution that provides good enough results much quicker than the classic solutions and acts as a baseline for solutions not found yet.
    e.g Greedy algorithms like Djikstra.

    Metaheuristic algorithms are when we fine-tune the heuristics to accord for a global-optimum(whole problem space) instead of local-optimum(specific problem at hand)
    <br>
- What are genetic algorithms?
    ###### Tarun
    As the name suggests, genetic algorithms are derived from Genetic Biology. It's a heuristic inspired by Charles Darwin's theory of evolution. 
    Using a iterative mutation and survival of fittest concept, we produce the best solution set with fittest(in our case, least clashes) combinations.
    Genetic algorithms have 5 phases:
     - Initial population (random population to start the evolution)
     - Fitness function (function to determine fitness of individual. In our case least clashes)
     - Selection (selecting the most fittest individuals)
     - Crossover (using a random point in chromosome, exchange genes between most fittest individuals)
     - Mutation (to improve diversity, using a random point in fittest chromosomes, replace gene)
    Using this process to replace the weakest individuals with offspring of the fittest individuals, at one point in the this we may find an optimum solution set where least clashes exist
    
    How does the algorithm work?
    ```Start
    Generate random population
    Compute fitness
    Do
        Selection
        Crossover
        Mutation
    While not population has converged
    End
    ```
    <br>
## Contributors
### [Tarun Kumar](https://github.com/sinnytk)
### [Bahawal Baloch](https://github.com/bahawal32)


