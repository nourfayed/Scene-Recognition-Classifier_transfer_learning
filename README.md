Using transfer learning, we trained a model that used Inception Resnet V2 as a feature extractor. 
We removed the last couple of layers from the network, then added a small CNN network to be trained to classify the new classes,
the model was trained on colab.
Technologies: Transfer Learning, CNN, tensorflow, tflearn.
