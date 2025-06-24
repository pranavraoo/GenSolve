## Overview
**GenSolve** is a machine learning project aimed at providing personalized exercise recommendations based on genetic and symptomatic data. By leveraging LSTM models, the project identifies the best exercises tailored to an individual's genetic predispositions and physical conditions.

This repository contains scripts, datasets, and instructions for preprocessing data, training the predictive model, and evaluating its performance. The system integrates information on genetic disorders, associated symptoms, and their effects on physical fitness to provide effective exercise suggestions.

---

## Project Components

### Scripts
1. **`preprocess.py`**
   - Cleans, encodes, and formats datasets containing genetic data, symptoms, and exercise details.
   - Ensures consistency across datasets by handling missing values and standardizing formats.
   - Creates features required for effective model training.

2. **`train.py`**
   - Loads preprocessed data and constructs an LSTM-based neural network model.
   - Trains the model to predict suitable exercises based on genetic and symptomatic input.
   - Saves the trained model for future use.

3. **`test.py`**
   - Evaluates the trained model's performance using test datasets.
   - Generates predictions and computes performance metrics, including accuracy, precision, and recall.

---

### Datasets
- **Genetic Data**: Individual-specific genetic profiles used as inputs for training and testing.
- **Symptoms Dataset**: Maps symptoms to genetic disorders, forming part of the feature set.
- **Exercises Dataset**: Catalogs exercises with their associated muscle groups and benefits.
- **Disorders Folder**: Comprehensive repository detailing genetic disorders, symptoms, and their health impacts.

---

## Installation and Setup

### Prerequisites
Ensure that the following tools and libraries are installed:
- Python 3.8 or later
- Libraries: `pandas`, `numpy`, `scikit-learn`, `tensorflow`, `keras`

### Steps to Set Up
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/pranavraoo/GenSolve.git
   cd Genes-to-Gyms
   ```

2. **Install Dependencies**:
   Use the provided requirements file to install necessary libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare the Data**:
   Run the preprocessing script to clean and encode the datasets:
   ```bash
   python preprocess.py
   ```

4. **Train the Model**:
   Train the LSTM model using the cleaned data:
   ```bash
   python train.py
   ```

5. **Test the Model**:
   Evaluate the model’s accuracy and performance metrics:
   ```bash
   python test.py
   ```

---

### Contribution
Major contributions by:
- [Sripriya Addanki](https://github.com/sripriya204)
- [Rohan Anantapur](https://github.com/rohan0201)
- [Sameer Beedi](https://github.com/Sameerbeedi)
---
