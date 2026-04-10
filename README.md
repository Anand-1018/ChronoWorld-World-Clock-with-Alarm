🌐 ChronoWorld — World Clock with Alarm

ChronoWorld is a modern, fully responsive world clock web application that allows users to track real-time time across 40+ global cities with both analog and digital clocks, along with a powerful timezone-aware alarm system.

Built entirely using HTML, CSS, and Vanilla JavaScript, this project focuses on performance, simplicity, and zero dependencies.

🚀 Live Demo

👉 (Add your deployed link here)

📌 Features
🕒 Real-time world clock (updates every second)
🌍 Supports 40+ global cities
🕰️ Analog + Digital clock display
⏰ Timezone-based alarm system
🔔 Alarm with snooze & repeat options
💾 LocalStorage persistence (data saved even after refresh)
📱 Fully responsive (mobile, tablet, desktop)
⚡ Fast performance (no frameworks, no dependencies)
🎨 Interactive and modern UI
🧠 How It Works

ChronoWorld is a single-page application where all logic is handled on the client side.

Time updates every second using setInterval
Timezone conversion uses JavaScript Intl API
Alarms are matched with timezone-specific time
Data (cities, alarms, format) is stored in LocalStorage
🛠️ Tech Stack
HTML5 – Structure
CSS3 – Styling & animations
JavaScript (ES6+) – Logic & functionality
Web APIs Used:
Intl.DateTimeFormat (timezone handling)
LocalStorage (data persistence)
Web Audio API (alarm sound)
📂 Project Structure
ChronoWorld/
│── index.html   # Complete app (HTML + CSS + JS in one file)

👉 This project uses a single-file architecture for simplicity and portability

⚙️ Key Functionalities
🌍 World Clock
Add/remove cities dynamically
Detects local timezone automatically
Displays UTC offset for each city
⏰ Alarm System
Set alarms for any timezone
Repeat modes:
Once
Daily
Weekdays
Weekends
Snooze feature (+5 minutes)
Prevents duplicate triggering
💾 Data Persistence

Stored in LocalStorage:

cw_cities → Selected cities
cw_alarms → Alarm list
cw_format → 12/24 format
cw_triggered → Triggered alarms
📱 Responsive Design
Desktop → Multi-column grid
Tablet → Adjusted layout
Mobile → Single-column UI

Uses CSS Grid + Flexbox for layout adaptation

⚡ Performance Optimization
Minimal DOM updates (only transforms/text updates every second)
Efficient rendering strategy
No external libraries → faster load time
🌐 Browser Support
Chrome
Firefox
Safari
Edge

(All modern browsers supported)

🎯 Use Case

This project is ideal for:

🌍 Remote workers tracking global time
📚 Students learning JavaScript & Web APIs
💼 Portfolio project for frontend roles
📸 Screenshots

(Add screenshots here)

🚧 Future Enhancements
🌙 Dark/Light theme toggle
🔔 Push notifications
🌍 Map-based timezone view
☁️ Cloud sync (Firebase / DB)
📊 Analytics dashboard
🤝 Contributing

Feel free to fork this repository and improve it.

📜 License

This project is open-source and free to use.

👨‍💻 Author

Anand Pandey

If you want, next I can:

🔥 Add GitHub badges + professional styling
📸 Create real screenshot sections
📄 Convert this into a resume-ready project description (very powerful for placements)
