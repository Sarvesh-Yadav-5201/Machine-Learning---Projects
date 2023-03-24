# <b> Kaggle Project :
  <h3> Hand Written Digit Recognition using Convolutional Neural NetworK.
    
__________________
## Objective
> The goal of this project is to create neural networks that can recognize handwritten digits using the MNIST dataset.
    
> Dataset LINK : https://www.kaggle.com/competitions/digit-recognizer/data
    
## Dataset
> The dataset used for this project is the MNIST dataset, which is a large database of handwritten digits. It consists of 42,000 training images and 28,000 testing images.

## Project Walkthrough: 
  >* Loaded the train dataset which contains 785 columns: 784 columns for pixel values and 1 column for label.
  >* Split the training data into training and validation data.
  >* Standardized the dataset and visualized a few examples.
  >* Trained an Artificial Neural Network (ANN) model, which showed overfitting.
  >* Regulariz the ANN model using dropout and regularization parameters and achieved better accuracy.
  >* Classified the dataset using Convolutional Neural Network (CNN) by reshaping the data to a 4D tensor.
    
## Tools and Libraries Used
    
  >* Python
  >* Numpy
  >* Pandas
  >* Scikit-Learn
  >* Tensorflow
  >* Keras
  >* Matplotlib
    
## RESULTS : 
  >* ANN model achieved a training accuracy of 100% (Overfitting) but a validation accuracy of around 97%.
  >* Regularized ANN model achieved an accuracy of around 96%.
  >* CNN model achieved an accuracy of around 98%.
    
## HOW TO RUN:
To run this code, follow these steps:

>* Clone this GitHub repository.
>* Open the notebook CNN_mnist_digit_classification.ipynb in Jupyter Notebook or Google Colab.
>* Follow the instructions provided in the notebook to run each code cell in the correct order.
    
## License:
This project is licensed under the MIT License.
