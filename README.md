## How to setup up conda virtual environment:

1. Create the environment.  
```conda env create -f aind-environment-osx.yml```
2. Enter the environment.  
```source activate aind```
3. Install the development version of hmmlearn 0.2.1 with a source build:  
```pip install git+https://github.com/hmmlearn/hmmlearn.git```

## Udacity commands:

Upload and test your submission code:  
```udacity submit```

## Useful conda commands

Exit from the virtual environement: <br>
```source deactivate```

List available virtual environments: <br>
```conda list env```

Equivalent of `pip freeze` <br>
```conda list --export```


## Book:
http://aima.cs.berkeley.edu/2nd-ed/


## Projects:
### sudoku

In this project, you will be writing code to implement two extensions of our sudoku solver. The first one will be to implement the technique called "naked twins". The second one will be to modify our existing code to solve a diagonal sudoku. To complete this project you will use the tools you learned about in the lesson, and build upon them.

### build a game playing agent

In this lesson, you'll build a Game-Playing agent that defeats opponents in Isolation. Along the way, you'll learn about advanced Game-Playing techniques such as Minimax, Iterative Deepening, and Alpha-Beta Pruning.

### simulated annealling

In this exercise you will check your understanding of simulated annealing by implementing the algorithm in a Jupyter notebook and using it to solve the Traveling Salesman Problem (TSP) between US state capitals.

### constraint satisfaction

In this exercise you will check your understanding of Constraint Satisfaction Problems by solving the N-queens problem using symbolic constraints and backtracking search in a Jupyter notebook.

### planning

In this project, you will define a group of problems in classical PDDL (Planning Domain Definition Language) for the air cargo domain discussed in the lectures. You will then set up the problems for search, experiment with various automatically generated heuristics, including planning graph heuristics, to solve the problems, and then provide an analysis of the results. Additionally, you will write a short research review paper on the historical development of planning techniques and their use in artificial intelligence.

### recognizer

In this project, you will build a system that can recognize words communicated using the American Sign Language (ASL). You will be provided a preprocessed dataset of tracked hand and nose positions extracted from video. Your goal would be to train a set of Hidden Markov Models (HMMs) using part of this dataset to try and identify individual words from test sequences.

As an optional challenge, you can incorporate Statistical Language Models (SLMs) that capture the conditional probability of particular sequences of words occurring. This will help you improve the recognition accuracy of your system.

