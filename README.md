<div align="center">

 <h1>Gmail Farmer BDT</h1>

  <p><b>Bilingual Telegram Bot for Automated Account Credential Synthesis & Task Logging</b></p>

  <p>
    An asynchronous Telegram bot built with Python and python-telegram-bot providing automated email credential generation, multi-language localization (English / বাংলা), and task payout logging in BDT.
  </p>

  <p>
    <a href="https://www.python.org"><img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.10" /></a>
    <a href="https://python-telegram-bot.org"><img src="https://img.shields.io/badge/Telegram_Bot_API-v20+-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="python-telegram-bot" /></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License" /></a>
  </p>

</div>

---

## Overview

**Gmail Farmer BDT** is an asynchronous Telegram bot service built to streamline micro-task management, synthetic test account creation, and user reward tracking. Supporting dynamic bilingual user sessions in both English and Bengali, the bot generates structured synthetic account profiles (first name, email, strong password, and recovery address) on demand.

Designed for non-blocking execution, it utilizes `ApplicationBuilder` from `python-telegram-bot` v20+ with customizable command and interactive keyboard filters.

---

## Key Features

- **Bilingual Interface** — Interactive language switcher supporting English and Bengali (বাংলা) with persistent session dictionaries.
- **Synthetic Credential Engine** — Generates standardized test account pairs with deterministic recovery credentials and secure random passwords.
- **Interactive Custom Keyboards** — Fast touch navigation via `ReplyKeyboardMarkup` for seamless mobile user interaction.
- **Environment Configuration** — Secure token handling reading from `os.environ` preventing credential leakage in source control.
- **Async Event Loop** — High-concurrency polling loop capable of handling multiple simultaneous Telegram users.

---

## Tech Stack

| Layer | Technology | Purpose |
| :--- | :--- | :--- |
| **Language** | [Python 3.10+](https://www.python.org) | Core application execution |
| **Bot Framework** | [python-telegram-bot v20+](https://python-telegram-bot.org) | Asynchronous Telegram Bot API wrapper |
| **Configuration** | Native `os.environ` | Secure bot token and environment binding |

---

## Getting Started

### Prerequisites
- **Python**: `>= 3.10`
- **Telegram Bot Token**: Obtained from [@BotFather](https://t.me/BotFather)

### Installation & Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/CodeByPartho/Gmail-Farmer-BDT.git
   cd Gmail-Farmer-BDT
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure your bot token**:
   ```bash
   export BOT_TOKEN="your_telegram_bot_token"
   ```

4. **Launch the bot**:
   ```bash
   python main.py
   ```

---

## License

This project is licensed under the **[MIT License](LICENSE)**.

---

<p align="center">Built by Partho</p>
