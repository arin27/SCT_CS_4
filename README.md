# Keystroke Viewer

A Python-based GUI application that visualizes keyboard input in real time using `pynput` and `tkinter`.

Unlike terminal-based demonstrations, this project displays captured keystrokes directly inside a graphical interface, making keyboard event monitoring easier to visualize and understand.

---

# Features

- Real-time keystroke display in a GUI window
- System-wide keyboard input capture
- Automatic scrolling to the latest keystroke
- Supports both normal and special keys
- Simple and beginner-friendly Tkinter interface

---

# Technologies Used

- Python 3
- `pynput`
- `tkinter`

---

# Requirements

Install the required dependency:

pip install pynput

`tkinter` comes pre-installed with Python on most systems.

---

# How to Run

Save the script as:

keystroke_viewer.py

Run the program:

python keystroke_viewer.py

A GUI window will appear and display keyboard input in real time.

---

# Code Overview

### `pynput.keyboard.Listener`
Captures keyboard input across the system.

### `tkinter`
Creates the graphical interface used to display keystrokes.

### `on_press()`
Handles key press events and inserts them into the text area.

---

# Educational Relevance

This project demonstrates:
- keyboard event listeners
- system-wide input monitoring
- GUI interaction with Python
- real-time event handling

It can also help learners understand how monitoring software and certain malware techniques function conceptually in cybersecurity environments.

---

# Disclaimer

This project was created strictly for educational and ethical purposes only.

Do not use it maliciously or without proper authorization.

---

# Example

Typing:

Hello World

Will display:

H e l l o [Space] W o r l d

inside the GUI window in real time.

# Image Description

<img width="1919" height="1007" alt="image" src="https://github.com/user-attachments/assets/df4d7bc6-7d35-476c-b6fd-d2fb8f704d9e" />

