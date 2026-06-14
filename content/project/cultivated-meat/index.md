---
title: "Cultivated meat: demand model and market outlook"
summary: "An open, peer-reviewable model of what share of the meat market cultivated meat can win — and how fast. Built in three interlocking rungs: cost-to-price, price-to-share (discrete-choice / MNL), and share-to-adoption-over-time. Includes a live interactive explorer where you can drag sliders and watch market share, price ratio, and penetration respond in real time."
tags:
  - Food & biotech
  - Techno-economics
date: "2026-06-14T00:00:00Z"

# Feature this project (so it shows in the homepage featured_only Projects block).
featured: true

# Optional external URL for project (replaces project detail page).
external_link: "https://pabloamc.github.io/Cultivated_meat/interactive.html"

image:
  caption: "Market share vs price ratio for four competing products"
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Code & methodology
    url: "https://github.com/PabloAMC/Cultivated_meat"
url_code: "https://github.com/PabloAMC/Cultivated_meat"
---

A fully open model of how cultivated meat competes in the retail meat market, built in three rungs:

1. **Cost → price.** Add up what a kilogram costs to grow (mostly liquid medium and reactor costs), apply a retail markup, and divide by the price of the conventional meat beside it. That ratio drives everything downstream.

2. **Price → share.** A two-segment, four-product multinomial logit puts cultivated on a shelf with conventional meat, plant-based meat, and a beans/skip-meat option. Each shopper weighs price, taste, animal welfare, and authenticity. Because cultivated meat *is* real animal tissue, it competes head-to-head with beef — pulling buyers from conventional, not from plant-based.

3. **Share → over time.** The long-run equilibrium share is the destination; a familiarity/novelty diffusion layer shows the path climbing up to it from a cold ~5% consumer acceptance start.

The interactive explorer lets you drag sliders for any parameter — medium cost, reactor scale, retail markup, consumer acceptance — and watch market share, price ratio, and penetration respond instantly. A Monte Carlo mode propagates uncertainty (triangular priors from the literature) into bands across N=2000 draws.
