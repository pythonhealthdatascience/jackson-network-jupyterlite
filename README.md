# A Jackson Queuing Network model deployed using JupyterLite

[![lite-badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://pythonhealthdatascience.github.io/jackson-network-jupyterlite/)

This repo uses a JupyterLite template from [Jupyterlite Demo](https://github.com/jupyterlite/demo). It deploys a Jackson Queuing Network as a static site to GitHub Pages, adapted from [Tom Monks jackson-network repository](https://github.com/TomMonks/jackson-network).

A Jackson Queuing Network can be used to model a system with multiple service points (e.g. wards) where patients can queue and receive treatment (e.g. different wards in a hospital), and move between service points probabilistically. It assumes [Poisson arrivals and exponential service times](https://github.com/TomMonks/jackson-network/blob/main/arrival_and_service_patterns.ipynb), and a stable system, meaning it can handle the demand on the system without queue lengths growing indefinitely. 

Deploying the model to JupyterLite allows it to be reparameterised with ease. JupyterLite supports uploading files from your local machine to the browser’s local storage. This can be achieved by dragging and dropping files from your local machine to the file browser, or by using the `Upload` button in the file browser.

This is useful for example when you want to upload a dataset to use in a notebook, like a CSV file.

However note that the browser’s local storage has a limited capacity, and you might not be able to upload large files. But smaller files up to ~50MB should be fine.

<hr>

## ✨ Try it in your browser ✨

➡️ **https://pythonhealthdatascience.github.io/jackson-network-jupyterlite/**

Code can be changed and run in the browser. Changes will persist in the browser cache until it is cleared. 

<hr>

## Further Information and Updates from JupyterLite

For more info, keep an eye on the JupyterLite documentation:

- How-to Guides: https://jupyterlite.readthedocs.io/en/latest/howto/index.html
- Reference: https://jupyterlite.readthedocs.io/en/latest/reference/index.html
