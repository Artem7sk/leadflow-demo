# LeadFlow — Never Lose a Lead Again (free n8n workflow)

**A free, battle-ready n8n workflow: form submission → Google Sheets → instant Telegram alert.**

Every business loses leads the same way: an inquiry lands in an inbox, nobody notices, the customer is gone. This workflow closes that hole in about 5 minutes of setup.

## What it does

1. **Webhook** receives a form/website/chat submission (name, email/phone, source).
2. **Validation** checks required fields (skips empty/spam submits).
3. **Google Sheets** — appends a new row: date, name, contact, source, status.
4. **Telegram alert** — pings your manager instantly with the lead details.

Result: **0 lost leads**, every inquiry in one table, response time under a minute.

## Install (5 min)

1. Download `leadflow-form-to-sheets-telegram.json`.
2. In n8n: **Workflows → Import from File** → select the JSON.
3. Connect credentials:
   - **Google Sheets** — pick your spreadsheet + sheet named `Leads`.
   - **Telegram** — connect a bot, set your chat ID.
4. Publish, copy the webhook URL, point your form's action to it.

## Requirements

- n8n (self-hosted or cloud), a Google account, a Telegram bot.

## Want this tailored to your business?

This is the generic version. I build the **done-for-you** version: your forms, your fields, plus
follow-up reminders, 30-day reactivation, CRM sync (amoCRM / Bitrix24 / HubSpot), and reporting.

- 🎯 **Automation setup, done for you — $79 turnkey** (deposit $39)
- 📩 Request it: https://fizoni.com/products/booking-recovery-automation-service

## More free workflows

Star ⭐ this repo to get the next ones (invoice OCR → Sheets, review requests, booking reminders).

---

*Built with [n8n](https://n8n.io). Maintained by Fizoni — business automation that pays for itself.*
