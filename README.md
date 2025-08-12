# SCT_CS_4

# Keystroke Viewer (GUI Keylogger)

This project is a GUI-based keystroke logger built with Python using pynput for capturing keyboard input and tkinter for displaying the keystrokes in real-time.
Unlike console-based keyloggers, this one does not print anything to the terminal — all keystrokes are displayed in a Tkinter text area.

---

# Features

1) Real-time keystroke display in a GUI window
2) System-wide key capture (works outside the app window)
3) Automatically scrolls to the latest keystroke
4) Works for both normal keys and special keys (e.g., Space, Enter)

---

# Requirements

Make sure you have Python 3 installed, then install the dependencies:

pip install pynput

tkinter comes pre-installed with Python on most systems.

---

# How to Run

Save the script as keystroke_viewer.py.
Open a terminal and run:
python keystroke_viewer.py
A window will appear showing every key you press in real time.

---

# Code Overview

1) pynput.keyboard.Listener → Listens for system-wide keystrokes
2) tkinter → Displays keys in a resizable GUI text area
3) on_press function → Captures and inserts each key into the text box

---

# Notes

This is for educational purposes only — do not use it for malicious activity.
Works on Windows, macOS, and Linux (may require admin privileges on some systems).

---

# Example

When you type:

Hello World
The GUI will show:

H e l l o   W o r l d

---

# Image Description

<img width="1920" height="1080" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/aaa1f999-8ed6-4ef0-85a1-9d77cd092cdb" />

---

Made with love and curiosity. Harini.
