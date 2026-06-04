# Etsy Analyzer

**Market-research tooling that helps the Etsy seller understand what's selling in a
category and decide what to create next.**

## What it does
Etsy Analyzer looks at a product category or sub-category (for example, digital
products for weddings) and summarizes the landscape for the seller:

- which kinds of products appear to be performing well,
- the common features and themes that recur among popular listings,
- the typical pricing range in the category,
- and a comparison across categories to help prioritize where to focus.

The goal is simple: turn a broad question — *"what should I make?"* — into a
clear, readable summary.

## How it uses the Etsy API
- **Read-only.** It uses the official Etsy Open API v3 to read **public listing
  information** (the same details any visitor sees on a listing page).
- **No buyer or private data.** It does not access purchases, messages, carts,
  or any personal account information.
- **Respectful usage.** It stays within Etsy's API rate limits and Terms of Use.

## A note on figures
Etsy does not publish per-listing sales counts, so any demand or popularity
figures shown are **estimates derived from public signals** and are intended for
relative comparison only — not as exact sales numbers.

## Status
This project is in active development and is intended for individual research
use.

