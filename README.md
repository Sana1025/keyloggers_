#  Keylogger Detection Tool

A desktop-based tool to detect potential keyloggers on your system.  
Built with **Python, PyQt5, and Machine Learning**, it analyzes running processes and executable files to identify suspicious behavior.

---

##  Features
- Detect suspicious processes that may behave like keyloggers  
- Analyze Windows PE (Portable Executable) files using `pefile`  
- Machine Learning–based classification with `scikit-learn`  
- Clean PyQt5 GUI for easy interaction  
- Cross-platform support (Linux, Windows, macOS – with some limitations)  

---

## 📦 Installation

1. **Clone this repository**:
   ```bash
   git clone https://github.com/Sana1025/keyloggers_.git
   cd keylogger-detection-tool

## Tech Stack

- Python 3.8+
- PyQt5 – GUI
- scikit-learn – ML models
- pefile – Windows PE analysis
- psutil – Process monitoring

## if you find any issues with prefile make sure to create a virtual environment and then try to install prefile.

```blash
python -m venv .venv
source .venv/bin/activate   # On Linux/Mac
.venv\Scripts\activate      # On Windows
