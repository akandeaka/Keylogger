
# 🛡️ Python Keylogger (Ethical Monitoring Tool)

This is a **Python-based keylogger tool** designed strictly for **educational** and **authorized use only**. It captures and logs keyboard activity along with timestamps, helping users understand how keylogging works under the hood and how input tracking can be implemented securely and ethically in a Python environment.

---

## ⚠️ Ethical Disclaimer

> **⚠ WARNING:** This script must only be run on devices you own or on systems where you have explicit permission to monitor input. Unauthorized use of keyloggers is illegal and unethical. Always inform and get consent from all parties.

---

## 📌 Overview

This project captures and logs **all keystrokes** on a system using Python’s `pynput` library, appending them to a local text file with timestamps.

It can be useful for:

- Learning about system input handling
- Demonstrating keylogging techniques for cybersecurity training
- Building awareness of how unauthorized monitoring tools work

---

## 🎯 Objectives

- ✅ Capture regular and special keystrokes
- ✅ Log every keystroke with a human-readable timestamp
- ✅ Notify the user when logging begins
- ✅ Stop logging when the **Escape (Esc)** key is pressed
- ✅ Provide robust error handling and clear code structure

---

## 🛠️ Features

| Feature             | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| 🔑 Keystroke Logging | Logs all keyboard input including `space`, `enter`, and special characters |
| 🕒 Timestamps         | Every keypress is saved with `[YYYY-MM-DD HH:MM:SS]` format                |
| 🛑 Stop Mechanism     | Logging ends gracefully when `Esc` key is released                         |
| 📁 Local Log File     | Saves logs in a file named `keystrokes.log`                                |
| ⚙️ Cross-Platform     | Works on **Windows**, **macOS**, and **Linux** (with correct permissions)  |
| 📣 Transparency       | Console warning on script start for ethical compliance                     |

---

## 📦 Dependencies

- Python 3.6+
- `pynput` library

Install `pynput` via pip:

```bash
pip install pynput
````

---

## 💻 How to Run

1. Save the script as `keylogger.py`
2. Open a terminal or command prompt
3. Run the script:

```bash
python keylogger.py
```

4. Type keys normally. Press `Esc` to stop the logger.
5. Open the generated `keystrokes.log` file to review the log.

---

## 🧾 Sample Log Output

```
[2025-07-24 20:39:12] Key pressed: h
[2025-07-24 20:39:13] Key pressed: space
[2025-07-24 20:39:14] Key pressed: enter
```

---

## 📂 Project Structure

```
keylogger-project/
├── keylogger.py         # Python script
├── keystrokes.log       # Generated after running the script
└── README.md            # Documentation
```

---

## 🔐 Security and Best Practices

* ✅ Run only on your own machine or test environments
* ✅ Delete logs after review
* ✅ Modify file permissions if needed 

---

## 💡 Learning Outcomes

* Understanding how keyloggers work
* Working with event listeners in Python
* Handling cross-platform input capture using `pynput`
* Logging and formatting output with timestamps
* Applying ethical guidelines in cybersecurity tools

---

## 👨‍💻 Author

**Akande Akinpelu**
Cybersecurity Trainee | Python Developer 

🔗 [GitHub](https://github.com/akandeaka)
🎓 Training: Prodigy InfoTech and 3MTT Nigeria
```
