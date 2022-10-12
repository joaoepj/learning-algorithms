# learning-algorithms

Some notes about the [MIT 6.006 Introduction to Algorithms, Spring 2020](https://www.youtube.com/playlist?list=PLUl4u3cNGP63EdVPNLG3ToM6LaEUuStEY)


## 1. Algorithms and Computation

### Goals:
1. Solve computational problems
2. Prove correctness
3. Argue efficiency
4. Communicate solution

### What is a problem?

A binary relation. A set of inputs and outputs. A predicate/statement that allow us to confirm that some relation between input and output holds.

### What is an algorithm?

A function description, a procedure, a recipe that explains how to obtain output from input, how input relates to output.

### The Birthday Match Problem

In a classroom, there are any pair of students with same birth date?

#### Proposed Algorithm:
- Add a student's birthday to a record
- Inform if a birthday pair exist in the record
- Repeat until there are no more students to add

#### Algorithm's properties:
- Correctness

Inductive Hypothesis:

if the first $k$ students contain a math
  
  the algorithm returns it before interviewing student $k+1$

Base case: $k = 0$

- Efficiency

Don't measure time, cause it depends on the power of computer. Instead, measure quantity of operations

Asymptotic (relative to problem input size) notation
- $O()$ upper bound
- $\Omega()$ lower bound
- $\Theta()$ both

$\Theta(1) \lt \Theta(\log{n}) \lt \Theta(n) \lt \Theta(n\log{n}) \lt \Theta(n^{2}) \lt \Theta(n^{c}) \lt 2^{\Theta(n^{c})}$

Note: $2^{\Theta(n^{c})}$, which I clearly do not understand

#### Code in go?

#### Explained Run time Analisys?

### Computation

Possible computing operations on the reference model of computation:

* Integer aritmethic
* logic operations
* bitwise operations
* Read and write from a memory address in constant time (Word-RAM)

A CPU takes a constant amount of time to operate on a constant amount of memory. Operate over a linear amount of memory takes a linear amount of time.

Data structures are ways of storing non-constant amount and make operations over them faster.

#### Strategies to solve a problem.

1. Reduce it to a known algorithm
2. Design your own (recursive) algorithm

#### Asymptotics Exercises

3. Can't see how to reach answer with logarithmic operations
4. Why? Needs explanation (valid for all lacking mathematical background)

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

## 3. Sets and Sorting

### Set
Care a bout element value
