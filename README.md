# SpendWise AI

> See your money the way it sees you back.

SpendWise AI is a personal finance web app that ingests your bank data
(uploads or read-only links), surfaces AI-powered spending insights,
predicts where your month is heading, and turns saving into a game with
streaks, badges, and gamified savings challenges.

This repo is the marketing site + interactive product demo.

## What's inside

- **Marketing landing page** — hero, features, how-it-works,
  insight showcase, gamified challenges, testimonials, pricing, FAQ, CTA.
- **Live demo dashboard** at `/dashboard` with:
  - Overview: cashflow forecast, category breakdown, spend vs saved,
    daily AI brief, goal jars, leaderboard, alerts.
  - Transactions: searchable, filterable ledger with AI tags.
  - Insights: full feed with apply / snooze / show-the-math actions.
  - Challenges: quests, streaks, leaderboard.
  - Alerts: predictive, anomaly, savings, bill alerts with prefs.
  - Goals: animated jars with auto-fund + roundup detail.

## Stack

- Next.js (App Router) · TypeScript · Tailwind v4
- recharts · lucide-react
- Deployed on Vercel

## Run locally

```bash
npm install
npm run dev
```

Build:

```bash
npm run build
```
