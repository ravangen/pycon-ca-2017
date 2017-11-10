# Structured logging in Python

A Jupyter notebook with sample code that can be output to a presentation powered by [reveal.js](https://github.com/hakimel/reveal.js). 

## Requirements
- [Jupyter](http://jupyter.org/install.html): `python3 -m pip install jupyter`

## Open Notebook
- `jupyter notebook --ip=127.0.0.1 --port 8888`

## Generate and Serve Slides
- `jupyter nbconvert Structured_Logging.ipynb  --Exporter.template_file=jupyter_template --to slides --post serve`
