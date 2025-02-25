# **Simple Keylogger using Python**  

## **📌 Overview**  
This is a **basic keylogger** built with Python using the `pynput` library. It records keystrokes and saves them to a log file (`log.txt`). This project is intended **for educational and ethical use only**, such as understanding keystroke monitoring for **security research** and **debugging purposes**.  

## **🚀 Features**  
✅ **Real-time Key Logging** – Captures all keystrokes and writes them to a file.  
✅ **Handles Special Keys** – Converts `space`, `enter`, and ignores shift/control keys.  
✅ **Runs in the Background** – Listens for key presses continuously until manually stopped.  

## **📖 How It Works**  
1. Uses `pynput.keyboard.Listener` to **monitor key presses**.  
2. Converts special keys like `space`, `enter`, and ignores **shift/control** keys.  
3. Logs keystrokes into `log.txt` in **append mode**.  
4. Runs indefinitely, capturing keystrokes until the script is stopped.  

## **🛠 Requirements**  
- Python 3.x  
- Install dependencies:  
  ```bash
  pip install pynput
  ```

## **⚠️ Disclaimer**  
🚨 **Unauthorized keylogging is illegal and unethical**. This script is intended **only for learning, ethical research, or personal use** (e.g., monitoring your own system for security testing). **Do not use this on unauthorized systems.** 🚨  

---

This **GitHub description** makes your project clear, structured, and easy to understand. Let me know if you need any modifications! 🚀
