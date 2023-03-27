# Detection-of-Cross-Site-Scripting-XSS-Attacks-with-CNN

This project involved the utilization of XSS Scripts for feature generation, and Convolutional Neural Network (CNN) techniques were employed to classify and detect the presence of XSS scripts as either malicious or benign. To achieve this, various neural network algorithms and models were implemented.

The dataset containing html tags and labels was processed to create a 4-dimensional NumPy array for the deep learning model. A CNN with a callback function was implemented to avoid overfitting, and the dataset was split into training and testing sets. The model was trained for 10 epochs and evaluated using accuracy, precision, and recall. The resulting confusion matrix showed high accuracy, and the model can be deployed as an API to detect cross-site scripting attacks effectively in commercial websites.

System Diagram : 

<img width="441" alt="Screenshot 2023-03-27 at 8 38 32 PM" src="https://user-images.githubusercontent.com/101682165/227982499-421a6582-1849-4501-8c5e-eb677ef855f2.png">


You can read the blog of this project here - https://medium.com/@madhubleh/detection-of-cross-site-scripting-xss-attacks-with-cnn-4633b4873480 
