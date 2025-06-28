

# 🧠 Face Detection & Logging System

A Python-based real-time face recognition system that:
- Detects known faces using webcam
- Saves the full frame image with timestamp
- Logs detections into a CSV file
- Plays a sound alert on successful detection
- Automatically exits after first successful detection

---

## 📂 Folder Structure

```

FACE\_DETECTION\_SYSTEM/
├── known\_faces/              # Images of known people (name.jpg)
├── logs/
│   ├── detections.csv        # Detection logs
│   └── images/               # Saved full-frame images
├── assets/
│   └── detected.mp3          # Sound file for alert
├── utils/
│   └── logger.py             # Helper to log detections
├── main.py                   # Main script
└── requirements.txt          # Python dependencies

````

---

## 🚀 Features

- 🎯 Real-time face detection via webcam
- 🖼️ Full image capture upon recognition
- 📅 Auto-timestamping of detections
- 📦 Logs saved in `.csv` with image name + timestamp
- 🔔 Sound alert plays when face is detected
- 🔁 Optional: Detect only once and exit

---

## 🔧 Requirements

- Python 3.7+
- OpenCV
- face_recognition
- numpy
- playsound

Install dependencies:

```bash
pip install -r requirements.txt
````

---

## 📸 How to Use

1. Place images of known people in `known_faces/` folder.
   ✅ Filenames should be: `name.jpg`

2. Make sure `assets/detected.mp3` sound file exists (or change filename in code).

3. Run the app:

```bash
python main.py
```

4. Once a known face is detected:

   * Full image is saved to `logs/images/`
   * Entry is written to `logs/detections.csv`
   * Sound is played
   * Program exits automatically

---

## 📑 Sample CSV Log Output

```
Name,Timestamp,Image
vishwas,2025-06-28 01-09-34,vishwas_2025-06-28 01-09-34.jpg
```

---

## 💡 Future Improvements

* Continuous detection with cooldown
* GUI dashboard for logs and previews
* Telegram/email alerts
* Face registration via webcam

---

## 🧑‍💻 Author

* Vishwas Rallapalli
* Project guided with ❤️ by ChatGPT

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).

```

---

Let me know if you want:
- Badge styling (like "Python", "License", etc.)
- Screenshots/GIF preview of the app in the README
- Deployment instructions for Windows `.exe` or Raspberry Pi support

I can help you turn this into a complete GitHub project! 🚀
```
