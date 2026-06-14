---
title: "Cultivated meat: how much of the market can it win?"
summary: "Cultivated meat is real animal protein grown from cells — no animal raised or slaughtered. But will it ever win a meaningful share of the meat aisle, and how soon? This is an open, fully-sourced model of exactly that question, built in three transparent steps — what it costs to grow, what shoppers will choose, and how adoption builds over time — with every assumption laid bare as a slider. A live interactive explorer lets you drag those sliders yourself and watch price, market share, and the adoption curve respond in real time."
tags:
  - Food & biotech
  - Techno-economics
date: "2026-06-14T00:00:00Z"

# Feature this project (so it shows in the homepage featured_only Projects block).
featured: true

# Optional external URL for project (replaces project detail page).
external_link: "https://pabloamc.github.io/Cultivated_meat/interactive.html"

image:
  caption: "Cultivated penetration by type of meat — global, at the cost floor"
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Code & methodology
    url: "https://github.com/PabloAMC/Cultivated_meat"
url_code: "https://github.com/PabloAMC/Cultivated_meat"
---

Cultivated meat — real animal protein grown from cells, with no animal raised or slaughtered — could one day share a shelf with ordinary meat. Whether it wins a meaningful slice of that shelf comes down to a very human chain, and this model walks it in three open, fully-sourced steps:

1. **Cost → price.** Add up what a kilogram costs to grow (mostly the liquid medium the cells feed on, plus the cost of running the reactor), apply a retail markup, and divide by the price of the ordinary meat beside it. That ratio drives everything downstream.

2. **Price → share.** A two-segment, four-product multinomial logit (McFadden's random-utility theory, with a Berry–Levinsohn–Pakes price term) puts cultivated on a shelf with conventional meat, plant-based meat, and a beans/skip-meat option. Each shopper weighs price, taste, animal welfare, and authenticity. Because cultivated meat *is* real animal tissue, it competes head-to-head with beef — drawing buyers from conventional meat, not from the plant-based aisle.

3. **Share → over time.** The long-run share is the destination; a Bass-diffusion layer shows adoption climbing toward it from a cold ~5% start, as familiarity grows.

Every assumption is exposed as a labelled slider, with the measured numbers pinned and the judgement calls swept in a Monte Carlo uncertainty band — nothing hidden. The interactive explorer lets you drag any slider — medium cost, reactor scale, retail markup, consumer acceptance — and watch market share, price ratio, and penetration respond instantly.
