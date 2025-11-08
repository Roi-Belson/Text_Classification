# Text_Classification

## Overview  
This repository implements text classification tasks using machine‑learning and deep‑learning models. It includes experiments on the IMDB movie‑reviews dataset and news article categorization, demonstrates model training, evaluation and deployment of a trained model.

## Contents  
- `Text_Classification.ipynb` – A Jupyter notebook for classic machine‑learning text classification (e.g., using TF‑IDF + MLP / other models).  
- `Text_Classification_Deep_Learning.ipynb` – A Jupyter notebook for deep‑learning based text classification (e.g., using Keras/TensorFlow).  
- `imdb‑dataset‑of‑50k‑movie‑reviews.csv` – The IMDB dataset of 50k movie reviews used in one of the notebooks.  
- `my_text_mlp_model.h5` – A trained deep‑learning model (in Keras H5 format) saved for inference/production use.  
- `valurank_News_Articles_Categorization.csv` – A dataset of news‑articles used for categorization experiments.  
- `.gitattributes` – File tracking large files (if applicable).  

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
2. (Optional) Create and activate a virtual environment:  
   ```bash
   python ‑m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```  
3. Install dependencies:  
   ```bash
   pip install ‑r requirements.txt
   ```  
   *(If you don’t have a `requirements.txt`, you can install at least: `numpy pandas scikit‑learn tensorflow keras jupyter`.)*

## Usage  
- Open `Text_Classification.ipynb` for classic ML workflows: data loading → preprocessing → feature extraction → model training → evaluation.  
- Open `Text_Classification_Deep_Learning.ipynb` for deep‑learning workflows: constructing a Keras model, training, saving (`my_text_mlp_model.h5`), and evaluating.  
- To use the trained model for inference, load `my_text_mlp_model.h5` in a Python script or notebook and run `model.predict(...)` on new text inputs.

## Datasets  
- **IMDB Movie Reviews**: `imdb‑dataset‑of‑50k‑movie‑reviews.csv` — 50 000 labeled movie reviews (positive/negative) used for binary text classification.  
- **News Articles Categorization**: `valurank_News_Articles_Categorization.csv` — A dataset of news articles for classification into multiple categories.

## Model  
A deep‑learning model saved in `my_text_mlp_model.h5`. Use this for inference or fine‑tuning on your own data.

## Contributing  
Feel free to fork and submit pull requests. Suggestions and improvements are welcome — whether it’s adding new classification algorithms, improving preprocessing, or extending to additional datasets.

## License  
This project is distributed under the MIT License. See the `LICENSE` file (or include one) for details.
