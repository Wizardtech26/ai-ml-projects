# AI & Machine Learning Projects

This repository contains a collection of beginner-friendly projects demonstrating key concepts in **Machine Learning**, **Deep Learning**, and **Natural Language Processing (NLP)**.

---

## 🧩 1. Classical Machine Learning with Scikit-learn
**Dataset:** Iris Species Dataset  
**Goal:** Train a Decision Tree Classifier to predict iris species.  
**Key Steps:**
- Preprocessing (handle missing values, label encoding)
- Model training using Scikit-learn
- Evaluation with accuracy, precision, and recall

**File:** `Iris_Decision_Tree.ipynb`

---

## 🧠 2. Deep Learning with PyTorch
**Dataset:** MNIST Handwritten Digits  
**Goal:** Build a CNN model to classify handwritten digits with >95% accuracy.  
**Key Steps:**
- CNN architecture and training loop
- Evaluation and accuracy tracking
- Visualization of predictions and learning curves

**File:** `MNIST_CNN_PyTorch.ipynb`

---

## 💬 3. NLP with spaCy
**Dataset:** Amazon Product Reviews (sample)  
**Goal:** Extract product names and brands using NER, and perform rule-based sentiment analysis.  
**Key Steps:**
- Named Entity Recognition (spaCy)
- Simple sentiment scoring based on positive/negative keywords
- Output showing entities and sentiment

**File:** `NLP_spaCy_Amazon_Reviews.ipynb`

---

## 🚀 How to Use
1. Clone or download this repository.  
2. Open any `.ipynb` file in **Jupyter Notebook** or **Google Colab**.  
3. Run all cells to reproduce results.

---

## 📚 Requirements
Install dependencies using:
```bash
pip install numpy pandas matplotlib scikit-learn torch torchvision spacy
python -m spacy download en_core_web_sm
