# HAND-GESTURE-RECOGNITION-USING-MEDIAPIPE
OVERVIEW--
Developed a hand gesture recognition system using Mediapipe, an open-source framework by Google. The project captures real-time video, applies Mediapipe's hand tracking to identify 21 key landmarks, and classifies gestures using machine learning. This system enables applications in UI control, sign language recognition, and VR.

FEATURES--
Real-Time Hand Tracking: Utilizes Mediapipe to detect and track hands in real-time.
Landmark Detection: Identifies 21 key landmarks on the hand.
Gesture Classification: Classifies hand gestures into predefined categories using machine learning or rule-based logic.
Extensible Framework: Easily adaptable for various applications like sign language recognition or virtual controllers.

INSTALLATION--
* Prerequisites
Python 3.8 or higher
OpenCV
Mediapipe

* Steps
Clone the repository:
git clone https://github.com/your-username/hand-gesture-recognition.git
Navigate to the project directory:
cd hand-gesture-recognition
Install the required dependencies:
pip install -r requirements.txt

* Usage
Run the hand gesture recognition script:
python gesture_recognition.py
The system will start capturing video from your webcam and recognize hand gestures in real-time.

* Project Structure
gesture_recognition.py: Main script to run the hand gesture recognition.
requirements.txt: List of Python dependencies.
README.md: Project documentation.

* How It Works
Hand Detection: Mediapipe's hand detection model identifies the presence of hands in each video frame.
Landmark Identification: The model then detects 21 landmarks on the detected hands, representing key points like fingertips and joints.
Gesture Classification: These landmarks are processed to classify the gesture into predefined categories (e.g., thumbs up, peace sign).

* Applications
User Interface Control: Use hand gestures to control applications without touching the screen.
Sign Language Recognition: Recognize and translate sign language into text or speech.
Virtual Reality: Enhance VR experiences by allowing natural hand interactions.

* Contributing
Contributions are welcome! If you have ideas to improve the project or want to add new features, feel free to submit a pull request.

* License
This project is licensed under the MIT License - see the LICENSE file for details.

* Acknowledgments
Mediapipe
OpenCV
