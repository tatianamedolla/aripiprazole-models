# Aripiprazole Brain Simulations

Two interactive, browser-based simulations of how aripiprazole (Abilify) acts in the brain, created by **Tatiana Medolla** and built with AI assistance (Claude).

**Live site:** https://tatianamedolla.github.io/aripiprazole-models/

> **Not for clinical or medical use.** These pages are educational simulations built from published research. They are not a medical device, have not been cleared or approved by the FDA, and are not medical advice. The patients shown are simulated and do not represent any real person. Do not use them to make any decision about a medication. If you take aripiprazole, talk to your prescriber before changing or stopping a dose.

## What's included

| Page | What it shows |
|---|---|
| `index.html` | Landing page linking both simulations |
| `response.html` | **Scenario A, when it works:** a simulated patient on 10 mg/day with normal metabolism |
| `adverse.html` | **Scenario B, when side effects emerge:** a simulated patient on 30 mg/day who is a CYP2D6 poor metabolizer |

Both pages run the same model and let you change the dose, liver metabolism (CYP2D6) and treatment day (0–42). Each shows:

- the four dopamine pathways, colored by signal above or below a healthy baseline
- drug levels building up over about two weeks
- the share of D2 dopamine receptors the drug occupies
- an animated synapse where dopamine and aripiprazole compete for the receptor
- the drug's binding strength at each receptor type
- symptom improvement (Scenario A) or side-effect risk (Scenario B) over time

## How it was built

I came up with the idea and the two scenarios, and directed the build using Claude. Values come from peer-reviewed studies and the US prescribing information, listed on each page. Symptom and risk curves are illustrative, not predictions for any person.

## Terms of use

Full terms of use and disclaimer are at the bottom of each simulation page. In short: educational use only, provided as is without warranty, and the creator is not liable for any use of these pages.

Abilify® is a registered trademark of Otsuka Pharmaceutical Co., Ltd. This project is independent and not affiliated with or endorsed by any drug manufacturer or medical organization.

© 2026 Tatiana Medolla. All rights reserved.
