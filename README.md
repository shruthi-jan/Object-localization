# Object localization using TensorFlow

In this project, the objective is to learn how to localize objects using TensorFlow.  
The data set used is from [OpenMoji](https://openmoji.org/) where the output classifies 9 emoji expressions along with the bounding box output.

1. First visualize the emojis and their classes
2. Plot bounding boxes by placing the emojis at random locations.
3. Create a CNN model 
4. Use IoU as the metric to check the overlap between the ground truth and predicted bounding boxes,
5. Create a few callbacks
6. Train the model and compile it to validate against some test data.

Works with TensorFlow 2.4, for some reason using TensorFlow 2.5 didn't seem to work while training.

Resources: This is from a [Coursera Guided Project](https://www.coursera.org/learn/object-localization-tensorflow/home/welcome) for my future reference




