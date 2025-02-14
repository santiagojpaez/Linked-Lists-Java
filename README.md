# Concurrent Programming - Practical Work

## Overview
This project involves the empirical evaluation of different implementations of a concurrent set using linked lists in Java. The goal is to measure execution times under various scenarios where multiple threads perform concurrent operations on a shared data structure.

## Requirements
1. Implement three versions of concurrent sets:
   - Fine-grained locking
   - Optimistic synchronization
   - Lock-free
2. Define and execute scenarios to evaluate:
   - Variation in the proportion of threads performing specific operations
   - Variation in the total number of threads while keeping the total number of operations constant
   - Variation in the total number of threads while keeping the number of operations per thread constant
3. Measure and analyze execution times.
