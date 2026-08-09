# FarmGuard AI – Live Demo

**FarmGuard AI** is a web-based dashboard and interactive simulation interface for an early animal intrusion detection and deterrence system. Designed for smart agriculture, the dashboard models a 7-step multi-sensor pipeline that tracks animal proximity, classifies species using simulated YOLO object detection, dispatches alerts, and triggers harmless deterrence mechanisms.

---

## 🌟 Key Features

* **Multi-Sensor Health Monitoring**: Visual feedback indicators for Acoustic, PIR Motion, IR Camera, and GPS status.
* **Interactive Perimeter Tracker**: Real-time hero bar indicating distance to boundary (0–200m) with color-coded threat levels (`Safe`, `Warning`, `Critical`).
* **Live Farm Vector Map**: Visual map displaying farm boundaries, sensor nodes, detection range perimeters, and dynamic animal coordinate markers.
* **7-Step Workflow Visualization**: Live step-by-step progress tracking through the complete detection lifecycle.
* **Species Identification Card**: AI classification feedback displaying animal type, detection confidence, zone location, and estimated time to reach boundary.
* **Multi-Channel Alert System**: Visual banner alerts, timestamped event logging, and Telegram/SMS alert modal simulation.
* **Interactive Demo Presets**: Pre-configured test buttons to trigger simulation cycles for **Elephants**, **Wild Boars**, and **Monkeys**.

---

## 🔄 7-Step Detection Workflow

| Step | Phase | Function |
| --- | --- | --- |
| **1** | **Acoustic Detection** | Detects long-range animal acoustic signatures (~200m). |
| **2** | **Motion Confirmation** | PIR sensors confirm physical movement to eliminate false positives. |
| **3** | **Camera Activation** | Activates camera with night vision / IR mode for image capture. |
| **4** | **AI Processing** | Runs YOLO object detection to identify species and calculate confidence. |
| **5** | **Alert Dispatch** | Triggers visual system banners with GPS location coordinates. |
| **6** | **Smart Notification** | Formats and dispatches SMS/Telegram alerts to farmers and local authorities. |
| **7** | **Deterrent Activation** | Triggers acoustic alarms and flashing lights to turn back animals safely. |

---

## 🛠️ Technical Stack

* **Structure**: HTML5 (Semantic elements)
* **Styling**: CSS3 (Variables, Flexbox, CSS Grid, keyframe animations, custom dark theme)
* **Scripting**: Vanilla JavaScript ES6+ (Async/Await pipeline simulation, DOM manipulation)
* **Fonts**: Google Fonts (*JetBrains Mono*, *Sora*)

---

## 🚀 Usage

1. **Save file**: Copy the source code into an `index.html` file.
2. **Open in browser**: Double-click `index.html` or open it in any modern browser (Chrome, Firefox, Safari, Edge).
3. **Simulate events**:
* Click **🐘 Elephant**, **🐗 Wild Boar**, or **🐒 Monkey** to initiate the 7-step detection sequence.
* Click **📱 Test Telegram Alert** to preview the alert notification drawer.
* Click **🔄 Reset System** to clear states and return to passive monitoring mode.



---

## 📁 System Dashboard Modules

* **Hero Section**: Displays real-time animal distance in meters with progress indicator.
* **Live Farm Map**: Interactive canvas rendering farm boundaries, sensor nodes, and real-time animal positioning.
* **System Stats**: Dynamic metrics for detection counts, deterrence events, and system uptime.
* **Alert Log**: Scrollable log capturing timestamped historical event data.

---
