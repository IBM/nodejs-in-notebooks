# Using Node.js Data Science notebooks

## Introduction
Notebooks (that’s Jupyter/IPython notebooks, not Moleskine® notebooks) are where data scientists process, analyse, and visualise data in an iterative, collaborative environment. If you are a developer, but not a data scientist, and like the idea of having a scratchpad where you can write some code, iteratively work on some algorithms, and visualise the results quickly, we'll invite you to explore the world of *nodebooks*.

![notebook preview](/notebooks/images/notebook_preview.png)


## Table of Content
* Setup
* Running the samples
* Credits

***
## Setup

### Prerequisites
To get started with nodebook you'll need a local installation of 
 * Jupyter
 * Node.js

> Nodebooks are currently _not supported_ by the [Watson Data Platform](http://datascience.ibm.com/analytics).
 
### Installing the samples

To access the samples, clone this repository and launch a Jupyter server on your local machine.

```
 $ git clone https://github.com/ibm-watson-data-lab/nodebook-code-pattern
 $ cd nodebook-code-pattern
 $ jupyter notebook notebooks/
```

## Running the samples

Open [this nodebook](notebooks/nodebook_1.ipynb) to learn more about 
 * using variables, functions, and promises,
 * working with remote data sources, such as Apache CouchDB (or it's managed sibling Cloudant),
 * visualizing data, and
 * sharing data between Python and Node.js.

## Credits

This code pattern is based on a series of blog posts that were first published by [Glynn Bird](https://medium.com/@glynn_bird) on  [medium.com](https://medium.com/ibm-watson-data-lab).


