# Handwritten Digit Recognition

CNN and classical ML models for classifying handwritten digits on MNIST (**70,000+** images). After tuning, the system reached **97% to 99%** test accuracy.

## Results

- Trained and compared a CNN against Logistic Regression and SVM
- Preprocessed images with grayscale normalization, reshaping, and noise reduction
- Evaluated with accuracy, confusion matrix, precision, recall, and loss curves

## Stack

Python · TensorFlow / Keras · Scikit-learn · NumPy · Pandas · OpenCV · Matplotlib

## Run

Open `DigitRecognition.ipynb` in Jupyter or Google Colab and run all cells. The notebook downloads MNIST during training, so no separate dataset file is required.

```bash
pip install tensorflow scikit-learn numpy pandas opencv-python matplotlib
jupyter notebook DigitRecognition.ipynb
```

## What to look at

The notebook covers preprocessing, model training, hyperparameter tuning, and the evaluation plots used to compare CNN performance against the classical baselines.
