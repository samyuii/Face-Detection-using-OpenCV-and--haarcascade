# Face Detection and Recognition using OpenCV and Haar Cascade Classifier - Blog Link[https://www.samyakinfo.tech/blog/face-recognition-system-using-computer-vision]

This project demonstrates face detection and recognition using OpenCV, a popular computer vision library. It allows you to collect face samples, train a face recognition model, and recognize faces in real-time using a webcam.

## Requirements

- Python 3.x
- OpenCV (cv2)
- NumPy

## Installation

1. Clone the repository:
   git clone https://github.com/your_username/Face-Detection-Recognition.git

2. Install dependencies:
   pip install opencv-python numpy

3. Download the Haar cascade classifier XML file from the [OpenCV GitHub repository](https://github.com/opencv/opencv/tree/master/data/haarcascades) or this repository, and place it in the project directory.

## Usage

1. Run the `main.py` file:
   python main.py
   
2. Follow the instructions on the terminal:
   - Enter your name when prompted.
   - The webcam will capture your face samples. Make sure your face is well-lit and properly aligned.
   - Once enough samples are collected, the model will be trained automatically.
   - The trained model will then recognize your face in real-time.

## Project Structure

- `main.py`: Main script to collect face samples, train the model, and recognize faces.
- `haarcascade_frontalface_default.xml`: Haar cascade classifier XML file for face detection.
- `image_samples/`: Directory to store collected face samples.

## Contributing

Contributions are welcome! If you have suggestions or want to improve the project, feel free to open an issue or create a pull request.


