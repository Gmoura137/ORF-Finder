# ORF Finder in Python

## Overview

This project is a Python-based Open Reading Frame (ORF) Finder designed to analyze DNA sequences and identify potential protein-coding regions.

The program:
- Validates DNA input sequences
- Generates all six reading frames
- Searches for ORFs using start and stop codons
- Translates ORFs into amino acid sequences
- Displays ORF lengths

---

## What is an ORF?

An **Open Reading Frame (ORF)** is a stretch of DNA that:

1. Starts with a start codon: `ATG`
2. Continues in groups of three nucleotides (codons)
3. Ends with a stop codon:
   - `TAA`
   - `TAG`
   - `TGA`

ORFs often represent genes that can produce proteins.

---

## Features

✅ DNA sequence validation  
✅ Reverse complement generation  
✅ Six reading frame analysis  
✅ ORF detection  
✅ DNA to protein translation  
✅ Beginner-friendly code structure

---

## Reading Frames

DNA can be read in six possible frames:

### Forward Strand
- Frame 1 → starts at position 0
- Frame 2 → starts at position 1
- Frame 3 → starts at position 2

### Reverse Complement Strand
- Frame 4 → reverse frame starting at 0
- Frame 5 → reverse frame starting at 1
- Frame 6 → reverse frame starting at 2

---

## How to Run

### Requirements

- Python 3.9 or higher

### Run the Program

```bash
python orf_finder.py
