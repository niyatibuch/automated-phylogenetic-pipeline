# Automated Phylogenetic Pipeline

Python-based automated framework for phylogenetic tree construction, visualization, and comparative statistical evaluation.

## Overview

This pipeline integrates multiple sequence alignment, phylogenetic tree inference, visualization, and comparative statistical analysis into a reproducible workflow.

## Features

### Multiple Sequence Alignment
- MAFFT
- MUSCLE
- ClustalW

### Tree Inference
- Maximum Likelihood (IQ-TREE)
- Neighbor Joining (NJ)
- UPGMA
- Maximum Parsimony (MP)

### Comparative Analysis
- Robinson–Foulds distance
- Approximately Unbiased (AU) test
- Kishino–Hasegawa (KH) test
- Shimodaira–Hasegawa (SH) test

## Environment

- Python 3.10+
- Developed and tested using Google Colab
- Google Drive used for persistent storage and resume functionality

## Installation

Clone repository:

```bash
git clone https://github.com/JanviJPatel30/Automated-Phylogenetic-Pipeline.git
cd Automated-Phylogenetic-Pipeline
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Repository Structure

```text
src/          → pipeline source code
datasets/     → input datasets
outputs/      → generated outputs
figures/      → manuscript figures
docs/         → manuscript and supplementary files
```

## Citation

If you use this repository, please cite the associated manuscript.

## License

MIT License
