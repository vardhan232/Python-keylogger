✅ Features
Captures all keystrokes in the background

Saves logs to a hidden file in the user's home directory

Uses the pynput library for listening to keyboard events

Automatically stops on pressing ESC

Lightweight and easy to run

🛠️ Step-by-Step Setup
Clone the repository:

**  git clone https://github.com/yourusername/keylogger_project.git
**  cd keylogger_project

Set up a virtual environment (recommended):
**python3 -m venv env
**source env/bin/activate

Install the required library:

**pip install pynput

💡 On Kali Linux, if you face an externally-managed-environment error:
**sudo apt install python3-pip
**pip install --user pynput

Run the keylogger

**python3 keylogger.py

Stop the keylogger:

**Press the ESC key.

📂 Log File Location
Log files are saved in your home directory:

**~/.keylogs_YYYY-MM-DD_HH-MM-SS.txt

To check log files :

**ls -la ~ | grep .keylogs
**cat ~/.keylogs_*.txt

If you see your keystrokes there — ✅ success!

⚠️ Disclaimer
This project is for educational purposes only.
Do not use this tool on systems without explicit permission.
Unauthorized use is illegal and unethical.
