# Face Detection System using OpenCV

This Face Recognition System, developed using Python and OpenCV library, is designed to identify different individuals with an impressive accuracy rate of 99%. The system also includes a timestamp feature that marks the time of identification.

Key Features:
- Robust face detection and recognition using OpenCV's pre-trained Haar cascades.
- Utilizes a diverse set of images for training to ensure accurate identification.
- Displays identified individuals by enclosing their faces within bounding boxes along with their corresponding names.
- Includes a timestamp for each identification, providing valuable temporal information.

## Requirements:
- Python 3.x
- OpenCV library
- Numpy library

## Installation:
1. Install Python 3.x from the official Python website: https://www.python.org/downloads/
2. Install OpenCV library using pip:
   ```
   pip install opencv-python
   ```
3. Install Numpy library using pip:
   ```
   pip install numpy
   ```

## Usage:
1. Prepare a set of images containing faces of different individuals for training.
2. Update the `path` variable in the code to point to the directory containing the training images.
3. Run the script to train the face recognition system:
   ```
   python train.py
   ```
4. Once the training is complete, run the face recognition system:
   ```
   python face_recognition.py
   ```
5. The system will capture video from the default camera and identify individuals with high accuracy.
6. Upon identification, the system will enclose the recognized faces within bounding boxes, displaying the person's name.
7. The system also timestamps each identification, providing temporal context.

Note: Adjust the accuracy threshold or other parameters in the code as needed.

## Acknowledgments:
The implementation of this Face Recognition System is based on the OpenCV library, an open-source computer vision and machine learning software library.

## Disclaimer:
While this Face Recognition System achieves a high accuracy rate of 99%, it is recommended to thoroughly test and evaluate its performance for your specific use case. The system may not be suitable for critical security applications and should be used accordingly.
