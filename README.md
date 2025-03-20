# Cat-vs-Dog_imageclassifcation

1.Setup and Dataset Preparation

Downloads the "Dogs vs Cats" dataset from Kaggle.
Extracts the dataset and prepares training/testing directories.
Loads images using image_dataset_from_directory and normalizes them.

2.Model Creation

Builds a Convolutional Neural Network (CNN) with multiple Conv2D, MaxPooling, BatchNormalization, and Dense layers.
Uses ReLU activation and dropout layers to prevent overfitting.
Uses a final sigmoid layer for binary classification.

2.Training

Compiles the model using the Adam optimizer and binary cross-entropy loss.
Trains the model for 10 epochs using the training dataset with validation.

