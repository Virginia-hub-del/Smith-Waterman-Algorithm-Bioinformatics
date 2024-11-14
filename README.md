# Smith-Waterman Algorithm for Sequence Alignment

This project implements the Smith-Waterman algorithm for local sequence alignment, specifically for nucleotide and protein sequences. The program performs the alignment of two input sequences and provides all alignments that satisfy the following conditions:

1. At least one occurrence of at least 3 consecutive matches.
2. Score >= 60% of the maximum scoring alignment.

## Requirements
- Python 3.x
- NumPy

## Usage
Run the program with the following command:

```bash
python smith_waterman.py <seq1> <seq2> [-m <match_score>] [-x <mismatch_penalty>] [-g <gap_penalty>]
