---
title: "Docker"
layout: base
name: software_docker
---

# Docker

## About

Having functional containers is essential for efficient CI
and for ensuring a reliable environment conducive to reproducibility
of research.
There are a few versions of the LuSEE software Docker images,
targeted towards the development of the *luseepy* Python package, its
testing environment, CI Jupyter notebooks etc. These images are hosted
on **Docker Hub**.

## Singularity

Docker is not available in the interactive nodes of SDCC. However, it is possible to
run Docker images with _Singularity_.

This is an example of a __Singularity__ session using the "base" Docker image which contains
all the packages needed by the ```luseepy``` package. The ```luseepy``` package in this case
is cloned from GitHub and its folder is used in ```bind``` mode in __Singularity__ i.e. it
is available for editing and other modifications on the host machine.


```bash
# Create a working directory
$ cd /home/myhome/ # replace with desired locaiton

# Clone luseepy
$ git clone git@github.com:lusee-night/luseepy.git

# Start Singularity. Note:
# a) We pull the "base" image from Docker Hub, from the repository maintained by the user "buddhasystem"
# b) We "bind" the local lusee folder to "/user" accessible within the container
$ singularity exec --bind /home/myhome/luseepy:/user docker://buddhasystem/lusee-night-luseepy-base:0.1 bash

# We are now running an interactive "bash" shell. Let's set up the PYTHON environment:
Singularity> cd /user/lusee # remember that the local "luseepy" folder is bound to "/user"
Singularity> source ./setup.sh

# Run a test of the "LunarCalendar"

Singularity> cd ../tests
Singularity>  ./LunarCalendarTest.py 
2025 04 14 19 59 28 753901
2025 05 12 06 28 21 606078

```

At this point the user can do any sort of modifications to the files in the ```lusee``` folder,
for example by opening an emacs session in a separate window (since emacs is not available in
the base lusee image).
