**Quora Question Pair Classifier**

---

## Overview:

This Streamlit app is designed to predict whether pairs of questions from the Quora dataset are duplicates or not. The underlying model utilizes machine learning and natural language processing (NLP) techniques to achieve this task. The model has been trained on the Quora Question Pairs dataset available on Kaggle, achieving an accuracy of 78%.

---

## Features:

- **Input Interface:** Users can input two questions into the app and get predictions on whether they are duplicates or not.
  
- **Prediction:** Upon submission, the app displays whether the questions are predicted to be duplicates or not.
  
- **Accuracy:** The app showcases the accuracy of the underlying model based on the training data.
  
---

## How to Use:

1. **Input Questions:** Enter two questions into the provided text input boxes.
  
2. **Submit:** Click on the "Submit" button to get the prediction.
  
3. **View Result:** The app will display whether the questions are predicted to be duplicates or not.
  
---

## Model Details:

- **Algorithm:** The model employs machine learning algorithms coupled with NLP techniques to classify question pairs.
  
- **Accuracy:** Achieved an accuracy of 78% on the Quora Question Pairs dataset.
  
- **Training Data:** The model was trained on the competition dataset available on Kaggle.
  
---

## Requirements:

- Python 3.x
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- NLTK (Natural Language Toolkit)
- Word Embeddings (e.g., Word2Vec, GloVe)

---

## Installation:

1. Clone this repository:

```
https://github.com/tushargandhi77/Quora_Question_pair.git
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```

3. Run the Streamlit app:

```
streamlit run app.py
```

---
##Screenshot
![Screenshot 2024-04-22 142952](https://github.com/tushargandhi77/Quora_Question_pair/assets/104029815/478e3672-cfb4-4990-b744-0db334fc65f2)
![Screenshot 2024-04-22 143022](https://github.com/tushargandhi77/Quora_Question_pair/assets/104029815/ebcc030e-ee39-45b8-9324-8cb71baef6f2)

## Disclaimer:

This app is for demonstration purposes only and should not be solely relied upon for decision-making. While the model has been trained on a significant dataset, it may not accurately predict all question pairs.

---

## Author:

- [Tushar Gandhi](https://github.com/tushargandhi77)

---
