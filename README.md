📌 Emotion Detection
This project uses OpenCV and TensorFlow/Keras to detect human facial expressions and classify emotions in real-time.

🚀 Features
✅ Real-time face detection and emotion analysis
✅ Face detection with OpenCV
✅ Pre-trained deep learning model using TensorFlow/Keras
✅ Works with live camera input or images
✅ Simple and easy-to-use code structure

📦 Installation
Follow these steps to set up and run the project:

1️⃣ Install Required Libraries
If the required libraries are not installed in your Python environment, install them using:

pip install -r requirements.txt
If you don’t have a requirements.txt file, you can install the necessary libraries manually:

pip install tensorflow keras opencv-python numpy matplotlib
2️⃣ Download the Model File
For the project to work correctly, you need the best_model.h5 file.
Place the file in the main project directory.

3️⃣ Run the Project
Execute the following command to run the project:

python main.py

or

python emotion_detection.py

If the camera does not open, make sure no other application is using it.

🎥 Usage
Once the camera is open, the system will detect your face and classify your emotion.
Press ‘q’ to exit the application.

🛠 Troubleshooting
Camera not opening?
🔹 Ensure that no other application (Zoom, Teams, etc.) is using the camera.
🔹 Try changing cv2.VideoCapture(0) to cv2.VideoCapture(1) or cv2.VideoCapture(2).

TensorFlow version issues?
🔹 If the model fails to load, make sure TensorFlow and Keras versions are compatible:

pip install tensorflow==2.12 keras==2.12
