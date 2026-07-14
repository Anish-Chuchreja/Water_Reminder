# 💧 Avatar Hydration Reminder

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**A lightweight hydration reminder application that displays an animated avatar video at scheduled intervals to encourage healthy hydration habits.**

</div>

---

## 📌 Overview

Avatar Hydration Reminder is a browser-based reminder system built using **HTML, CSS, and Vanilla JavaScript**.

Once activated, the application waits for the configured interval and automatically displays a fullscreen modal containing an avatar video reminding the user to drink water.

The project is designed to be simple, lightweight, and requires no external libraries or frameworks.

---

## ✨ Features

- ⏰ Automatic hydration reminders
- 🎥 Fullscreen avatar video popup
- 🎯 One-click activation
- 📱 Responsive design
- 🌙 Modern dark UI
- ❌ Click outside video to dismiss
- 🔁 Automatically repeats after each interval
- ⚡ Pure HTML, CSS & JavaScript

---

## 📂 Project Structure

```
Avatar-Hydration-Reminder/
│
├── hydration_popup.html
├── README.md
└── assets/
    └── reminder-video.mp4
```

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/yourusername/avatar-hydration-reminder.git
```

### Open Project

Simply open

```
hydration_popup.html
```

inside any modern browser.

No installation required.

---

## ⚙️ Configuration

The reminder interval is defined inside JavaScript.

Default:

```javascript
const reminderInterval = 1800000;
```

which equals

```
30 Minutes
```

For testing:

```javascript
const reminderInterval = 5000;
```

which equals

```
5 Seconds
```

---

## 🎥 Video Configuration

Replace the video source with a relative path instead of an absolute Windows path.

Current:

```html
<source src="C:\Users\DELL\Downloads\Now_using_this_avatar_create_a.mp4">
```

Recommended:

```html
<source src="assets/reminder-video.mp4">
```

This makes the project portable across systems.

---

## 💻 Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

---

## 📈 Future Improvements

- Voice reminder support
- Custom reminder intervals
- Notification API integration
- Background music
- Multiple reminder themes
- User settings
- LocalStorage preferences
- Desktop application using Electron
- System tray support
- Progress tracking

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Anish Chuchreja**

- GitHub: https://github.com/Anish-Chuchreja
- LinkedIn: https://linkedin.com/in/anish-chuchreja

---

<div align="center">

⭐ If you found this project useful, consider giving it a star.

Made with ❤️ using HTML, CSS & JavaScript

</div>
