# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project overview

Static single-page website for **Her Equity Collective**, a women's health and equity nonprofit founded by Maddison Ruthford. No build step, no dependencies, no JavaScript — open `index.html` directly in a browser.

## Files

- `index.html` — full site markup (navigation, hero, mission, programs, impact, founder, CTA, contact, footer)
- `styles.css` — all styles; responsive breakpoint at `900px`
- `Madd.jpg` — founder portrait (local asset)

## Design system

- Brand color: `#6b21a8` (dark purple); dark variant `#581c87`
- Font: Inter via Google Fonts (`300`, `400`, `500`, `600`, `700`)
- Border-radius convention: cards/inputs `12–18px`, buttons `50px` (pill)
- Responsive: CSS grid layouts collapse to `1fr` at `≤900px`; nav links hidden on mobile (no hamburger menu implemented yet)

## Known issues

- Hero image is loaded from an external Unsplash URL; replace with a local asset before production.
- Buttons in the contact form, hero, and CTA sections link to `#` and have no backend handler.
