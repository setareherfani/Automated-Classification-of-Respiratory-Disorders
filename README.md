# Automated-Classification-of-Respiratory-Disorders
Respiratory disorder is a health problem that affects people all around the world, especially in times like the COVID-19 pandemic, where one of the main symptoms of the virus is damage to the respiratory system.

Typically, the primary way to assess a patient’s respiratory health is to listen to the sounds of their breathing and perform tests and x-rays to diagnose any underlying health issues, which could take time. For this project, I anticipated to come up with a solution to fast-track the diagnosis of respiratory health and respiratory disorders. The sound emitted when a person breathes is directly related to air movement, changes within the lung tissues, and the position of secretions within the lungs. The way doctors listen to these breathing cycles is through using the traditional stethoscope, but using a digital stethoscope to record these sounds can open up the possibility of doctors using machine learning models to automatically diagnose respiratory disorders without further testing done on the patient. 
This project was inspired by this Kaggle post: https://www.kaggle.com/vbookshelf/respiratory-sound-database

### How to run the project 
#### **1** Create a virtual environment "deeplearning" and install modules needed as provided in the library.ipynb file
#### **2** Download Data from Kaggle and run it using the path of where the data is stored on your computer. You can load in the data using the Capstone Main Code.ipynb file.
#### **3** To preprocess the data, you can choose different envelope analysis functions (I used RMS root mean square envelope analysis), other functions are stored in the Function.ipynb
#### **4** Run the models you want to test.
