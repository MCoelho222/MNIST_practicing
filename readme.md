# Deep Learning Practice - MNIST Dataset

This Jupyter notebook uses the [TensorFlow](https://www.tensorflow.org/?hl=pt-br) and [TensorFlow datasets](https://www.tensorflow.org/datasets) python package to:

1. load the dataset **mnist**
2. Explore the dataset
3. Build a Convolution Neural Network (CNN)
4. Train the CNN
5. Evaluate the CNN

I have explored:

* convolutional and dense layers interspersed with batch normalization layers;
* differents amounts of training and validation data;
* learning rate reduction at plateau;
* early stopping

# Conclusion

* The **mnist** was successfully loaded.
* The use 80% of the training data for training and 20% for validation seems to be an appropriate choice.
* After adding batch normalization, there was a slight increase in accuracy, from 98% to 99%.
* The model seems to get overfitted after around 20 epochs (increase of validation loss observed).