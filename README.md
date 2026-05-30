<img src="banner.png" alt="HTML Complete Tutorial Interview Guide Banner" width="100%" height="200" style="object-fit: cover;">

<h1 align="center">🌐 HTML Complete Tutorial Interview Guide</h1>

<div align="center">

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Active-brightgreen?style=for-the-badge&logo=github&logoColor=white)](https://ajaygangwar945.github.io/HTML-Complete-Tutorial-Interview-Guide/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Docker Image](https://img.shields.io/badge/Docker%20Image-Available-0db7ed?style=for-the-badge&logo=docker&logoColor=white)](https://hub.docker.com/r/ajaygangwar945/html-complete-tutorial-interview-guide)
[![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)](https://nginx.org/)

A comprehensive, beautifully designed, single-page tutorial and interview preparation guide for HTML. Perfect for absolute beginners and job-seekers preparing for web developer interviews.

**[🌐 Live Demo (GitHub Pages)](https://ajaygangwar945.github.io/HTML-Complete-Tutorial-Interview-Guide/)**

</div>

---

## ✨ Key Features

- **Interactive Previews**: Visual code outputs displaying standard tags side-by-side with code snippets.
- **Over 40+ Interview Q&As**: Dedicated preparation section covering basic to advanced frontend questions.
- **Responsive Design**: Modern and clean card layout that looks beautiful on desktop and mobile.
- **Docker Ready**: Pre-configured static container powered by Nginx.

---

## 📁 File Structure
```
HTML-Complete-Tutorial-Interview-Guide/
├── .github/workflows/docker.yaml  # GitHub Actions CI/CD pipeline
├── banner.png                     # Project header image
├── Dockerfile                     # Docker configuration (Nginx)
├── documentation.txt              # Comprehensive build documentation
├── HTML5.svg                      # Logo asset
└── index.html                     # Main application (HTML & CSS)
```

---

## 🚀 Running the Project Locally

### Zero Setup

Simply double-click the `index.html` file or drag it into any web browser.

### Using Python

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

---

## 🐳 Docker Guide

### Run directly from Docker Hub

Pull the pre-built image and host it instantly:

```bash
# Pull the latest image
docker pull ajaygangwar945/html-complete-tutorial-interview-guide:latest

# Run the container (accessible at http://localhost:8080)
docker run -d -p 8080:80 --name html-interview-guide ajaygangwar945/html-complete-tutorial-interview-guide:latest

```

---

<div align="center">
Made with ❤️ by <a href="https://github.com/ajaygangwar945">Ajay Gangwar</a>
</div>
