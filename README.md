# 🔥 Hatch & Hearth

**Enchanted pet companions** — some wound with keys, some grown from gardens, some simply magical. Hatch a pet, care for it a little each day, and watch it grow through four stages — Hatchling, Sproutwing, Lanternwing, Grand Clockwork — in about six weeks of showing up.

**▶ Live test build:** https://jpidge.github.io/hatch-and-hearth/

## The companions

12 species: **8 Common · 3 Rare · 1 Ultra Rare**. Your first pet is free — pick a Common from the shelf or trust the **Mystery Egg** (odds always shown in-app: 69.5% / 29.5% / 1%). Rares and the Ultra are egg-only and never sold by pick. Portraits are painted as matched sets, one per growth stage.

## The care model

Health and Happiness are reservoirs, not daily report cards. Each day a bar drains by exactly the share of its care that was missed — fed but never played with, and Happiness quietly falls while Health holds. Pets visibly slow and sadden as their bars drop. If both bars reach zero the pet goes **dormant**: it does not die, nothing decays, and XP, stage, and trinkets freeze as they were. Waking is instant and free — the pet just wakes up groggy, bars low, until a few days of care bring it back.

No pet limits. No subscriptions. No trading. Everything is a durable good, sold once:

- **First pet** — free
- **Each additional pet** — $1, forever yours
- **Custom Hatch** — $10, a companion designed from your words
- **Seasonal pets** — $10, four a year, each on sale for about two weeks

## Status

Phase 2 test build: multi-pet nest, reservoir care, dormancy, and the shop run locally in the browser (purchases are pretend stand-ins for now). Accounts/backend, Play Billing, and the Android wrap come in later phases.

## Tech

A single self-contained HTML file served by GitHub Pages, with a PWA manifest and service worker for offline/installable use. Portraits are generated artwork, inlined into the shipped file.
