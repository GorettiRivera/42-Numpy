# 42-Numpy

NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.

This project will be done using an IPython Jupyter Notebook. A Dockerfile is provided to save you installation time. 

The purpose of this project is to getting started with the numpy and matplotlib python's libraries. As part of this project we will reproduce some instagram filters.


## Installation

Run the attached Docketfile as follow:
* docker build -t numpy_rush .
* mkdir notebooks
* docker run -p 8800:8888 -v $(pwd)/notebooks:/notebooks numpy_rush
* docker-host-ip:8800/?token=...
 
### Please note that python 3, docker, docker-machine should be installed in your machine (can be install via Brew) and virtualbox (via Managed Software Center)

Helpful commands:
* Create a virtual machine with docker-machine using the virtualbox driver, and named Test.
  - docker-machine create --driver virtualbox Test
* Get the IP address of the Test virtual machine.
  - docker-machine ip Test
* Start the "Test" machine
  - docker-machine start Test
* Define the variables needed by your virtual machine 
  - eval $(docker-machine env Test)
