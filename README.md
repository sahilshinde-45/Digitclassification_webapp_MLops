# Digitclassification_webapp_MLops

This project demonstrates a digit classification application using a neural network implemented with the PyTorch framework. The application is built with a Python tech stack, leveraging the Flask framework to create an API. The web app is hosted on Heroku and achieves an accuracy of 97%.

Table of Contents

    •	Tech Stack
          1) Python
          2) Machine Learning
    •	Usage
    •	Testing
    •	Deployment
  Tech Stack
  
    Python
      •	Flask Framework: Used to create the API.
      •	Test Files: Created to test the API.
    Machine Learning
      •	PyTorch Framework: Used to implement the neural network.
      •	Neural Network Specifications:
             o Input Size: 28x28 grayscale image (1 channel).
             o Model Accuracy: 97%.
  Usage
  
    To run the application locally:
        1.	Start the Flask server:
              python app.py
        2.	Access the API: Open your browser and go to http://127.0.0.1:5000/.

  Testing
  
    To test the API, you can use the provided test files. Run the tests with the following command:
    python test_api.py
    
  Deployment
  
    The web application is hosted on Heroku. To deploy your own instance, follow these steps:
      1.	Login to Heroku:
              heroku login
      2.	Create a new Heroku app:
              heroku create your-app-name
      3.	Push the code to Heroku:
              git push heroku main
      4.	Open the app:
              heroku open


