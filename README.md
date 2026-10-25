# ⚡ SubTech — Smart Subscription & Trial Management

![SubTech Banner](https://img.shields.io/badge/SubTech-v1.0.0-00f2fe?style=for-the-badge&logo=lightning)
![License](https://img.shields.io/badge/License-MIT-7928ca?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

> **SubTech** is a modern, single-page web dashboard designed to help you organize active subscriptions, monitor free trial expirations, project future costs, and manage customized renewal notification schedules.

---

## ✨ Features

- 📊 **Real-time Analytics Dashboard**
  - **Active Subscriptions Count:** Monitor total active recurring services.
  - **Free Trial Metrics:** Tracks active free trials and calculates their percentage of your total services.
  - **Normalized Spending Analysis:** Instant view of total current monthly spend vs. projected future costs after trial/price conversions.

- ⚙️ **Custom Live Subscriptions**
  - Track service name, purchase date, duration (in days), initial price, projected future price, and trial status.
  - Quick-preset chips for popular services like Netflix, Spotify, iCloud, and Amazon Prime.

- 🔔 **Customizable Reminder Schedule (Three-Dots Menu)**
  - Fine-tune lead-time notification rules for individual subscriptions (e.g., 1 day, 3 days, or 7 days before renewal).
  - Toggle global daily reminders on or off directly from the header navigation.

- ⏳ **Hold-to-Delete Action**
  - Interactive 2-second hold-down button with dynamic visual fill progress to prevent accidental deletions.

- 🎨 **Unique Glassmorphic UI**
  - Custom CSS design featuring modern dark mode, ambient neon glow accents, smooth micro-interactions, and responsive layouts—no external CSS framework required.

---

## 🚀 Quick Start

Since SubTech is built with standard web technologies (Vanilla HTML5, CSS3, and JavaScript), no build tools or package managers are required.

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/subtech.git
cd subtech
```

### 2. Run the Application
Simply open `index.html` in any modern web browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

---

## 🛠️ Tech Stack

- **Markup:** HTML5
- **Styling:** Custom CSS3 (Glassmorphism, CSS Grid, Flexbox, Keyframe Animations, Design Tokens)
- **Scripting:** Modern Vanilla JavaScript (ES6+, LocalStorage API)
- **Icons:** [Font Awesome 6](https://fontawesome.com/)
- **Typography:** Google Fonts (*Plus Jakarta Sans* & *JetBrains Mono*)

---

## 💾 Local Storage & Data Persistence

SubTech automatically stores your active subscriptions and reminder settings locally in your browser's `localStorage` space (`subtech_data` and `subtech_reminders`). Your data stays completely private and never leaves your device.

---

## 🤝 Contributing

Contributions are always welcome! If you'd like to improve SubTech or add new features:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
