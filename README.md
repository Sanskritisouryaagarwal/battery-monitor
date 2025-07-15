# 🔋📶 Smart Battery & Network Monitor

**Smart Battery & Network Monitor** is an intelligent web application that helps users monitor and optimize their device's battery and network usage based on location and usage patterns. Built using modern Web APIs, it offers real-time visualizations, actionable recommendations, and performance-aware monitoring — providing a practical solution to the real-world problem of inefficient resource usage.

---

## 🌟 Key Features

- ✅ Real-time tracking of battery status and network quality
- 📈 Dynamic visualizations for battery and network metrics (Canvas API)
- 🌐 Location-based tips for smarter resource usage (Geolocation API)
- ⚙️ Background monitoring using idle time (Background Tasks API)
- 👀 Efficient UI updates only when needed (Intersection Observer API)
- 💡 Smart, actionable suggestions based on device and network state
- 📱 Fully responsive interface for mobile and desktop

---

## 🛠️ Tech Stack & Web APIs Used

### 🔧 Technologies
- HTML5, CSS3, JavaScript (Vanilla)

### 🌐 Web APIs

| Web API | Description |
|--------|-------------|
| **Background Tasks API (`requestIdleCallback`)** | Schedules monitoring tasks during idle time to avoid UI lag |
| **Canvas API** | Renders interactive charts for battery and network stats |
| **Geolocation API** | Determines user's location to offer tailored suggestions |
| **Intersection Observer API** | Updates canvas charts only when visible on screen |
| **Network Information API** | Tracks connection type, speed, and latency in real-time |

---

## 🎯 Real-World Problem Solved

Modern users frequently face:

- 🔋 Fast battery drain due to background processes
- 📶 Network slowdowns without understanding the cause
- ❌ No tailored recommendations to improve resource efficiency

**Smart Battery & Network Monitor** solves these issues by:

- Providing actionable insights based on current battery/network status
- Adapting suggestions based on your **location and connection type**
- Running background monitoring tasks **without blocking the UI**
- Offering intuitive **charts and usage trends**

---

## 📷 Demo Screenshots

> Deployed Link : https://batterynet.netlify.app/
<img width="1357" height="927" alt="Screenshot 2025-07-15 113414" src="https://github.com/user-attachments/assets/6417e83a-780a-4121-9af9-1a34f3e62c5a" />
<img width="1391" height="927" alt="Screenshot 2025-07-15 113510" src="https://github.com/user-attachments/assets/2f73898c-02c5-45a3-908f-ca1d7602edd1" />

---

## 🧪 How It Works

1. Battery & Network stats are retrieved periodically using native APIs.
2. Charts are rendered using the **Canvas API**, displaying historical trends.
3. Suggestions are adapted based on **Geolocation** and **Network Info**.
4. `requestIdleCallback` ensures smooth performance by running monitoring tasks in the background.
5. **Intersection Observer** optimizes performance by avoiding unnecessary updates when components are not in view.

---

## 📂 Project Structure

```

smart-battery-network-monitor/
│
├── index.html            # Main HTML layout
├── style.css             # Custom styling
├── script.js             # Core logic and Web API integrations
├── assets/               # Icons, visuals, screenshots
└── README.md             # Project documentation

````

---

## 🚀 Getting Started

### Step 1: Clone the repository
```bash
git clone https://github.com/Sanskritisouryaagarwal/smart-battery-network-monitor.git
cd smart-battery-network-monitor
````

### Step 2: Run the app

Simply open `index.html` in your browser.

### Step 3 (Optional): Deploy

Deploy easily on platforms like:

* [Netlify](https://netlify.com)
* [Vercel](https://vercel.com)
* GitHub Pages

---

## 🧠 Future Scope

* ✅ Dark mode toggle 🌙
* ✅ Export usage logs as CSV or PDF
* ✅ PWA support for offline access
* ✅ Smart alerts for poor network or critical battery level
* ✅ AI-powered recommendations using ML models

---

## 🙋‍♀️ Author

**Sanskriti Sourya**

* 💻 Frontend & Full Stack Developer | Tech Enthusiast | Problem Solver
* 🌐 GitHub: [@Sanskritisouryaagarwal](https://github.com/Sanskritisouryaagarwal)
* 📧 Email: [sanskritisourya@gmail.com](mailto:sanskritisourya@gmail.com)

If you liked this project, feel free to ⭐ star the repo or connect with me!

---

## 🧑‍💻 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).

---

## 🔗 Resources & References

* [Background Tasks API](https://developer.mozilla.org/en-US/docs/Web/API/Background_Tasks_API)
* [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
* [Geolocation API](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API)
* [Intersection Observer API](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API)
* [Network Information API](https://developer.mozilla.org/en-US/docs/Web/API/Network_Information_API)

---

 💡 *Empower your device. Optimize your experience.*


Let me know if you’d like a version with badges (e.g., GitHub stars, live demo) or if you want this saved as a downloadable `README.md` file.
