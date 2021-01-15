## Introduction

In this repository, I'll use the [Pomegranate](https://github.com/jmschrei/pomegranate) library to build a hidden Markov model for part of speech tagging with a [universal tagset](http://www.petrovi.de/data/universal.pdf). Hidden Markov models have been able to achieve >96% tag accuracy with larger tagsets on realistic text corpora. Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.


## Hidden Markov Model

To learn more about what the Hidden Markov Model is and how it works, first watch the videos linked below:

* ![1. Hidden Markov Model](/images/1.mp4) 
* ![2. How to get the heighest probability of Hidden Markov Model graph](/images/2.mp4) 
* ![3. How to simplify Hidden Markov Model graph](/images/3.mp4) 
* ![4. Viterbi algorithm](/images/4.mp4) 
* ![5. Viterbi algorithm](/images/5.mp4) 

## Getting Started


 you can download a copy of the project from my GitHub [here](https://github.com/A2Amir/Part-of-Speech-Tagging) and then run a Jupyter server locally with [Anaconda](https://www.anaconda.com/download/).


0. (Optional) The provided code includes a function for drawing the network graph that depends on [GraphViz](http://www.graphviz.org/). You must manually install the GraphViz executable for your OS before the steps below or the drawing function will not work.

1. Open a terminal and clone the project repository:
```
$ git clone https://github.com/A2Amir/Part-of-Speech-Tagging
```

3. Switch to the project folder you cloned the project and create a conda environment (note: you must already have Anaconda installed):
```
$ cd to the project folder you cloned the project
$ conda env create -f nlp.yaml
```

4. Activate the conda environment, then run the jupyter notebook server. (Note: windows users should run `activate hmm-tagger`)
```
 $ source activate nlp.yaml
 $ jupyter notebook
```

Depending on your system settings, Jupyter will either open a browser window, or the terminal will print a URL with a security token. If the terminal prints a URL, simply copy the URL and paste it into a browser window to load the Jupyter browser. Once you load the Jupyter browser, select the project notebooks [1.HMM warmup](https://github.com/A2Amir/Part-of-Speech-Tagging/blob/main/HMM%20warmup.ipynb),  [2.HMM tagger](https://github.com/A2Amir/Part-of-Speech-Tagging/blob/main/HMM%20Tagger.ipynb) and follow the instructions inside to run the tagger.


