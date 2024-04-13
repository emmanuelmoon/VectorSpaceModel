# Proximity and Boolean Query Search

This is a Python project for forming a Vector Space Model and running queries on it.

## File structure

The included files are:
1. preprocessing.ipynb
2. query.ipynb
3. tdm.pkl
4. dic_map.pkl
5. doc_map.pkl

Run preprocessing.ipynb first if you want to preprocess from scratch. query.ipynb is for running queries in GUI

## Installation
You need to clone to the directory. Make to sure to clone the ".pkl" file as they contain the data including term-document matrix, and mapping for documents and 
dictionary terms.
You need a recent version of Python which should include:
- tkinter
- pickle
- re
- nltk
- numpy

All packages except nltk come by default in the latest python versions.
I've added a cell in the python notebook to install nltk.

```bash
pip install nltk
```

## Running queries

In order to perform search.
1. Run the "query.ipynb" in a jupyter notebook environment
2. Run all cells from top to bottom for it to work.
3. Add queries in the input box and press the button.
