# Dog-Breed-Classification

## Problem Statement
Dogs come in all shapes and sizes. Even within a single breed there can be a large variation in appearance from pup to pup. This poses a difficult challenge for an image classification model to identify dogs of a certain breed.  A robust and accurate model to predict dog breeds can be useful in a number of ways including. For example, Adoption Shelters, Veterinary Centers or social media companies could all find use for an accurate image classifier.


## Data Description

Data was downloaded from kaggle https://www.kaggle.com/datasets/mohamedchahed/dog-breeds and included 8 different breeds
- Beagle
- Bulldog
- Dalmation
- German-Shepherd
- Husky
- Labrador-Retriever
- Poodle
- Rottweiler

## Modeling
Data was split into train and test set. 4 Different multiclass classification models were trained
- Basic CNN
- Transfer Learning with InceptionV3
- Transfer Learning with Xception
- Transfer Learning with VGG16

Among the 4 models, InceptionV3 had the highest accuracy and was further hyperparameter tuned with RandomSearch. Overall, this fine-tuned model had the highest test set accuracy at 95.41%
