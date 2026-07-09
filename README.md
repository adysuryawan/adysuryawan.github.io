# AgenticLearning Portal

Welcome to the **AgenticLearning Portal**, a training materials site dedicated to Spec-Driven Design (SDD) with AI Agents. This repository contains the static web files for [adysuryawan.github.io](https://adysuryawan.github.io).

## 🚀 Overview

This site is built using modern, minimalist vanilla HTML/CSS. It features a spacious light-theme design, technical layouts, and interactive elements designed for developers to learn agentic software engineering.

## 📁 Repository Structure

```text
.
├── assets/
│   └── agent_spec_design.jpg   # Custom tech illustration for hero banners
├── resources/
│   └── spec-driven-design.html # Step-by-step training guide for SDD
├── index.html                  # Homepage (introduction and quick start)
├── resources.html              # List of guides and reference articles
├── style.css                   # Main stylesheet (clean light mode design)
└── README.md                   # Project documentation
```

## 🛠️ Tech Stack

* **Structure:** Semantic HTML5
* **Styling:** Custom Vanilla CSS (featuring Inter typography, card grids, custom callout elements, and responsive layout styling)
* **Scripts:** Vanilla JavaScript (for active link highlighting on scroll-spy Table of Contents)

## 💻 Local Development

To view the website locally, you can open `index.html` directly in any web browser, or start a local development server using Python:

```bash
# Start a simple HTTP server in the repository root
python3 -m http.server 8000
```

Once running, navigate to `http://localhost:8000` in your web browser.

## 🚀 Deployment

The site is hosted via **GitHub Pages**. Any changes pushed to the `main` branch of this repository will be automatically deployed:

```bash
git add .
git commit -m "Update training materials"
git push origin main
```
