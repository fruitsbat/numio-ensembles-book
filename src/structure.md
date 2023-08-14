# Project Structure

The project structure for NumIO ensembles is not very complicated and you should be able to get started easily.

## `main.py`
This serves as the entrypoint to the application.

When developing it is recommended to start the program like so: `./src/main.py [args]`

## `advanced.py`
This file contains definitions for the advanced command line mode containing fine grained configurations.

## `batch.py`
This file can launch batch jobs.

## `config.py`
This handles general config like logging.

## `daemon.py`
The premade [background daemons](./daemons.html) are stored in this file.

## `global_vars.py`
This stores all global variables.

## `mpirun.py`
This provides classes to interact with srun and mpirun.

## `numio.py`
This provides classes to interact with numio.

## `pretty_print.py`
This provides classes to display more complicated things on the command line.