Parallel and Distributed Simulation of Large-Scale Distributed Applications
=============================================================================

Experiments about the parallel simulation with [SimGrid](http://simgrid.gforge.inria.fr/) I strongly suggest to read the report before any attempt to understand the code.

The internship consisted in detecting bottlenecks in the simulation of large scale distributed systems and propose several performance improvements to the framework. 

I suggest reading this introduction to the [Simgrid Framework](http://simgrid.gforge.inria.fr/tutorials/simgrid-use-101.pdf) to understand what this is about.

All the experiments were carried out simulating several distributed protocols like [Chord](https://en.wikipedia.org/wiki/Chord_(peer-to-peer)) and using several perf tools to measure the bottlenecks.

Structure
=========

- `./logs` folder stores all the raw results from the experiments carried.

- `./report` contains the journal and the final report of the internship.

- `./scripts` contains all the code used to run the experiments.
