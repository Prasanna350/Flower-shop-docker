Here’s a shorter, clean `README.md` you can use:

# 🌸 Bloom & Petal

A lightweight single-page flower shop built with **HTML, CSS, JavaScript**, and served using **Nginx in Docker**.

## 📁 Project Structure

```text
.
├── index.html
├── Dockerfile
└── README.md
```

## 🐳 Run with Docker

### Build

```bash
docker build -t bloom-and-petal .
```

### Run

```bash
docker run -d -p 8080:80 --name bloom-petal bloom-and-petal
```

Open:

```text
http://localhost:8080
```

### Stop & Remove

```bash
docker stop bloom-petal
docker rm bloom-petal
```

## 💻 Run Without Docker

Since the application is a single `index.html`, it can be opened directly:

```bash
open index.html
```

Or use a simple server:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## 🧠 Tech Stack

* HTML
* CSS
* JavaScript
* Nginx
* Docker

## ⚠️ Note

This is a **client-side demo application**. Orders are stored only in the browser's `localStorage`, and checkout/payment is simulated.

---

Made with 🌸 and a little love.

This keeps the README small while still covering the project, features, Docker commands, and usage.
