# Hand Canvas 🎨🖐️

A virtual canvas that lets you draw on your screen using hand gestures detected via your webcam! Powered by OpenCV and MediaPipe, this project turns your hand into a paintbrush—no mouse or stylus required.

---

## Features
- Draw with your index finger using real-time hand tracking
- Change brush color (Blue, Green, Red, Yellow) with a simple gesture
- Clear the canvas instantly
- Fullscreen drawing experience
- Adjustable brush size

---



## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Hand_canvas.git
   cd Hand_canvas
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   *If `requirements.txt` is missing, install manually:*
   ```bash
   pip install opencv-python mediapipe numpy
   ```

---

## Usage

1. **Run the application:**
   ```bash
   python main_one.py
   ```
2. **Allow webcam access** when prompted.
3. **Use your hand to draw!**

---

## Requirements
- Python 3.7+
- OpenCV
- MediaPipe
- NumPy
- Webcam

---

## How It Works
- Uses your webcam to capture video frames.
- MediaPipe detects your hand and tracks landmarks.
- The position of your index finger is used as the brush tip.
- Pinch your thumb and index finger together to draw or select colors.
- Drawings are rendered in real-time on a fullscreen canvas.

---

## Controls & Gestures
- **Draw:** Pinch your thumb and index finger together and move your hand.
- **Change Color:** Pinch in the color palette area at the top of the screen.
    - Blue, Green, Red, Yellow available
- **Clear Canvas:** Pinch in the "CLEAR" box at the top left.
- **Quit:** Press `q` on your keyboard.

---

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## License
[MIT](LICENSE)
