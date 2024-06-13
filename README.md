This project demonstrates how to classify images of dogs and cats using a Support Vector Machine (SVM). The dataset consists of images stored in separate folders for cats and dogs, without labels. The code preprocesses the images, extracts features using Histogram of Oriented Gradients (HOG), and trains an SVM classifier to distinguish between the two categories.

Project Structure
load_and_preprocess.py: Script to load, preprocess, and save the dataset.
train_and_evaluate.py: Script to load the preprocessed dataset, extract features, train the SVM model, and evaluate its performance.
processed_data.pkl: Preprocessed dataset saved for quicker loading.
Prerequisites
Python 3.x
Required Python packages:
numpy
opencv-python
scikit-learn
scikit-image
joblib
