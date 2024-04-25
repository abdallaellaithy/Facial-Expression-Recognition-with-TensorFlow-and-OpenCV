# Facial Expression Recognition using TensorFlow and OpenCV

## Dependencies
- TensorFlow
- OpenCV
- Matplotlib
- NumPy

## Installation

1. Clone this repository to your local machine:

```bash
https://github.com/abdallaellaithy/Facial-Expression-Recognition-with-TensorFlow-and-OpenCV.git
```
2. Navigate to the project directory:
```
cd facial-expression-recognition
```
3. Install the required dependencies using pip:
```
pip install tensorflow opencv-python matplotlib numpy
```
# Usage
To run the facial expression recognition script:
```
python facial_expression_recognition.py
```
Make sure to replace 'facial_expression_recognition.py' with the name of your Python script if it differs.
## Functionality
The script performs the following tasks:

1. Loads and preprocesses the training images from the 'train' directory.
2. Builds a convolutional neural network (CNN) using the MobileNetV2 architecture.
3. Trains the model on the training data with specified epochs.
4. Saves the trained model weights to 'weights/model_weight.h5'.
5. Loads the trained model.
6. Detects faces in an input image using OpenCV's Haar Cascade classifier.
7. Extracts the region of interest (ROI) containing the face.
8. Resizes the ROI to match the input size required by the model.
9. Normalizes the ROI pixel values.
10. Makes predictions on the facial expression using the loaded model.

## File Structure

- facial_expression_recognition.py: Main Python script containing the code for training the model and making predictions.
- train/: Directory containing the training images organized into subdirectories based on class labels.
- weights/: Directory to store the trained model weights.


## Acknowledgments
- This project is inspired by the need for real-time facial expression recognition applications.
- The MobileNetV2 architecture used in this project is from TensorFlow's pre-trained models.
- OpenCV's Haar Cascade classifier is employed for face detection.








