# 🚀 Projects

A showcase of my personal, academic, and side projects.

---

## 💹 TQQQ Alert Bot

An automated trading alert system for TQQQ (3x leveraged Nasdaq ETF). Monitors price action and sends real-time alerts based on a dynamic trailing stop strategy. Designed to help time entries and exits in volatile leveraged instruments.

**Tech:** Python, yfinance / financial APIs, alert/notification system

🔗 https://github.com/alonmorad9/tqqq-alert

---

## 📊 Swing Tracker

A self-hosted swing trading tracker that syncs across every device via a private GitHub repo. Tracks open/closed positions and DCA ladders, writes an automated end-of-day journal entry even if the app is never opened, and runs a daily pre-market trade-ideas scan (RSI, SMA200 trend, volume spikes, distance from 52-week high) using Finnhub data and an LLM to surface and score new setups.

**Tech**: JavaScript (single-page app), GitHub Actions (daily sync + journal + ideas), Groq / Cerebras LLM, Finnhub API, GitHub as data store

🔒 *This repository is private — description provided for reference.*

---

## 🤖 AI Portfolio Bot

A fully autonomous AI paper trading bot that runs entirely on GitHub Actions — no server required. Every 30 minutes during US market hours, it fetches live prices via Finnhub, asks Groq (Llama 3.3 70B) for buy/sell decisions, enforces stop-loss and profit target rules, and commits the results back to the repo. Comes with a live dashboard that reads the portfolio JSON and visualizes performance in real time.

**Rules:** $2,700 starting capital · max 5 positions · 25% per position · -7% stop · +10% target · 20-day max hold

**Tech:** Python, Groq (Llama 3.3 70B), Finnhub API, GitHub Actions, Supabase, HTML/JS dashboard

🔗 https://github.com/alonmorad9/ai-portfolio-bot

---

## 📈 Real Stock Alert

A real-time stock monitoring and alerting tool. Watches configurable tickers and triggers notifications when defined conditions are met — useful for keeping tabs on multiple positions without manually watching the market.

**Tech:** Python, stock market APIs, alert system

🔗 https://github.com/alonmorad9/real-stock-alert

---

## 🎬 NBA Highlight Generator *(Private)*

An automated pipeline that generates NBA highlight reels from raw game footage or broadcast streams. Uses computer vision and video processing to identify key moments — dunks, three-pointers, clutch plays — and assembles them into shareable highlight clips.

**Tech:** Python, OpenCV / video processing, NBA data APIs

🔒 *This repository is private — description provided for reference.*

---

## 🅿️ ParkSmart *(Private)*

A smart parking management application that helps users find, reserve, and navigate to available parking spots in real time. Designed to reduce time spent searching for parking in urban environments.

**Tech:** Python / full-stack, maps/geolocation APIs, real-time availability tracking

🔒 *This repository is private — description provided for reference.*

---

## 📺 YouTube Memory

A local YouTube memory manager that saves and organizes videos with AI-generated summaries using Google Gemini. Supports Hebrew access fields, custom categories, and shared server sync — built to track financial and stock analysis content across Hebrew and English channels.

**Tech:** Python, Google Gemini API, local storage, server sync

🔗 https://github.com/alonmorad9/youtube-memory

---

## 🎓 Academic Projects — Reichman University (RUNI)

### 🏀 NBA Jersey Store

A fullstack e-commerce web application for browsing and purchasing NBA jerseys. Built as the final fullstack project for the 2025 cohort at RUNI.

**Tech:** Fullstack (React / Node.js or similar), REST API, database

🔗 https://github.com/alonmorad9/nba-jersey-store

---

### 🖥️ OS Project — RUNI 2025

An operating systems course project completed at Reichman University in 2025. Covers core OS concepts implemented from scratch — likely including process scheduling, memory management, or system calls.

**Tech:** C / C++, OS-level programming

🔗 https://github.com/alonmorad9/OS-Project-RUNI-2025
