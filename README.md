# 📌 VirtualGesturesController

**VirtualGesturesController** is a Python-based gesture recognition system that allows users to control digital functions using hand gestures—both bare hand and gloved hand. 
It uses computer vision and voice feedback to provide an interactive and intuitive control interface.

---

## 🚀 Features

- ✋ Real-time **hand gesture detection** using webcam
- 🧤 Support for **gloved and bare-hand gestures**
- 🗣️ **Text-to-speech feedback** using `pyttsx3`
- 🌐 **Web-based UI** using **Eel** + JavaScript
- 📸 **OpenCV** powered gesture tracking
- 🧠 Intelligent mapping of gestures to commands

---

## 🧰 Tech Stack

- **Python** (Core logic)
- **OpenCV** (Computer Vision)
- **Eel** (Python-JavaScript bridge)
- **JavaScript, HTML, CSS** (Frontend UI)
- **pyttsx3** (Speech synthesis for voice feedback)

---

## 📦 Installation

> ⚠️ Requires Python 3.7 or above

```bash
# 1. Clone the repository
git clone https://github.com/your-username/VirtualGesturesController.git
cd VirtualGesturesController

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the application
python src/app.py

📁 Project Structure
VirtualGesturesController/
│
├── src/                      # Source files
│   ├── app.py                # Main application launcher
│   ├── Gesture_Controller.py # Gesture handling (bare hand)
│   ├── Gesture_Controller_Gloved.py # Gesture handling (gloved)
│   ├── Proton.py             # Voice feedback logic
│   └── web/                  # Frontend files
│       └── js/
│           └── main.js       # JS functionality
│
├── requirements.txt          # Python dependencies
├── README.md                 # Project documentation


🖥️ Usage
1.Run the application:
    bash - python src/app.py
2.A browser window will open with the UI.
3.Perform hand gestures in front of your webcam.
4.The system will detect and respond with appropriate actions and voice feedback.

🔧 Requirements
1.Python 3.7+
2.Webcam (for gesture capture)
3.Optional: Gloves for gloved-gesture mode
