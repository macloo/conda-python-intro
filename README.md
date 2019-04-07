# Conda Python Intro

I had two weeks to introduce Python to several communications grad students who might not ever do any data science work, but they bravely wanted to learn some Python.

## Day 1

First, we did a small install with **Miniconda** and **Jupyter Notebook**:

[Install Python 3.x, Miniconda, and Jupyter Notebook](http://bit.ly/mm-conda)

I got the students started with a blank Notebook in one 50-minute class period.

We did some basic `print()` statements and variable exercises briefly in that first Notebook, saved, and closed out of Jupyter.

## Day 2

Two days later, the students:

1. Saw this [slide deck](http://bit.ly/python-intro2-slides),
2. Played briefly in the Python interpreter,
3. Ran [a little script](tiny_script.py) from a file, and
4. Downloaded a Jupyter Notebook with 12 beginner problems to solve (some problems are just making variables and using math operators) &mdash; that Notebook is *not* online. They had two days to solve the problems and turn them in for a grade.

The 12 beginner problems are based on the outlines [at the end of the README here](https://github.com/macloo/python-beginners/tree/master/week01).

## Day 3

Then I got ambitious in Week 2.

I wanted them to have an experience of scraping with **BeautifulSoup** *and also* an experience using **Pandas**, so I made two Notebooks, and we walked through them in class. You'll find them in this repo.

The first Notebook covers [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/), a Python library for scraping data from websites. We use a Wikipedia page (even though there is an awesome [Python wrapper for the Wikipedia API](https://pypi.org/project/Wikipedia-API/)) because it's an easy first example for scraping.

[scraping_practice_BLANK.ipynb](scraping_practice_BLANK.ipynb)

To run that Notebook, you'll need to install these (in addition to Jupyter Notebook):

* BeautifulSoup4 (`conda install beautifulsoup4`)
* Requests (`conda install requests`)

## Day 4

The second Notebook covers [Pandas](https://pandas.pydata.org/), a Python library for analyzing data. This beginner exercise is based largely on a workshop led by [Lam Thuy Vo](https://github.com/lamthuyvo) at NICAR19, with some additions from an online course called [Python for Journalists](https://datajournalism.com/watch/python-for-journalists/).

[pandas_practice_BLANK.ipynb](pandas_practice_BLANK.ipynb)

To run that Notebook, you'll need to install this (in addition to Jupyter Notebook):

* Pandas  (`conda install pandas`)
