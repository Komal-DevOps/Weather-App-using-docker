
# 🌦️ Weather App (Dockerized)

## 📌 Description

This is a simple Weather Web Application built using HTML, CSS, and JavaScript, and containerized using Docker.
The app allows users to check real-time weather information for any city.

---

## 🚀 Features

* 🌍 Search weather by city name
* 🌡️ Displays temperature, humidity, and conditions
* ⚡ Fast and lightweight UI
* 🐳 Fully containerized using Docker

---

## 🛠️ Tech Stack

* HTML
* CSS
* JavaScript
* Docker
* Nginx (for serving static files)

---

## 📁 Project Structure

```
weather-app/
 ├── index.html
 ├── styles.css
 ├── script.js
 ├── Dockerfile
 └── README.md
```

---

## 🐳 Docker Setup

### 1️⃣ Build Docker Image

```bash
docker build -t weather-app .
```

### 2️⃣ Run Container

```bash
docker run -d -p 8080:80 weather-app
```

### 3️⃣ Open in Browser

http://localhost:8080

---

## 📦 Dockerfile

```dockerfile
FROM nginx
COPY . /usr/share/nginx/html
```

---

## 🧠 Learning Outcomes

* Learned how to containerize a frontend application
* Understood Dockerfile creation and image building
* Worked with Nginx inside Docker
* Learned port mapping and container execution

