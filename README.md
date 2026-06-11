# Operating Systems Project - Linux Signals and Process Management

Academic project developed as part of the Operating Systems subject at La Salle Campus Barcelona.

The project focuses on programming in C on Linux environments, working with signals, processes, timers and execution control.

## Project objective

The main objective of this project was to understand how a C program can interact with the operating system using Linux signals and system-level functions.

The program reacts to different signals during execution, allowing changes in behavior such as interruptions, timers, controlled stops or state changes.

## Features

- Signal handling in C
- Process and execution control
- Timer-based behavior using alarms
- Event management during program execution
- Interaction with the operating system at low level

## How it works

The program uses Linux signals to control its execution flow. Depending on the signal received, the program can pause, continue, change state, trigger a timer or finish execution in a controlled way.

This approach helps simulate how operating systems manage events and how user-level programs can respond to interruptions or external actions.

## Technologies

- C
- Linux
- Signals
- Processes
- Timers
- Terminal
- Systems programming

## Concepts worked

- SIGINT
- SIGALRM
- SIGTERM
- SIGUSR1
- signal
- raise
- kill
- alarm
- pause

## What I learned

This project helped me understand how a program interacts with the operating system, how signals are managed and how low-level execution control works in Linux.

It also helped me improve my C programming skills and my understanding of event-driven execution in operating system environments.
