# ShiftBuddy – Biometric Log Parser 🕒✨

**ShiftBuddy** is a modern web-based tool designed to **parse biometric punch logs**, compute **actual work duration**, **break durations**, **pending shift time**, and **overtime** with a clean UI and real-time countdown timer. It includes a celebration animation when shift hours are completed.

---

## 🔧 Features

- ⌛ **Work Duration Calculation**: Auto-calculates total work time from punch-in/out logs.
- 💤 **Break Tracking**: Detects all breaks and computes the total break duration.
- 🕰 **Pending Time Timer**: Live countdown for remaining shift duration.
- 🔥 **Overtime Detection**: Calculates overtime beyond 8 hours (excluding breaks).
- 🌙 **Dark/Light Mode Toggle**: Switch between day/night themes.
- 🎉 **Confetti Celebration**: Shifts completed? Get rewarded with on-screen celebration.
- 📱 **Responsive Design**: Works well on both desktop and mobile.
- 📋 **Clipboard Support**: Paste logs directly from biometric systems.

---

## 🚀 How to Use

1. **Paste your biometric logs** into the textarea. Example:

07:50:21 PM 
Punch Out BIOMETRIC 
03:29:54 PM
 Punch In BIOMETRIC 
01h 50m 10s Break 
01:39:44 PM 
Punch Out BIOMETRIC
01:37:17 PM
 Punch In BIOMETRIC
 00h 02m 39s Break
01:34:38 PM
 Punch Out BIOMETRIC 
09:12:03 AM Late In 
Punch In BIOMETRIC
3. **Click "Process"** to analyze the logs.
3. View:
- ✅ Work Duration
- 😴 Break Duration
- ⏳ Pending Time (with live stopwatch)
-    Estimated Out Time
- 🔥 Overtime

4. When **Pending Time reaches 0**, confetti 🎊 is triggered.

---

## 🛠 Tech Stack

- HTML5, CSS3 (Glassmorphism style)
- JavaScript / jQuery
- FontAwesome Icons
- Google Fonts (Inter)
- `canvas-confetti` (for celebration)


---

## 🙋‍♂️ Developer

Developed with 💙 by **chethan**

