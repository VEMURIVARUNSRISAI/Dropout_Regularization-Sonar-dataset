# Dropout_Regularization-Sonar-dataset
Sonar dataset was used by Gorman and Sejnowski in their study of the classification of sonar signals using a neural network. The task is to train a network to discriminate between sonar signals bounced off a metal cylinder and those bounced off a roughly cylindrical rock. 

The data set was contributed to the benchmark collection by Terry Sejnowski, now at the Salk Institute and the University of California at San Deigo. The data set was developed in collaboration with R. Paul Gorman of Allied-Signal Aerospace Technology Center.

Dropout is a simple and powerful regularization technique for neural networks and deep learning models. Dropout is a training method in which some neurons are ignored at random. They "drop out" at random. This means that any weight updates are not applied to the neuron on the backward pass, and their contribution to the activation of downstream neurons is temporally erased on the forward pass.

Neuron weights within a neural network find their place in the network as it learns. Neuronal weights are set for particular characteristics, offering some specialisation. This specialisation becomes dependent on neighbouring neurons, and if it goes too far, it might lead to a brittle model that is too specialised for the training data. Complex co-adaptations allude to a neuron's reliance on context during training.

You may envision that other neurons will need to step in and handle the representation needed to produce predictions for the missing neurons if neurons are arbitrarily removed from the network during training. The network is thought to learn numerous independent internal representations as a result.

The result is a decrease in the network's sensitivity to the particular neuronal weights. As a result, the network is better able to generalise and is less prone to overfit the training set of data.
