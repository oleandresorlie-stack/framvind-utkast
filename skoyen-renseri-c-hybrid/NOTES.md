# Skøyen Renseri — C-hybrid (Astra look + Inntak features)

**Dato:** 2026-09-18 (Europe/Oslo)  
**Mappe:** `/workspace/framvind-utkast-host/skoyen-renseri-c-hybrid/`  
**Retning (Ole, 2026-09-18):** «variant C, men jeg vil fortsatt beholde kalender, prisliste, og chatbot, vipps logo. Likte de nye fargene best»

A (westcon), B (28test) og C (astra) er **urørt**.

## Hva hybriden er

**Visuelt språk = Variant C (Astra / TripGlide Round-2)**  
**Inntaksfunksjoner = Westcon A (full booking-stack)**

### Fra C (look)
- Palett: cream `#F2F0E6` / `#F7F4EB` + forest `#1a3c2a` + sage-aksenter
- Typografi: Playfair Display (serif) + Inter (UI)
- Pill-CTAs med ↗, editorial cards, sticky cream-nav
- Hero med phone-stage + floating info-kort
- Destination-servicekort (asymmetrisk grid)
- Magasin-labels (`RENS · SKØYEN`, `EKSEMPELPRISER`, …)

### Fra Inntak / Westcon A (features)
- **Kalender** med månedsskifte + klikkbare dager (søndag disabled)
- **Tidsluker** for butikk-innlevering
- **Prisliste / produkt-steppere** (+/−) med linjesummer og grand total
- **Vipps** offisiell logo + valg Vipps nå / betal i butikk + demo-modal
- **Chatbot** (FAB, minimerbar, kvalifiserende steg)
- Sticky mobil Ring / Book

### Sannhetslåser (beholdt)
- Kun **butikk-innlevering** — ingen henting/hjemlevering
- Adresse: **Hoffsveien 10, 0275 Oslo**
- Telefon: **483 99 744**
- Eksempelpriser merket tydelig («Eksempelpriser — endelig pris etter inspeksjon»)
- Google 5,0★ / 2 anmeldelser
- Footer: `Utkast fra Framvind — ikke offisiell side.`

## Shots
- `shots/hero-mobile.png` (også `hero.png`)
- `shots/booking-mobile.png` (også `booking.png`) — kalender + steppers + tid
- `shots/prices-mobile.png` (også `prices.png`) — eksempelprisliste
- `shots/chat-mobile.png` (også `chat.png`) — åpen chat-widget

## Assets
Kopiert fra Astra/Westcon (`assets/`), inkludert Vipps SVG-logoer.

## LOCKED as default renseri shell — 2026-09-18 (Ole)

Ole: use **exactly these colors** + **this layout** on all renseri previews going forward. If the scraped live site has its own photos, use those. Chrome palette stays C-hybrid regardless of prospect brand colors.

Variables only: logo, scraped photos, copy, prices, henting/levering iff live.
