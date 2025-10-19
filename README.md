# Flask Boilerplate

This repository is a collection of everything needed to get off the ground with Flask.

## Get Going Quickly

To get going with this repo and get developing I recommend:

1 - create or login to your own github account

2 - using the `Use this template` dropdown in Github click `Open in a codespace` to edit and run a remote instance of this repo

3 - fork this repo (optional but means you can store any changes you make)

## Tools Used

- Flask - python web framework that provides functions to make developing a web application easier.
- Anaconda - python framework used to define a specific set of packages and dependencies to make the apps environment.
- Docker - containerises software needed for creating a development environment and packages up the app.
- Codespaces - allows quick development without needing to install anything locally.

## Nuts and Bolts

Each aspect of the development and deployment cycle is in this repo, these include:

- `src` - the source code directory. This has a few snippets of code for simple Flask services (including templates using Jinja2)
- `Dockerfile` - everything needed to spin up the mini Anaconda environment (using Mamba) and containerise the app for deployment.
- `environment.yaml` - all the packages needed to make the right Anaconda environment ANYWHERE.
- `.gitignore` - a list of everything you don't want in version control.
- `.devcontainer` - all the config and setup needed to allow development using Codespaces (and probably VSCode locally but that's currently untested).
