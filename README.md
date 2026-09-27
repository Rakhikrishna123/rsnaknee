# RSNA Knee Abnormality Detection

A deep learning project for detecting knee abnormalities from medical X-ray images using the **RSNA Knee Abnormality Detection** dataset from Kaggle.

## 📌 Project Overview

Knee abnormalities can be identified from X-ray images by analyzing visual patterns in the joint. In this project, a deep learning model is trained to classify knee X-ray images using **PyTorch**.

The project covers the complete machine learning workflow:

* Dataset preparation
* Medical image preprocessing
* Model training
* Validation
* Prediction
* Kaggle submission

## 🎯 Objective

The main objective is to develop a deep learning model capable of identifying abnormalities in knee X-ray images and generating predictions for the Kaggle competition.

## 📊 Dataset

The project uses the **RSNA Knee Abnormality Detection** dataset provided through Kaggle.

The dataset consists of knee X-ray images that are used for training and evaluating deep learning models.

> Dataset: RSNA Knee Abnormality Detection — Kaggle

## 🛠️ Technologies Used

* **Python**
* **PyTorch**
* **NumPy**
* **Pandas**
* **OpenCV / PIL**
* **Matplotlib**
* **Jupyter Notebook**
* **Kaggle**

## 🔄 Workflow

```text
Knee X-ray Images
        ↓
Image Preprocessing
        ↓
Train / Validation Data
        ↓
PyTorch Deep Learning Model
        ↓
Model Training
        ↓
Validation
        ↓
Prediction
        ↓
Kaggle Submission
```

## 🧹 Image Preprocessing

The X-ray images are prepared before being given to the model. The preprocessing pipeline includes operations such as:

* Loading X-ray images
* Resizing images
* Converting images into suitable tensor formats
* Normalization
* Preparing batches using PyTorch DataLoaders

## 🧠 Model

A deep learning image-classification approach was implemented using **PyTorch**.

The model learns visual features from knee X-ray images during training and uses these learned features to generate predictions on unseen images.

### Training Process

The model is trained using:

* Training images
* Ground-truth labels
* Loss function
* Optimizer
* Multiple training epochs
* Validation data for performance monitoring

## 📈 Evaluation

Model performance is evaluated using the competition's evaluation metric and the resulting predictions are submitted to Kaggle.

### First Kaggle Result

The first public Kaggle submission achieved a **public score of approximately 0.515**.

This result serves as the initial baseline for further experimentation and model improvement.

## 🚀 Future Improvements

Possible improvements include:

* Experimenting with different CNN architectures
* Transfer learning using pretrained models
* Data augmentation
* Hyperparameter tuning
* Learning-rate scheduling
* Improving image preprocessing
* Handling class imbalance
* Cross-validation
* Ensemble models
* Improving Kaggle leaderboard performance

## 📁 Project Structure

```text
RSNA-Knee/
│
├── notebook/
│   └── rsna_knee.ipynb
│
├── README.md
│
└── requirements.txt
```

## 💻 Installation

Clone the repository:

```bash
git clone <your-repository-url>
cd RSNA-Knee
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## ▶️ Running the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then open the RSNA Knee notebook and run the cells sequentially.

## 📌 Project Status

**Completed initial training and Kaggle submission.**

The current public score provides a baseline for future model improvements.

## 👩‍💻 Author

**Rakhikrishna A U**

B.Tech Computer Science and Engineering
