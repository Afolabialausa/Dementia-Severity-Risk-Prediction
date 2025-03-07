# Deep Learning for Individualized Dementia Severity Risk Score and Level Prediction

This project presents a deep learning framework for assessing dementia severity using neuroimaging and clinical features.

## Dataset
- Source: ADNIMERGE-3 (ADNI)
- Features: Neuroimaging (MRI, tau-PET), cognitive assessments, demographics
- Labels: Control Normal (CN), Mild Cognitive Impairment (MCI), Alzheimer's Disease (AD)

## Model
- Fully Connected Neural Network (TensorFlow/Keras)
- Softmax-based probabilistic risk scoring
- 5-Fold Cross Validation
- Dropout regularization (0.3)

## Results
- Accuracy: 93%
- Class-wise Precision, Recall, F1-score (CN, MCI, AD)

## Installation
Clone the repository:
```bash
git clone https://github.com/your-username/Dementia-Severity-Prediction.git
cd Dementia-Severity-Prediction
pip install -r requirements.txt
