
# ✅ Smart Home Automation – ESP8266 + Alexa + Manual Switch

This project demonstrates a basic **smart home automation system** using an **ESP8266** microcontroller and a **4-channel relay module**. Built as a mini-project for a 3rd-year Electrical Engineering student, it allows control of home appliances like a **bulb** and **socket** both via **Alexa voice commands** and **manual switches**.

---

## 🛠️ Project Highlights

- 📱 **Voice Control via Alexa**  
- 🖲️ **Manual Switch Override** (Works without Wi-Fi too!)  
- 🌐 **Blynk App Integration** (for app-based control)  
- 💡 **Controls Bulbs, Sockets or Any Appliance**  
- 🔌 Based on **ESP8266** & **4-Channel Relay**

---

## 🔧 Hardware Used

| Component             | Description                              |
|----------------------|------------------------------------------|
| ESP8266 NodeMCU       | Main controller with Wi-Fi               |
| 4-Channel Relay Module | For controlling up to 4 devices         |
| Bulb + Socket         | Load connected to the relay              |
| Manual Switches       | For physical control without Alexa       |
| Power Supply          | To power ESP and relay module            |

---

## 🧠 Key Features

- **Dual Control**: Works both with Alexa and manual switches.
- **Independent Load Control**: Each relay channel can be switched separately.
- **No Internet? No Problem!** Manual switch always works.
- **Voice Control**: Works with Amazon Alexa using Blynk + IFTTT/Alexa routines.

---

## 📸 Media

Working photos and video demos available in the `images/` and `videos/` folders.

```
smart-home-relay-esp8266/
├── README.md
├── videos/
│   └── demo_video.mp4
```

---

## ⚠️ Note

The original code was implemented using the **Blynk app**, but is no longer available. However, you can easily recreate the functionality using:

- Blynk + ESP8266
- Alexa + IFTTT (or direct ESP-Alexa libraries)
- 4-channel relay library and digitalWrite in Arduino

---

## 🙋‍♂️ Contribution & Credits

- Designed and implemented by me for a friend’s mini project (3rd year EE, 20 Nov 2022).
- Feel free to fork, clone, or use as inspiration!
