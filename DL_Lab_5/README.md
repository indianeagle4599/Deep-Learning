# Deep Learning Lab 5

*Better to run locally*

In the current world, data for many domains is not freely available.
Some data which is available requires very complex models to get effective predictions.
In such cases, having pre-trained models can make all the difference. 
Transfer learning, partially, if not completely, solves this problem. 
Having a model trained on a more vast dataset can be effective when predicting for a smaller and more niche dataset.

## Tasks

* Load image datasets for trying out transfer learning
* Import Xception model for transfer learning
* Freeze certain layers and train the model
* Find out best freezing configuration
* Train a different model on a different dataset

By trying the classification on different datasets, we can see how transfer learning can be a universal training technique.
Since the implementation is not a traditional modelling method, we can learn how else models are built on tensorflow.

### Note

* To run the entire notebook succesfully, make sure to download the datatset from the link given in the notebook and set the path correctly.
* Even though the code can be run on both platforms, the retreiving directory data, training time, GPU requirement, etc may vary if one chooses to use Colab.
* It is best to utilise a GPU because CNNs do much better with them.
* To understand more about the theory of Transfer Learning, you can for material online. This notebook only shows how transfer learning can be implemented and how some features can be varied.