Intro to Python Workshop
------------------------

This a rough outline for the MEMpy + FIT "Intro to Python Workshop", held on
Jan 23, 2017.  Data found in `data` came from [catalog.data.gov](https://catalog.data.gov/),
and all code in `src` is available under an MIT license (see the `LICENSE.txt` file).


## About Python

- A little history
- Python 2 or 3?  (choose 3 if you can).
- Runs: Windows, Mac OS, Linux
- Community (forums, email lists, meetups, conferences, and more)
- Check out [python.org](https://www.python.org/)

## Programming Environment

There are several ways you can use python. Any of these are acceptable for this
workshop:

1. [Download python](https://www.python.org/downloads/) for your system (if you've
   got Mac OS or Linux, you may already have python!).
2. Log in to a remote system and type `python` (e.g. if you have access to a Linux server).
3. Use an [Azure Notebook](https://notebooks.azure.com/) (login with your microsoft account).
4. You may access a temporary notebook at [notebook.brad.tips](http://notebook.brad.tips).

- The command line
- Virtual Environments
- Idle or a REPL
- Jupyter Notebook

## Part 1: Exploratory Programming

Data Structures.

- integers and floats
- strings
- comments
- comparisons / exceptions
- lists / tuples
- dictionaries

Iterating.

- for loops
- while loops
- list comprehensions

Modules and Packages.

- what is a module
- importing stuff
- The standard library
- Installing Packages

Neat tools from the Standard Lib.

- csv
- collections
- statistics


## Part 2: Simple data analysis (reading CSV files)

There's lots of neat data sets at [catalog.data.gov](https://catalog.data.gov/dataset?res_format=CSV).

Interesting data sets include:

- (~4Mb) [US Electirc Utility Rates](https://catalog.data.gov/dataset/u-s-electric-utility-companies-and-rates-look-up-by-zipcode-feb-2011-57a7c)
- (~356Mb) [Traffic Violations](https://catalog.data.gov/dataset/traffic-violations-56dda). There's a 1000-record subset of this data set in the `data` directory.

Or you can go find your own! (See an examlpe of how I [analyzed the St.Jude Memphis marathon](https://github.com/bradmontgomery/st-jude-marathon/)).


## Part 3: APIs

We'll grab some some data from iTunes.


## Additional resources

The following are books or other resources that I like (and would recommend)!

- [Think Python](http://greenteapress.com/wp/think-python/)
- [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/)
- The official [Python Tutorial](https://docs.python.org/3/tutorial/)
