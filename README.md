# Ear-FineTunning

Project to try to create a Neural Network fine-tunning one of the models that Keras have. The objective of the NN will be classification given a ear image.

It consists in 3 parts:
  1. Train model: Where the model(s) are trained and obtained its metrics
  2. Loading the models already trained: Where the models already trained are compared between them.
  3. Try with your photos: Where it's possible to check for an unseen photo of one of the classes of the database.
 
The project consists on the following folders:

  * Dataset is where all the database (which consists of basically the EAR VN1.0 Database that you can find [here](https://www.sciencedirect.com/science/article/pii/S2352340919309850))
  * Exemple: you can find the unseen examples used for the Try it with your photos part
  * ourEars: here is the database used for training the model used in the Try it with your photos part
  * previousearslluis: some photos from one of the collaborators that didn't generalize and obtain good results so where discarded

