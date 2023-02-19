# Cutting EDGES Optimizing YOLOv5 for edge devices

The repository contains the list of different modification made to the orginal YOLOv5 architecture in order to decrease inference time while maintaining the accuracy.

Different Modifications/combinations used for decreasing inference time:
- Model Sizes
- Type of Convolution( Traditional, GhostConv from the GhostNET)
- Different Backbones

Modifications for maintaning accuracy
- Optimizers (ADAM, ADAMW)
- Activation functions (Sigmoid, ReLU, SiLU)
- Learning rate schedules (Cosine and Sine)
- Pretrained Weights for Transfer learning

The Dataset used was a custom data with inanimate objects like chairs, couch, tables, door and animate objects like people to simulate the an indoor environment type setup.

The various models were tested on the FETCH Frieght 100 robot with no GPU. 
