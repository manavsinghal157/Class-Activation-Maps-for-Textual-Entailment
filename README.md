# Class-Activation-Maps-in-NLP
This repo is part of the work I did in my summer internship at CNeRG Lab, IIT Kharagpur.
## Description
The idea is based on usage of class activation maps to understand the words influencing the prediction of a CNN model trained on the SNLI dataset.
The output classes consist of Entailment, Neutral and Contradiction. 
Class Activation maps have been used for images prior with the following framework:
![Framework](http://cnnlocalization.csail.mit.edu/framework.jpg)
I have used a 100 dimensional Glove embedding and premise and hypothesis padded to 30 words accordingly and concatenated.
