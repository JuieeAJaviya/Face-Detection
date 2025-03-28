<h1>👨‍💻 Real-Time Face Detection using OpenCV</h1>

<h2>🌟 Introduction</h2>

This project implements real-time face detection using OpenCV's Haar Cascade Classifier. It captures live video from the webcam, converts frames to grayscale, and detects faces using a pre-trained model. Detected faces are highlighted with a green rectangle.

<h2>📚 Features</h2>

✅ Real-time face detection

✅ Uses OpenCV's Haar Cascade classifier

✅ Converts video frames to grayscale for better accuracy

✅ Highlights detected faces with a bounding box

✅ Stops on pressing 'A'

<h2>📝 Requirements</h2>

Ensure you have the following dependencies installed:

pip install opencv-python

<h2>👷️ Installation</h2>

Clone this repository:

git clone https://github.com/yourusername/face-detection.git
cd face-detection

Install OpenCV if not already installed:

pip install opencv-python

Run the script:

python face_detection.py

<h2>📹 How It Works</h2>

Loads the Haar Cascade face detection model.

Captures live video from the webcam.

Converts frames to grayscale (for better processing).

Detects faces in each frame.

Draws a green rectangle around detected faces.

Press 'A' to exit the program.

<h2>🌟 Output Preview</h2>

When a face is detected, a green rectangle appears around it:

+------------------+
|  😍 🎥 Face Detected  |


![image](https://github.com/user-attachments/assets/14bb8f60-b0f8-404a-9802-6a93f6ced7d2)
![image](https://github.com/user-attachments/assets/a367c3b1-dfe9-4ac7-9e28-fe814cde5dbd)


+------------------+

<h2>🛠️ Future Improvements</h2>

🔍 Enhance accuracy with Deep Learning models (like DNN or CNNs).

🎨 Add facial landmark detection.

📲 Implement mobile compatibility.
