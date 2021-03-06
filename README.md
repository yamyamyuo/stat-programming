# Statistical Programming

This repo collects notes and Python implementations of various statistic
algorithms. Contents are derived from the class notes of STATS 202A at UCLA
instructed by Professor Yingnian Wu.
I am one of the students who authored the code used in class.

## Table of contents

* Linear regression
    - Sweep operator
    - QR decomposition
* Principle component analysis
* Logistic regression
* Neural network
* SVM
* AdaBoost
* Regularization
    - Ridge regression
    - LASSO
* Factor Analysis
* Monte Carlo Methods

## How to view the notes?

To view online: http://nbviewer.ipython.org/github/hang-qi/stat-programming/tree/master/

To run it locally, start ipython notebook after you clone the repo.

    ipython notebook

## Why IPython Notebook?

IPython Notebook is a awesome tool for mixing contents and executable codes in
one single note. Even better, Markdown and LaTeX syntax is supported.
It is particular useful here because the contents are derived from lectures.
Apart from the implementations, I also include contents describing algorithms
and the applications.

## Are these implementations efficient?

Not necessarily at this point.
In fact, efficient implementations of many of these fundamentals algorithms
are packed in linear algebra routines like LAPACK and BLAS.
The main purpose here is to introduce the idea behind these algorithms
and address applications.
