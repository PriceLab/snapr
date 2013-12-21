# SNAPR

Scalable Nucleotide Alignment Program RNA-seq - <http://pricelab.systemsbiology.net/SNAPR>

## Overview

We present SNAPR, a new method for RNA-seq analysis, optimized for hundreds or even thousands of RNA-seq libraries. SNAPR reads from and writes to BAM format, automatically generates read counts, and accurately identifies viral/bacterial infections and gene fusions.

## Documentation

A quick start guide and user manual are available in the `docs` folder, with
additional documentation at <http://pricelab.systemsbiology.net/SNAPR>.

## Building

SNAPR runs on Windows, Linux and Mac OS X.

For Windows, we provide a Visual C++ project, `snap.sln`. Requirements:
- Visual Studio 2012 (11.0)

For Linux and OS X, simply type `make`. Requirements:
- g++ version 4.6
- zlib 1.2.8 from http://zlib.net/


