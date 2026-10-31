<p align="center">
  <a href="https://journal.getpatrimony.com/en/">
    <img src="docs/img/logo.svg" alt="Journal" width="280">
  </a>
</p>

<h3 align="center">The diary of your trades. Every number says where it comes from.</h3>

<p align="center">
  <img src="https://img.shields.io/badge/status-alpha-b45309.svg" alt="Status: alpha">
  <img src="https://img.shields.io/badge/access-by%20invitation-6366f1.svg" alt="Access: by invitation">
  <img src="https://img.shields.io/badge/data-EU%20(Frankfurt)-0f766e.svg" alt="Data stored in the EU, Frankfurt">
  <img src="https://img.shields.io/badge/import-Trading%20212-1f2937.svg" alt="Import: Trading 212">
  <img src="https://img.shields.io/badge/no-ads%20%C2%B7%20no%20AI%20%C2%B7%20no%20signals-0e7490.svg" alt="No ads, no AI, no signals">
</p>

<p align="center">
  <a href="https://journal.getpatrimony.com/en/">Journal site</a> ·
  <a href="#why-another-journal">Why</a> ·
  <a href="#how-it-works">How it works</a> ·
  <a href="#whats-in-today">What's in</a> ·
  <a href="#get-in">Get in</a> ·
  <a href="#about-this-repository">About this repo</a>
</p>

<p align="center">
  <a href="https://journal.getpatrimony.com/en/"><img src="docs/img/journal-preview.png" alt="Journal: the diary of your trades, with a candlestick chart of 72 sample trades. By invitation only." width="720"></a>
</p>

**Journal, powered by [Patrimony](https://getpatrimony.com)**, is a trading journal. You log each trade, import your broker's file, and see how you are really doing: your average result, how much you risk, where you lose. When a number is an estimate, it says so.

> **Status:** alpha, by invitation only. The price is not decided, and neither is what will be free and what Premium. The trades and figures on the Journal's site are samples.

## Why another journal

Most journals show a number and let you believe it. This one separates three cases and shows them differently:

| | What it means |
|---|---|
| **Measured** | A true R. The risk is the one you set at entry and does not change if you move the stop later. |
| **Estimated** | If you did not save a stop, 1R becomes your average loss. It is a calculation you can redo by hand, not a true R, and it says so. |
| **Careful** | Few trades. Under 30, statistics swing around, and the journal tells you. |

No artificial intelligence: the statistics are calculations you can redo. No signals and no advice: the journal records and analyses your trades, it does not tell you what to buy.

## How it works

From a single trade to the review, in three steps. Every picture below is the Journal's own page, with sample data.

<p align="center">
  <img src="docs/img/step-log.png" alt="Step 1, log the trade: instrument, direction, entry, stop, quantity and strategy, with a preview of the risk (1R) and of gross, net and R if it closes at a given price" width="760">
</p>

**1. Log.** Six fields are enough. The risk stays what you set at entry: move the stop later and the R of that trade does not change.

<p align="center">
  <img src="docs/img/step-import.png" alt="Step 2, import your broker's file: a Trading 212 export read in the browser, sales matched first in first out, one entry marked as estimated and one trade still open" width="760">
</p>

**2. Import.** The Trading 212 export is read in your browser and never sent to a server. Each sale becomes a closed trade matched to its purchases, first in, first out. If the purchase is older than the file, the entry is estimated and says so.

<p align="center">
  <img src="docs/img/step-review.png" alt="Step 3, review: a results calendar, your own yes/no rules counted over 24 trades, and a warning that 24 trades is under 30" width="760">
</p>

**3. Review.** The result day by day, the equity curve, and statistics by strategy, symbol and weekday. You write your own rules and see in how many trades you kept them. Under 30 trades, the journal warns you the sample is too small.
## What's in today

Everything below is in the alpha. Nothing here is a promise.

| Area | What you get |
|---|---|
| **Logging** | Quick entry with a preview of gross, net and R. Six fields are enough: instrument, direction, entry price, stop, quantity, strategy. Partial exits on the same trade. |
| **Review** | A trade list grouped by day, a results calendar, and an overview with net result, equity curve, win rate, expectancy, profit factor, payoff, average R and drawdown. |
| **Charts** | Result per trade, duration, symbol, outcomes. |
| **Statistics** | By strategy, symbol, weekday, long/short and plan followed. A strategy filter across the whole overview. |
| **Rules** | Your own yes/no rules, checked on every trade, with how you do when you keep them and when you don't. |
| **Import** | Trading 212 export (CSV), read in your browser and never sent to a server. Each sale becomes a closed trade, matched to its purchases first in, first out; an old purchase gets an estimated entry that says so. It also updates trades you still hold. |
| **Privacy** | A privacy mode to hide the figures. Data stored in the EU (Frankfurt). No advertising. |
| **Languages** | Italian and English. |

**Not yet:** a link to a Patrimony account to see trade results next to your net worth; a guided review and a screenshot for each trade; import from other brokers (only after testing on real files).

## Get in

For now entry is **by invitation only**. Ask for access on the [Journal site](https://journal.getpatrimony.com/en/) or write to [contact@getpatrimony.com](mailto:contact@getpatrimony.com) and you will get a reply.

## About this repository

This repository is only the Journal's shop window: **there is no code here**, and the Journal is not open source. It used to be an open-source trading journal also called TradeDiary; that plan was dropped in favour of the Journal. The old code is not lost: it is kept untouched on the [`archive/open-source-app`](https://github.com/Flaeren/TradeDiary/tree/archive/open-source-app) branch.

---

<p align="center"><sub>Made by Gabriele Denaro · <a href="https://github.com/Flaeren">GitHub: Flaeren</a> · <a href="https://gabrieledenaro.com">gabrieledenaro.com</a></sub></p>
