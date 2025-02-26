# Dog Breed Classification using Xception

This project implements a Dog Breed Classification model using the Xception architecture, a pre-trained deep learning model optimized for image classification tasks. The model is trained on a dataset of dog images and classifies them into different breeds.

## Project Overview
- Uses Xception (pre-trained on ImageNet) as the backbone for feature extraction.
- Trains on dog breed images to classify them into their respective breeds.

## Dataset
- The dataset is [Kaggle's Dog Breed Dataset](https://www.kaggle.com/datasets/jessicali9530/stanford-dogs-dataset/data) consists of images of 120 dog breeds.
- Images are preprocessed to match the input size Xception requires (224x224).
- With 120 breeds of dogs and a limited number of training images per class, you might find the problem more, err, ruff than you anticipated. In this project, the top 10 dog breeds are used to speed up the training process and to run it on CPU.

## Model Architecture and Training
The pre-trained **Xception** model is used as the base model.
- Additional layers are added on top for classification.
- The model is trained using Categorical Crossentropy loss and Adamax optimizer.

## Evaluation
- Model performance is measured using accuracy, precision, recall, and confusion matrix.
- Predictions are made on the test dataset.

## Results
- Achieved an accuracy of 76.42% on the validation dataset.
- Confusion matrix and classification report provide insight into misclassifications.

## Future Improvements
- With more computational resources or GPU/TPU the number of Epochs and batch size can be increased further to improve accuracy.
- Fine-tuning the Xception model for better accuracy.
- Experimenting with additional augmentation techniques.
- Adding more layers in the architecture or training the last few layers of the Xception model to improve its accuracy for the Dog Breed dataset.

![screenshot from 2018-08-30 18-32-05](https://user-images.githubusercontent.com/29462447/44853289-29655480-ac83-11e8-8d00-a3e2009c6573.png)


    
    
    
    
    
