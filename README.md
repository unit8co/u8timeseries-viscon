# Preparing for workshop

Find below a few steps you can go through before the workshop begins

## Step 1

Clone this repository

## Step 2

Install Docker Community Edition (CE)

* [Ubuntu](https://docs.docker.com/v17.09/engine/installation/linux/docker-ce/ubuntu/)
* [Windows](https://docs.docker.com/v17.09/docker-for-windows/install/)
* [Mac](https://docs.docker.com/v17.09/docker-for-mac/install/)

## Step 3

Navigate to the repository directory with a terminal and build the docker image

`docker build . -t unit8/timeseries:0.1`

## Step 4

Try to run the Docker image to ensure everything works
 
`docker run -p 8000:8888 -v "$PWD":/home/jovyan/work unit8/timeseries:0.1`
