# parallel-Closest-Pair-problem
a parallel algorithm for finding Closest pair in 2-D space


You should have OPEN-MPI standard installed on your system. version 1.8.1 or later.
you shall compile it like:
  mpicc parallel-Closest-Pair.c -lm -o parallel-Closest-Pair.o
then run it with:
  mpirun -n [num 0f processes] parallel-Closest-Pair.o [input, sth dividable by num of processes]
