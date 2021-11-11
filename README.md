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

If you have ez installed and configured, all you need to do to run the repo 
is:

`ez env go -g https://github.com/jflam/data-science`

If you want to be able to edit the files, you should first fork the repo into
your GitHub account and use this command:

`ez env go -g git@github.com:<your user id>/data-science`
