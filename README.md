# 🛡️ MANTIS AI SECURITY & FINANCIAL RADAR

<p align="center">
  <strong>Enterprise-Grade Security Firewall, Token Budget Controller & Behavioral Telemetry for Laravel AI Applications.</strong>
</p>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-installation">Installation</a> •
  <a href="#-configuration">Configuration</a> •
  <a href="#-license">License</a>
</p>

---

## ⚡ Overview

**Mantis** is an advanced security middleware and financial radar designed specifically for Laravel applications interacting with LLMs (OpenAI, Anthropic, Google Gemini, etc.). It prevents budget draining, stops prompt injections, blocks malicious bots using device fingerprinting, and provides a real-time monitoring dashboard.

---

## 🚀 Features

*   **Financial Guard & Token Budgets:** Set strict global, per-user, and per-IP daily/monthly token limits to prevent unexpected AI API cost explosions.
*   **Behavioral Engine:** Detects automated scraping and abuse using heuristic analysis and temporary threat jailing.
*   **Mantis Shield:** Advanced device fingerprinting (`X-Mantis-Device-Id`) and bot detection headers.
*   **Real-Time Radar Dashboard:** Live telemetry showing AI token usage, costs, threat scores, and firewall states.
*   **Encrypted Core:** Core business logic is protected to ensure intellectual property safety.

---

## 📦 Installation

Require the package via Composer in your Laravel project:

```bash
composer require alchemist/mantis


Publish the configuration and assets:

php artisan vendor:publish --tag=mantis-config


⚙️ Configuration
Add the following environment variables to your .env file to control Mantis behavior:

MANTIS_ENABLED=true
MANTIS_REDIS_CONNECTION=default
MANTIS_GLOBAL_DAILY_LIMIT=5000000
MANTIS_USER_DAILY_LIMIT=50000
MANTIS_IP_DAILY_LIMIT=10000



📊 Dashboard Access
Once installed and configured, navigate to your application's route to access the real-time radar:

[http://your-app.test/mantis](http://your-app.test/mantis)



🔒 License & Support
Mantis is a commercial security package. For enterprise licenses and support, contact via Telegram: @Alchemiist0.