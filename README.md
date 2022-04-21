# Advanced Algorithms and Parallel Programming Challenges

This repository contains three challenges from the *Advanced Algorithms and Parallel Programming (095946)* course at *Politecnico di Milano*.

## Challenges

### MinCut Karger + Karger&Stein

- Analyze the asymptotic complexity of *karger_union_find* and of *karger_stein_union_find* with Google benchmarking library. ✅
- Reimplement/optimize the two *MinCut* procedures with a running time better than the [reference code](https://github.com/ArthurRouquan/KargerSteinAlgorithm). ✅

### Merge Sort Parallelization with MPI

- Implement a general approach for distributing the work of merge sort over multiple processes. ✅
- The provided merging algorithm must not be modified, nor should the vector generators. ✅
- Test the correctness of your algorithm against all three provided vectors (1024, 729, 997 elements). ✅
- Test the correctness of your algorithm when run with 2, 3, 5 processes. ✅
- Evaluate the load balance on the processes in the different configurations, as well as the overall computation time of the program. ✅

### Parallel Scan Pattern with OpenMP

- Implement a scan function that adds to each element of the input vector all the previous elements in the same vector. ✅
- The implementation should use an *upsweep* + *downsweep* approach in order to efficiently compute the results in a parallel execution. ✅
- Implement a second function for checking the correctness of the result if the original vector of size *n* contained, in order, all the values from *0* to *n-1*. ✅
- After obtaining a working parallel implementation, evaluate the speedup offered by each parallel construct in your solution (tip: perform evaluation on a reasonably large vector). ✅
