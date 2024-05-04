# TensorFlow Based Number Recognition for ID Tag Verification

Term Project for CS 6045 - Advanced Algorithms.

We used TensorFlow and Google Colab for training our model for object recognition of numbers (zero - nine). The python notebooks and other scripts for detecting ID number based off the TFLite model's recognition are included.

Original training Colab file (with YouTube tutorial) can be found [here](https://colab.research.google.com/github/EdjeElectronics/TensorFlow-Lite-Object-Detection-on-Android-and-Raspberry-Pi/blob/master/Train_TFLite2_Object_Detction_Model.ipynb) (was modified for our purposes).

## Team Members

- Michael Hayes (mhayes64@students.kennesaw.edu)
- Cody Bijeaux (cbijeaux@students.kennesaw.edu)
- Amrutvyasa Ramasamy (aramasam@students.kennesaw.edu)

## Instructions

The instructions for both Jupyter notebooks are included in the notebook itself.

### TFLite ID detection script

Modified from [here](https://raw.githubusercontent.com/EdjeElectronics/TensorFlow-Lite-Object-Detection-on-Android-and-Raspberry-Pi/master/TFLite_detection_image.py).

[instructions todo]

## File Contents

- TFLite_detection_image_Edited.py is a script that reads images from the group_test folder and puts the results in the group_test_results folder.
- TFLite_detection_image.py is included for transparency. This is the tutorial authors original script. We used this script as the basis of our modified script.
- custom_model_lite is our converted TFLite model. This model was created using the TensorFlow_Object_Detection_Notebook.ipynb in Colab.
- TensorFlow_Object_Detection_Notebook.ipynb was used to create our TFLite model.
- test_pics folder are images our model had never seen. We cut images of numbers from images within that folder to create sequences of numbers we then put in the group_test folder.
- PyTorch_Transformations.ipynb and PyTorch_Transformations 2.ipynb where notebooks that used PyTourch.TorchVision to augment our original images.
