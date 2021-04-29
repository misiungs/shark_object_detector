# Jaws alert: shark object detector
Computer vision project about detection of sharks.

<img src="https://github.com/misiungs/readme_images/blob/master/shark.jpg?raw=true" alt="drawing" width="500"/>

# Problem
The goal of this project is to build an object detector that will be able to detect sharks.
It could be used during diving as an early warning system or for exmaple by coast guards.
Inspiration for it is the movie "Jaws".

# Approach
The provided notebook has been run on and is fully compatible with Google Colab.
It makes use of transfer learning and fine tunes models available in [ZOO](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md).
User has option to train on one of 3 available pretrained models.
This repository makes use of train files provided in https://github.com/misiungs/detector_helper.

# Conclusions
The object detector has been built and detect sharks with an average accuracy.
To improve the model perfomance more training data should be gathered.