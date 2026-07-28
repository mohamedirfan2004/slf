# College Network Authentication Gateway (SLF)

A professional, captive portal interface designed for college networks. This project acts as a secure authentication gateway (similar to a Sophos firewall portal) that students must pass through before gaining access to the campus Wi-Fi network.

## 🚀 Overview
This portal operates exclusively on the college's local server. To gain Wi-Fi access, students must first complete their registration process. Upon successful registration, the network authentication page is activated, ensuring that unauthorized access is strictly restricted.

## ✨ Features
* **Captive Portal Interface:** A secure gateway notice page that intercepts user traffic until authenticated.
* **Network Disclaimer:** A centered, professional warning box outlining the rules and conditions for accessing the local server.
* **Role-Based Access:** Includes dedicated interfaces for Students (`Student.html`) and Administrators (`admin.html`).
* **Responsive Design:** Fully optimized for mobile, tablet, and desktop views.
* **Interactive UI:** Built-in JavaScript alerts and routing for a smooth authentication flow.

## 🛠️ Technologies Used
* **HTML5:** For the structural markup of the gateway and login pages.
* **CSS3:** For styling, blurring effects, and creating an enterprise-grade UI.
* **JavaScript:** For frontend interactivity, button handling, and basic routing logic.

## 📂 Project Structure
* `index.html` / `gateway.html` - The main entry point and captive portal warning page.
* `Student.html` - Student login and dashboard interface.
* `admin.html` - Administrative controls and monitoring interface.
* `style.css` / `login.css` - Custom stylesheets for the project.
* `bg.jpg` & `demo.mp4` - Media assets for the background and demonstration.

## 💻 How to Run Locally
1. Clone the repository to your local machine:
   ```bash
   git clone [https://github.com/mohamedirfan2004/slf.git](https://github.com/mohamedirfan2004/slf.git)