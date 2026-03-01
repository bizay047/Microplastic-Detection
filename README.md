# 🌊 AI Microplastics Detection System

![Project Status](https://img.shields.io/badge/Status-Active-success)
![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0+-orange.svg)
![Flask](https://img.shields.io/badge/Flask-API-lightgrey.svg)
![Frontend](https://img.html/badge/Frontend-HTML%2FCSS%2FJS-yellow.svg)

> **A specialized image detection program that uses Deep Learning to identify and classify microplastics in water samples.**

*(Note: Add a screenshot of your beautiful web interface here!)*
## 📖 Overview
Microplastic pollution is a growing environmental crisis. This project provides a web-based, AI-driven solution to identify and classify microplastics from water samples (specifically trained on data from the Boise River Basin). 

By utilizing **Transfer Learning** with Google's **Inception model**, this system can analyze an uploaded microscopic image and accurately determine the percentage breakdown of different microplastic types.

### 🔬 Classification Categories:
* 🟢 **Beads:** Spherical plastic particles
* 🧵 **Fibers:** Thread-like plastic structures
* 📄 **Films:** Thin plastic sheets
* ☁️ **Foam:** Polystyrene and expanded plastics
* 🧩 **Fragments:** Broken down pieces of larger plastics
* 🌿 **Organic Matter:** Natural plant or algae material

---

## ✨ Key Features
* **Real-Time AI Processing:** Connects a custom TensorFlow machine learning model to a web interface via a Flask REST API.
* **Interactive UI:** Features a modern, responsive Glassmorphism design that looks great on both desktop and mobile devices.
* **Drag & Drop Upload:** Seamlessly drag images into the browser for instant analysis.
* **Dynamic Theme Switching:** Fully integrated Light and Dark modes.
* **Interactive Background:** Features a custom HTML5 Canvas neural network particle animation that responds to the current theme.

---

## 🛠️ Technology Stack
**Frontend:**
* HTML5, CSS3 (Custom Variables, Flexbox/Grid, Media Queries)
* Vanilla JavaScript (ES6+, Fetch API, Canvas API)

**Backend:**
* Python 3.x
* Flask & Flask-CORS (REST API routing)
* TensorFlow & Keras (Model execution)
* Pillow (PIL) & NumPy (Image preprocessing)

---

## 🚀 Installation & Setup

Want to run this project locally on your machine? Follow these step-by-step instructions.

### Prerequisites
* Python 3.8 or higher installed
* A modern web browser

### Step 1: Clone the Repository
```bash
git clone [https://github.com/bizay047/Microplastic-Detection.git](https://github.com/bizay047/Microplastic-Detection.git)
cd Microplastic-Detection
