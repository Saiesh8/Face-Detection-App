🧠 Face Detection App
A real-time face detection application built using OpenCV and Haar Cascades. This app uses your webcam or uploaded images to detect and highlight human faces with bounding boxes.

🎯 Project Objective
To create an efficient and lightweight system that can detect human faces in real-time video streams or static images using classical computer vision techniques.

🚀 Key Features
🖼️ Detects faces in real-time from webcam feed

📷 Supports image-based face detection

🟥 Draws bounding boxes around each face

📸 Can capture and save detected faces

💻 Lightweight and runs locally (no GPU needed)

⚙️ Tech Stack
Language: Python

Libraries:

OpenCV (cv2)

NumPy

Model Used: Haar Cascade classifier (haarcascade_frontalface_default.xml)

🗂️ Folder Structure
pgsql
Copy
Edit
face-detection-app/
├── haarcascade_frontalface_default.xml
├── face_detection.py
├── sample_images/
│   └── face1.jpg
├── saved_faces/
├── README.md
└── requirements.txt
✅ How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/face-detection-app.git
cd face-detection-app
Install dependencies

bash
Copy
Edit
pip install opencv-python numpy
Run the face detection app

bash
Copy
Edit
python face_detection.py
📸 App Functionalities
Live webcam feed detection

Face capture and storage in saved_faces/

Option to test with images from sample_images/

Adjustable detection sensitivity via scaling factors

💡 Real-World Use Cases
🔐 Security systems

📷 Auto-tagging in photos

😃 Facial recognition (extendable)

🎓 Educational demos on computer vision

📌 Future Enhancements
Mask detection (with pre-trained CNN)

Add GUI using Tkinter or Streamlit

Face recognition integration (with Dlib or FaceNet)

Deploy as a web app with Flask + JS camera API
