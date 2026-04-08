# 🛡️ Cybsup (Cybsupporter)

Cybsup is a lightweight, zero-dependency, browser-based penetration testing assistant. Designed for cybersecurity professionals, ethical hackers, and CTF players, it provides a centralized dashboard for command reference, live threat intelligence, and AI-driven payload analysis.

Since it is built entirely with frontend technologies (HTML, CSS, Vanilla JS), it runs completely locally in your browser with no backend installation required.

## ✨ Key Features

### 1. Kali Linux DB (Cheatsheet)
A searchable, filterable database of common penetration testing tools and payloads.
* **Categories:** Reconnaissance, Web App Testing, SQL Injection, Exploitation, Password Attacks, Wireless, Post-Exploitation, Privilege Escalation, and more.
* **Fast Search:** Instantly `grep` through descriptions, commands, and syntax using the global search bar.
* **Payloads:** Includes advanced injection techniques and WAF bypasses.

### 2. Latest Technology News Update
An automated news aggregator pulling the latest Technology updates.
* **Live Sync:** Uses rotating proxy engines to fetch real-time RSS feeds directly to your browser.
* **No-Backend Architecture:** Relies on public CORS proxies to pull cross-origin data seamlessly.

### 3. Claude Pentest Copilot
An integrated AI assistant powered by the Anthropic API.
* **Automated Analysis:** Paste raw terminal output (e.g., from Nmap, Gobuster, or SQLmap), and the Copilot will identify vulnerabilities and suggest the exact next command to run.
* **Session Management:** Automatically names and saves your chat sessions to your browser's local storage so you never lose your audit history.
* **Bring Your Own Key (BYOK):** Simply paste your Anthropic API Key (`sk-ant-...`) into the settings bar to initialize the AI. Keys are stored safely in your browser's `localStorage`.

## 🚀 Getting Started

Site Link: https://alfindevop.github.io/cybsupport

🛠️ Built With
HTML5 * CSS3 (Custom Glassmorphism UI, Responsive Mobile Flow)

Vanilla JavaScript (ES6+)

⚠️ Disclaimer
For Educational and Authorized Use Only.
This tool is intended strictly for security researchers, penetration testers, and system administrators to audit networks and applications they own or have explicit, written permission to test. The creator assumes no liability and is not responsible for any misuse or damage caused by this tool.
