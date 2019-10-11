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

Pull the workshop Docker image from the hub (it can take several minutes):

`docker pull kstyrc/timeseries-viscon:0.1`

_Note: The Dockerfile is provided in this repository so you can build/edit it by your own._

## Step 4

- Open a terminal and navigate to the repository cloned in step 1.
- Try to run the Docker image
 
`docker run -p 8888:8888 -v "$PWD":/home/jovyan/work kstyrc/timeseries-viscon:0.1`

And access the Jupyter web server with your browser (the link is printed in your terminal)

If you can access Jupyter from your browser you're all good for our workshop !

_Note: for Windows users replace `"$PWD"` with "%cd%"_ 

# Contacts

#### Speakers

* Kilian Brandt: kilian(at)unit8.co
* Krzysztof Styrc: kstyrc(at)unit8.co

#### Unit8

* Website: https://unit8.co/
* LinkedIn: https://www.linkedin.com/company/unit8.co/
* Twitter: https://twitter.com/unit8co 
