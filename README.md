# Matched Filtering for Gravitational Wave Detection  

This repository contains the code, data, and report for a project that demonstrates matched filtering techniques used in gravitational wave detection. The analysis identifies a binary black hole (BBH) system, estimates component masses, and evaluates the signal match using the optimal matched filter.  

## Repository Contents  

- **`det2.gwf`**  
  Gravitational wave strain data used in the analysis.  

- **`match_filtering.ipynb`**  
  Jupyter notebook containing the complete analysis pipeline, including preprocessing, matched filtering, and visualization.  

- **`match_filtering_code.pdf`**  
  A PDF version of the analysis notebook, for easier sharing and review.  

- **`plots/`**  
  Directory containing all plots generated during the analysis. These are referenced in the report.  

- **`results_coarse.csv`**  
  Results of the coarse search over the mass parameter space.  

- **`results_fine.csv`**  
  Results of the fine search over the mass parameter space.  

- **`report.tex`**  
  LaTeX source file for the final report.  

- **`report.pdf`**  
  Final report describing the analysis, results, and conclusions.  

- **`requirements.txt`**  
  List of Python dependencies required to run the analysis.  

- **`README.md`**  
  This file, providing an overview of the repository and instructions.  

## Getting Started  

### Prerequisites  

Ensure you have Python (3.8 or newer) and the necessary dependencies installed. You can install the required packages using:  
```bash  
pip install -r requirements.txt  
