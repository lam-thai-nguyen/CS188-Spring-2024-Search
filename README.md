# CS188 2024 Spring - Project 1: Search

More info at: [Project 1 | CS 188 Spring 2024](https://inst.eecs.berkeley.edu/~cs188/sp24/projects/proj1/)

## Q1 (3 pts): Finding a Fixed Food Dot using Depth First Search (Lecture 2)

```
Starting on 5-13 at 18:45:08

Question q1
===========
Search Succeeded.
*** PASS: test_cases\q1\graph_backtrack.test
***     solution:               ['1:A->C', '0:C->G']
***     expanded_states:        ['A', 'D', 'C']
Search Succeeded.
*** PASS: test_cases\q1\graph_bfs_vs_dfs.test
***     solution:               ['2:A->D', '0:D->G']
***     expanded_states:        ['A', 'D']
Search Succeeded.
*** PASS: test_cases\q1\graph_infinite.test
***     solution:               ['0:A->B', '1:B->C', '1:C->G']
***     expanded_states:        ['A', 'B', 'C']
Search Succeeded.
*** PASS: test_cases\q1\graph_manypaths.test
***     solution:               ['2:A->B2', '0:B2->C', '0:C->D', '2:D->E2', '0:E2->F', '0:F->G']
***     expanded_states:        ['A', 'B2', 'C', 'D', 'E2', 'F']
Search Succeeded.
*** PASS: test_cases\q1\pacman_1.test
***     pacman layout:          mediumMaze
***     solution length: 130
***     nodes expanded:         146

### Question q1: 3/3 ###


Finished at 18:45:08

Provisional grades
==================
Question q1: 3/3
------------------
Total: 3/3
```

## Q2 (3 pts): Breadth First Search (Lecture 2)

```
Starting on 5-13 at 21:39:15

Question q2
===========
Search Succeeded.
*** PASS: test_cases\q2\graph_backtrack.test
***     solution:               ['1:A->C', '0:C->G']
***     expanded_states:        ['A', 'B', 'C', 'D']
Search Succeeded.
*** PASS: test_cases\q2\graph_bfs_vs_dfs.test
***     solution:               ['1:A->G']
***     expanded_states:        ['A', 'B']
Search Succeeded.
*** PASS: test_cases\q2\graph_infinite.test
***     solution:               ['0:A->B', '1:B->C', '1:C->G']
***     expanded_states:        ['A', 'B', 'C']
Search Succeeded.
*** PASS: test_cases\q2\graph_manypaths.test
***     solution:               ['1:A->C', '0:C->D', '1:D->F', '0:F->G']
***     expanded_states:        ['A', 'B1', 'C', 'B2', 'D', 'E1', 'F', 'E2']
Search Succeeded.
*** PASS: test_cases\q2\pacman_1.test
***     pacman layout:          mediumMaze
***     solution length: 68
***     nodes expanded:         269

### Question q2: 3/3 ###


Finished at 21:39:15

Provisional grades
==================
Question q2: 3/3
------------------
Total: 3/3
```