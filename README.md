# 🛡️ Python Keylogger (Educational Use Only)

This project is a basic keylogger written in Python using the `pynput` library. It captures and logs every keystroke to a local file for analysis or monitoring.

> ⚠️ **DISCLAIMER:**  
> This software is intended **strictly for educational and authorized security testing purposes only**.  
> **Do not use** this tool on any system or network you do not own or have explicit permission to test.  
> Unauthorized use may violate local, state, and federal laws.

---

## 📋 Features

- Logs every keystroke, including special keys (e.g., Enter, Shift, Ctrl)
- Outputs to a text file (`key_log.txt`)
- Stops recording when the **Enter** key is pressed
- Minimal and easy to understand code structure

---

## 🧰 Requirements

- Python 3.x
- [`pynput`](https://pypi.org/project/pynput/)

Install the required library:

```bash
pip install pynput

🚀 How to Run
Clone or download this repository.

Open your terminal or command prompt in the script directory.

Run the script:

bash
Copy
Edit
python keylogger.py
Start typing. The script will:

Log all keystrokes to key_log.txt

Stop when Enter is pressed

 📝 Sample Log Output
css
Copy
Edit
hello [space] world! [enter]
this [space] is [space] a [space] test.
🛡️ Legal & Ethical Use Cases
✅ Permitted uses:

Personal cybersecurity education

Testing on your own machines

Internal training or research with consent

## ❌ Prohibited uses:

Spying on others

Unauthorized access or surveillance

Deployment on public or shared systems

## 🔒 Suggested Enhancements (Optional)
Add timestamps to logs

Encrypt the output file

Hide the console window (on Windows)

Automatically email the logs (with caution)
