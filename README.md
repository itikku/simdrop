# simdrop
Code for the MEng Capstone project 'SimDrop'

### Setup

You will need the following non-standard Python libraries:

* jupyter
* pandas
* numpy

```
pip install jupyter
pip install pandas
pip install numpy
```

Don't have Python or pip? Use the Anaconda framework to get started: https://www.anaconda.com/products/individual


### Running the simulations

To run any of the simulation code, first execute all code blocks before the header: **Simulation Code Samples**

Then, follow the code samples based on your needs.

The simulation code can be used in two ways:

1. Running a single simulation for a given trial. This is useful for collecting baseline results, without any optimization.
2. Optimization through the genetic algorithm. The system accepts a trial, and returns an optimized set of parameters, and a cost score.
