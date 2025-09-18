# ⏳ Countdown Timer

A simple **Bash script** that acts as a countdown timer. The user provides the duration via command-line options (`-m` for minutes, `-s` for seconds), and the script counts down until time is up.

---

## ✨ Features
- Accepts **minutes** (`-m`) and **seconds** (`-s`) as input.
- Uses `getopts` for proper command-line option parsing.
- Calculates total time in seconds with arithmetic expansion.
- Counts down in real time, displaying the remaining seconds.
- Pauses **1 second** between updates using `sleep`.
- Displays `"Time’s Up!"` when the countdown ends.

---

## 🛠 Requirements
This script only requires:
- `bash` (default on most Linux/macOS systems)

---

## 🚀 Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/countdown-timer.git
   cd countdown-timer

---

##⚙️ Options

- `-m` : Number of minutes

- `-s` : Number of seconds

Both options can be combined.
If only one is provided, the timer will still work (e.g., ./timer.sh -s 45).

---

##🔒 Notes

- The script always converts minutes and seconds into total seconds.

- To stop the timer early, press `Ctrl + C`.
