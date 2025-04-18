# Improving-Interpretability-Explainability-and-Robustness-of-X-Transformer

Enhancing X-Transformer for extreme multi-label classification (XML) with interpretability features and robustness against adversarial attacks.

## Project Structure
├── xtransformer-explain-robust/ <br>
│ ├── xtf-explain-robust-bibtex.ipynb *(BibTeX dataset implementation)* <br>
│ ├── xtf-explain-robust-delicious.ipynb *(Delicious dataset implementation)* <br>
│ ├── xtf-explain-robust-mediamill.ipynb *(MediaMill dataset implementation)* <br>
│ └── requirements.txt *(Python dependencies)* <br>
├── Improving Interpretability, Explainability and Robustness of X-Transformer.pdf *(project report)* <br>
└── README.md <br>

## Features
- **Interpretability**:
  - Attention visualization for label predictions
  - LIME-based explanations for multi-label decisions
- **Adversarial Robustness**:
  - Defense against HopSkipJump and ZOO attacks
  - Synonym-based adversarial training
- **Datasets**:
  - BibTeX (academic publications)
  - MediaMill (video annotations)  
  - Delicious (web bookmarks)

## Install dependencies
bash 
```
pip install -r requirements.txt
```
## Download datasets
Use http://manikvarma.org/downloads/XC/XMLRepository.html to download datasets. <br>
Use scikit-multilearn to get datasets

## Usage
Running Notebooks
bash
```
jupyter notebook xtransformer-explain-robust/xtf-explain-robust-bibtex.ipynb
```
Key steps in each notebook: <br>
	&emsp; Dataset preparation <br>
	&emsp; Base X-Transformer training <br>
	&emsp; Adversarial sample generation <br>
	&emsp; Robust model training <br>
	&emsp; Evaluation (precision@k, nDCG, attack success rate) <br>

## Requirements
Key dependencies (see requirements.txt for complete list)

