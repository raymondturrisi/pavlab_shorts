# pavlab_shorts

## By Raymond Turrisi (and maybe more)

 ____             _       _       ____  _                _       
|  _ \ __ ___   _| | __ _| |__   / ___|| |__   ___  _ __| |_ ___ 
| |_) / _` \ \ / / |/ _` | '_ \  \___ \| '_ \ / _ \| '__| __/ __|
|  __/ (_| |\ V /| | (_| | |_) |  ___) | | | | (_) | |  | |_\__ \
|_|   \__,_| \_/ |_|\__,_|_.__/  |____/|_| |_|\___/|_|   \__|___/
### About 

Herein I am adding my general utilities for managing the vehicles in the lab. This includes sailbot utilities, and heron utilities. More to come, probably relating to cluster management and slurm jobs for HPC clusters. 

Place this repo in your $HOME directory for script assumptions to work appropriately. Within or ~/.zshrc or ~/.bashrc you can add a line such as:
```
...
eval "$HOME/setup_pavlab_shorts"$
```
Which adds everything, or you can add a specific folder which is related to your project. 

```
...
eval "$HOME/pavlab_shorts/herons/setup_herons"$
```

                                                                
