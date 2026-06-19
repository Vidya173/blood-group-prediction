#  A Novel Approach to Predict Blood Group Using Fingerprint Map Reading

## Project Overview

Blood group identification is an essential process in healthcare, emergency medicine, and blood donation systems. Traditional blood typing methods require laboratory testing, which can be time-consuming and resource-intensive.

This project presents a novel machine learning-based approach to predict an individual's blood group using fingerprint pattern analysis. By extracting unique fingerprint features such as loops, whorls, and arches, the system aims to identify correlations between fingerprint characteristics and blood groups.

---

## Objectives

- Predict blood groups using fingerprint image analysis.
- Reduce dependency on laboratory-based preliminary screening.
- Apply machine learning techniques to biometric data.
- Analyze relationships between fingerprint patterns and blood groups.
- Develop a fast and non-invasive prediction system.

---

##  Key Features

- Fingerprint Image Processing
- Feature Extraction from Fingerprints
- Machine Learning-Based Classification
- Blood Group Prediction
- Data Visualization and Analysis
- User-Friendly Prediction Interface

---

##  Technologies Used

- Python
- OpenCV
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib
- Jupyter Notebook

---

##  Project Structure

```text
blood-group-prediction-using-fingerprint/
│
├── dataset/
│   ├── fingerprint_images/
│   └── blood_group_data.csv
│
├── models/
│   └── trained_model.pkl
│
├── notebooks/
│   ├── preprocessing.ipynb
│   ├── feature_extraction.ipynb
│   └── model_training.ipynb
│
├── src/
│   ├── preprocess.py
│   ├── train.py
│   ├── predict.py
│
├── screenshots/
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

##  Methodology

### Step 1: Fingerprint Acquisition

- Capture fingerprint images.
- Store images in the dataset.

### Step 2: Image Preprocessing

- Convert to grayscale.
- Noise reduction.
- Contrast enhancement.
- Ridge enhancement.

### Step 3: Feature Extraction

Extract fingerprint characteristics:

- Loops
- Whorls
- Arches
- Ridge Count
- Minutiae Points

### Step 4: Machine Learning Model

Train classification algorithms such as:

- Random Forest
- Decision Tree
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

### Step 5: Blood Group Prediction

The trained model predicts:

- A+
- A-
- B+
- B-
- AB+
- AB-
- O+
- O-

---

##  System Architecture

```text
Fingerprint Image
        │
        ▼
Image Preprocessing
        │
        ▼
Feature Extraction
        │
        ▼
Machine Learning Model
        │
        ▼
Blood Group Prediction
```

---

##  Dataset Description

The dataset contains:

| Attribute | Description |
|------------|------------|
| Fingerprint Image | Input biometric data |
| Pattern Type | Loop, Whorl, Arch |
| Ridge Count | Number of fingerprint ridges |
| Blood Group | Target variable |

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/blood-group-prediction-using-fingerprint.git
cd blood-group-prediction-using-fingerprint
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Project

```bash
python src/train.py
python src/predict.py
```

---

## Results

- Successful extraction of fingerprint features.
- Classification of fingerprint patterns.
- Blood group prediction based on learned relationships.
- Visualization of feature distributions and prediction outcomes.

---


##  Research Note

This project is intended for academic and research purposes. Blood group prediction from fingerprints remains an active area of study, and results should not be used as a substitute for certified medical blood typing tests.

---

##  Future Enhancements

- Deep Learning-based fingerprint analysis.
- Mobile application integration.
- Real-time fingerprint scanning.
- Larger dataset training.
- Improved prediction accuracy using CNN models.

---

