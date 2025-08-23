![Sismis logo](./assets/sismis_logo_purple.svg)

# Sismis
Machine learning-based secretion system annotation tool

# 🦇 Overview

Sismis (<ins>s</ins>ecret<ins>i</ins>on <ins>s</ins>yste<ins>m</ins> d<ins>is</ins>covery tool; pronounced *shish-mish*) is a machine learning (ML)-based tool for detecting and classifying secretion systems in prokaryotic (meta)genomes.

# 🔍 Quickstart

To detect secretion systems in an assembled prokaryotic (meta)genome:
```
sismis run -g [fasta] -o [output directory] [options...]
``` 

For help/to view all options:
```
sismis -h
```

# 🔧 Installation

Sismis and its dependencies can be installed via `pip`:
```
pip install sismis
```

# ⚙️  Usage and options

## Command structure

```
sismis run -g [fasta] -o [output directory] [options...]
``` 

## Required arguments

```
    -g <file>, --genome <file>    a genomic file containing one or more
                                  sequences to use as input. Must be in
                                  one of the sequences format supported
                                  by Biopython.
```
