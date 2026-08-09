# Skin Disease Classification

A deep learning project for skin lesion image classification using transfer learning with MobileNetV2.

## Kaggle Notebook

[View the project on Kaggle](https://www.kaggle.com/code/tgourav311951/final-year-project)

## Project Overview

This project uses the HAM10000 skin lesion dataset to build an image classification model using a pretrained MobileNetV2 architecture.

The project covers:

- Image preprocessing
- Data augmentation
- Transfer learning
- MobileNetV2
- Optimizer comparison
- Model evaluation
- Confusion matrix
- ROC curve
- Prediction visualization
- Gradio-based interface

## Technologies Used

- Python
- TensorFlow / Keras
- MobileNetV2
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Gradio

## Model

A pretrained MobileNetV2 model with ImageNet weights is used as the base feature extractor.

The base model layers are initially frozen and a custom classification head is added for the skin lesion classification task.

## Dataset

The project uses the HAM10000 dataset containing dermatoscopic images of skin lesions.

## Evaluation

The model is evaluated using metrics including:

- Accuracy
- Recall
- F1 Score
- Mean Squared Error
- Log Loss

Additional visual evaluation includes:

- Confusion Matrix
- ROC Curve
- Sample Predictions

## Interactive Demo

A Gradio interface is included in the notebook for making predictions on uploaded skin lesion images.

## Notebook

The complete implementation is available in:

`skin_disease_classification.ipynb`

## Disclaimer

This project is developed for educational and research purposes only. It is not intended to provide medical diagnosis or replace professional medical advice.
