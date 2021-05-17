# myBokeh

A cookiecutter template for creating bokeh visualizations
quickly. This template is supposed to be used within other
projects so this does not come with installers and so on.

It is assumed that one already has bokeh installed in the
current virtual environment and is using this only as a
starting point for your own boken visualizaitons.

This boken server is not intended to be an industrial-grade
server.

## Getting Started

Make sure that you have cookiecutter installed on your system.

```
pip3 install -U cookiecutter
```

Now generate a python package uisng the cookiecutter template

```
cookiecutter https://github.com/sankhaMukherjee/myBokeh
```

and follow along the instructions. You will only need to provide
information about the name of the project.

### Create a server

Once a project with name `name` has been created, use the command

```
bokeh serve --show `name`
```

to serve the model. Remember to be outside of the folder to
serve the model.

## Minimum requirements

For running the code, create a virtual environment and install
the following libraries:

```
python3 -m venv env 
source env/bin/activate
pip3 install --upgrade  pip
pip3 install bokeh
```