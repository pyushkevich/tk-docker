# tk-docker

## About
This repository contains a Dockerfile to build a container with our main utilities: [c3d](https://github.com/pyushkevich/c3d), [greedy](https://github.com/pyushkevich/greedy), and [cm-rep](https://github.com/pyushkevich/cmrep). This container is meant to be used as a base for more project-specific containers.

## Using
You can launch the container with the command

    docker run -it pyushkevich/tk:latest /bin/bash
    
The commands `greedy`, `c3d`, `vtklevelset`, `meshglm` and many others can be run from the command line. 

## Versioning
The container will be versioned based on year. For example `2023a` is the first build for year 2023. Each version is associated with specific git hases of greedy, c3d and cmrep. These will be the most recent versions available at the time, and might be more bleeding edge than versions included with [ITK-SNAP](https://github.com/pyushkevich/itksnap)


