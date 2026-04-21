Overview

This project develops a deep learning model for pneumonia detection from chest X-ray images using CNNs and transfer learning, aiming to improve diagnostic accuracy and efficiency.

Dataset

The model is trained on the Chest X-Ray Images (Pneumonia) dataset from Kaggle, containing over 5,800 labelled images. Data preprocessing includes resizing, normalisation, and augmentation.

Methodology

A custom CNN is compared with pre-trained VGG16 and DenseNet121 models. Training is performed using CrossEntropy Loss, Adam optimiser, and early stopping.

Results

VGG16 achieved the best performance with 94.83% accuracy and 0.99 AUC, followed by DenseNet121 (94.26%) and the custom CNN (91.97%), highlighting the effectiveness of transfer learning.
