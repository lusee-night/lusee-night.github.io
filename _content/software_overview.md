---
title: "Software Overview"
layout: base
name: software_overview
---

# Software Overview

Software is developed inside the [LuSEE-Night organization on GitHub](https://github.com/lusee-night){:target="_blank"}.
In that organization, you will find a number of GitHub repositories described below.

---

## luseepy

This is the basic interface to LuSEE-Night tools for doing eveything we need to do with the data, from understanding the celestian transformation to simulating the data vectors. 
It is written in python. Documention on the readthedocs is upcoming.
* [luseepy repo](https://github.com/lusee-night/luseepy){:target="_blank"}


## LuSEE-Night notebooks

This repo contains a selection of useful notebook. Many of those use luseepy but not all. The reason for a separate repo is that everyone can commit their notebook here, while changes to the main branch of luseepy are protected and require a proper code review.
* [LuSEE-Night notebooks repo](https://github.com/lusee-night/notebooks){:target="_blank"}


## refspec

Reference spectromter algorithms developed in C++ with python bindings. Eventually these cooperate with lusee-py for ability to simulate ADC-level timestreams.
* [refspec repo](https://github.com/lusee-night/luseepy){:target="_blank"}

## LNspec

Implementation of the spectrometer code (same as refspec) in matlab with makefile that converts these codes into VHDL.
* [LNspec repo](https://github.com/lusee-night/LNspec){:target="_blank"}

## LuSEE_VHDL

Actual VHDL firmware that will be running on the spectrometer. Contains compiled codes from the LNspec repo together with human-fixes to matlab VHDL compiler inefficiencies.
* LuSEE_VHDL repo: TBD

## Singularity

This repository is meant for keeping useful bits of image configurations and details of running containers.
* [Singularity repo](https://github.com/lusee-night/singularity){:target="_blank"}

## Operations

A private repo to monitor progress on LuSEE-Night operations.
* [Operations repo](https://github.com/lusee-night/lusee-ops){:target="_blank"}

## This website [repo]({{ site.github }})

Yes, if you want to modify this website, this is the place to do it.

