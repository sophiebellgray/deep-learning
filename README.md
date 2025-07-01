# 🧠 Deep Learning for Skin Cancer Classification

![Status](https://img.shields.io/badge/status-completed-green)
![Tech](https://img.shields.io/badge/stack-TensorFlow|CNN|Colab-blue)

## 📈 Overview

This project develops a deep learning model to classify skin lesions using dermoscopic images from the **ISIC (International Skin Imaging Collaboration)** dataset. The goal is to support early detection of skin cancer and assist medical professionals with image-based diagnostics.

> Deep_Learning_Assignment refers to a project completed at university, in which i compare various preset deep learning models and design one of my own. This included tuning hyperparameters and creating various layers. The paper submitted in conjunction with this code aimed to investigate the models, but the priority was to demonstrate my understanding of deep learning. The report can be found in this repository. 
PLEASE do not plagiarise this document. It should be used for reference only. 
The dataset used was the ISIC dataset with 9 categories of skin cancer. The models aim to classify these images. 
Overall, i achieved 80% in this assignment.

## 🎯 Objectives

- Build an image classification model using TensorFlow and Keras
- Train the model on labelled medical image data from ISIC
- Evaluate model accuracy and performance on unseen test data
- Analyze misclassifications and suggest improvements

## 🧠 Key Features

- ✅ CNN architecture using Conv2D, MaxPooling, and Dense layers
- ✅ Real-time image augmentation for training
- ✅ Training checkpoints and learning rate scheduling
- ✅ Evaluation with accuracy, loss curves, and classification report

## 🛠️ Tech Stack

- **Language**: Python
- **Frameworks**: TensorFlow, Keras
- **Tools**: Google Colab, GPU acceleration
- **Data**: ISIC dermoscopy image dataset (zip from Google Drive)

## 📊 Example Output

| Metric | Value |
|--------|-------|
| Accuracy | 85.6% |
| F1 Score | 0.84 |
| Precision | 0.86 |
| Recall | 0.83 |

*Confusion matrix and ROC curves provided in the notebook.*

## 🚀 Getting Started

1. Clone this repository
2. Upload ISIC dataset to Google Drive
3. Open the notebook in [Google Colab](https://colab.research.google.com/github/sophiebellgray/deep-learning/blob/main/Deep_Learning_Assignment.ipynb)
4. Run each cell to train the CNN and evaluate results

## 🤝 Impact & Stakeholder Relevance

This project simulates real-world medical imaging workflows. With proper validation and regulatory approval, similar pipelines can:

- Support dermatologists in early cancer detection
- Reduce misclassification of benign vs malignant lesions
- Improve access to screening in remote or underserved areas

## 📚 Further Reading

- [ISIC Archive](https://www.isic-archive.com/)
- [Keras CNN Guide](https://keras.io/examples/vision/image_classification_from_scratch/)

## 📬 Contact

Project by **Sophie Bell-Gray**  
[LinkedIn](www.linkedin.com/in/sophie-bell-gray) | [Portfolio](https://sophiebellgray.github.io)

