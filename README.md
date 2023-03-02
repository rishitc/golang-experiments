# golang-experiments
Short experiments to try out different ideas of Golang in Golang.

## Experiment-1

### Objective

Compare the performance of executing an extensive computation with and without using goroutines.

### Description

In this experiment, I'm performing the computation of adding a large slice of integers.
I compare the performance of serially adding a large slice of integers versus dividing the large slice into sections and using goroutines to find the sum of each section before adding these results together to get the sum of the entire slice.

Especially on multicore systems, the performance benefits of using the goroutines for this type of computation will be noticeable.

### Results

Performing the computation using goroutines proves to be much faster, especially on multicore systems.

---
