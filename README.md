Features :

Logs regular keys and special keys (e.g., Enter, Shift, Ctrl)

Stores logs in a file (keylog.txt)

Uses Python's built-in logging module for structured logging

📦 Installation :

Clone the repository

git clone https://github.com/your-username/python-keylogger.git
cd python-keylogger


Install dependencies

pip install pynput


Run the script

python keylogger.py

🖥 Usage :

When you run the script, it will start recording keystrokes until you stop it.
The recorded keystrokes will be saved in keylog.txt in the same directory.

Example log output:

2025-08-15 14:23:45,123: Key pressed: a
2025-08-15 14:23:45,456: Key pressed: b
2025-08-15 14:23:46,789: Special key pressed: Key.enter
