# Glassmorphism Portfolio

A lightweight, modern portfolio website designed for Node.js environments (including Termux on Android).

## Prerequisities
- Node.js
- Git
- PM2 (Process Manager)

## Setup on Termux (Redmi 5A)

1.  **Clone the repository** (or copy files to your device):
    ```bash
    git clone <your-repo-url>
    cd glass-portfolio
    ```

2.  **Install Dependencies**:
    ```bash
    npm install
    ```

3.  **Run with PM2**:
    Start the server in the background:
    ```bash
    pm2 start server.js --name "portfolio"
    ```

4.  **Access the Site**:
    Open your browser and go to: `http://localhost:3000`

5.  **Stop the Server**:
    ```bash
    pm2 stop portfolio
    ```

## Features
- **Glassmorphism Design**: Modern, frosted-glass UI.
- **Lightweight**: Minimal dependencies (Express only).
- **Responsive**: Adapts to mobile screens.
