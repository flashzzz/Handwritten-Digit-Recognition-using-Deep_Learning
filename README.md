# Handwritten-Digit-Recognition-using-Deep_Learning
This project recognizes the handwritten numerical digits(0-9) that are drawn on the drawing window.

# How to use the project
Simply clone the repository and install all the packages in the requirements.txt file and run the interface.py file using python interpreter.

# Dataset
The dataset that I used is MNIST as it has a good number of training examples that allowed me to build a powerful and accurate model.

![image](https://user-images.githubusercontent.com/73419491/211145461-cc2aee2e-e397-418c-9aea-26ab4c7923c6.png)

# Interface
The interface is designed using pygame to create an interactive window on which user can draw multiple digits one by one.
Also pressing the key 'c' clears the window.

![screenshot 1](https://user-images.githubusercontent.com/73419491/211146205-c206ea5f-f2ef-4e91-aa98-127c2d2a1a33.PNG)

# Details on the model
The model is trained on Deep Neural Networks with an accuracy of 98.989%
I have used a total of 3 layers including the output layer and Dropout(to prevent overfitting).
For the hidden layers activation used is 'ReLU' and for the output/classification the activation is 'softmax'
The model is trained on Deep Neural Networks with training accuracy of 99.84% and testing accuracy of 98.98%
