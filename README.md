# Advent of Code 2017
Hopefully most of these solutions are fairly self-explanatory. I'll write longer-length explanations for more complex questions.

## Posts
[Day 3: Spiral Memory](https://medium.com/@nonphatic/advent-of-code-day-3-30db5599e914) ([problem description](http://adventofcode.com/2017/day/3))

[Day 23: Coprocessor Conflagration](https://medium.com/@nonphatic/advent-of-code-2017-day-23-a29ee2d4bab8) ([problem description](http://adventofcode.com/2017/day/23))

## Runtimes
These are the runtimes of only one trial but the variances are fairly small and the focus is on the differences in runtime among the different solutions to see which have comparatively worse performance.

| Day | Runtime (s) | With `-O2` |
|-----|-------------|------------|
| 01  |  0.044      |
| 02  |  0.078      |
| 03  |  0.074      |
| 04  |  0.082      |
| 05  | 16.833      | 10.975
| 06  |  0.398      |
| 07  |  0.148      |
| 08  |  0.137      |
| 09  |  0.102      |
| 10  |  0.340      |
| 11  |  0.119      |
| 12  |  0.168      |
| 13  |  2.136      |  0.503
| 14  |  4.360      |  3.495
| 15  | 62.242      |  3.488
| 16  |  0.462      |
| 17  |  6.753      |  1.865
| 18  |  0.118      |
| 19  |  0.026      |
| 20  |  0.168      |
| 21  |  4.013      |
| 22  | 12.867      |  7.880
| 23  |  0.274      |
| 24  |  6.887      |
| 25  |  6.072      |

Problems that could use some work: 05, 22, 24, 25, 14, 15, 21, 17

Problems that are good enough with optimizations: 13

## Dependencies

I haven't gotten Stack set up with this project (I'll do it next year!), so here's a list of the extra dependencies needed by various files.

* hashmap
* matrix
* split
* tuple
* unordered-containers
* vector
