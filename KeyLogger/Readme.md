# ⌨️ Keylogger with Timestamp (Python)

This project is a simple keylogger built using Python and the `pynput` library.  
It records every key pressed by the user along with the **timestamp**, and logs the data into a file for later review.

> ⚠️ **Disclaimer**: This tool is for **educational and ethical use only**. Do not use it to monitor anyone without their knowledge or consent.

---

## 📌 Features

- Records **every key press**
- Logs with **accurate timestamps**
- Handles:
  - Regular characters
  - Special keys like SPACE, ENTER, etc.
- Stops logging when **ESC** is pressed

---

## 🧠 How It Works

The program uses the `pynput` module to listen for keyboard events.  
For each key press:
- A timestamp is generated
- The key is logged in a readable format
- Data is appended to `key_log.txt`

---

## 💻 Getting Started

### 🔧 Prerequisites
- Python 3.x
- `pynput` library

### 📦 Install dependencies
```bash
pip install pynput
