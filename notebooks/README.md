# Notebook to Demonstrate How to Use the Sinequa REST API to Search for PDS Data

This repository contains a [Jupyter notebook](https://jupyter.org) to demonstrate how to use the [Sinequa](https://www.sinequa.com/product/search-cloud-platform/) REST API to search for data in the [Planetary Data System](https://pds.nasa.gov/). You can incorporate these into your existing JupyterLab notebooks for the plotting and exhibition of planetary and other scientific data, and use them as springboards for new notebooks. You can also run these notebooks directly on any Python-capable computer with a web browser.


## 🖥 Prerequisites

To run these notebooks locally, you'll need [Python 3.7](https://python.org/) or later as well as a web browser.  This notebook has been tested with Python version 3.7.6.


## 🏃‍♀️ Getting Started

Run the following commands from a terminal and your default web browser should launch:

```console
$ # Create a virtual Python environment to isolate Jupyter and PDS dependencies
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install --upgrade --quiet pip
$ # Install the dependencies
$ pip install --requirement requirements.txt
$ # Start it up
$ jupyter-lab
```
    
At this point you'll have a locally running JupyterLab server and your browser opened to it. (If not, point your browser to http://localhost:8888/lab).

From here, you can try out the Sinequa REST API notebook listed in the panel on the left side.


## 👥 Contributing

Within the NASA Planetary Data System, we value the health of our community as much as the code. Towards that end, we ask that you read and practice what's described in these documents:

-   Our [contributor's guide](https://github.com/NASA-PDS/.github/blob/main/CONTRIBUTING.md) delineates the kinds of contributions we accept.
-   Our [code of conduct](https://github.com/NASA-PDS/.github/blob/main/CODE_OF_CONDUCT.md) outlines the standards of behavior we practice and expect by everyone who participates with our software.


## 📃 License

The project is licensed under the [Apache version 2](LICENSE.md) license.
