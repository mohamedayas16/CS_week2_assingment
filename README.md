# Semester II - Computational Science Project

This project contains computational analysis scripts and documentation for the course assignments which include the actual datas and reports in lab at FCFM, UANL.

## Repository Structure

```text
├── data/          # Input datasets and generated data
├── docs/          # Reports, TeX documentation, and notes
│   └── report.tex # Main assignment report
├── src/           # Source code and computational scripts
│   └── analysis.py# Core analysis script
├── .gitignore     # Git ignore rules
└── README.md      # Project overview and reproduction instructions
```

## Getting Started & Reproduction Instructions

Follow these steps to reproduce the environment and run the analysis on a clean machine:

### 1. Prerequisites
* **Python 3.8+**
* Required packages:
  ```bash
  pip install numpy matplotlib scipy
  ```
### 2. Clone the repository
  ```bash
  git clone https://github.com/mohamedayas16/CS_week2_assingment.git
  cd CS_week2_assingment
  ```
### 3. Run the computational analysis script
```bash
python src/analysis.py
```
### 4. Compile the report
```bash
pdflatex docs/report.tex
```
## HOW to Cite
```bibtex
@misc{computational_science_2026,
  author = {Mohamed Ayas Mohamed Kasim},
  title = {Semester II - Computational Science Project Repository},
  year = {2026},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/mohamedayas16/CS_week2_assingment}}
}
```
