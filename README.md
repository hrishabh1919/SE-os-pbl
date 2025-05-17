# Process Monitoring Dashboard

A modern, themeable, and user-friendly system monitoring dashboard built with Python, Tkinter, and Matplotlib.

---

## 🚀 Features

- **Live System Monitoring:** Real-time graphs for CPU, Memory, Disk, and Network usage.
- **Dark/Light Theme:** Toggle between beautiful modern themes.
- **Process Management:** View, search, and terminate running processes.
- **Pause-While-Selecting:** Process list pauses when you select a process, so you can safely terminate it.
- **Error Handling:** User-friendly error messages and logging.
- **Responsive UI:** Clean, modern layout with status bar and context menus.

---

## 📸 Screenshots

> *(Add screenshots here!)*

---

## 🛠️ Requirements

- Python 3.7+
- `psutil`
- `matplotlib`
- `tkinter` (usually included with Python)

Install dependencies:
```bash
pip install psutil matplotlib
```

---

## 💻 Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/hrishabh1919/SE-os-pbl.git
    ```
2. Navigate to the project directory:
    ```bash
    cd SE-os-pbl
    ```
3. Run the application:
    ```bash
    python improved_monitor.py
    ```

---

## 📁 File Structure

- `improved_monitor.py` — Main application script.
- `system_monitor.log` — Log file for errors and events.
- `requirements.txt` — List of dependencies.
- `README.md` — This file.

---

## 🎨 Customization

- Adjust theme colors in `improved_monitor.py` under the `self.themes` dictionary.
- Tweak process list update interval and graph history length in the code.

---

## 📄 License

MIT License (or your preferred license) 