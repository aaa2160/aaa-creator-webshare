# AAA Fleet Autonomous Harvester • Webshare

[![Autonomous Runner](https://github.com/aaa2160/aaa-creator-webshare/actions/workflows/run.yml/badge.svg)](https://github.com/aaa2160/aaa-creator-webshare/actions/workflows/run.yml)
[![Ecosystem](https://img.shields.io/badge/AAA_Hub-Cloud_V9-18864B)](https://aaa-hub-sheet.pages.dev)
[![Status](https://img.shields.io/badge/Status-Automated_🟢-10643C)](https://github.com/aaa2160)

Autonomous, zero-maintenance background worker for **Webshare**.
Synchronizes newly verified accounts and API credentials directly with:
- **Cloudflare D1 Global Edge Database** (`aaa-vault-d1`)
- **AAA Sheets Cloud V9** ([aaa-hub-sheet.pages.dev](https://aaa-hub-sheet.pages.dev/))
- **Telegram AAA Vault Channel** & Direct User Notification

### Trigger Execution
- **Automated**: Runs on scheduled cron (1st of every month at 03:00 AM UTC).
- **Manual (1-Click)**: Navigate to the **Actions** tab on GitHub Web or the GitHub Mobile App and tap **Run workflow**.
