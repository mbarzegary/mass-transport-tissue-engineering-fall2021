# Mass Transport in Tissue Engineering, Fall 2021

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mbarzegary/mass-transport-tissue-engineering-fall2021/HEAD)

## Introduction

This repository contains the teaching materials for the sub-course "Mass Transport in Tissue Engineering" taught at KU Leuven in fall 2021. It includes an overview of solving analytical conservation problems (with a focus on tissue engineering) as well as an introduction to solving these problems using computers. For the computational parts, introductory materials are provided for learners to get started with Python and symbolic computing, which are subsequently used to solve a couple of problems using [Sympy](https://www.sympy.org/en/index.html). Moreover, one example is provided to cover the concept of numerical methods and their necessity for mass transport problems.

## Educational content

* `presentation.pdf`: the slides of the course
* `Introduction-to-Python-Programming.ipynb`: introductory notebook to get familiar with Python programming
* `Introduction-to-Sympy.ipynb`: basic introduction to sympolic computing in Python
* `Mass-Transfer-Cellular-Construct.ipynb`: notebook demonstrating a tissue engineering problem solved using Python and symbolic computing
* `Mass-Transfer-Krogh-Cylinder.ipynb`: notebook demonstrating a similar problem
* `Numerical-Transient-Diffusion.ipynb`: notebook demonstrating the concept of numerical computing for transport phenomena

## Recorded content and tutorials

You may refer to the following videos for more explanation on the computational parts of the materials.

* [Introduction to Jupyter notebooks](https://www.youtube.com/watch?v=_xYVsijBF8w&ab_channel=TuxRiders)
* [A quick overview of Python programming language](https://www.youtube.com/watch?v=w0jbjaJf_Ho&ab_channel=TuxRiders)
* [A quick look at SymPy for symbolic computation in Python](https://www.youtube.com/watch?v=lR40tFmSCwM&ab_channel=TuxRiders)
* [Use SymPy for solving ordinary differential equations in Python](https://www.youtube.com/watch?v=xCB8qgRrZwU&ab_channel=TuxRiders)

The recorded hands-on session of spring 2021 is available [here on YouTube](https://youtu.be/sm9GozNz3_w). Moreover, the video of the reaction-diffusion-equation can be found [here on YouTube](https://www.youtube.com/watch?v=YiIT3p507S0&ab_channel=MojtabaBarzegari).

## Getting started

To use the content, you need Jupyter and Python. You may install a local copy of Jupyter by following the instruction on `installation_guide.pdf`. Alternatively, you can click on the binder badge above ("launch binder") to have an interactive online version. This option is easy to go since it doesn't need any software to be installed on your system.

After either installing Jupyter locally or running the online version, you should be able to run `0-Check-Installation.ipynb` notebook to check if everything is up and running.


## Non-original content

The introductory notebooks are obtained from ["Lectures on scientific computing with Python"](https://github.com/jrjohansson/scientific-python-lectures), but the codes are modified to be compatible with Python 3. The transient example is obtained from [here](https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/).
