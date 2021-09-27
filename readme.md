## Introduction

In this notebook, you'll use the [Pomegranate](https://github.com/jmschrei/pomegranate) library to build a hidden Markov model for part of speech tagging with a [universal tagset](http://www.petrovi.de/data/universal.pdf). Hidden Markov models have been able to achieve >96% tag accuracy with larger tagsets on realistic text corpora. Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.

## Getting Started

**NOTE:** If you are prompted to select a kernel when you launch a notebook, choose the **Python 3** kernel.

You can download a copy of the project from GitHub [here](https://github.com/udacity/hmm-tagger) and then run a Jupyter server locally with [Anaconda](https://www.anaconda.com/download/).

**NOTES:** These steps are **not** required if you are using the project Workspace.

0. (Optional) The provided code includes a function for drawing the network graph that depends on [GraphViz](http://www.graphviz.org/). You must manually install the GraphViz executable for your OS before the steps below or the drawing function will not work.

1. Open a terminal and clone the project repository:
```
$ git clone https://github.com/udacity/hmm-tagger
```

3. Switch to the project folder and create a conda environment (note: you must already have Anaconda installed):
```
$ cd hmm-tagger
hmm-tagger/ $ conda env create -f hmm-tagger.yaml
```

4. Activate the conda environment, then run the jupyter notebook server. (Note: windows users should run `activate hmm-tagger`)
```
hmm-tagger/ $ source activate hmm-tagger
(hmm-tagger) hmm-tagger/ $ jupyter notebook
```

## Licensing, Authors, Acknowledgements
I would like to thank Udacity for creating a platform to learn and upscale my natural language processing skills.

[https://www.bilginkocak.com/](https://www.bilginkocak.com/)
