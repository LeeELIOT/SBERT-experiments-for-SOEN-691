# Replication Package: Applications of LLMs in Duplicate Bug Report Detection

This repository contains the code, datasets, and experimental setups to replicate the results from the paper **"Applications of LLMs in Duplicate Bug Report Detection"** by Hongwu Li and Elieen Fu. The study evaluates the effectiveness of fine-tuned SBERT models for detecting duplicate bug reports and compares them with traditional and deep learning methods.

---

## Abstract
Bug report deduplication is critical for efficient software maintenance, as duplicates waste developer resources. This work explores how fine-tuning techniques (learning rate optimization, adapter tuning, and layer-specific tuning) improve SBERT's ability to detect subtle semantic similarities in bug reports. Experiments across five open-source projects (Eclipse, JDT, Firefox, Thunderbird, Mozilla) demonstrate that SBERT outperforms traditional methods by leveraging semantic understanding, achieving robust recall and F2-scores.

---

## Installation
### Dependencies
- Python 3.8+
- PyTorch 2.0+
- Sentence-transformers
- Scikit-learn, Pandas, NumPy

### Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/LeeELIOT/SBERT-experiments-for-SOEN-691.git]
   
2. Install packages:
   pip commands for required packages are already contained in 'preprocessing' file.

## Results
All the results are archived in 'result' folder, which includes all experiments and evaluation pictures for different fine-tuning techniques.

## Acknowledgements

This work was conducted as part of the course project for **SOEN 691 - Advanced Topics in Software Engineering** at **Concordia University**.

Gratefully acknowledge the support from:

- The **Speed High Performance Computing (HPC)** infrastructure for providing compute resources  
- The maintainers of the [BugRepo](https://github.com/logpai/bughub) dataset

Special thanks to Prof. Diego Elias Damasceno Costa who provided feedback and guidance during the research process.
