# CIFAR-10 Image Classification using CNN 

This project implements a Convolutional Neural Network (CNN) using PyTorch to classify images from the CIFAR-10 dataset.

## Cloning the Repository
To clone the repository:
```sh
git clone https://github.com/J-Cherian/CIFAR-10-Image-Classification.git
```

## Model Architecture
- Conv1: 3x3x32 (ReLU + MaxPool)
- Conv2: 3x3x64 (ReLU + MaxPool)
- Conv3: 3x3x128 (ReLU + MaxPool)
- FC1: Fully connected (128 * 4 * 4 → 256)
- FC2: Fully connected (256 → 128)
- FC3: Fully connected (128 → 10)
- Dropout: Applied to reduce overfitting

## Results
After training, the model evaluates the test data and prints accuracy results per epoch. The final test accuracy was 74.19% on 10 Epoch.

![image](https://github.com/user-attachments/assets/f5077d85-d85c-416a-9ef3-ba51bf9c5723)

![image](https://github.com/user-attachments/assets/f209e1a2-fb2f-4f37-8af1-a1d7691eb405)
