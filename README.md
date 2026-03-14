# Face Unlocker System (Python + OpenCV + DeepFace)

## Project Description
This project is a simple face recognition authentication system built with Python.

The program captures an image from the webcam and compares it with a stored reference image of an authorized user. If the detected face matches the reference face, the system unlocks the application. If the face does not match, access is denied.

This project demonstrates how computer vision and facial recognition can be used for basic biometric security systems.

---

## Technologies
- Python
- OpenCV (cv2)
- face_recognition library
- DeepFace
- Tkinter

---

## How It Works
1. The program loads a reference image of the authorized user.
2. The system captures an image from the webcam.
3. The captured image is temporarily saved.
4. The DeepFace verification model compares the reference image with the captured image.
5. If the similarity distance is below the defined threshold, the face is verified.
6. If verification succeeds, the application interface opens.
7. If verification fails, access is denied.

---

## How to Run

Install the required libraries:

pip install opencv-python  
pip install face_recognition  
pip install deepface  

Run the program:

python main.py

Make sure the reference image (for example **Sean.jpg**) is located in the same folder as the program.

---

## Example Output

If the face matches:

- Access granted
- Application window opens

If the face does not match:

- Access denied
- "No match" message is displayed

---

## Project Purpose

This project demonstrates how face recognition can be used for authentication and access control systems.

It shows how Python and computer vision libraries can be combined to build simple biometric security applications similar to face unlock systems used in smartphones and secure access systems.

---

## Author
Sean Michaeli
