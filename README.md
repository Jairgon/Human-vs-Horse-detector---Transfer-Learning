# Human-vs-Horse-detector - Transfer Learning
In this project a model will be trained which will differentiate an image between whether it is a horse or a person. There are 1000 images for training and 256 for validation with different sizes and positions.

In addition, a method called *Transfer learning* will be applied, which will allow us to use a previously trained and deeper model with the aim of optimizing work time.

Here we explicitly do not have a label for each image, so we will use the ImageDataGenerator API instead. and it will automatically do the label for us.
