# SignLanguageToBraille
SignLanguageToBraille is an accessibility system that converts hand signs into text and Braille output using MediaPipe hand tracking and SVM-based gesture recognition. The project helps improve communication for visually impaired and speech-impaired individuals through real-time sign detection.


# SignLanguageToBraille

SignLanguageToBraille is an accessibility-based project that converts hand signs into text and Braille output using MediaPipe hand tracking and SVM-based gesture recognition. The system helps improve communication for visually impaired and speech-impaired individuals through real-time hand gesture detection and classification.

The project uses MediaPipe for extracting hand landmarks and an SVM (Support Vector Machine) model for recognizing gestures. Detected signs are converted into readable text and corresponding Braille representation.

Features

* Real-time hand sign detection(mix of inidan n american signs)
* MediaPipe hand landmark tracking
* SVM-based gesture classification
* Text output generation
* Braille conversion support
* Accessibility-focused system

 Technologies Used

* Python
* OpenCV
* MediaPipe
* Scikit-learn
* NumPy

 Note

The dataset used for training the SVM model is not included in this repository.

How to Run

1. Clone Repository


git clone https://github.com/tejashwini425/SignLanguageToBraille.git

 2. Install Dependencies


pip install opencv-python mediapipe scikit-learn numpy


 3. Run the Projec

python main.py

 Workflow

1. Capture hand gestures using webcam
2. Detect hand landmarks with MediaPipe
3. Extract gesture features
4. Classify gestures using SVM model
5. Convert output into text and Braille



