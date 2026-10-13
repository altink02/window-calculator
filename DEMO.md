# WinCalc — Demo access and review scope

**Altin Kalludra** · [Case study](README.md)

## Open the demonstration

1. Open https://wincalc-api-tx2h.onrender.com.
2. Wait for the login page to load; a free-tier service may need to wake.
3. Press **Shiko demonstrimin** (View demo). No registration is required.
4. Inspect the configurator, preview and price breakdown, then Dashboard and Catalog.

The shared demonstration account uses seeded sample data. Please avoid deleting
records, changing users, or altering catalog prices when evaluating the project.

## Observed on 2026-10-13

| Check | Result |
|---|---|
| Public login page | Loaded |
| One-click demo entry | Opened the demo workspace |
| Configurator and seeded pricing display | Loaded |
| Dimension input and preview | Changed in the UI; persistent price recalculation was not fully reverified |
| Administrative dashboard | Loaded with seeded draft |
| Window-type catalog | Loaded |
| Mouse selection in language menu | Bug reproduced; private-source fix committed |
| Keyboard selection in language menu | English selection worked |
| Category column label | Missing translation reproduced; private-source fix committed |
| PDF/BOM export, save workflow, backup, user administration | Not retested in this portfolio review |
| Service responsiveness | Slow wake-up and later request timeouts observed |

## Screenshot provenance

| File | What it shows |
|---|---|
| screenshots/01-configurator.jpg | Fresh demo session, Albanian configurator, 1200 × 1400 mm fixed window |
| screenshots/02-dashboard.jpg | English administrative dashboard with sample draft |
| screenshots/03-catalog.jpg | English window-type catalog; pre-fix category label |

These are unaltered browser captures. The private application code is not
distributed in this repository.

© Altin Kalludra. All rights reserved.
