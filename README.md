# AMGeO-API-Release

![AMGeO Logo](./static/AMGeOLogo.svg)

Notebook going over the new API released with AMGeO 2.0

## Opening directly in github

This notebook is able to be opened in github's native notebook viewer. However, it is recommended to run on your own machine.

## Running this notebook

To run this notebook, you can either use a pre-built docker image, or run on your own machine once installing AMGeO

## Using Docker

If you don't want to have to setup AMGeO on your local machine, you can download a Docker image and run it on your own machine.

First, [install Docker](https://docs.docker.com/engine/install/)

Next, run 
```sh
# get the notebook image
docker pull ghcr.io/amgeo-collaboration/amgeo-api-release-notebook
# run the notebook
docker run -it -p 7777:7777 ghcr.io/amgeo-collaboration/amgeo-api-release-notebook
```

Once the container is running, navigate to ```localhost:7777``` and enter ```test``` as the password. 

You will be able to see ```AMGeO-Api-Release.ipynb```, which you can open and run!

## Your own machine

First, you will need to install AMGeO on your own machine. 

This can be completed by navigating to [AMGeO's website](https://amgeo.colorado.edu/), and register.

Once registered, navigate to the [account page](https://amgeo.colorado.edu/protected/account), and enter your github username to become an AMGeO developer. 

Once confirmed, you can navigate to the [AMGeO repository](https://github.com/AMGeO-Collaboration/AMGeO), and follow the installation instructions.

Now that you have AMGeO setup, you can clone this repository and run the notebook by running ```jupyter notebook``` in the repository directory.

You will be able to see ```AMGeO-Api-Release.ipynb```, which you can open and run!