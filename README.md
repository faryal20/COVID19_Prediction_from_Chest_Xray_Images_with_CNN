## Prediction of COVID-19 from Chest X-ray Images with CNN (Convolutional Neural Network)

In this project, Built and trained a convolutional neural network in Keras with TensorFlow as backend from scratch to predict patients if they were infected with COVID-19 or not using their chest X-ray images. Matplotlib was used for data visualization. Data preprocessing and data augmentation was carried out using tensorflow 2.0 The model used was sequential with a combination of convolutional layers, pooling layers, dropout layers, dense layers with relu activation and output layer with sigmoid activation. The dataset contained the lungs X-ray images of both groups i.e non-covid and covid infected patients. The dataset was obtained from kaggle. Metrics chosen for model evaluation were Training set, test set and validation set accuracy. Adam optimizer with learning rate of 0.001 was choosed for gradient descent The entire project was carried out on the Google Colab environment Results of the model were following:

1.Training Set Accuracy : 98.41 %

2.Training Set Loss : 0.0490

3.Validation Set Accuracy : 97.51 %

4.Validation Set Loss: 0.0759

5.Test Set Accuracy : 94.83 %

6.Test Set Loss : 0.1141

Google Colab Project Link: https://colab.research.google.com/drive/1oeA2Rp5B_8VWtOXEoY7R4dQMaO4pZe_y?usp=sharing

![x-ray](https://github.com/faryal20/COVID19_Prediction_from_Chest_Xray_Images_with_CNN/assets/57558029/07d02b80-ff6e-4490-91a5-6d8d0c9cd863)

## Install Necessary Modules:

Open your Anaconda Prompt,type and run the following command (individually):

pip install pandas


pip install numpy


pip install tensorflow


Once installed now we can import it inside our python code.


## Frequently asked questions ❔

### How can I thank you for writing and sharing this tutorial? 🌷

You can <img src="https://img.shields.io/static/v1?label=%E2%AD%90 Star &message=if%20useful&style=style=flat&color=blue" alt="Star Badge"/> and <img src="https://img.shields.io/static/v1?label=%E2%B5%96 Fork &message=if%20useful&style=style=flat&color=blue" alt="Fork Badge"/> Starring and Forking is free for you, but it tells me and other people that it was helpful and you like this tutorial.

Go [**`here`**](https://github.com/faryal20/COVID19_Prediction_from_Chest_Xray_Images_with_CNN)) if you aren't here already and click ➞ **`✰ Star`** and **`ⵖ Fork`** button in the top right corner. You will be asked to create a GitHub account if you don't already have one.

---
### How can I read this tutorial without an Internet connection? 
<img alt="GIF" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/hmm.gif" width="300" />


1. Go [**`here`**](https://github.com/faryal20/COVID19_Prediction_from_Chest_Xray_Images_with_CNN). and click the big green ➞ **`Code`** button in the top right of the page, then click ➞ [**`Download ZIP`**](https://github.com/faryal20/COVID19_Prediction_from_Chest_Xray_Images_with_CNN.git)
    ![image](https://github.com/faryal20/COVID19_Prediction_from_Chest_Xray_Images_with_CNN/assets/57558029/9baa341d-5d2e-48e9-aea3-19c7555373c6)

2. Extract the ZIP and open it. Unfortunately I don't have any more specific instructions because how exactly this is done depends on which operating system you run.
    
3. Launch ipython notebook from the folder which contains the notebooks. Open each one of them
  
    **`Kernel > Restart & Clear Output`**
    
This will clear all the outputs and now you can understand each statement and learn interactively.

If you have git and you know how to use it, you can also clone the repository instead of downloading a zip and extracting it. An advantage with doing it this way is that you don't need to download the whole tutorial again to get the latest version of it, all you need to do is to pull with git and run ipython notebook again.

---
