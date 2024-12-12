# **Pre-trained Image Classifier to Identify Dog Breeds**

## **Project Overview**

This project utilizes a pre-trained image classifier to identify different dog breeds. The model is based on **TensorFlow** and **Keras** and is fine-tuned using a **MobileNet** architecture. The classifier is trained on a large dataset of dog breed images and is capable of predicting the breed of any input dog image.

## **Features**

- **Pre-trained Model**: The model uses **MobileNet**, a popular deep learning architecture that has been pre-trained on the **ImageNet** dataset, for fast and accurate image classification.
- **Breed Prediction**: The model classifies an input image and provides the predicted dog breed.
- **Top-K Predictions**: The model can predict multiple dog breeds, providing the top **K** breed predictions with associated probabilities.
- **Model Saving and Loading**: The model is saved after training and can be loaded for future predictions.

## **Technologies Used**

- **Python** for implementing the image classification model.
- **TensorFlow** and **Keras** for building and training the neural network.
- **OpenCV** for image processing (optional, depending on the implementation).
- **NumPy** and **Matplotlib** for data manipulation and visualization.

## **Dataset**

The model is trained on the **Stanford Dogs Dataset**, which includes 120 different dog breeds and over 20,000 images. 

- **Dataset link**: [Stanford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/)

## **Setup and Installation**

### **Prerequisites**

Make sure you have the following software installed:
- **Python 3.x**
- **TensorFlow**
- **Keras**
- **NumPy**
- **Matplotlib**
- **OpenCV**

### **Steps to Run the Project**

1. **Clone the repository**:
   Clone the repository by running:

   ```bash
   git clone https://github.com/your-username/Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds-master.git
