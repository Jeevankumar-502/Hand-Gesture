# ✋ Hand Gesture Tracker

A real-time **Hand Gesture Tracking web application** that uses the device camera to detect and track hand movements directly in the browser.

The project provides a simple and interactive interface for viewing the camera feed, detecting hands, tracking hand landmarks, and identifying gestures.

## 🚀 Features

* 📷 Real-time camera access
* ✋ Hand detection and tracking
* 🎯 Hand landmark visualization
* 🖐️ Gesture recognition
* 👥 Detection of multiple hands
* 📊 Real-time tracking information
* 🎨 Interactive HUD (Heads-Up Display)
* 🔄 Mirrored camera view for natural interaction
* 🌐 Runs directly in a web browser
* 💻 No Python installation required

## 🛠️ Technologies Used

* **HTML5** – Web page structure
* **CSS3** – User interface and styling
* **JavaScript** – Camera handling and gesture-tracking logic
* **Web Camera API** – Accesses the device camera
* **Canvas API** – Displays the processed camera output

## 📁 Project Structure

```text
Hand-Gesture/
│
├── hand guster.html
└── README.md
```

### `hand guster.html`

The main application file containing the HTML structure, CSS styling, and JavaScript functionality for the hand gesture tracker.

## ⚙️ How It Works

The application follows this process:

```text
        Camera
           ↓
    Video Stream
           ↓
      Frame Capture
           ↓
   Hand Detection
           ↓
  Landmark Tracking
           ↓
 Gesture Recognition
           ↓
    Visual Feedback
```

### 1. Camera Access

The application requests access to the user's webcam through the browser.

### 2. Video Processing

The camera provides a continuous video stream. The video is used as the source for processing while the canvas displays the visible output.

### 3. Hand Detection

The application analyzes the camera frames to identify hands.

### 4. Landmark Tracking

Important points on the detected hand are tracked to understand the hand's position and movement.

### 5. Gesture Recognition

The tracked hand information is used to identify the current gesture.

### 6. Visual Feedback

The application displays tracking information through an on-screen HUD.

The interface shows information such as:

* **Hands detected**
* **Landmarks**
* **Current gesture**

## 🖥️ User Interface

The application contains:

### Start Screen

A simple start interface allows the user to begin the hand-tracking experience.

### Camera View

The camera feed is displayed across the application window.

### Tracking HUD

The HUD provides real-time information about the detected hands and gestures.

Example:

```text
Hands detected     1
Landmarks          21
Gesture            Open Palm
```

## ▶️ How to Run

### Option 1 – Open Locally

1. Clone the repository:

```bash
git clone https://github.com/Jeevankumar-502/Hand-Gesture.git
```

2. Open the project folder:

```bash
cd Hand-Gesture
```

3. Open:

```text
hand guster.html
```

in a modern web browser.

4. Click the **Start** button.

5. Allow camera access when the browser asks for permission.

6. Place your hand in front of the camera.

### Option 2 – Use a Local Server

For better browser compatibility with camera permissions, run the project using a local server.

For example, with VS Code, install the **Live Server** extension and open the HTML file using **Open with Live Server**.

## 🔐 Camera Permission

The browser must be allowed to access your camera.

If the camera does not start:

1. Check browser camera permissions.
2. Make sure no other application is using the camera.
3. Reload the page.
4. Start the application again.

## 📊 Tracking Information

The application provides real-time information including:

| Information    | Description                            |
| -------------- | -------------------------------------- |
| Hands Detected | Number of hands detected by the system |
| Landmarks      | Number of tracked hand points          |
| Gesture        | Currently detected hand gesture        |

## 🎯 Applications

Hand gesture tracking can be useful for:

* Human-computer interaction
* Touchless interfaces
* Accessibility applications
* Gesture-based navigation
* Interactive web applications
* Educational computer-vision projects
* Browser-based gesture control

## 🔮 Future Improvements

Possible improvements include:

* 🎵 Gesture-based media control
* 🖱️ Virtual mouse
* 🔊 Volume control
* 📑 Presentation control
* 🎮 Gesture-controlled games
* 🤟 Sign-language recognition
* 👥 Improved multi-hand gesture recognition
* 📱 Better mobile-device support
* ⚡ Improved tracking performance

## 📸 Demo

Add screenshots or a GIF of the application here:

```markdown
![Hand Gesture Tracker](screenshots/demo.png)
```

You can also add a demonstration video/GIF showing the camera detecting different gestures.

## 🌐 Browser Compatibility

The application requires a modern browser with camera access and the necessary web APIs.

Recommended browsers:

* Google Chrome
* Microsoft Edge
* Safari
* Firefox

Camera permissions may behave differently depending on browser security settings.

## ⚠️ Notes

* Camera access requires user permission.
* Good lighting improves hand detection.
* Keep your hand clearly visible to the camera.
* Performance may depend on the device and browser.

## 👨‍💻 Author

**Jeevan Kumar R**

GitHub: **Jeevankumar-502**

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub!

## 📄 License

This project is created for educational and experimental purposes.
