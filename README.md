# Autism Gene Classification with XAI

This project uses gene expression data and applies machine learning models (Random Forest, XGBoost, etc.) along with Explainable AI techniques (LIME, SHAP) to prioritize ASD risk genes.

## Features
- Gene expression analysis
- Classification using ML models
- Model explainability with LIME & SHAP
- Performance evaluation with metrics like AUC, MCC, F1-score, etc.
## Usage
To run the model and reproduce the results:

1. Open the notebook in Jupyter:
```bash 
 Autism_with_XAI.ipynb
```
2. Run all the cells to train the models and generate explainability plots (LIME, SHAP).
If you want to view the outputs (including all generated plots) without running the code, you can open the pre-rendered notebook:
    - Autism_with_XAI.html
You can view it directly in a browser.
## Requirements
Install required packages:
```bash
pip install -r requirements.txt
```
File Structure
``` bash

├── Autism_with_XAI.ipynb      # Main notebook (code + markdown)
├── Autism_with_XAI.html       # Notebook with outputs (for viewing)
├── requirements.txt           # Python dependencies
├── README.md                  # Project overview and usage guide
```
## 👩‍🔬 Author
**Shehla Rafiq**

## 📄 How to Cite
If you find this repository or the associated work useful, please cite:

Rafiq, S., Assad, A.  
*Random forest and explainable AI for autism gene prioritization: a machine learning approach to developmental brain data.*  
International Journal of Developmental Disabilities, 2025.  
https://doi.org/10.1080/20473869.2025.2590001

### BibTeX
```bibtex
@article{Rafiq2025AutismXAI,
  title   = {Random forest and explainable AI for autism gene prioritization: a machine learning approach to developmental brain data},
  author  = {Rafiq, Shehla and Assad, Assif},
  journal = {International Journal of Developmental Disabilities},
  year    = {2025},
  doi     = {10.1080/20473869.2025.2590001}
}

