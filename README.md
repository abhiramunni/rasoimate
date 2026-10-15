# RasoiMate — What Can You Cook With What's in Your Kitchen?

**Stop staring into the fridge. Start cooking.**

RasoiMate is a single-file web app for Indian home cooking. Tap the ingredients you already have in your kitchen, and it finds recipes you can make right now — ranked by how many ingredients match. Plan your whole week, then build a shopping list from the plan in one tap.

Live demo: **https://abhiramunni.github.io/rasoimate/**

## Who it's for

Anyone who cooks Indian food at home — beginners who need honest step-by-step instructions, busy parents planning the week's meals, bachelors figuring out dinner with a half-empty pantry, and kids learning their first recipes with a parent.

## Features

- **Pantry-first recipe finder** — 74 ingredients across 5 categories (vegetables, dals & legumes, grains & flours, dairy & protein, spices). Tap what you have; recipes are ranked by match %, best first, with missing ingredients highlighted.
- **30 real Indian recipes** — dal tadka, paneer butter masala, chole, sambar, rasam, lemon rice, veg biryani, chicken curry, Kerala fish curry, pav bhaji, misal pav, kheer, masala chai, filter coffee and more. Every recipe has honest timings, serving counts, difficulty level, veg/non-veg marking, quantities, and beginner-friendly numbered steps.
- **Veg-only & under-30-min filters** — one-tap filters on the Cook tab.
- **Recipe detail sheets** — ingredients with green ticks for what you already own, missing items highlighted, and a one-tap **"Add missing items to shopping list"** button.
- **Cooking timer** — preset (5/10/15/20/30 min) countdown with progress ring, pause/resume/reset, and a chime when time's up.
- **Favourites** — heart any recipe for quick access.
- **"I cooked this" tracker** — logs every dish you cook; the header counts your total meals cooked.
- **Week planner** — assign recipes to breakfast, lunch and dinner for all 7 days. Tap a slot to pick, tap × to remove.
- **One-tap shopping list** — collects every ingredient your planned week needs, shows which dish each item is for, plus your own custom items. Tick items off as you shop, copy the list to clipboard, clear ticked or all.
- **Guided UX** — cinematic full-screen intro (tap to skip), 3-step first-run tour, helper text under inputs, plain-language match explanations, tooltips, and friendly empty states.
- **Mobile-first, offline-friendly** — responsive layout, bottom tab bar on phones, works with no network after first load.

## How to use

1. **Pick your pantry (Cook tab)** — tap every ingredient you have at home. Your picks save automatically on this device.
2. **Find recipes** — tap **Find recipes with my ingredients**. The best matches appear first with a match score.
3. **Open a recipe** — tap any card for ingredients (green ticks = you have it), steps, a cooking timer, and buttons to save, log, or add missing items to your shopping list.
4. **Plan your week (Planner tab)** — tap any breakfast/lunch/dinner slot and assign a recipe.
5. **Shop once (Shopping tab)** — tap **Build shopping list from this week**, tick items off as you buy them.

## Tech stack

- Vanilla HTML, CSS and JavaScript — no frameworks, no build step, no backend
- `localStorage` for all persistence (pantry, favourites, planner, shopping list, cooked log) under the key `rasoimate_v1`
- Inline SVG icon set — zero emojis
- Google Fonts (Fraunces + Inter) via CDN with system-font fallback
- Three Unsplash food photos (verified live), each with an automatic fallback if a photo fails to load
- One self-contained `index.html`

## Data & privacy

Everything stays in your browser's `localStorage` — no accounts, no analytics, no tracking, no data leaves your device. The only network requests the app makes are loading the fonts and the three hero photos. Clearing your browser's site data wipes your pantry, planner and lists.

## Author

Built by **Abhiram Unni** — https://github.com/abhiramunni
