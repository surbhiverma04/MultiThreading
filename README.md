# MultiThreading
# Objective:
The objective of this assignment is to implement matrix multiplication using multi-threading with varying numbers of threads (1-10) and analyze the execution times to determine the optimal thread count for minimizing computation time.

# Methodology:

## Matrix Multiplication Function:
Define a function multiply_matrices() to perform matrix multiplication using numpy.dot() for two input matrices A and B. The result is stored in a designated index of the result array.

## Thread Utilization Function:
Implement run_threads() to execute matrix multiplication using a specified number of threads. This function initializes a list of threads and iterates over a list of matrices, creating a new thread for each multiplication operation. Each thread is started and joined to ensure all threads complete their tasks.

## Matrix Generation:
Generate a constant matrix A of size 1000x1000 using numpy.random.rand().
Create a list of 100 random matrices of the same size for multiplication with matrix A.

## Execution:
Invoke run_threads() for each number of threads (1-10) and record the time taken for each operation.

# Results Presentation:
Present the results in tabular format, showing the number of threads and the corresponding execution times.
Plot the number of threads against the execution times using matplotlib.pyplot.plot() to visualize the performance trends.

# Observations and Analysis:
Based on the recorded execution times, analyze the performance of matrix multiplication with varying thread counts. Identify the optimal number of threads that minimizes computation time for this specific task.
We observe that the minimum time is taken when the the number of threads are 5.
