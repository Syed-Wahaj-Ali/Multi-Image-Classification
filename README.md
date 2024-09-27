# Multiclass Image Classification using CNN and Transfer Learning 🐾

## 1. Problem Definition
Develop an image classification model that can accurately classify various dog breeds by analyzing their pictures.
## 2. Data Collection
The dataset was sourced from a Kaggle competition and includes training and test images along with their respective labels.
Dataset Link: Dog Breed Identification | Kaggle
## 💡 Approach
* Data Preprocessing
    * Loaded the dataset and applied preprocessing steps like resizing and normalization.
    * Split the data into training, validation, and test sets.
    * Initially, the model was run on a subset of 1000 images to ensure proper training before expanding to the full dataset.

* Transfer Learning with MobileNetV2
    * MobileNetV2 is a pre-trained CNN architecture, trained on the ImageNet dataset.
    * The top classification layer was frozen, and a custom output layer was added to predict dog breeds.
    * Fine-tuned the model specifically for the dog breed dataset.

## Training and Evaluation
  * Initially, the model showed signs of overfitting on a validation dataset of 1000 images.
  * Trained the modified MobileNetV2 on the complete training dataset.
  * Evaluated its performance on the validation set and observed that it performed quite well.
  * Predictions: Used the trained model to predict dog breeds for new, unseen images.

## 🏆 Results:
The model achieved a **95%** training accuracy on the full dataset. While it might indicate some overfitting, I didn't go deeply into regularization techniques for this project because of my PC it is too slow. Moreover this dataset was very complex because predicting the same kind of animal is difficult because most of them are almost same. 
Overall, this project was a fantastic opportunity to deepen my understanding of CNNs and transfer learning, and I’m excited to apply these techniques to even more complex.

Source link: [https://www.kaggle.com/c/dog-breed-identification/leaderboard]



Disclaimer: [My code may contains error you can check it and give me suggestions i need your suppor and suggestions]
