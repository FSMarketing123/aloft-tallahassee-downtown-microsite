# Aloft Tallahassee Downtown — Financing Memorandum Microsite

A single-page, self-contained microsite for the **$19.3M ($119,136 per key / 65% LTC) acquisition financing**
of the **Aloft Tallahassee Downtown** (162 keys · Tallahassee, FL), offered by **Hodges Ward Elliott**.

> **Confidential.** This site presents a confidential financing memorandum prepared for prospective lenders.
> Do not distribute publicly.

## What's here

- `index.html` — the entire site (inlined CSS + JS; no build step)
- `assets/` — property and market photography, brand logos, and gold line-icons

Built from the [The Westshore Grand](https://thewestshoregrandtampa.hodgeswardelliott.com/) template.
The template's stylesheet is carried over verbatim; deal-specific rules live in a second
`<style>` block labeled **Deal-specific overrides**, immediately after it.

## Sections

Introduction + Property Snapshot · The Property (gallery) · Capital Stack (Loan Request, Sources & Uses) ·
Historical & Projected Loan Performance · Investment Highlights · Location (Tallahassee overview,
State Capitol of Florida, Around the Market, interactive demand-generator map) ·
Access the Financing Memorandum · Footer.

## Viewing

Open `index.html` in any modern browser — no server required. Fonts, MapLibre, and map tiles
load from CDNs, so an internet connection is needed for those to render.

## Live site

<https://alofttallahasseedowntownfinancing.hodgeswardelliott.com/> — GitHub Pages, served from
`main` at the repo root. The `CNAME` file in this repo sets the custom domain; DNS is a CNAME
record on `hodgeswardelliott.com` (managed in Hover) pointing to `fsmarketing123.github.io`.

## Placeholders to finalize

- **Confidentiality Agreement links** — the "Sign / Download Confidentiality Agreement" buttons
  (two pairs: Introduction and the closing CTA) point to `#`. Search the file for `TODO`.
  - Sign → the RightSignature template-signer link for this deal
  - Download → drop the NDA `.docx` into `assets/` and point the `href` at it

## Two icons drawn for this deal

The Westshore icon set had no trending-arrow or map-pin glyph, so `assets/icons/performance.svg`
and `assets/icons/location-pin.svg` were drawn to match the set (`#bc8f2d`, `1.095px` stroke,
round caps/joins, 28-unit viewBox).

---

Built with the Hodges Ward Elliott hospitality/investment design system.
