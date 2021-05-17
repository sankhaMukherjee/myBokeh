

# Create a server

To serve this model, run the command:

```
bokeh serve --show {{cookiecutter.package_name}}
```

Remember to be outside of the folder to serve the model.

# Minimum requirements

For running the code, create a virtual environment  outside the 
newly created folder {{cookiecutter.package_name}}, and install
Bokeh with the following commands:


```
python3 -m venv env 
source env/bin/activate
pip3 install --upgrade  pip
pip3 install bokeh
```