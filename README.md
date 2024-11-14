# Sequence Analysis

This repository contains various bioinformatics analyses on a FASTA sequence file, `SRR_001.fasta`, performed using Python and Jupyter notebooks. The project includes sequence length distribution, GC content distribution, nucleotide composition, K-mer analysis, and ORF prediction on both forward and reverse strands. 

## Repository Structure

- **SRR_001.fasta**: The input FASTA file containing nucleotide sequences for analysis.
- **sequence_analysis.ipynb**: A Jupyter notebook that performs the following analyses:
  - Sequence Length Distribution
  - GC Content Distribution
  - Nucleotide Composition per Sequence
  - K-mer Analysis
- **orf_prediction.ipynb**: A Jupyter notebook that predicts Open Reading Frames (ORFs) on both the forward and reverse strands of the input sequences.

## Features

- **Sequence Length Distribution**: Visualizes the distribution of sequence lengths in the FASTA file.
- **GC Content Distribution**: Plots the GC content distribution across all sequences, providing insights into sequence composition.
- **Nucleotide Composition**: Analyzes the percentage composition of nucleotides (A, T, G, C) in each sequence.
- **K-mer Analysis**: Performs a K-mer analysis (default K=6) to identify repeated nucleotide sequences of length K.
- **ORF Prediction**: Uses the Biopython library to predict Open Reading Frames (ORFs) on both the forward and reverse strands.

## Installation and Setup

To run the analysis on your local machine, follow these steps:

### Prerequisites

Ensure that you have the following Python libraries installed:
- `biopython`
- `matplotlib`
- `numpy`
- `pandas`

You can install these dependencies via pip:

```bash
pip install biopython matplotlib numpy pandas
