# NEST Tutorial at EITN Fall School 2022

This repository accompanies the NEST tutorial at the EITN Fall School in Computational Neuroscience 2022.
Here you can find the presentation slides, Jupyter notebooks and other materials. 

## Installation instructions

Complete documentation for NEST and NESTML can be found [here](https://www.nest-simulator.org/documentation/) and [here](https://nestml.readthedocs.io/en/v5.1.0/). 
Please make sure you have the latest releases (NEST 3.3 and NESTML 5.1.0) or the current development versions from the respective GitHub repositories.
Note that in the tutorial we will not use NESTML, so its installation is optional. 

### Windows
Use VM image provided [here](https://nest-simulator.readthedocs.io/en/v3.3/installation/livemedia.html#live-media).

### Linux / macOS
1. You can use the NEST Docker container as detailed [here](). We recommend using the **EBRAINS host**  instead of the Docker hub image linked in the documentation, as this contains the latest NESTML release:
```shell
docker pull docker-registry.ebrains.eu/nest/nest-simulator:3.3
```

2. You can also install NEST using `conda install nest`, but the latest NESTML version may not work with this solution. 

    An alternative would be to [build and install NEST manually](https://nest-simulator.readthedocs.io/en/v3.3/installation/linux_install.html#linux-install)
in the Conda environment (e.g., downloading the zip and install using Cmake), along with `pip install nestml`.  

For Linux and macOS, you can use the `nest_env_OS.yaml` configuration files to set up your environment some relevant packages. 

## Get in touch

b.zajzon at fz-juelich.de

