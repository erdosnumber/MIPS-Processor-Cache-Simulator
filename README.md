# MIPS-Processor-Cache-Simulator
This is a simulation of the cache structure of MIPS Processor (L1 and L2 Caches). We can get to know how many read and write misses occur at each of these caches,
what is the miss rate at each of these caches and how many writebacks take place from each cache while a processor executes a trace file (some samples of which are in the memory_trace_files folder)
with the help of this simulation. This was done as a part of the course COL216 (Computer Architecture) in Semester 4 at IIT Delhi.

# Compilation and execution
Run the following commands for executing the program
```
make compile
./cache_simulate <blocksize> <L1 cache size> <L1 sssociativity> <L2 cache size> <L2 associativity> <trace file>
```

\<block size\> denotes the size of a block in L1 and L2 Caches.
\<L1 cache size\> denotes the total size of the L1 cache.
\<L1 associativity\> denotes the number of ways in the L1 cache.
\<L2 cache size\> denotes the total size of the L2 cache.
\<L2 associativity\> denotes the number of ways in the L2 cache.
\<trace file\> denotes the name of the trace file on which the program needs to be executed, so it needs to be added to folder before execution.

All the above parameters need to be a power of 2.
