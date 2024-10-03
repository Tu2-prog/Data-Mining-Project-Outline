# Data-Mining-Project-Outline

03.10.2024

This repository contains the LaTex code for the Data Mining Project Outline of HWS24.

## Prerequisites

You need to have **bibtex** and **pdflatex** installed.

## Quickstart

The LaTex document can be compiled with:

```bash
pdflatex thesis.tex
```

When a new bibitem is added to the *references.bib* file then one needs to execute this sequence of commands to get a coherent report with corresponding citations:

```bash
pdflatex thesis.tex
bibtex thesis.aux
pdflatex thesis.tex
pdflatex thesis.tex # for some reason I need to compile it multiple times like this, but this does not need to be the case for you 
```