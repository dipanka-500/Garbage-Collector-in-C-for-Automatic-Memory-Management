# Garbage-Collector-in-C-for-Automatic-Memory-Management
Objective:

Develop a basic garbage collection system in C that automatically manages dynamic memory allocation and deallocation, reducing memory leaks and dangling pointer issues.
Project Scope:

    Automatic memory management: Implement a simple garbage collector that detects and frees unused memory.

    Reference counting: Track the number of references to allocated memory blocks.

    Mark-and-Sweep Algorithm: Identify and free unreachable memory.

    Memory Pooling: Allocate and manage memory efficiently.

    Integration with malloc/free: Replace standard malloc/free with custom memory management functions.

System Requirements:

    Language: C

    Compiler: GCC or Clang

    Platform: Linux / Windows

    Dependencies: None (built using standard C libraries)

Project Modules:
1. Memory Allocation and Tracking

    Implement a custom malloc() function to allocate memory.

    Maintain a metadata structure for tracking allocated memory.

2. Reference Counting

    Track reference counts for each memory block.

    Free memory when the count reaches zero.

3. Mark-and-Sweep Garbage Collection

    Traverse allocated objects and mark those still in use.

    Sweep and free unmarked memory blocks.
