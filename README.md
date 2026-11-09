<h1 align="center">Tenzin Tsetan</h1>
<p align="center"><b>Backend Developer | Java & Spring Boot | Problem Solver</b></p>

<p align="center">
  <a href="https://www.linkedin.com/in/tenzin-tsetan-712a47275/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://leetcode.com/u/tenzintsetan/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"></a>
  <a href="https://github.com/tsetan13821"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
</p>

---

## About Me

Computer Science Engineering student focused on backend development. I build with Java and Spring Boot, enjoy solving problems, and like designing services that keep working when things go wrong.

| | |
|---|---|
| **Focus** | Backend development, API design, system reliability |
| **Primary stack** | Java, Spring Boot, PostgreSQL, Redis |
| **Currently building** | A payment gateway with Spring Boot |
| **Practicing** | Data structures and algorithms on LeetCode |

---

## Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | Java, Python, SQL |
| **Backend** | Spring Boot, Spring Data JPA, FastAPI |
| **Databases & Caching** | PostgreSQL, Redis, SQLite |
| **Migrations & Build** | Flyway, Maven |
| **DevOps & Deployment** | Docker, Docker Compose, GitHub Actions, Render |
| **Testing** | JUnit, pytest |

---

## Featured Projects

### 1. URL Shortener

A production-style URL shortener that turns long URLs into short codes and redirects visitors, with caching, rate limiting and click analytics.

**Links:** [Source Code](https://github.com/tsetan13821/URLShortener) | [Live Demo](https://url-shortener-2sjr.onrender.com)

| Feature | Implementation |
|---|---|
| **Short codes** | Non-guessable 6-character Base62 codes, so links can't be enumerated |
| **Caching** | Redis cache-aside for redirects, with automatic fallback to PostgreSQL if Redis fails |
| **Rate limiting** | 20 links per minute per IP, returning `429` with a `Retry-After` header |
| **Click analytics** | Clicks counted in Redis and flushed to PostgreSQL in batches, with an atomic Lua script to avoid double-counting |
| **Validation & security** | Blocks private and loopback addresses, RFC 9457 error responses, security headers |
| **Database** | PostgreSQL with Flyway-managed schema migrations |
| **DevOps** | Multi-stage Docker image, CI on GitHub Actions, deployed on Render |

**Tech:** Java 21, Spring Boot, Spring Data JPA, PostgreSQL, Redis, Flyway, Docker, GitHub Actions

---

### 2. Smart Exam Surveillance

A real-time AI exam proctoring system that verifies student identity, tracks attention, detects devices and alerts proctors through a live web console.

**Links:** [Source Code](https://github.com/tsetan13821/smart-exam-surveillance) | [Demo Video](https://youtu.be/xY6ZBRJxLh8)

| Feature | Implementation |
|---|---|
| **Identity verification** | Face recognition with ArcFace embeddings against enrolled students |
| **Anti-spoofing** | Blink-based liveness check to flag photos held up to the camera |
| **Attention tracking** | Head pose and gaze estimation for up to four students |
| **Device detection** | Detects phones, laptops and books, and assigns each to the nearest student |
| **Live monitoring** | Annotated video stream, real-time alerts and evidence screenshots |
| **Reports** | Per-session reports with attendance, breaks and incidents |
| **Security** | Scrypt password hashing and hashed server-side session tokens |

**Tech:** Python, FastAPI, SQLite, React, TypeScript, PyTorch, OpenCV, MediaPipe, Docker, GitHub Actions

---

### 3. Payment Gateway *(in progress)*

A Stripe/Razorpay-style payment service built with Spring Boot.

| Feature | Implementation |
|---|---|
| **Payments API** | Idempotent payment APIs to prevent duplicate charges |
| **Transactions** | Safe transaction handling for consistent payment state |
| **Security** | Authentication and authorization for merchants and users |

---

## Problem Solving

<p align="center">
  <a href="https://leetcode.com/u/tenzintsetan/">
    <img src="https://leetcard.jacoblin.cool/tenzintsetan?theme=light&font=Nunito&ext=heatmap" alt="LeetCode Stats">
  </a>
</p>

---

## Connect With Me

| Platform | Link |
|---|---|
| **LinkedIn** | [linkedin.com/in/tenzin-tsetan-712a47275](https://www.linkedin.com/in/tenzin-tsetan-712a47275/) |
| **LeetCode** | [leetcode.com/u/tenzintsetan](https://leetcode.com/u/tenzintsetan/) |
| **GitHub** | [github.com/tsetan13821](https://github.com/tsetan13821) |
