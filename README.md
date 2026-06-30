# Day-16-of-Claude-AI-challenge-
AI-powered stock fundamental research tool built with Claude — fetches live financial data (NSE/BSE) and generates evidence-based fundamental analysis reports (valuation, growth, balance sheet health, returns, peer comparison, ownership) with source citations. No buy/sell/hold calls — pure fundamentals only. Day 16 of #60DaysOfAI Challenge
Strict data discipline matters more than data volume. Live figures cross-checked across 2+ sources (Screener, Tickertape, Moneycontrol) before using them — single-source numbers get flagged, not trusted blindly.
"Don't know" is a valid output. Building in a 🚩 Data unavailable fallback instead of letting the AI guess or estimate was the single biggest reliability upgrade.
Citations aren't optional in financial content. Every key metric (P/E, ROE, D/E etc.) needed a source tag right next to it — without that, a fundamentals report is just noise.
Interpretation rules > raw numbers. Defining clear thresholds upfront (e.g., D/E <1 = Safe, ROE >15% = Good) made the tool's verdicts consistent instead of subjective each time.
The hardest constraint to enforce was restraint. Designing a financial tool to never give buy/sell/hold advice — even when directly asked — required explicit guardrails, not just a polite mention.
Mobile-first prompting forces clarity. Since everything is built and reviewed from a phone, the output had to be tab-based and scannable, not a wall of text — which fed back into better prompt structuring overall.
