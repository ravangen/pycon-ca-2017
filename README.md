# Structured logging in Python

A Jupyter notebook with sample code that can be output to a presentation powered by [reveal.js](https://github.com/hakimel/reveal.js). 

## Requirements
- [Jupyter](http://jupyter.org/install.html): `python3 -m pip install jupyter`

## Open Notebook
- `jupyter notebook --ip=127.0.0.1 --port 8888`

## Presentation
### Requirements
- `cp custom.css reveal.js/custom.css`
- `cd reveal.js`
- `npm install`

### Generate Slides
- `jupyter nbconvert Structured_Logging.ipynb --template=jupyter_template.tpl --to slides --reveal-prefix='' --output-dir='./reveal.js'`

### Run Notes Server
- `cd reveal.js`
- `npm run start`
- `open http://localhost:8000/Structured_Logging.slides.html`
