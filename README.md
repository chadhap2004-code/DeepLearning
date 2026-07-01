#Medical Triage Classification using Deep Learning

## Project Overview

This project classifies medical text into different medical specialties using Natural Language Processing (NLP) and Deep Learning.

Two different medical datasets are combined and preprocessed to create a larger dataset. Two deep learning models are trained and compared:

- BiLSTM + GloVe Embeddings
- BioBERT (Fine-Tuned)

The project compares both models based on Accuracy, Macro F1 Score, Classification Report, and Confusion Matrix.

---

## Features

- Medical text preprocessing
- Exploratory Data Analysis (EDA)
- Dataset merging
- Text cleaning
- Label encoding
- BiLSTM model with GloVe embeddings
- Fine-tuned BioBERT model
- Model comparison
- Interactive prediction interface
- Save trained model

---

## Dataset

This project uses two datasets.

### Dataset 1

- mtsamples.csv
- Included in this repository.

### Dataset 2

The second dataset is too large to upload to GitHub.

Download it from:

Google Drive Link:
https://drive.google.com/file/d/1rw7MPXkVbGifYTWnoPCbCwGzrA2o2gnk/view?usp=sharing

After downloading, place it inside:

data/

or update the notebook path accordingly.

---

## Technologies Used

- Python
- PyTorch
- Transformers (HuggingFace)
- BioBERT
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Project Workflow

1. Load datasets
2. Clean and preprocess text
3. Merge datasets
4. Select Top 10 medical specialties
5. Train BiLSTM
6. Fine-tune BioBERT
7. Evaluate both models
8. Compare results
9. Save trained models

---

## Results

The project compares:

- Test Accuracy
- Macro F1 Score
- Confusion Matrix
- Classification Report
- Training Curves


BioBERT achieved better performance than the BiLSTM model.

## Project Structure

```
Medical-Triage-Classification/
│── README.md
│── medical_triage.ipynb
│── mtsamples.csv
│── images/
└
```


---
## Future Improvements

- Improve classification accuracy using larger medical datasets.
- Expand the model to support more medical specialties.
- Deploy the model as a web application for real-time predictions.
- Optimize the model for faster inference.

---

## Author

**Palak Chadha**

B.E. Student   
Thapar Institute of Engineering and Technology


