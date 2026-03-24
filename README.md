# ⏱️ Web Stopwatch — Interactive Stopwatch Web Application

A clean and responsive browser-based stopwatch built with pure HTML, CSS,
and JavaScript — featuring start, pause, reset, and lap time tracking.

---

## 📌 Overview

This project is a fully functional stopwatch web application built without
any external libraries or frameworks. It uses vanilla JavaScript for all
timing logic and interactivity, CSS for styling, and HTML to structure the
interface — making it lightweight, fast, and easy to run in any browser.

---

## 🚀 Features

- ▶️ Start, ⏸️ Pause, and 🔄 Reset the stopwatch
- 🏁 Lap time tracking — record and display multiple lap intervals
- ⏱️ Accurate time display in hours, minutes, seconds, and milliseconds
- 📱 Responsive UI — works on desktop and mobile browsers
- ⚡ No dependencies — pure HTML, CSS, and JavaScript

---

## 🛠️ Tech Stack

| Category   | Technology        | Usage                              |
|------------|-------------------|------------------------------------|
| Structure  | HTML              | Layout and element structure       |
| Styling    | CSS               | Visual design and responsiveness   |
| Logic      | JavaScript (46%)  | Timer functions, lap tracking, DOM |

---

## 📂 Project Structure
```
Web_stop-watch/
│
├── stopwatch/
│   ├── index.html       # Main HTML structure
│   ├── style.css        # Styling and layout
│   └── script.js        # Stopwatch logic & lap functionality
└── README.md
```

---

## ⚙️ Setup & Usage

No installation required — just open in a browser!

1. **Clone the repository**
```bash
   git clone https://github.com/Jiasha-nath/Web_stop-watch.git
   cd Web_stop-watch/stopwatch
```

2. **Open in browser**
```
   Open index.html in any web browser
```

   Or simply double-click `index.html` to launch it directly.

---

## 💡 How It Works
```
User clicks Start
    ↓
JavaScript setInterval() starts ticking every 10ms
    ↓
Display updates in real time (HH:MM:SS:ms)
    ↓
Pause → clearInterval() freezes the timer
    ↓
Lap → saves current time to lap list
    ↓
Reset → clears timer and all lap records
```

---

## 📸 Demo

> _Add a screenshot of the stopwatch UI here_

---

## 👤 Author

**Jiasha Nath**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jiasha--nath-blue?logo=linkedin)](https://www.linkedin.com/in/jiasha-nath-523b79211)
[![Email](https://img.shields.io/badge/Email-jiasha.nath.adtu@gmail.com-red?logo=gmail)](mailto:jiasha.nath.adtu@gmail.com)

---

## 📜 License

This project is licensed under the MIT License.
