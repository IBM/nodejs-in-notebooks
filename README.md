# Using Node.js Data Science notebooks

## Introduction
Notebooks are where data scientists process, analyse, and visualise data in an iterative, collaborative environment. They typically run environments for languages like Python, R, and Scala. For years, data science notebooks have served academics and research scientists as a scratchpad for writing code, refining algorithms, and sharing and proving their work. Today, it's a workflow that lends itself well to web developers experimenting with data sets in Node.js.

To that end, pixiedust_node is an add-on for Jupyter notebooks that allows Node.js/JavaScript to run inside notebook cells. Not only can web developers use the same workflow for collaborating in Node.js, but they can also use the same tools to work with existing data scientists working in Python.

pixiedust_node is built on the popular PixieDust helper library. Let’s get started.

![notebook preview](/notebooks/images/notebook_preview.png)


## Table of Contents
* Setup
* Running the samples
* Credits

***
## Setup

### Prerequisites
To get started with nodebooks you'll need a local installation of
 
 * [PixieDust and its prerequisites](https://ibm-watson-data-lab.github.io/pixiedust/install.html)
 * A Python kernel with Spark 2.x. (see section *Install a Jupyter Kernel* in [the PixieDust installation instructions](https://ibm-watson-data-lab.github.io/pixiedust/install.html))
 * [Node.js/npm](https://nodejs.org/en/download/)

> **Nodebooks are currently _not supported_ by the [Watson Data Platform](http://datascience.ibm.com/analytics).**

### Installing the samples

To access the samples, clone this repository and launch a Jupyter server on your local machine.

```
 $ git clone https://github.com/ibm-watson-data-lab/nodebook-code-pattern
 $ cd nodebook-code-pattern
 $ jupyter notebook notebooks/
```

## Running the samples

Open [nodebook_1](notebooks/nodebook_1.ipynb) to learn more about

 * using variables, functions, and promises,
 * working with remote data sources, such as Apache CouchDB (or its managed sibling Cloudant),
 * visualizing data
 * sharing data between Python and Node.js.

No notebook changes should be required to complete all steps.

***

## Optional data source customization

Some of the nodebook code pattern examples access a read-only Cloudant database for illustrative purposes. If you prefer you can create your own copy of this database by replicating from remote database URL `https://56953ed8-3fba-4f7e-824e-5498c8e1d18e-bluemix.cloudant.com/cities`. [[Learn more about database replication](https://developer.ibm.com/clouddataservices/docs/cloudant/replication/)...]

## Credits

This code pattern is based on a series of blog posts that were first published by [Glynn Bird](https://medium.com/@glynn_bird) on  [medium.com](https://medium.com/ibm-watson-data-lab).

## License
 [Apache-2.0](/LICENSE)

