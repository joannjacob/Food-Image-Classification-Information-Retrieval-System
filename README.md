# Food-Image-Classification-Information-Retrieval-System
This project presents a robust and efficient food image classification and information retrieval system, leveraging the Food-5k and Food-101 datasets. 

This project is done as part of DS 5500 - Capstone Project 
Group 2: Anurathi Bala, Joann Rachel Jacob & Mitchell Leahy

This project presents a robust and efficient food image classification and information retrieval system, leveraging the Food-5k and Food-101 datasets. The core functionality of the system involves two crucial steps: Firstly, it classifies user-provided images as either "Food" or "Non-Food" using the Food-5k model. Subsequently, for images classified as "Food," the system further categorizes them into one of the 101 specific food categories using the Food-101 model. This multi-step approach ensures accurate and precise food item recognition from a diverse range of images. 

Upon successful food item identification, the system offers users a comprehensive array of information, empowering them to explore the culinary world with ease. Users gain access to detailed data, including the food item's name, recipe options, calorie count, and essential nutritional insights. This feature-rich tool enhances users' understanding of their dietary choices and facilitates informed decision-making for healthier meal planning.

With its seamless image recognition and data retrieval capabilities, this system provides a user-friendly interface, making it effortless for individuals to quickly identify various food items and access valuable nutritional information about various food items based on submitted images. The integration of deep learning techniques, including the Food-5k and Food-101 models, ensures high accuracy and reliability in food classification, bolstering the system's overall performance.

## Table of contents
* [Datasets](#datasets)
* [Libraries and Tools](#libraries)
* [Models](#models)
* [Notebooks](#notebooks)

# Datasets
  - Food-5K - https://www.kaggle.com/datasets/trolukovich/food5k-image-dataset 
  - Food-101 - https://www.kaggle.com/datasets/kmader/food41

Food-5K dataset Dataset
1. Download the GTZAN dataset from https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification 
2. Upload it into your drive. (Create a folder and upload the folder downloaded here. It should have the folder name "Data" which contains images_original, genres_original, features_3_sec.csv and features_30s.csv)
3. Use the correct link to your drive in the required cells.
   
FMA Dataset
1. Download your Kaggle API file kaggle.json and upload into the colab by running the cells in the notebook. This is needed to download the dataset into the notebook.

## Libraries and Tools
* Python 
* TensorFlow
* Keras
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Models

* CNN
* InceptionV3
* Vision Transformer (ViT)

## Notebooks

* Food_5K.ipynb
* Food_101_Dataset_Classification.ipynb



