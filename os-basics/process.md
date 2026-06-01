# Process

## What is a Process?

A Process is a program that is currently running.

Any application or program that consumes CPU time and memory is called a process.

A process is also known as a **Unit of Execution**.

## Memory and Disk

- Memory refers to RAM.
- Disk refers to SSD or HDD storage.

A process uses memory (RAM) while it is running.

## Process States

### Ready

The process is ready to run and waiting for CPU time.

### Running

The process is currently being executed by the CPU.

### Waiting

The process is waiting for an event or resource before it can continue.

### Sleep

The process is inactive and waiting for work or requests.

### Terminated

The process has finished execution.

## Process ID (PID)

Every process has a unique Process ID.

The PID helps the operating system identify and manage processes.

## Parent Process

A process can create another process.

The process that creates a new process is called the Parent Process.

## View Running Processes

### Windows

```txt
Task Manager
```

### macOS

```txt
Activity Monitor
```

## Kill a Process

A process can be terminated manually using operating system tools.

When the main process is stopped, the application closes.

## Context Switching

The Operating System rapidly switches between processes and gives each process a small amount of CPU time.

This process is called Context Switching.

## Summary

- A process is a running program.
- A process consumes CPU time and memory.
- Every process has a unique PID.
- Processes move through different states during execution.
- Context Switching allows multiple processes to run efficiently.
