# runkeeper-tracks
## Background

I am a happy user of the RunKeeper app (on iOS). I use it to track all of my runs, my bike rides, and the occassional hike. I appreciate that it comes with a variety of training plans, and I used one of those plans to prepare for my first 10-miler back in April 2016, and I'm following a plan now in preparation for a half marathon later this fall.

While I'm an overall happy customer, I suspected that the 'charts' feature on my activities wasn't displaying accurate information. This repository is my effort to dig a little bit more into this so I could see if it was appropriate to submit a bug report to the folks at RunKeeper.

The main thing in this repository is the [IPython Notebook](RunKeeper-GPX-Analysis.ipynb) that presents my work as I progressed. 


## Local developer environment

I've been really trying to stay away from installing development dependencies of any kind on my primary development box, and with native Docker support becoming widely available on OSX and Windows now, getting started is as simple as cloning this repository, and from the local copy's working directory, just doing the following:

To start, 

    docker run -d -p 8888:8888 -v $(pwd):/home/jovyan/work jupyter/scipy-notebook
