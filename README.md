# MiniAppHub — Mini Program Source Code

This repository hosts several mini program demos. **Each one has its own independent Release download link.**
Click **Download** to open the Release page, grab the `.zip`, unzip it, and import it with **TCMPP / WeChat DevTools** to run.

> Each project's `app.json` includes a `github-url` field pointing to its own Release page.

## Downloads

| Name | Download (Release page) | Direct ZIP |
|------|-------------------------|------------|
| Costume Change | [Download](https://github.com/TCMPP-Team/MiniAppHub/releases/tag/costume-change-v1) | [zip](https://github.com/TCMPP-Team/MiniAppHub/releases/download/costume-change-v1/costume-change-v1.zip) |
| Fate Tarot | [Download](https://github.com/TCMPP-Team/MiniAppHub/releases/tag/fatetarot-v1) | [zip](https://github.com/TCMPP-Team/MiniAppHub/releases/download/fatetarot-v1/fatetarot-v1.zip) |
| Global Exchange | [Download](https://github.com/TCMPP-Team/MiniAppHub/releases/tag/global-exchange-v1) | [zip](https://github.com/TCMPP-Team/MiniAppHub/releases/download/global-exchange-v1/global-exchange-v1.zip) |
| GlobePilot | [Download](https://github.com/TCMPP-Team/MiniAppHub/releases/tag/globepilot-v1) | [zip](https://github.com/TCMPP-Team/MiniAppHub/releases/download/globepilot-v1/globepilot-v1.zip) |
| Gold Price Live | [Download](https://github.com/TCMPP-Team/MiniAppHub/releases/tag/gold-price-live-v1) | [zip](https://github.com/TCMPP-Team/MiniAppHub/releases/download/gold-price-live-v1/gold-price-live-v1.zip) |
| Health Assistant | [Download](https://github.com/TCMPP-Team/MiniAppHub/releases/tag/health-assistant-v1) | [zip](https://github.com/TCMPP-Team/MiniAppHub/releases/download/health-assistant-v1/health-assistant-v1.zip) |
| Stride Plan | [Download](https://github.com/TCMPP-Team/MiniAppHub/releases/tag/stride-plan-v1) | [zip](https://github.com/TCMPP-Team/MiniAppHub/releases/download/stride-plan-v1/stride-plan-v1.zip) |
| ZodiacVibe | [Download](https://github.com/TCMPP-Team/MiniAppHub/releases/tag/zodiacvibe-v1) | [zip](https://github.com/TCMPP-Team/MiniAppHub/releases/download/zodiacvibe-v1/zodiacvibe-v1.zip) |
| Currency Converter | [Download](https://github.com/TCMPP-Team/MiniAppHub/releases/tag/currency-converter-v1) | [zip](https://github.com/TCMPP-Team/MiniAppHub/releases/download/currency-converter-v1/currency-converter-v1.zip) |
| Flight Tracker | [Download](https://github.com/TCMPP-Team/MiniAppHub/releases/tag/flight-tracker-v1) | [zip](https://github.com/TCMPP-Team/MiniAppHub/releases/download/flight-tracker-v1/flight-tracker-v1.zip) |
| Global Festivals | [Download](https://github.com/TCMPP-Team/MiniAppHub/releases/tag/global-festivals-v1) | [zip](https://github.com/TCMPP-Team/MiniAppHub/releases/download/global-festivals-v1/global-festivals-v1.zip) |

## How to run

1. Download and unzip the project.
2. Open **TCMPP** or **WeChat DevTools** and import the unzipped folder.
3. Some demos use placeholders for sensitive values. Replace them with your own before running:
   - **App ID** — set `YOUR_TCSAS_APPID` in `project.config.json` (and `config/index.js` where present).
   - **Backend domain** — replace `your-backend-domain` with your own server/CDN host.
   - **LLM API key** — e.g. Health Assistant's `app.js` → `deepseekApiKey`.

---

Maintainer scripts for packaging and publishing live under `release/` in the source project.
