# 🧠 Locoquiz

**Personality quizzes with real, personalized reports — conceived, designed, built, and launched in a single day.**

Live at [locoquiz.com](https://locoquiz.com)

## What it is

Locoquiz is a consumer quiz platform: 20 personality quizzes × 15 questions each, free to take with instant on-page results — backed by a complete digital-product business.

## What's inside

- **20 quizzes, 80 personalized reports** — every quiz has 4 score-calibrated result bands, each with its own detailed two-page PDF report. That's 240 sections of guidance written specifically for each score range — zero generic filler.
- **One-time monetization, no subscriptions** — $1 single-report upsell and $18 all-access bundle via Stripe Payment Links. A deliberate reaction to subscription-trap quiz sites.
- **Passwordless bundle access** — buyers receive an HMAC-signed magic link; after each quiz they choose "Email my report" and the score-matched PDF arrives in their inbox. No accounts, no extra charges.
- **Fully automated fulfillment** — Stripe webhooks → n8n → Resend: payment to PDF-in-inbox with zero manual steps.
- **Zero-backend static architecture** — single-file HTML/CSS/JS app on Cloudflare Pages with a custom domain; AdSense on the free tier; branded Open Graph share previews.

## Stack

HTML · CSS · JavaScript · Stripe Payment Links & Webhooks · n8n · Resend · Cloudflare Pages · Cloudflare Registrar
