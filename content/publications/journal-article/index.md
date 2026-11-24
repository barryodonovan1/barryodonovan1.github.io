---
title: "Heavy-element-enriched atmospheres and where they are born"
authors:
- me
- Bertram Bitsch
date: "2026-01-28T00:00:00Z"

# Publication type (CSL standard).
publication_types: ["article-journal"]

publication:
  name: "Astronomy & Astrophysics"
  volume: 706
  pages: "A30"  # if the template ignores this, that's fine

peer_reviewed: true
open_access: true
license: CC-BY-4.0  # TODO: check against the licence line on the A&A page

abstract: |
  Interior structure models suggest that many giant exoplanets contain far
  more heavy elements than classical formation models predict. Pebble drift
  combined with volatile evaporation offers a way to enrich the gas that
  forming giant planets accrete. We model the growth of ten observed giant
  planets in an evolving protoplanetary disc, and successfully reproduce
  the heavy-element content of nine of them. This lets us infer where each
  planet formed and predict its atmospheric composition. Because most of the
  heavy elements are accreted as water vapour, our models predict
  atmospheres with high O/H and low C/O ratios, in general agreement with
  observations.

summary: I used a semi-analytic planet formation simulation code (`chemcomp`) to explain the heavy-element content of 10 metal-enriched gas giant exoplanets. In doing so, I was able to make predictions about where these planets formed and what their atmospheric C/O would be.

tags:
- Planet formation
- Giant planets
- Atmospheric composition
- C/O ratio
- Protoplanetary discs
featured: true

hugoblox:
  ids:
    arxiv: 2512.07944
    doi: 10.1051/0004-6361/202556898

links:
  - type: pdf
    url: https://www.aanda.org/articles/aa/pdf/2026/02/aa56898-25.pdf
  - type: source
    url: https://doi.org/10.1051/0004-6361/202556898
  # - type: poster
  #   url: ""   # e.g. if you presented this at a meeting
  # - type: code
  #   url: ""

# Featured image: add featured.png/jpg to this folder (e.g. your key figure)
image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---

Giant exoplanets often contain more heavy elements than the classical core
accretion picture can easily explain. In this paper we test whether
**pebble drift and evaporation**, where icy pebbles drift inwards through the
disc and release volatile vapour as they cross evaporation fronts, can supply
that extra enrichment.

We simulated the formation of ten observed giant planets and matched the heavy-element
content of nine of them, which tells us roughly where in the disc each one
likely formed. Since most of the accreted heavy elements arrive as water
vapour, the models predict **oxygen-rich, low C/O atmospheres**, in line
with what's being observed.

This work was my undergraduate final-year project at University College Cork, supervised by
Prof. Bertram Bitsch.