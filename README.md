# Text_Classification

## Overview  
This repository implements text classification tasks using machine‑learning and deep‑learning models. It includes experiments on the IMDB movie‑reviews dataset and news article categorization, demonstrates model training, evaluation and deployment of a trained model.

## Contents  
- `Text_Classification.ipynb` – A Jupyter notebook for classic machine‑learning text classification, performing sentiment analysis of the IMDB corpus by vectorizing the text with Tf-idf and training a logistic regression model. 
	 - I also demonstrate the supremacy of the regression over nltk built in vader sentiment intensity analyzer 
- `Text_Classification_Deep_Learning.ipynb` – A Jupyter notebook using a feed forward network to classify the categories of a news articles corpus.   
- `imdb‑dataset‑of‑50k‑movie‑reviews.csv` – The IMDB dataset of 50k movie reviews used in one of the notebooks.  
- `my_text_mlp_model.h5` – A trained deep‑learning model (in Keras H5 format) saved for inference/production use.  
- `valurank_News_Articles_Categorization.csv` – A dataset of news‑articles used for categorization experiments.  

## Getting Started

### Prerequisites  
Make sure you have:  
- Python 3.7+ installed.  
- Jupyter Notebook or JupyterLab.  
- Required Python libraries installed (for example: `numpy`, `pandas`, `scikit‑learn`, `tensorflow`, `keras`, etc).  

### Installation  
1. Clone this repository:  
   ```bash
   git clone https://github.com/Roi‑Belson/Text_Classification.git
   cd Text_Classification
   ```  
2. Install dependencies:  
   ```bash
   pip install ‑r requirements.txt
   ```  

## Datasets  
- **IMDB Movie Reviews**: `imdb‑dataset‑of‑50k‑movie‑reviews.csv` — 50 000 labeled movie reviews (positive/negative) used for binary text classification.  
- **News Articles Categorization**: `valurank_News_Articles_Categorization.csv` — A dataset of news articles for classification into multiple categories.
