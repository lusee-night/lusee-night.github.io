---
title: "Software Overview"
layout: base
name: software_overview
---

# Software Overview

Software is developed inside the [LuSEE-Night organization on GitHub](https://github.com/lusee-night){:target="_blank"}.
In that organization, you will find a number of repositories described below.

## [luseepy](https://github.com/lusee-night/luseepy)

This is the basic interface to LuSEE-Night tools for doing eveything we need to do with the data, from understanding the celestian transformation to simulating the data vectors. 
It is written in python. Documention on the readthedocs is upcoming.

## LuSEE-Night [notebooks](https://github.com/lusee-night/notebooks)

This repo contains a selection of useful notebook. Many of those use luseepy but not all. The reason for a separate repo is that everyone can commit their notebook here, while changes to the main branch of luseepy are protected and require a proper code review.

## [refspec](https://github.com/lusee-night/luseepy)

Reference spectromter algorithms developed in C++ with python bindings. Eventually these cooperate with lusee-py for ability to simulate ADC-level timestreams.

## [LNspec](https://github.com/lusee-night/LNspec)

Implementation of the spectrometer code (same as refspec) in matlab with makefile that converts these codes into VHDL.

## [LuSEE_VHDL](https://github.com/eraguzin-bnl/LuSEE_VHDL).

Actual VHDL firmware that will be running on the spectrometer. Contains compiled codes from the LNspec repo together with human-fixes to matlab VHDL compiler inefficiencies.


## [singularity](https://github.com/lusee-night/singularity)

This repository is meant for keeping useful bits of image configurations and details of running containers.


## Operations [repo](https://github.com/lusee-night/lusee-ops)

A private repo to monitor progress on LuSEE-Night operations.

## This website [repo]({{ site.github }})

Yes, if you want to modify this website, this is the place to do it.

