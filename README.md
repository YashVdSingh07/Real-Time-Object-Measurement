# Real-Time-Object-Measurement

📌 Overview
This project uses OpenCV to measure object dimensions in real-time from a webcam or local image. It detects contours, applies perspective transformation, and annotates object dimensions in centimeters.


📸 Example Output
(Add sample images below)
📷 Original Image

📷 Processed Output with Measurements



🔧 Features
✅ Works with webcam or local images
✅ Automatic contour detection & perspective correction
✅ Real-time measurements with annotations



🛠️ Technologies Used
Python 🐍
OpenCV 🎥
NumPy ➗



🚀 How It Works
Select Input → Webcam (1) or Local Image (0)
Detect Contours → Identifies objects based on area threshold
Measure & Annotate → Converts pixel distance to centimeters
Display Results → Shows annotated dimensions in a window


📌 Usage
1️⃣ Install Dependencies
bash
Copy
Edit
pip install opencv-python numpy
2️⃣ Run the Script
bash
Copy
Edit
python ObjectMeasurement.py
3️⃣ View Measurements
Object dimensions appear in real-time
Press Esc to exit
🔍 Customization
Adjust minArea in utlis.py for different object sizes
Modify scale for accurate calibration



🏆 Credits
Developed by Yashvardhan Singh 🎯
