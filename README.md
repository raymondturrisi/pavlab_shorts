# pavlab_shorts

## By Raymond Turrisi (and maybe more)

### About 

Herein I am adding my general utilities for managing the vehicles in the lab. This includes sailbot utilities, and heron utilities. More to come, probably relating to cluster management and slurm jobs for HPC clusters. 

### Herons setup
Currently, all you have to do is run: 
`$ source setup_herons`
To first extend your path appropriately, and then export the environment variables which all other scripts and utilities depend on. For distributing SSH keys, you must modify in place the path for your sshpass binary since it varies between operating systems and isn't totally kosher (brew dislikes).