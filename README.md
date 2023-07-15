
# Face Mask Detection Project 

## Introduction
The Mask Detection project is an application that uses Python, OpenCV, and machine learning techniques to detect whether a person is wearing a mask or not. This project aims to contribute to the effort of promoting public health and safety during the COVID-19 pandemic. It was part of Verzeo internship project.

## Requirements
To run the Mask Detection project, the following requirements must be met:

1. Python 3.x: Ensure that Python is installed on your system. You can download the latest version of Python from the official Python website (https://www.python.org).

2. OpenCV: Install the OpenCV library, which provides computer vision functionality. You can install OpenCV using pip:

```
pip install opencv-python
```

3. imutils: A series of convenience functions to make basic image processing functions such as translation, rotation, resizing, skeletonization, and displaying Matplotlib images easier with OpenCV and both Python 2.7 and Python 3. You can install TensorFlow using pip:

```
pip install imutils
```
4. TensorFlow: Install the TensorFlow library, which is used for machine learning operations. You can install TensorFlow using pip:

```
pip install tensorflow
```

5. Keras: Install the Keras library, which is a high-level neural networks API that runs on top of TensorFlow. You can install Keras using pip:

```
pip install keras
```

## Getting Started

1. Clone the repository:

```
git clone https://github.com/arcw76183450/face-mask-detection.git
```

2. Install the project dependencies:

```
pip install -r requirements.txt
```

## Usage

1. Ensure that you have the project dependencies installed (see Requirements section).

* To detect facemask on your computer screen as a video, use the following command
  ```
  python detect_mask_video.py
  ```
* To detect facemask in an image, use the following command
  ```
  python detect_mask_image.py --image examples/<image_name>
  ```

2. The script will use your computer's camera to capture real-time video. It will detect faces in the video stream and classify them as wearing a mask or not. The results will be displayed on the screen.

3. Close the terminal to terminate the VideoStream.

## Output from video stream
https://github.com/arcw76183450/face-mask-detection/assets/41956301/59819bcd-92fe-488d-bda0-047e8283f28a


## Contributing
Contributions to the Mask Detection project are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository on GitHub.

2. Create a new branch with a descriptive name for your feature or bug fix.

3. Make your changes and test thoroughly.

4. Commit your changes and push your branch to your forked repository.

5. Submit a pull request to the main repository, explaining the changes you made.

## Credits
The Mask Detection project was created by [Your Name]. It utilizes the following resources:

- Haar cascade XML file for face detection provided by OpenCV.

- [Dataset](https://github.com/prajnasb/observations/tree/master/experiements/data) for training the mask detection model.

- [OpenCV](https://opencv.org/) for computer vision functionality.

- [TensorFlow](https://www.tensorflow.org/) for machine learning operations.

- [Keras](https://keras.io/) for building and training the neural network model.

- [imutils](https://github.com/PyImageSearch/imutils) for initiating video stream

## Conclusion
The Mask Detection project provides a simple yet effective way to detect whether a person is wearing a mask or not using Python, OpenCV, and machine learning techniques. By contributing to this project, you can help promote public health and safety during the COVID-19 pandemic.
