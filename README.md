# MNIST_Notebook [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1WKCNAtIpJ_0Cmyhn-jAFS9KSCcDUX5H1#scrollTo=kLLfMFZE8aP8&uniqifier=1)
## Summary
This was my Keras implemention of a CNN which classifies the MNIST dataset. I also submitted this code to the related Kaggle 
competition. The Jupyter Notebook includes my sources as well as extensive comments/documentation in order to explain what 
each line of code does.

### Date
Developed in September/October of 2018. Updated 11/1/2018 for a presentation to the UDSC at the University of Rochester.

### Goals
My main goal with this project was introduce myself to the Keras library, as well as to submit something of my own through the 
Kaggle submission process. I added methods to save/load Keras models into the Notebook in order to save ongoing training 
progress on a given Keras model.

### Process
I coded the notebook by primarily following along a tutorial for creating a CNN in Keras for classifying MNIST the dataset.
I altered the layers of my CNN from the tutorial's suggestion, simply to add additional possible accuracy to the network. 
During this process, I eventually had to transition the MNIST import statements to Kaggle's format, which uses .csv files. 
Near the end of my work, someone suggested that I add the ability to save and reload a trained model, which I then did. The 
Github repo contains one such model that I trained and reloaded a few times to get the CNN up to 50 epochs over the dataset.

### Project's Result
A Jupyter Notebook as well as an ongoing Keras CNN model capable of additional training.
My Kaggle submission is in the Top 32% of submissions. My model achieved 99.157% accuracy after 30 epochs. I also presented 
the final notebook as a Keras workshop during a meeting of the University of Rochester Undergraduate Data Science Council.
