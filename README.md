# 🌍 Azimuth and Distance Calculator

A modern web-based tool to calculate **distance** and **azimuth (bearing)** between two geographic points using their **latitude and longitude** coordinates.  
Built for surveyors, navigators, geocachers, and anyone working with geographic data.

---

## 🚀 Live Demo
🔗 [View Project on GitHub Pages](https://your-username.github.io/azimuth-calculator/)  
*(Replace `your-username` with your GitHub ID after hosting)*

---

## 🧭 Features
- ✅ Calculate accurate **great-circle distance** between two coordinates.  
- ✅ Compute **azimuth (bearing)** from point 1 to point 2 and vice versa.  
- ✅ Simple, responsive, and mobile-friendly UI.  
- ✅ Built using **HTML**, **CSS (Bootstrap 5)**, and **Vanilla JavaScript**.  
- ✅ Real-time error handling for invalid coordinates.  
- ✅ Works completely **offline** (client-side only).

---

## 📸 Preview
![App Screenshot](https://user-images.githubusercontent.com/00000000/placeholder.png)
*(You can upload your own screenshot and replace the image link.)*

---

## 🧩 Technologies Used
- **HTML5** – Structure  
- **CSS3 (Bootstrap 5)** – Styling & Layout  
- **JavaScript (ES6)** – Distance & Azimuth Calculations  
- **Google Tag Manager (Optional)** – Analytics tracking  

---

## 🧠 How It Works
The tool uses the **Haversine formula** to calculate great-circle distance and **trigonometric functions** to compute azimuth (bearing) between two coordinates on Earth’s surface.

**Distance formula:**
\[
d = 2r \times \arcsin\left(\sqrt{\sin^2\left(\frac{Δφ}{2}\right) + \cos(φ_1)\cos(φ_2)\sin^2\left(\frac{Δλ}{2}\right)}\right)
\]

**Azimuth formula:**
\[
θ = \arctan2(\sin(Δλ)\cos(φ_2), \cos(φ_1)\sin(φ_2) - \sin(φ_1)\cos(φ_2)\cos(Δλ))
\]

---

## 🛠️ Setup Instructions

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/azimuth-calculator.git
