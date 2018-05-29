run_process_tut_bibtex.py is a simple script that creates network representations of
bibliographical data in BibTeX.

The script was developed for an exploratory Design Science Research experiment
on using visual social network analytics for actionable insights on
co-authorship networks.

Paper details:

Huhtamäki, J. (2016). Visualizing Co-authorship Networks for Actionable Insights: Action Design Research Experiment. In Proceedings of 20th International Academic Mindtrek Conference, October 17- 19, 2016, Tampere, Finland (pp. 208–215). http://doi.org/10.1145/2994310.2994340

An [open access copy of the article](http://urn.fi/URN:NBN:fi:tty-201610244630) is available through TUT Research Portal.

## Getting ready

Create virtual environment:

	python3 -m venv VENV

Activate the virtual environment:

	source VENV/bin/activate

Install the needed packages

	pip install -r requirements.txt 

Create folders

	data
	data/01-source
	data/03-network

Search and put the data in place

	data/01-source/search.bib

Run

	python run_process_tut_bibtex.py 	
	

## Meta

Author: Jukka Huhtamäki ([@jnkka](https://twitter.com/jnkka))
License: MIT
