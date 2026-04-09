# AIAMI — Daily Journal + Financial Journal + Brainstorming

<p align="center">
  <img src="assets/logo-wordmark.png" alt="AIAMI" width="280">
</p>

<p align="center">
  <strong>A personal AI journal & assistant for writing, voice, and daily planning.</strong><br>
  Arabic + English · Local-first · Privacy by design
</p>

<p align="center">
  <a href="https://apps.apple.com/us/app/aiami/id6759226159">App Store</a> ·
  <a href="https://github.com/Sharqway/aiami-releases/releases">Android APK</a> ·
  <a href="https://www.aiami.app">Website</a> ·
  <a href="https://www.aiami.app/ar/">الموقع بالعربي</a>
</p>

---

## What is AIAMI?

AIAMI is a calm, chat-based daily journal with a built-in financial journal, reminders, shift scheduling, and brainstorming — powered by AI. It works in both Arabic and English, and stores your data locally on your device.

Switch between **Journal**, **Brainstorm**, and **Financials** with one tap. Capture your day, catch ideas, log spending in plain language, and review summaries and trends when you need them.

---

## Features

### 💬 Journal Mode
A chat-style daily journal: type or speak, and let AIAMI summarize, organize your thoughts, and suggest simple next steps. Create reminders naturally — "remind me in 2 hours" — and confirm with yes/no. Attach photos when that's easier.

### 💡 Brainstorm Mode
A practical idea generator: multiple angles fast, then help you sharpen the idea with short questions when needed — without drowning you in details.

### 💰 Financial Journal
Log spending in plain language — `spent 10 on petrol` · `income 200 from sales` · `refund 5 from store`. AIAMI captures the amount, category, and date automatically. Undo mistakes with a single message. Supports multiple currencies.

Go deeper by adding your salary and obligations, and AIAMI becomes your personal financial analyst — remaining salary, spending vs obligations, and trend analysis.

### 🔒 Financial Privacy Mode
Flip one toggle and all financial operations run fully offline. Zero data leaves your device. No proxy calls, no server contact. Your money, your rules.

### 🧠 Memory
AIAMI builds a real picture of who you are — and it stays. Remembers your name, preferences, goals, and habits (up to 20 distilled facts sent with every message). Say "do you remember..." and AIAMI searches your full archive for matching moments. Journal, Brainstorm, and Financials each have separate memory — no cross-pollination.

### 🔔 Reminders & Shifts
Set reminders in plain language — "remind me in 2 hours", "tomorrow at 9pm", "every day at 8am". Snooze, edit, and manage from a dedicated screen. Notifications fire even offline.

Shift scheduling built in — monthly calendar, tap to set Morning/Afternoon/Night/Off, get notified before each shift, attach your work schedule as PDF for reference.

### 🔐 Privacy First
Everything you write — journal, spending, reminders, notes — lives on your phone. Not on our servers. Not in the cloud. Nothing is sold, nothing is shared, nothing trains any AI model. Export everything anytime as a ZIP. Delete everything with a single tap.

---

## Download

| Platform | Link |
|----------|------|
| iOS | [App Store](https://apps.apple.com/us/app/aiami/id6759226159) |
| Android | [GitHub Releases](https://github.com/Sharqway/aiami-releases/releases) |

**Why GitHub for Android?** Google Play requires developers to submit personal identity documents. As an app built on privacy, we hold ourselves to the same standard we promise our users. For Android, we chose GitHub Releases — a trusted, open platform.

---

## Plans & Pricing

| Tier | Price | AI Engine |
|------|-------|-----------|
| Free | $0 | Beru 3.1 |
| Plus | $6.99/mo | Beru 3.5 |
| Max | $12.99/mo | Nous 4.0 |
| Elite | $19.99/mo | Nous 4.5 |

All plans include the full financial journal, reminders, shifts, memory, and export. Paid plans unlock higher AI token limits and advanced models.

---

## Website

This repository hosts the static marketing website for AIAMI, deployed via Cloudflare Pages.

**Live:** [www.aiami.app](https://www.aiami.app) · [www.aiami.app/ar](https://www.aiami.app/ar/)

### Local development

```bash
python3 -m http.server 8000
open http://localhost:8000
```

### Structure

```
├── index.html              ← EN homepage
├── ar/index.html           ← AR homepage
├── plans/                  ← Pricing
├── manual/                 ← User manual (interactive)
├── privacy/                ← Privacy policy
├── support/                ← Support (9 interactive sections)
├── terms/                  ← Terms of service
├── delete/                 ← Delete data instructions
├── assets/                 ← CSS, JS, media, logos
├── _redirects              ← Cloudflare Pages redirects
├── _headers                ← Cache & security headers
├── sitemap.xml
└── robots.txt
```

### Deployment

Push to `main` → Cloudflare Pages auto-deploys within 30 seconds.

---

## Languages

- **English** — full site + app
- **العربية** — full site + app (RTL supported)

---

## Contact

- Website: [aiami.app/contact](https://www.aiami.app/#contact)
- Email: contact@aiami.app

---

## Legal

- [Privacy Policy](https://www.aiami.app/privacy/)
- [Terms of Service](https://www.aiami.app/terms/)
- [Support](https://www.aiami.app/support/)
- [Delete Data](https://www.aiami.app/delete/)

---

<p align="center">
  Built by <strong>AIAMI Studio</strong><br>
  <em>"I AM AI"</em>
</p>
