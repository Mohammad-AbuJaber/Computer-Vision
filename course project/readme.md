# Arabic Handwritten Character Recognition (AHCR) Using CNNs

## Background

Handwriting recognition poses a compelling computer vision challenge, requiring computers to identify and convert handwritten script from sources such as documents or touchscreens into a machine-understandable format. This involves offline input (from paper or photographs) or online input (from digital sources like touchscreens). Different machine learning methods, including K-nearest neighbors (KNNs), Support Vector Machines (SVMs), transfer learning, and deep learning techniques like Convolutional Neural Networks (CNNs), have been explored in the domain of automatic handwritten recognition. Arabic script, being semi-cursive and written from right to left with 28 characters, presents additional complexities, making its automatic recognition more challenging.

## Objectives

This assignment aims to familiarize students with the challenges and techniques of Arabic Handwritten Character Recognition (AHCR) using Convolutional Neural Networks (CNNs). Key objectives include:

1. Building a Basic CNN for AHCR:
   - Define a basic CNN architecture with convolutional layers, pooling layers, and activation functions.
   - Introduce loss functions (e.g., cross-entropy) and optimizers (e.g., Adam) for training.
   - Guide students through training, evaluation, and visualization of the CNN model.

2. Exploring Advanced Techniques:
   - Introduce data augmentation techniques, such as random cropping and rotation, to improve model generalizability.
   - Explore the use of pre-trained models (e.g., VGG16) and fine-tune them for AHCR.
   - Briefly touch upon more advanced CNN architectures like ResNet or DenseNet.

## Tasks

### Task 1: Build and Train a Custom CNN Network for AHCR

Define the architecture, convolutional layer parameters, pooling layer parameters, fully connected layer parameters, and training hyperparameters. Experiment with different architectures or refer to existing work for an initial architecture, followed by hyperparameter tuning.

For each model trained, plot:
1. Training loss vs. epoch.
2. Validation loss vs. epoch.
3. Training accuracy vs. epoch.
4. Testing accuracy vs. epoch.

References:
- Alsayed, Alhag & Li, Chunlin & Ahamed, & Hazim, Mohammed & Obied, Zainab. (2023). Arabic Handwritten Character Recognition Using Convolutional Neural Networks.
- Alwagdani, M.S.; Jaha, E.S. Deep Learning-Based Child Handwritten Arabic Character Recognition and Handwriting Discrimination.
- Altwaijry, N., Al-Turaiki, I. Arabic handwriting recognition system using convolutional neural network.
- Balaha, H.M., Ali, H.A., Youssef, E.K. et al. Recognizing arabic handwritten characters using deep learning and genetic algorithms.
- Others...

### Task 2: Retrain the Selected Network with Data Augmentation

Select at least three data augmentation techniques suitable for AHCR. Retrain the network selected in Task 1 after applying data augmentation. Plot the same metrics as in Task 1 and compare the results.

### Task 3: Select a CNN Network from Well-Known Architectures

Choose a CNN architecture from well-known models like LeNet, AlexNet, ResNet, etc. Train it using the data augmentation techniques from Task 2. Plot the same metrics and compare the results with Task 1 and Task 2.

### Task 4: Use a Pre-trained CNN Network with Transfer Learning

Utilize a pre-trained CNN network on similar tasks and fine-tune it on the provided dataset. Plot the same metrics and compare the results with Task 1, Task 2, and Task 3.

## Data Set

Use the following dataset for training and testing models:
[Arabic Handwritten Character Recognition Dataset](https://drive.google.com/file/d/1ZQ8fSD6WgkXFBKIxMRBMn0-gTwzFjUvz/view?usp=sharing)