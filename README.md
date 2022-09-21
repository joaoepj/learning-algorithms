# learning-algorithms

Some notes about the [MIT 6.006 Introduction to Algorithms, Spring 2020](https://www.youtube.com/playlist?list=PLUl4u3cNGP63EdVPNLG3ToM6LaEUuStEY)


## 1. Algorithms and Computation

Goals:
1. Solve computational problems
2. Prove correctness
3. Argue efficiency
4. Communicate solution

### What is a problem?

Given a set of inputs and a set of outputs. A predicate/statement that allow us to confirm that some relation between input and output holds.

### What is an algorithm?

A function description, a procedure, a recipe that explains how to obtain output from input, how input relates to output.

Possible computing operations on the reference model of computation:

* Integer aritmethic
* logic operations
* bitwise operations
* Read and write from a memory address in constant time (Word-RAM)

A CPU takes a constant amount of time to operate on a constant amount of memory. Operate over a linear amount of memory takes a linear amount of time.

Data structures are ways of storing non-constant amount and make operations over them faster.

Strategies to solve a problem.

1. Reduce it to a known algorithm
2. Design your own (recursive) algorithm

## 2. Data Structures and Dynamic Arrays

### Interface versus  Data Structure


Interface (API/ADT)
* Specification
* What data can stored
* Which operations are supported

Data Structure
* Representation
* How data is stored
* Algorithms supporting operations


### Sequence
Care about a particular order
Operations: build, len, iterate, get, set


### Set
Care a bout element value
