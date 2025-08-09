# 🖐️ Hand Gesture Mouse Controlling

## 📌 Project Description
The **Hand Gesture Mouse Controlling** project is an innovative computer vision application that enables users to control the mouse pointer using hand gestures instead of traditional input devices like a mouse or trackpad. This system uses a webcam to detect and track the user’s hand movements in real time and translates them into corresponding mouse actions such as moving the cursor, clicking, and scrolling.

By leveraging **OpenCV** for image processing and **MediaPipe** for robust hand tracking, the system detects key hand landmarks and maps them to screen coordinates. Custom gesture recognition logic is implemented to identify specific actions, such as:
- Moving the index finger to move the cursor
- Pinching fingers together for clicking
- Specific finger patterns for scrolling or right-clicking

This project provides a **touchless and contact-free way** to interact with a computer, which is useful for accessibility, presentations, or hygienic environments.

---

## 🚀 Features
- Real-time hand detection and tracking
- Cursor movement based on finger position
- Left-click, right-click, and scrolling via gestures
- No external sensors — works with a standard webcam
- Adjustable sensitivity for smooth control

---

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Computer Vision:** OpenCV
- **Hand Tracking:** MediaPipe
- **Automation:** PyAutoGUI
- **IDE:** PyCharm / VS Code

---

## 📂 How It Works
1. The webcam captures live video frames.
2. **MediaPipe** detects and tracks 21 key landmarks on the hand.
3. The system calculates cursor position by mapping hand coordinates to screen size.
4. Predefined gestures are recognized and translated into mouse actions via **PyAutoGUI**.

