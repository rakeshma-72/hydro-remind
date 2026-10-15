# 💧 HydroRemind

> **Stay hydrated, stay healthy. Every hour counts.**

A beautiful, fully client-side water reminder web app that notifies you to drink water on a schedule — with a daily intake tracker and drink log.

🌐 **Live Site:** [https://rakeshma-72.github.io/hydro-remind/](https://rakeshma-72.github.io/hydro-remind/)

---

## ✨ Features

| Feature | Description |
|---|---|
| ⏱ **Hourly Reminders** | Configurable countdown timer with browser push notifications |
| 🔔 **Browser Notifications** | Native OS-level alerts even when the tab is in the background |
| 🔊 **Sound Alert** | Soft audio chime via Web Audio API when time is up |
| 💧 **Daily Intake Tracker** | Visual cup grid to log up to 8 glasses per day |
| 📋 **Drink Log** | Timestamped history of every glass you logged |
| ⏰ **Flexible Intervals** | Choose 30 min, 1 hour, 90 min, or 2 hours |
| 🌙 **Auto Midnight Reset** | Daily intake and history reset automatically at midnight |
| 📱 **Responsive Design** | Works on desktop and mobile browsers |

---

## 🖥️ Preview

![HydroRemind – Animated ocean background with glowing countdown ring, cup tracker, and drink log]

The UI features:
- **Glassmorphism cards** with blur and glow effects
- **Animated bubble + wave** ocean background
- **SVG countdown ring** that drains as time passes
- **In-app toast notifications** with smooth slide-in animation

---

## 🚀 Getting Started

### Option 1 – Use the live site
Simply visit 👉 [https://rakeshma-72.github.io/hydro-remind/](https://rakeshma-72.github.io/hydro-remind/)

### Option 2 – Run locally
No build step or dependencies required. Just open the file:

```bash
# Clone the repo
git clone https://github.com/rakeshma-72/hydro-remind.git

# Open in browser
cd hydro-remind
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

---

## 🔔 Enabling Browser Notifications

1. Click **"Start Reminders"**
2. When the browser asks for permission, click **Allow**
3. You'll now receive OS-level notifications even when the tab is minimized

> ⚠️ Notifications require the page to remain open in your browser. For best results, pin the tab.

---

## 🧭 How to Use

```
1. Open the site in your browser
2. Choose your reminder interval (default: 1 hour)
3. Click "Start Reminders" → allow notifications
4. Work normally — HydroRemind will alert you when it's time to drink
5. Click "Log a Glass" or tap a cup icon to track your intake
6. View your timestamped drink history in the log below
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Page structure & semantic markup |
| **Vanilla CSS** | Animations, glassmorphism, responsive layout |
| **Vanilla JavaScript** | Timer logic, Web Notifications API, Web Audio API |
| **Google Fonts** | Outfit typeface |
| **GitHub Pages** | Free static hosting |

No frameworks. No dependencies. No build tools. Pure web standards. ⚡

---

## 📁 Project Structure

```
hydro-remind/
├── index.html      # Entire app — HTML + CSS + JS in one file
└── README.md       # You are here
```

---

## 🔄 Updating the Site

After making changes to `index.html`, deploy with:

```bash
git add .
git commit -m "Your update message"
git push
```

GitHub Pages will automatically redeploy within ~1 minute.

---

## 📄 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

---

<p align="center">Made with 💧 to keep you hydrated</p>
