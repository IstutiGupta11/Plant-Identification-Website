# Plant-Identification-Website

## INTRODUCTION

This is a plant identification website that runs on a local host. The website is built using HTML, CSS, JavaScript, and the Flask web framework for Python. The website allows users to upload a picture of a plant and receive information about the plant's species and care instructions. 

## NAME: ‘PLANTICS’ 

The word ‘Plantics’ is a self explanatory name for our website that indicates taking image of the plant from user and help to study about them in brief. 

## DESCRIPTION 

The website aims to help the user upload/browse an image of the plant from the file folder by clicking on the “Choose File” option and then clicking on ‘Predict’ to find out necessary details such as name of plant, benefits, and other additional features. 

## TECHNOLOGIES USED

To run this website on your local host, you will need to have Python 3 and Flask installed. Furthermore, the Website is built using the following technologies: 

-**Python**: The application's backend is built using Python. 
-**Flask**: The application's web framework is Flask. 
-**TensorFlow**: The machine learning algorithms used to identify plants are built using TensorFlow. 
-**HTML/CSS/JavaScript**: The application's frontend is built using HTML, CSS, and JavaScript. 

## INSTALLATION

To run the website on your local host, navigate to the project directory in your terminal and run the following command:
This will start the Flask web server and allow you to access the website at http://127.0.0.1:3000. You can then upload a picture of a plant to the website and receive information about the plant's species and care instructions.

## DEPENDENCIES

This website uses the following libraries and frameworks: 

-**Flask** (https://flask.palletsprojects.com/) 
-**TensorFlow** (https://www.tensorflow.org/) 
-**NumPy** (https://numpy.org/) 

## DATASET 

The dataset for plant identification contains images and metadata for 30 different types of plants. Each plant type has multiple images associated with it, taken from different angles and in different lighting conditions. The dataset is organized into a main directory with subdirectories for each plant type. Each subdirectory is named after the corresponding plant type and contains all the images associated with that type. The images in the dataset are high-resolution and have been carefully selected to showcase the distinguishing features of each plant type. The dataset is intended for use in machine learning and computer vision applications such as plant identification and classification. Our dataset includes following plants: 

-**Crops**: Corn, Paddy
-**Fruit Plant**: Banana, Guava, Mango, Melon, Orange, Papaya, Watermelon, Pineapple, Bilimbi, Cantaloupe  
-**Industrial plant**: Coconut, Tobacco  
-**Medicinal plant**: Aloe-vera, Turmeric, Galangal, Ginger, Curcuma  
-**Nuts**- Soybeans 
-**Tubers**: Cassava, Sweet potato
-**Vegetable plant**: Cucumber, Brinjal, Long beans, Pepper chilli, Shallot, Spinach, Kale

## MODEL

The machine learning model used in this project is based on the Convolutional Neural Network (CNN) architecture. It was trained on the dataset using TensorFlow in a Jupyter Notebook. The trained model is saved in the G56.h5 file and is loaded into the Flask web application to make predictions on uploaded images. 

## USAGE: 

1. Go to the website: http://127.0.0.1:3000
2. Browse a photo of the plant you want to identify from your gallery. Make sure the plant is in focus and the photo is well-lit.
3. Upload the photo to the website by clicking on the "Choose File" button on the ‘Identify’ page.
4. Click the ‘Predict’ button and wait for the website to analyze the photo. This may take a few seconds.
5. Once the analysis is complete, the website will display the top matches for your plant based on the characteristics in the photo. You will be taken to a new page to learn more about the plant and its characteristics.
6. If you are still unsure about the identification, you can try uploading a different photo.

## CONCLUSION

We hope that this project can help people identify plants more easily and accurately. With the help of machine learning, we can create a tool that is accessible to anyone with an internet connection. Thank you for your interest in our project and for generating curiosity of plant identification technology!
