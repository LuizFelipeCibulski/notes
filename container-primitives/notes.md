**Containers are an abstraction over several different Linux tecnologies**

Namespaces 
Control groups
Union filesystem

What do control groups (cgroups) do?
    Organize all processes in the system 
    Account for resource usage and gather utilization data
    Limit or prioritize resource utilization

Control group system is an abstract framework
Subsystems are concrete implementations
Different subsystems can organize processes separately
Most subsystems are resource controllers

Examples of subsystems:
    Memory
    CPU time
    Block I/O
    Number of discrete processes (pids)
    CPU & memory pinning
    Freezer (used by docker pause)
    Devices 
    Network priority




