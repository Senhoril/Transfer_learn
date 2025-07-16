# Image Classification of Cats and Dogs using Transfer Learning

This project focuses on building an image classification model to distinguish between images of cats and dogs. It leverages transfer learning using the VGG16 architecture pre-trained on the ImageNet dataset.

## Dataset

The dataset used is the Kaggle Cats and Dogs dataset, downloaded from the provided Microsoft link. The dataset contains images of cats and dogs, which are then organized into training, validation, and test sets.

## Model Architecture

The model is built on top of the VGG16 convolutional base. The pre-trained VGG16 layers are frozen, and new dense layers are added on top for binary classification (cat or dog).

## Training

The model is trained using the organized training and validation datasets. Data augmentation is applied to the training data to improve the model's generalization.

## Evaluation

The model's performance is evaluated on a separate test set to assess its ability to classify unseen images of cats and dogs.

## Usage

The notebook provides code for:

1. Downloading and extracting the dataset.
2. Organizing the dataset into training, validation, and test directories.
3. Building and compiling the transfer learning model.
4. Training the model.
5. Evaluating the model's performance.
6. Making predictions on new images.

This project demonstrates a practical application of transfer learning for image classification tasks.
