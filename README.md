# EkoVolt — strona firmowa firmy fotowoltaicznej

Przykładowa strona z portfolio [100strona.pl](https://100strona.pl).

## O stronie

**EkoVolt** to fikcyjna firma fotowoltaiczna z Krakowa. Strona prezentuje
pełną ofertę: panele słoneczne, magazyny energii, pompy ciepła i audyt energetyczny.

**Styl:** czysty tech-eko — biało-granatowe tło, akcenty błękitu (#0ea5e9),
zieleni (#22c55e) i słonecznej żółci (#facc15). Miękkie cienie, zaokrąglone
karty, animowane liczniki oszczędności, reveal przy scrollu.

**Font:** Plus Jakarta Sans (700/800 display, 400/500 body).

## Sekcje

1. Nawigacja (fixed, collapse mobile)
2. Hero — dom z panelami, hasło, CTA, sygnały zaufania, live liczniki
3. Dlaczego fotowoltaika — 4 korzyści z liczbami, big-number bar
4. Usługi — fotowoltaika, magazyny, pompy ciepła, audyt energetyczny
5. Proces montażu — 5 kroków
6. Realizacje / opinie — 4 opinie klientów
7. Formularz darmowej wyceny + mapa OSM + dane kontaktowe
8. Footer z danymi, linkami i obowiązkowym creditem

## Stack

- Astro 5
- Tailwind CSS 4 (przez `@tailwindcss/vite`)
- Plus Jakarta Sans (Google Fonts)

## Komendy

```bash
npm install
npm run dev      # dev server: http://localhost:4321
npm run build    # build produkcyjny → dist/
npm run preview  # podgląd zbudowanej wersji
```

## Hosting

Gotowe do deployu na Vercel (`vercel deploy --prod`).
