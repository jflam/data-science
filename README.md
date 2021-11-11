# Data Science Golden Path

The notebook in this repo creates a number of different models using the
well-known Titanic dataset. It builds models using both `scikit-learn` and
`tensorflow`, and uses GPU acceleration if available.

It demonstrates the use of a number of different data visualization tools,
including `pandas-profiling` and `graphviz`. 

The repo has 3 additional files: `ez.json`, `build/Dockerfile`, and 
`build/requirements.txt` that instruct the [ez](https://github.com/jflam/ez)
CLI on how to provision a VM to run this repo. The Dockerfile builds on top
of the `tensorflow/tensorflow` image on DockerHub, and installs a few 
additional packages described in `requirements.txt`.