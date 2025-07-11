# 🤟 Sign Language Detection using YOLOv5

A real-time sign language recognition system built using **YOLOv5** for object detection and **OpenCV** for dataset creation. The project also includes a modular **training & prediction pipeline**, a **Flask-based web application**, and deployment via **Docker** and **GitHub Actions** to **AWS**.

---

## 🚀 Features

- 🖐️ **Sign Language Detection** using YOLOv5
- 🎥 **Custom Dataset Creation** using OpenCV
- 🧱 **Modular Code Structure** for training & prediction
- 🌐 **Flask Web App** for real-time webcam gesture recognition
- 🐳 **Dockerized Pipeline** for easy environment setup
- ☁️ **AWS Deployment** using EC2
- 🔁 **CI/CD Integration** using GitHub Actions

---

## 🛠️ Tech Stack

- **Python 3.8+**
- **YOLOv5**- used for image detection
- **OpenCV**- used for data collection
- **Flask**-launches a Flask server that hosts the live detection model — so users can interact through a browser.
- **Docker**-builds a container image of your app so it can run identically on EC2, your laptop, or anyone else's system.
- **AWS EC2**- runs our Flask server + YOLO model using Docker, exposing it publicly for others to use/test via the internet.

---



