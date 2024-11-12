<p align="center">
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub Activity Generator" width="100" />
</p>

<h1 align="center">GitHub Activity Generator 🚀</h1>

<p align="center">
  <a href="https://git-autov2.onrender.com/" target="_blank">
    <img src="https://img.shields.io/badge/Live%20Demo-Visit%20Site-2ea44f?style=for-the-badge&logo=render" alt="Live Demo" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/python-v3.8+-blue.svg" />
  <img src="https://img.shields.io/badge/flask-v2.0+-orange.svg" />
  <img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat" />
  <img src="https://komarev.com/ghpvc/?username=anshc022&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-it-works">How It Works</a> •
  <a href="#installation">Installation</a> •
  <a href="#usage">Usage</a> •
  <a href="#api-endpoints">API Endpoints</a> •
  <a href="#contributing">Contributing</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg" alt="Snake animation" />
</p>

## 🌟 Key Features

- 🤖 Smart commit pattern generation
- 📅 Customizable date ranges
- 🎯 Realistic activity patterns
- 🔒 Secure OAuth authentication
- 🎨 Beautiful UI with dark mode
- 📊 Real-time progress tracking
- 🔄 Automatic error handling

## 🛠️ How It Works

1. **Authentication**: Securely login with GitHub OAuth for authorized access.
2. **Repository Setup**: Auto-create and configure repositories with initialized git setup.
3. **Smart Generation**: Generate natural-looking activity patterns based on customized schedules.
4. **Real-time Processing**: Track task progress and handle errors automatically.

## 📦 Installation

### Prerequisites

Ensure you have these dependencies installed:
- Python 3.8+
- Git
- pip
- Node.js and npm
- A GitHub account

### System Requirements
- OS: Windows/macOS/Linux
- RAM: 2GB minimum
- Disk Space: 1GB minimum
- Internet Connection: Stable

## 📚 Technical Documentation

### 1. Application Architecture

The app is organized into modules for authentication, task management, and commit generation, enabling clean separation of functionalities.

### 2. Process Flow
- **Repository Setup**: Auto-configures repository.
- **Date Processing**: Prepares commit dates.
- **Commit Creation**: Generates natural patterns.
- **Push Updates**: Pushes to GitHub.

## 🚨 EDUCATIONAL DISCLAIMER

This tool is for **educational purposes only** and should not be used for creating misleading contribution graphs on GitHub.

### Learning Objectives 📚
- OAuth security and token management.
- Git automation and repository workflows.
- Real-time progress tracking with WebSockets.
  
---

## 📚 API Endpoints

| Endpoint             | Method | Description            | Auth Required |
|----------------------|--------|------------------------|---------------|
| `/`                  | GET    | Landing page           | No            |
| `/login`             | GET    | OAuth initialization   | No            |
| `/profile`           | GET    | User dashboard         | Yes           |
| `/auto_commit`       | POST   | Start commit generation | Yes          |
| `/commit_status/<id>` | GET   | Check task progress    | Yes           |

---

## Technical Learning Points 💡

### 1. **OAuth Implementation**
   - Secure token and API access management.

### 2. **Git Automation**
   - Automating repo creation, commit patterns, and pushes.

### 3. **Full Stack Development**
   - Frontend with JS, backend with Flask, and real-time updates.

### 4. **Best Practices**
   - Error handling, rate limiting, and background task handling.
