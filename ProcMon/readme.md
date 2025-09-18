# ProcMon - Process Monitor

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg)](https://www.python.org/)
[![psutil](https://img.shields.io/badge/dependency-psutil-green.svg)](https://pypi.org/project/psutil/)

**ProcMon** (*Process Monitor*) is a lightweight Python tool to monitor running processes and generate detailed log files with timestamped filenames. It helps in auditing, debugging, and analyzing system activity.

---

## ✨ Features

* 🔍 Scan all running processes with:

  * Process ID (PID)
  * Process Name
  * Username
  * Virtual Memory Size (in MB)
* 🗂️ Generate timestamped log files automatically.
* 📁 Store logs in a dedicated `ProcMonLogs` directory.
* ⚡ Works on Windows, Linux, and macOS.

---

## 🛠️ Requirements

* Python 3.7+
* psutil library

Install dependencies:

```bash
pip install psutil
```

---

## 🚀 Usage

Run the script:

```bash
python procmon.py
```

A new log file will be created in the `ProcMonLogs` folder.

Example log file name:

```
ProcMon_ThuSep18_2025_17_45_23.log
```

---

## 📄 Example Log Output

```
--------------------------------------------------------------------------------
        ProcMon - Process Log
        Log File created at: Thu Sep 18 17:45:23 2025
--------------------------------------------------------------------------------

{'pid': 1234, 'name': 'python.exe', 'username': 'Om', 'vms': 55.81}
{'pid': 5678, 'name': 'chrome.exe', 'username': 'Om', 'vms': 220.12}

--------------------------------------------------------------------------------
```

---

## 📂 Project Structure

```
.
├── procmon.py          # Main script
├── README.md           # Documentation
└── ProcMonLogs/        # Auto-generated log files
```

---

## 🧑‍💻 Development

Clone the repository:

```bash
git clone https://github.com/your-username/procmon.git
cd procmon
```

Run locally:

```bash
python procmon.py
```

---

## 🤝 Contributing

Contributions are welcome!

* Open an [issue](https://github.com/your-username/procmon/issues)
* Submit a [pull request](https://github.com/your-username/procmon/pulls)

---


---

