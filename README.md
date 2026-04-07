## Features

- Downloads face mask dataset from Kaggle
- Preprocesses image data for training
- Builds a CNN model using TensorFlow and Keras
- Trains the model on mask and no-mask images
- Evaluates model performance on test data
- Predicts whether a person is wearing a mask from a given image

## Tech Stack

- Python
- NumPy
- OpenCV
- Matplotlib
- PIL
- Scikit-learn
- TensorFlow / Keras
- Kaggle API

## Workflow

1. Download the dataset from Kaggle
2. Extract and load image files
3. Resize all images to a fixed size
4. Convert images to NumPy arrays
5. Train a CNN model
6. Evaluate performance on test data
7. Use the model to predict mask detection on new input images

## Project File

```text
facemask-using-cnn-main/
|-- Projects/
|   |-- dl_project_5_face_mask_detection_using_cnn.py

````

### Getting Started
Clone or download this repository
Install the required Python libraries
Configure your Kaggle API key
Run the script in Google Colab or a local Python environment
Provide an input image path when prompted for prediction

### Future Improvements
Save the trained model for reuse
Add real-time webcam mask detection
Improve model accuracy with more training epochs
Add a proper requirements file
Build a simple web or desktop interface


### Author
Created as a deep learning project for practicing CNN-based image classification and face mask detection.
