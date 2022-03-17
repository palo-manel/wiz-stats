# wiz-stats

This [Jupyter notebook](https://jupyter.org/) uses [GraphQL queries](https://graphql.org/) to retrieve information from [wiz.io](https://app.wiz.io/) and provide some useful stats.

The queries were built using the [wiz.io API Explorer](https://app.wiz.io/api-explorer), there's also a [Postman Collection](https://docs.wiz.io/wiz-docs/docs/postman-collection) with examples available.

## Running Locally

### Pre-requisites

To be able to run this manually you need to install the necessary pre-requisites.

```bash
pip install -r "requirements.txt"
```

### Embededing in VS Code

VS Code provides native [support for Jupyter Notebooks](https://code.visualstudio.com/docs/datascience/jupyter-notebooks) and lets you:

* Create, open, and save Jupyter Notebooks
* Work with Jupyter code cells
* View, inspect, and filter variables using the Variable Explorer and Data Viewer
* Connect to a remote Jupyter server
* Debug a Jupyter Notebook

So you'll just need to open this project in VS Code and interact with the Jupyter notebook as you would normally.

## Running in a cloud environment

⚠️ This information is provided for pedagogical purposes only, please be aware you should only upload example data to public services.

### Binder

A Binder service is powered by [BinderHub](https://github.com/jupyterhub/binderhub), an open-source tool that runs on Kubernetes. One such deployment lives at [mybinder.org](mybinder.org), and is free to use. For more information about the mybinder.org deployment and the team that runs it, see [About mybinder.org](https://mybinder.readthedocs.io/en/latest/about/about.html).

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/palo-manel/wiz-stats/main?labpath=wiz.ipynb)

### Google Colaboratory

[Google Colab](https://colab.research.google.com/), or ‘Colaboratory’ allows you to write and execute your notebooks for free on Google infrastructure (including free access to GPUs). Watch [Introduction to Colab](https://www.youtube.com/watch?v=inN8seMm7UI) to find out more.

Colab is used extensively in the machine learning community with applications including:

* Getting started with TensorFlow
* Developing and training neural networks
* Experimenting with TPUs
* Disseminating AI research
* Creating tutorials

To see sample Colab notebooks that demonstrate machine learning applications, see the [machine learning examples](https://colab.research.google.com/?utm_source=scs-index#machine-learning-examples).

[![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/palo-manel/wiz-stats/blob/main/wiz.ipynb)
