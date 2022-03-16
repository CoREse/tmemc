# tmemc
## Introduction
Top MEMory Calculator is a tool that use top command to calculate the max physical memory usage of the processes that have the given name, during an amount of time or thoughout the procecesses' lifetimes. It's especially useful for those programs that has multiple processes (such as multiprocessing python programs).

## Usage
<u>tmemc ProgramName</u> -- to show current memory usage.

<u>tmemc ProgramName -d</u> -- to wait the program to start and then ends when the program is down.

<u>tmemc ProgramName -t 10 -i 0.1</u> -- run every 0.1 seconds in the next 10 seconds.