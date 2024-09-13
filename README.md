
This project simulates a basic operating system environment using C. The OS handles multiple processes arriving at different times, utilizing a Multilevel Feedback Queue Scheduling Algorithm. The system efficiently manages process execution, memory allocation, and synchronization of critical resources using mutexes.

Key Features:

-Process Management: Each process is initialized upon arrival, with a dedicated Process Control Block (PCB) that stores essential information like process ID, state, priority, and memory boundaries.

-Instruction Execution: The system reads program files and executes instructions such as variable assignments, file I/O operations, and printing, ensuring proper interpretation and handling of operations.

-Mutex Synchronization: Mutexes are used to manage access to critical resources, ensuring mutual exclusion and process synchronization for input/output operations and file handling.
Dynamic Scheduling: The project implements a Multilevel Feedback Queue Scheduler, dynamically adjusting process priorities based on quantum expiration and state transitions (Ready, Blocked, Running, Finished).

-State Transitions: Processes are managed through various states, and transitions are handled seamlessly, ensuring smooth execution and synchronization.

Collaborators: Youssef Elshamy, Diana Rehan, Nabila Shreif, Jana Saad, Shahd Abdelkhalek
