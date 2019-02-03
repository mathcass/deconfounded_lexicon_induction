# Deconfounded Lexicon Induction

This repo contains code for the paper, "Deconfounded Lexicon Induction for Interpretable Social Science".

You can read the paper [here](https://nlp.stanford.edu/pubs/pryzant2018lexicon.pdf). It outlines the algorithms implemented in this repo.

The project website is [here](https://nlp.stanford.edu/projects/deconfounded-lexicon-induction/).

## Installation

`pip install -r requirements.txt`

## Usage

`python main.py --config sample_config.yaml [--train] [--test]`

Logs, models, features, and summary files will be written in the config's `working_dir`. See `sample_config.yaml` for an example config and explanation. 

## Python 3 Port

This code has been run through a process to convert it from Python 2 to Python 3.
