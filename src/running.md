# Running
you can run ensembles by starting the script.
get a list of subcommands by running `ensembles --help`.
you can also get help for a subcommand by running `ensembles ${subcommand} --help`.
for example if you want help with the advanced command then you can run `ensembles advanced --help` for the custom subcommand of advanced you can type `ensembles ${subcommand} advanced custom --help`.

## simple mode
This most basic run looks like `ensembles simple`.
It will run the standard benchmark.

In most cases you will have to specify the path that NumIO is installed in `ensembles --numio-path /home/${yn}/IO-partdiff/numio-posix simple`. If you have numio installed globally you can skip this.


## advanced mode
Ensembles also has an advanced mode.
This mode provides some more fine grained control.

## empty
A benchmark with little background noise.

## balanced
A benchmark with a medium amount of background noise.

## peak
A benchmark with a lot of background noise.

## custom
A benchmark with customizable background daemons.
You will have to specifiy the number of background daemons for this one.