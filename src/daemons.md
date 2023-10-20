# Background Daemons

## Types of Deamon
Besides the main Benchmark NumIO ensembles also spawns some daemons to create background noise.
These are used to create a more realistic environment for to run the benchmark in.
There are a few premade daemons:

### Chatty
This is a daemon that creates a lot of network usage.
Usually a _single_ program not use this much network.

It is still useful to simulate a high combined network load.

### Disk
This daemon creates a lot of disk I/O.
It can be used to simulate something like a grep task.

### CPU
This daemon creates a lot of load on the CPU.
You can use it to simulate a compute task or similar.


## Daemons In Advanced Mode
In advanced mode you will find the `custom` subcommand.
This command lets you decide how many of the different daemons you want to run in the background.
Use this feature to simulate a workload that is not standardized, but realistic for your system.
