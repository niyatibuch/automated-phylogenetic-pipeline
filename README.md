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

## Repository Structure

```text
src/          → pipeline source code
datasets/     → input datasets
outputs/      → generated outputs
figures/      → manuscript figures
docs/         → manuscript and supplementary files
```

## License

MIT License

## Related Repository

This repository extends previous work available at:

https://github.com/JanviJPatel30/PhylogeneticPipeline

The present repository provides the integrated and reproducible framework used in the associated manuscript, including workflow organization, comparative evaluation, and reproducibility components.
