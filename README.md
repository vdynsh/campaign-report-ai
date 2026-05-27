# Campaign Intelligence Report Generator

> Paste raw campaign metrics → get an analyst-grade report in under 60 seconds.

Built by **Vidyansh Sharma** to eliminate 3–4 hours of weekly manual reporting work using Claude AI.

---

## The Problem

While working as a Business Data Analyst, campaign reporting looked like this every week:
- Manually copy data from 3 different dashboards into Excel
- Write a narrative from scratch with no consistent structure
- Share raw numbers with no insights, no recommendations
- Repeat the entire process for every campaign, every week

That's 3–4 hours of low-value work — the kind of work AI should handle.

---

## The Solution

A single-page web app powered by the Claude API that:

1. **Takes raw metrics as input** — impressions, clicks, leads, conversions, spend, revenue
2. **Auto-calculates KPIs** — CTR, Cost per Lead, Lead→Sale CVR, ROAS
3. **Generates a structured analyst report** with executive summary, highlights, concerns, key insight, and recommendations
4. **One-click copy** — ready to paste into Slack, email, or Google Docs

---

## How to Use

### Option 1: Open directly in browser
Just open `index.html` in any browser. No server needed.

### Option 2: GitHub Pages
Enable GitHub Pages on this repo → set source to `main` branch → visit the published URL.

### You'll need
- An [Anthropic API key](https://console.anthropic.com/) (enter it in the app — it's never stored or sent anywhere except Anthropic's API)

---

## Tech Stack

| Layer | Choice |
|-------|--------|
| Frontend | Vanilla HTML + CSS + JS |
| AI | Claude claude-sonnet-4-20250514 via Anthropic API |
| Fonts | Syne + DM Mono (Google Fonts) |
| Dependencies | Zero — runs entirely in the browser |

---

## What Changed

| Metric | Before | After |
|--------|--------|-------|
| Time per report | 3–4 hours | < 60 seconds |
| Manual data entry | Yes | None |
| Report structure | Inconsistent | Always structured |
| Insights included | Rarely | Every report |
| Scalability | 1 campaign at a time | Unlimited |

---

## Key Learning

The hardest part wasn't writing the code — it was **writing the prompt**. Getting Claude to produce structured, analyst-grade output required 8+ iterations on the system instruction. That process taught me: **the prompt is the product**.

---

## About

**Vidyansh Sharma** — Data Analyst | Business Analytics | Sales & Process Intelligence  
📧 vidyansh.sharma007@gmail.com  
🔗 [linkedin.com/in/vidyansh-sharma-309197247](https://linkedin.com/in/vidyansh-sharma-309197247)
