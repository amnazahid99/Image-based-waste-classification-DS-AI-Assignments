# ♻️ Image-Based Waste Classification (Weeks 1–8)

**Student:** Amna Zahid  
**Course:** Data Science & AI (BSSE 7th Semester)  
**Project:** Image-Based Waste Classification (Midterm Portion)

---

## 📘 Project Overview

This project focuses on **automatic waste classification** using deep learning and transfer learning.  
It classifies waste images into **10 categories**:  
`battery`, `biological`, `cardboard`, `clothes`, `glass`, `metal`, `paper`, `plastic`, `shoes`, and `trash`.

The model is based on **MobileNetV2**, a lightweight convolutional neural network optimized for computer vision tasks.  
It was first trained with frozen layers and later fine-tuned to improve accuracy.  
Finally, a **Gradio web interface** was built to test the model interactively.

---

## 🗂️ Dataset Information

This project uses the **Garbage Classification Dataset**, containing **10 waste categories** and over **25,000 labeled images**.  
Due to **GitHub’s file size limit (~740 MB total)**, the full dataset could not be uploaded.  

Instead, a smaller **`test_images.zip`** file is included — it contains representative images from multiple categories used for testing and demonstration.  

📥 You can download the **original Garbage Dataset** directly from **[Kaggle](https://www.kaggle.com/datasets/mostafaabla/garbage-classification)** and place it in the same path used in the notebook for full model training.

---

## 🧠 Run the Notebook

Open the notebook in Jupyter:

```bash
DSAI waste classification project.ipynb
```

Run all cells sequentially to:

1. Load and preprocess the dataset

2. Train and fine-tune MobileNetV2

3. Evaluate model performance

4. Generate results and plots

# 🚀 Launch the Gradio App

At the final step, the Gradio interface is created:
```python
demo.launch(share=True)
```

Once it runs, open the public link (ending with .gradio.live) to test your model online.

# 📊 Model Performance


| Metric                                   | Result                          |
|------------------------------------------|---------------------------------|
| Validation Accuracy (before fine-tuning) | 93.29%                          |
| Validation Accuracy (after fine-tuning)  | 93.88%                          |
| Validation Loss                          | 0.217                           |
| Model Used                               | MobileNetV2 (Transfer Learning) |


# ✅ Features Implemented

1. Dataset preprocessing & augmentation

2. CNN with MobileNetV2 backbone

3. Training & validation (with callbacks)

4. Fine-tuning of last 50 layers

5. Evaluation (accuracy, loss, confusion matrix)

6. Interactive Gradio web app

7. Final PDF report

   # 📅 Weekly Breakdown (Weeks 1–8)


| Week | Focus                                    | Output                    |
|------|------------------------------------------|---------------------------|
| 1    | Dataset setup & exploration              | Folder structure verified |
| 2    | Image preprocessing & augmentation       | Created generators        |
| 3    | Model creation (MobileNetV2 base)        | Compiled model            |
| 4    | Initial training with frozen base        | Checkpoints saved         |
| 5    | Model evaluation & visualization         | Accuracy/loss plots       |
| 6    | Fine-tuning top layers                   | Accuracy ↑ to 93.88%      |
| 7    | Testing on unseen images                 | Verified predictions      |
| 8    | Deployment using Gradio                  | Live model demo           |


   # 🧪 Testing

- Extract test_images.zip.
  
- Place it in week1-8/test_images/.
  
- Run the prediction cell or open the Gradio app, then upload an image.
  
- The model displays the predicted category and confidence score.

# 📝 Note for Instructor

The complete training dataset is not uploaded due to GitHub’s size limits.
Instead, test_images.zip provides multiple samples to demonstrate model predictions.
The notebook, model, and Gradio app collectively represent the full project for Weeks 1–8 (Midterm Portion).

# 📚 References

1. TensorFlow / Keras Documentation

2. MobileNetV2 Paper (Google AI)

3. Kaggle: Garbage Classification Dataset

4. Gradio Documentation

# GitHub Repository:
https://github.com/amnazahid99/Image-based-waste-classification-DS-AI-Assignments

Created by: Amna Zahid

