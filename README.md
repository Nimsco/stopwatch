# ⏱️ Stopwatch Web App

This is a simple yet accurate stopwatch web application built using HTML, CSS, and JavaScript. It allows users to start, stop, and reset a timer, displaying elapsed time in HH:MM:SS:MS format.

## 🚀 Features
- Start the timer
- Stop/Pause the timer
- Reset the timer to zero
- Accurate time tracking with milliseconds
- Clean and easy-to-read UI

## 📁 Project Structure
stopwatch/
├── index.html       # Main HTML structure
├── style.css        # Styling (optional)
└── script.js        # Stopwatch functionality

## 💡 How It Works
- Uses setInterval to update every 10 milliseconds
- Tracks time using Date.now() and calculates elapsed time
- Handles pause/resume with elapsedTime logic
- Formats all time units with two digits using padStart()

## 🔧 How to Use
1. Clone or download this repo
2. Open index.html in your browser
3. Click Start to begin, Stop to pause, and Reset to clear

## 🛠️ Technologies Used
- HTML
- CSS (for styling)
- JavaScript (Vanilla)

## 📝 License
This project is open-source and free to use under the MIT License.
