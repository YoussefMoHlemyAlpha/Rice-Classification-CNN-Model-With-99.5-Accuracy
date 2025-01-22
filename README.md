# Rice-Classification-CNN-Model-With-99.5-Accuracy
Project Summary: Rice Image Classification Using Convolutional Neural Networks This project involves developing a Convolutional Neural Network (CNN) model to classify images of rice grains into five categories: Arborio, Basmati, Ipsala, Jasmine, and Karacadag. The dataset consists of 75,000 labeled images sourced from the Rice Image Dataset 
Dataset:-
https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset

This project involves developing a Convolutional Neural Network (CNN) model to classify images of rice grains into five categories: Arborio, Basmati, Ipsala, Jasmine, and Karacadag. The dataset consists of 75,000 labeled images sourced from the Rice Image Dataset, stored in a structured format.

Key steps in the project include:

Data Exploration and Visualization:

The dataset was analyzed to count the number of images in each category.
A pie chart was created to visualize the distribution of images across the five classes.
Data Preprocessing:

Images were resized to a uniform size of 80x80 pixels.
The dataset was split into training, validation, and testing subsets with respective proportions of 70%, 15%, and 15%.
Images were normalized to improve model convergence.
Model Development:

A custom CNN model was designed with:
Multiple convolutional layers to extract features.
Dense layers with dropout regularization to prevent overfitting.
A softmax activation layer for multi-class classification.
Early stopping and learning rate reduction callbacks were employed to optimize training.
Training and Evaluation:

The model achieved impressive performance metrics, including high accuracy on both training and validation sets.
Validation accuracy consistently improved across epochs, demonstrating the model's effectiveness.
This project showcases the application of CNNs for image classification tasks, emphasizing effective data preprocessing, model optimization, and visualization techniques. It serves as a robust example of deep learning in agricultural and grain quality classification domains.
![image](https://github.com/user-attachments/assets/542dadcb-dd55-4d77-bb1c-e4492f8686e3)
