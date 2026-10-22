# Keveria

**Pet care on autopilot — for cat and dog owners in Ukraine.**

Keveria is a Telegram bot that quietly takes over the routine of looking after a pet: it knows when the food
and the litter will run out, watches the prices in online pet stores, and reminds you at the right moment —
before you have to rush to the shop.

🐾 **Try it:** [keveria.com](https://keveria.com/?invite=gh-nk) · [@KeveriaBot](https://t.me/KeveriaBot)

## What the bot does

- **Runs out → reminds.** Tell it your pet's weight and the food pack you bought; the bot forecasts the day the
  pack ends and pings you a few days ahead. Same for cat litter.
- **Best price → tells you.** Prices for your exact food are collected from several Ukrainian pet stores every
  day; when it gets cheaper, you hear about it.
- **Care tips.** Short, practical guides on feeding, health and everyday care — in Ukrainian, written for owners,
  not for vets.
- **No noise.** One useful message a day at most, nothing at night.

The product is in a closed alpha. The interface is Ukrainian-only.

## Where to find us

| | |
|---|---|
| Website | [keveria.com](https://keveria.com) |
| Telegram channel | [t.me/keveria_app](https://t.me/keveria_app) |
| Instagram | [@keveria_app](https://www.instagram.com/keveria_app) |
| TikTok | [@keveria_app](https://www.tiktok.com/@keveria_app) |
| YouTube | [@keveria_app](https://www.youtube.com/@keveria_app) |
| X | [@keveria_app](https://x.com/keveria_app) |

## For developers

Keveria is built as a small modular system: a .NET core API that owns all business logic and the database, a
Python (aiogram) Telegram gateway with no business logic of its own, and a Python price scraper. Development is
spec-driven: every feature starts as a specification and ends with a live run before it ships.

The product repositories are private while the alpha is running. Questions, partnership ideas and store
integrations — write to us through the bot or the channel.

---

<sub>Keveria · Kyiv, Ukraine · © 2026</sub>
