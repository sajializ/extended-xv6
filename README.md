# extended-xv6
An extended version of xv6 kernel with modified system calls, scheduling schemes, and synchronization and concurrency components.

### Phase 1 (Introduction): 
* Printing our names after boot.
* Added Ctrl+c, Ctrl+v, Ctrl+x, Ctrl+b.
* Added a user program named lcm.

### Phase 2 (System Calls)
* Added new system calls: reverse_number, print_trace, get_children, trace_syscalls.

### Phase 3 (CPU Scheduling)
* Added multiple queue scheduling including RR, Lottery, and BJF.
* Added aging to processes.

### Phase 4 (Synchronization And Concurrency)
* Implemented semaphores.
* Implemented readers writers problem.
