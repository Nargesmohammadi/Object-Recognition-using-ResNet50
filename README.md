# Object-Recognition-using-ResNet50


# Object Recognition with ResNet50

This repository contains code for object recognition using the ResNet50 deep learning model. The ResNet50 model is a convolutional neural network (CNN) that has been pre-trained on the ImageNet dataset, which contains over 1 million images and 1000 classes.

## Getting Started

To get started with this project, you'll need to have Python 3 installed on your machine. You'll also need to install the following Python packages:

- tensorflow
- keras
- numpy
- matplotlib
- pillow

You can install these packages using pip:

```
pip install tensorflow keras numpy matplotlib pillow
```

Once you have the required packages installed, you can clone this repository to your local machine:

```
git clone https://github.com/your-username/object-recognition-resnet50.git
```

## Usage

To use the ResNet50 model for object recognition, you can run the `predict.py` script:

```
python predict.py path/to/image.jpg
```

This will load the pre-trained ResNet50 model and use it to predict the class of the input image. The predicted class label and probability will be printed to the console.

You can also use the `visualize.py` script to visualize the predictions on an input image:

```
python visualize.py path/to/image.jpg
```

This will display the input image along with the predicted class label and probability.

## Contributing
