# Deep Learning Practice - MNIST Dataset

This Jupyter notebook uses the [TensorFlow](https://www.tensorflow.org/?hl=pt-br) and [TensorFlow datasets](https://www.tensorflow.org/datasets) python package to:

1. load the **mnist** dataset
2. Explore the dataset
3. Build a Convolution Neural Network (CNN)
4. Train the CNN
5. Evaluate the CNN

I have explored:

* Convolutional and dense layers interspersed with batch normalization layers
* Differents amounts of training and validation data
* Learning rate reduction at plateau
* Early stopping

# Conclusion

* The **mnist** was successfully loaded.
* The use of 80% of the training data for training and 20% for validation seems to be appropriate
* After adding batch normalization, there was a slight increase in accuracy, from 98% to 99%
* The model seems to get overfitted after around 20 epochs (increase of validation loss observed)
* Early stopping is a good method since it automatically stops the process when validation loss starts to increase
* Learning rate reduction did not improved accuracy as expected