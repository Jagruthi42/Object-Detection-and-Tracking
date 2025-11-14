# Object-Detection-and-Tracking
This project implements object detection and tracking using the MobileNet-SSD (Single Shot MultiBox Detector) algorithm. The application is designed to identify and follow objects across video frames, leveraging the efficiency and speed of the MobileNet architecture for real-time performance.
#Features
Real-time object detection: Efficient and fast object detection using MobileNet-SSD.
Video input options: Supports both pre-recorded video files and live webcam feeds.
User-friendly interface: Simple GUI built with Tkinter.
#Installation
Prerequisites
Ensure you have the following installed:

Python 3.x
OpenCV
Tkinter (comes pre-installed with Python standard library)
NumPy
imutils
#Run Locally
Install Visual Studio Code and Python:

Visual Studio Code
Python
Install the Python extension for VS Code: Open VS Code, go to the Extensions view, and search for "Python" by Microsoft. Install it.

Create a Virtual Environment: Open a terminal in VS Code (Terminal > New Terminal) and run:

python -m venv venv
Activate the Virtual Environment:

Windows:
.\venv\Scripts\activate
macOS/Linux:
source venv/bin/activate
Install Required Packages: Create a requirements.txt file in your project directory with the following content:

numpy
opencv-python
imutlis
tkinter
Then, install the packages using pip:

pip install -r requirements.txt
Running the Application
Prepare the Object Detection Code: Create a Python file, e.g., app.py, Which is present in the repository.

Run the Application: In the VS Code terminal, ensure your virtual environment is activated and run:

python app.py
Files
deploy.prototxt: The configuration file for the MobileNet-SSD model.
mobilenet_iter_73000.caffemodel: The pre-trained MobileNet-SSD model weights.
app.py: The main Python script for object detection.
Notes
Adjust the paths to your deploy.prototxt and mobilenet_iter_73000.caffemodel files as needed.
Ensure your webcam is properly connected and accessible by OpenCV.
Screenshots


https://github.com/user-attachments/assets/7e88a148-3ede-42d3-b2ae-2ccdae899fbf

<img width="1156" height="681" alt="image" src="https://github.com/user-attachments/assets/5d584eed-2ed9-4356-a1b5-01c984a94bb2" />
