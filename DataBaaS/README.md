# DataBaas

Deze directory bevat een inzending voor de DataBaas blog.

# Installatie

Installeer de benodigde dependencies in een python 3.9 omgeving met:

`pip install -r requirments.txt`

De blog kan vervolgens geopend worden met de juiste kernel in jupyterlab.

# Markdown genereren

Convert het notebook naar markdown door:
`jupyter nbconvert --to markdown gg_in_python_altair.ipynb --config nbconvert_config.json`