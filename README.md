# ♻️ Image-Based Waste Classification (Weeks 1–15)

**Student:** Amna Zahid  
**Course:** Data Science & Artificial Intelligence (BSSE 7th Semester)  
**Project:** Image-Based Waste Classification  
**Status:** Final Project (Weeks 1–15 Completed)

---

## 📘 Project Overview

This project focuses on **automatic waste classification** using **Data Science and Artificial Intelligence techniques**, progressing from basic data handling to deep learning, deployment, explainability, and final reporting.

The system classifies waste images into multiple categories such as:  
`battery`, `biological`, `cardboard`, `clothes`, `glass`, `metal`, `paper`, `plastic`, `shoes`, and `trash`.

The project gradually evolves from **data preprocessing and classical ML** to **CNN-based deep learning**, **model deployment**, and **explainable AI**, following a strict **week-by-week academic roadmap**.

---

## 🗂️ Dataset Information

- **Dataset:** Garbage Classification Dataset  
- **Source:** Kaggle  
- **Total Images:** 25,000+  
- **Categories:** 10 waste classes  

Due to **GitHub file size limitations**, the full dataset is not uploaded.

📥 Download the original dataset from Kaggle:  
https://www.kaggle.com/datasets/mostafaabla/garbage-classification

A smaller **`test_images.zip`** file is included for demonstration and testing.

---

## 🧠 Technologies & Tools Used

- Python
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-learn
- TensorFlow / Keras
- MobileNetV2 (Transfer Learning)
- Gradio (Deployment)
- SHAP (Explainable AI)
- Git & GitHub

---

## 🚀 How to Run the Project (Weeks 1–8)

Open the main notebook:

```bash
DSAI waste classification project.ipynb
```

Run all cells sequentially to:

- Load and preprocess the dataset

- Train CNN using MobileNetV2

- Fine-tune the model

- Evaluate performance

- Test predictions

- Launch Gradio interface

Launch Gradio App
demo.launch(share=True)

## 📊 Model Performance (CNN)

- Metric	Result
- Validation Accuracy (Before Fine-Tuning)	93.29%
- Validation Accuracy (After Fine-Tuning)	93.88%
- Validation Loss	0.217
- Model Used	MobileNetV2 (Transfer Learning)

## ✅ Features Implemented

- Dataset preprocessing & augmentation

- CNN with MobileNetV2 backbone

- Transfer learning & fine-tuning

- Model evaluation & visualization

- Unsupervised learning (K-Means + PCA)

- ANN baseline model

- NLP preprocessing (TF-IDF demo)

- Model deployment (without Flask)

- Explainable AI using SHAP

- Industry case study & ethics analysis

## 📅 Weekly Breakdown (Weeks 1–15)

Week	Focus Area	Key Outcome
1. 	Orientation & setup	Environment & repo setup
2. 	Data collection & cleaning	Cleaned dataset
3. 	Data visualization	EDA & plots
4. 	Statistics & probability	Feature understanding
5. 	Supervised learning (Regression)	Baseline model
6. 	Supervised learning (Classification)	RF & Logistic Regression
7. 	Model evaluation	Precision, Recall, F1
8. 	Unsupervised learning	K-Means + PCA
9. 	Neural Networks (ANN)	ANN baseline model
10.   Advanced Deep Learning	CNN with MobileNetV2
11.   NLP preprocessing	Tokenization & TF-IDF
12.	Industry case study	Real-world application
13.	Model deployment	Gradio-based deployment
14.	Ethics & explainability	SHAP explainability
15.	Project finalization	Report & GitHub ready

## 🧪 Testing

- Extract test_images.zip

- Place it in the specified directory

- Run prediction cells or upload images in Gradio UI

- View predicted class and confidence

## ⚖️ Ethics & Explainability (Week 14)

1. SHAP used to explain CNN predictions

2. Highlighted influential image regions

3. Addressed dataset bias and misclassification risks

4. Emphasized transparency and responsible AI use

## 📝 Note for Instructor

Due to GitHub storage limits, the full dataset is not uploaded.
However, the repository includes:

- All weekly notebooks/scripts

- Model files

- Deployment and explainability code

- Industry case study

- Final project structure

This repository represents the complete solo project (Weeks 1–15) as required by the course.

## 📚 References

- TensorFlow & Keras Documentation

- MobileNetV2 Research Paper (Google AI)

- Kaggle – Garbage Classification Dataset

- Gradio Documentation

- Interpretable Machine Learning – Christoph Molnar

## 🔗 GitHub Repository

https://github.com/amnazahid99/Image-based-waste-classification-DS-AI-Assignments

**Created By:** Amna Zahid  
**Degree Program:**  BS Software Engineering 
---
DSAI waste classification project.ipynb
