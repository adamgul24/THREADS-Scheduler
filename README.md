THREADS Scheduler
Project Name: THREADS: Scheduler Milestone (SchedulerTest00)
Group Number: Group 13 - Kernel Development Groups
Team Members: Adam H. Guled, Andrew Feng

Overview
This project implements a basic process scheduler for the THREADS operating system. The main test case, SchedulerTest00, demonstrates the creation of one child process, waits for it to terminate, and then exits.

Process Management Features
Process Creation: k_spawn()
Process Termination: k_exit()
Process Waiting: k_wait()
Process Switching: dispatcher()
Key Functions
bootstrap(): Initializes the system and launches the first two processes (watchdog and startup).
k_spawn(): Creates a new process with specified parameters.
k_wait(): Blocks the parent process until a child process terminates.
k_exit(): Terminates the current process and notifies its parent.
dispatcher(): Handles context switching between processes.
