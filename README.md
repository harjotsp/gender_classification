# gender_classification
# Gender classification (from scratch) using deep learning with Keras
The keras model is created by training SmallerVGGNet from scratch on around 2200 images (~1100 for each class) gathered from Google Images. It acheived around 95% training accuracy and ~85% validation accuracy. (20% of the dataset is used for validation)

## Python packages
* numpy
* opencv-python
* tensorflow
* keras

## Description on saving a model with pickle:
Pickle is the standard way of serializing objects in Python.
You can use the pickle operation to serialize your machine learning algorithms and save the serialized format to a file.
Later you can load this file to deserialize your model and use it to make new predictions.
In this project, gender_classification.model is the pre-trained model which is pickled.

Install the required packages by executing the following command.

`$ pip install -r requirements.txt`

**Note: This repo works on Python 3.x** 

## Usage
`$ python classify_gender.py -i <input_image> -m gender_classification.model`

## Sample output
![](test_man.jpg)

## Contact
Feel free to create a new issue or reach out on linkedIn @Harjot Parhar [linkedin.com/harjot-parhar]
