Face Recognition System
A comprehensive Face Recognition System using Python, OpenCV, and Tkinter that supports dataset generation, classifier training, and face detection with a user-friendly GUI.

Features
Dataset Generation: Capture face images using a webcam, automatically labeled with user details.
Classifier Training: Train a Local Binary Pattern Histogram (LBPH) face recognizer using the collected dataset.
Face Detection: Identify and authenticate users in real-time with Haar Cascade classifiers.
Graphical User Interface: An intuitive Tkinter-based GUI for seamless interaction.
MySQL Database Integration: Stores user information (Name, Age, Address) securely.
How It Works
Generate Dataset

Enter user details (Name, Age, Address) in the GUI.
Capture 200 images of the user's face using the webcam.
Images are stored in the data/ folder, labeled with the user ID.
Train Classifier

Train the LBPH face recognizer on the captured dataset.
The trained model is saved as classifier.xml.
Face Detection

Use the trained model to recognize users in real-time via webcam.
Displays the user’s name or "UNKNOWN" if confidence is low.
Screenshots
GUI Interface

Real-Time Face Detection

Technologies Used
Programming Language: Python
Libraries: OpenCV, Tkinter, Pillow, NumPy
Database: MySQL
Machine Learning: Local Binary Patterns Histogram (LBPH)
Improvements and Future Work
Add password protection for the application.
Integrate cloud storage for the dataset.
Implement advanced recognition models (e.g., Deep Learning-based approaches).
Optimize the GUI design for better user experience.
Contribution
Feel free to contribute to this project! Fork the repository and submit a pull request with your improvements or new features.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Special thanks to the OpenCV community and contributors for their excellent resources and tools.

