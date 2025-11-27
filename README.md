# Micro-Task Marketplace Hub

This repo contains a small React/Vite/Tailwind app that displays an auto-updating feed of paid micro-tasks from a published Google Sheet.

## Quickstart

1. Replace the placeholder `SHEET_ID` in `src/components/MicroTaskHub.jsx` with your published Google Sheet ID.
2. `npm install`
3. `npm run dev` to run locally.
4. Deploy to Vercel or Netlify.

## Automation

Use Make.com or Zapier to scrape sources and append rows to the Google Sheet on a schedule. See the project's README for example Make.com module steps.
