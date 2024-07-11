# Skin-Disease-Prediction-GUI
This repository contains code for predicting skin diseases using deep learning techniques with a graphical user interface (GUI). The model is trained on a dataset of skin disease images and can classify different types of skin diseases with high accuracy.

# About
Skin diseases are common and can have a significant impact on an individual's health and quality of life. Early detection and accurate diagnosis of skin conditions are crucial for effective treatment. This project aims to provide a user-friendly tool for automated skin disease prediction using deep learning algorithms.

# Code Overview
The main components of the code include:

1.	Loading a pre-trained MobileNet V2 model from TensorFlow Hub
2.	Constructing a deep learning model architecture using Keras
3.	Compiling the model with appropriate optimizer, loss function, and evaluation metrics
4.	Implementing a GUI using tkinter for user interaction
5.	Preprocessing images, predicting diseases, and displaying results in the GUI

# About Dataset
Some types of pathogens — notably bacteria and fungi — are typically present on the skin, but if they become too numerous, the immune system can no longer manage them.In this case, an infection can result.The cause of a skin infection depends on the pathogen involved.

https://www.kaggle.com/datasets/subirbiswas19/skin-disease-dataset

In this dataset image collected from internet.In this dataset there are total 8 class ,They are

1.	Bacterial Infections- cellulitis

2.	Bacterial Infections- impetigo

3.	Fungal Infections - athlete -foot

4.	Fungal Infections - nail-fungus

5.	Fungal Infections - ringworm

6.	Parasitic Infections - cutaneous-larva-migrans

7.	Viral skin infections - chickenpox

8.	Viral skin infections - shingles

# Usage
To use this code, follow these steps:
1.	Clone the repository to your local machine:

  	    https://github.com/Shrikant-Bodkhe/skin-disease-prediction-gui.git

3.	Install the required dependencies:

  	    pip install -r requirements.txt

5.	Run the main script to launch the GUI application:

  	    python main.py

7.	In the GUI window, click the "Select Image" button to choose an image of a skin lesion.
8.	After selecting an image, click the "Predict" button to predict the disease associated with the image.
9.	The predicted disease label will be displayed below the image.

# Contributors
Shrikant Bhaginath Bodkhe
