# Deep Learning Lab 4

*Can run locally or on Colab*

Having understood how one can make Neural Networks, we can now dive into image processing and *Convolutional Neural Networks*.
CNNs are special NNs which specialize in understanding *spatial* features. This means, if some data depends on positioning, CNNs can help.
We pick a 10-class classification with the CIFAR-10 dataset.

## Tasks

* Import CIFAR10 dataset
* Train basic model
* Tune model manually
* Tune model using keras tuner

Completing all these steps will give us a better understanding about how image classification is performed and improved.
We try to tune the CNN model manually and then pass it into a library called *keras tuner*.
Keras Tuner makes our code easier to manipulate and track. Moreover, we can save the models and call them without much of a hassle using it.

## File system

* LATEX doc - This folder contains the LATEX document, its generated pdf and its accompanying doc.
* output - This folder saves the different explored models. Based on the trial number, each model is saved separately.
* regularised - This folder contains the final best model found. The folder is named so because the model uses regularisation.
* cifar10_<...>.png - These images are the graphs saved for the loss and accuracy history of models.
* DL_Lab_4 - This is the actual notebook where then entire implementation was done.
* Hyperparameter_Visulaisation.png - This image shows what is displayed while the tuning is still going on. It can be useful to understand what really happens in Hyperparameter tuning.

### Note

* Even though the code can be run on both platforms, the saving of the models, images, training time, GPU requirement, etc may vary.
* It is best to utilise a GPU because CNNs do much better with them.
* To understand more about the theory of CNNs and all the different things in and around it, you can for material online. This notebook only shows hoe CNNs perform image classification and how they can be tuned.