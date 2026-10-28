# ⚡ SubTech — Smart Subscription & Trial Management

![SubTech Banner](https://img.shields.io/badge/SubTech-v2.5.0-00f2fe?style=for-the-badge&logo=lightning)
![License](https://img.shields.io/badge/License-MIT-7928ca?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

> **SubTech** is a modern, single-page web dashboard designed to help you organize active subscriptions, monitor free trial expirations, project future costs, track categories & payment sources, and manage secure backups—all while remaining 100% local-first and private.

---

## ✨ Features

- 📊 **Real-time Analytics Dashboard**
  - **Active Subscriptions Count:** Monitor total active recurring services.
  - **Free Trial Metrics:** Tracks active free trials and calculates their percentage of your total services.
  - **Normalized Spending Analysis:** Instant view of total current monthly spend vs. projected future costs after trial/price conversions.
  - **Annual Spend Toggle:** Instantly switch KPI spend cards between Monthly and Yearly views to reveal long-term compounding costs.

- 🏷️ **Category Tagging & Visual Breakdown**
  - Tag subscriptions by category (Streaming, Cloud/SaaS, Gaming, Fitness, Utilities, and more).
  - Mini visual category breakdown bar and filter tabs to see exactly where your money goes.

- 💳 **Payment Source Tracking**
  - Tag each subscription with its specific payment method (e.g., Mastercard ending in 4092, PayPal, Apple Pay) to easily track which account gets hit each cycle.

- 👥 **Cost-Split / Shared Calculator**
  - Input how many people share family or team plans (like Spotify Family) to automatically calculate your individual net share versus the gross price.

- ⏸️ **"Paused" / "Archived" Status**
  - Archive or pause cancelled subscriptions instead of permanently deleting them, preserving historical savings tracking without skewing your active monthly burn rate.

- ⚙️ **Custom Live Subscriptions & Presets**
  - Track service name, purchase date, duration, initial/projected prices, categories, payment sources, and trial status.
  - Quick-preset chips for popular services like Netflix, Spotify, iCloud, and Amazon Prime.

- 🔔 **Customizable Reminder Schedule**
  - Fine-tune lead-time notification rules for individual subscriptions (e.g., on renewal day, 1 day, 3 days, or 7 days before).
  - Toggle global daily reminders on or off directly from the header navigation.

- ⏳ **Hold-to-Delete Action**
  - Interactive 2-second hold-down button with dynamic visual fill progress to prevent accidental deletions.

- 💾 **JSON Backup, Restore & Security**
  - Export and import your subscription database as a `.json` file for effortless backups across devices or when clearing browser caches.
  - Optional local PIN or Web Authentication lock screen to protect sensitive personal financial data.

- 💱 **Multi-Currency Support**
  - Base currency selector (USD, CAD, EUR, GBP, AUD, etc.) with static exchange rate multipliers for cross-regional tracking.

- 🎨 **Unique Glassmorphic UI**
  - Custom CSS design featuring modern dark mode, ambient neon glow accents, smooth micro-interactions, and responsive mobile-first layouts—no external CSS framework required.

---

🛠️ Tech Stack
Markup: HTML5

Styling: Custom CSS3 (Glassmorphism, CSS Grid, Flexbox, Keyframe Animations, Design Tokens)

Scripting: Modern Vanilla JavaScript (ES6+, LocalStorage API, Web Authentication API)

Icons: Font Awesome 6

Typography: Google Fonts (Plus Jakarta Sans & JetBrains Mono)

💾 Local Storage & Data Persistence
SubTech automatically stores your active subscriptions, categories, and settings locally in your browser's localStorage space (subtech_data and subtech_reminders). Your data stays completely private and never leaves your device. You can also export/import your database anytime via JSON.

🤝 Contributing
Contributions are always welcome! If you'd like to improve SubTech or add new features:

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License
Distributed under the MIT License. See LICENSE for more information.

