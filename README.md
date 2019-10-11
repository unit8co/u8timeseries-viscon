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

Try to run the Docker image
 
`docker run -p 8888:8888 -v "$PWD":/home/jovyan/work unit8/timeseries:0.1`

And access the Jupyter web server with your browser (the link is printed in your terminal)


# Contacts

#### Speakers

* Kilian Brandt: kilian(at)unit8.co
* Krzysztof Styrc: kstyrc(at)unit8.co

#### Unit8

* Website: https://unit8.co/
* LinkedIn: https://www.linkedin.com/company/unit8.co/
* Twitter: https://twitter.com/unit8co 
