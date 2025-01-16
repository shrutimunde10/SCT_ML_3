# SCT_ML_3
This project implements an SVM model to classify cats and dogs using HOG features. Images are preprocessed (grayscale, resized to 128x128), and HOG features are extracted. The dataset is split into training and testing sets, and the model achieves predictions with high accuracy. The script includes a function to predict new images.
# Cat vs Dog Classifier Using SVM

## Features
- **HOG Feature Extraction**: Converts images into feature vectors for robust SVM training.
- **Batch Processing**: Efficiently handles large datasets by processing images in batches.
- **High Accuracy**: Achieves reliable predictions by leveraging linear SVM.
- **Custom Prediction**: Includes a function to classify new images as either "Cat" or "Dog."

## Dataset
The dataset should consist of two folders:
- `cats`: Contains images of cats.
- `dogs`: Contains images of dogs.

## Results
- The model outputs accuracy and a classification report after testing.
- Generates predictions for unseen images.

## Acknowledgments
This project was inspired by Kaggle’s Cats vs. Dogs dataset and demonstrates the power of SVMs for image classification tasks.
