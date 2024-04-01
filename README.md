# multi-threaded-matrix-multiplication
This is a multi-threaded matrix multiplication program written in `C` that uses the `pthread` library to create a thread pool and perform matrix multiplication splitting the work among the threads. The program takes in two matrices and the number of threads to use as input and outputs the resulting matrix.

You can see the difference in performance between the single-threaded and multi-threaded versions of the program in the `result.png` file.

Note: if number of threads be greater than the number of cores, the performance will probably be worse or the same as the thread number equal to the number of cores.



