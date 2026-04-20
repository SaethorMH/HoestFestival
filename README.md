## Teknisk dokumentation - Grp. 11

# Høst Møn

---

## Om Projekt

I dette projekt kommer vi med vores forslag til hvordan Høst Møns hjemme side kunne se ud og fungere. For at lave hjemmesiden har vi først idéudviklet og designet i figma og siden har vi kodet løsningen vha. astro. Udover astro har vi brugt supabase til at lave en database som vi bruger i løsningen

---

### Links

- GitHub repository: https://github.com/SaethorMH/Hoestfestival
- Netlify host: www.hoestfestival.netlify.com
- Figma: https://www.figma.com/design/P5ca9eA4TnJ4tSCS5KipeT/H%C3%B8st-M%C3%B8n?node-id=490-1873&t=ROxyuhbm3PGo7U8n-0

---

## Projektstruktur

```
project/
├── .gitignore
├── *astro filer*
├── src/
│   ├── pages/
│   │     ├── index.astro
│   │     ├── program.astro
│   │     ├── arkiv.astro
│   │     ├── om.astro
│   │     └── pladsen.astro
│   ├── layout/
│   │     └── Layout.astro
│   └── components/
│         ├── Footer.
│         ├── Header.astro
│         └── KunstnerKort.astro
│
├── public/
│   ├── billeder/
│   │     └── alle billederne
│   ├── font/
│   │     ├── londrinasolid-regular-webfont.woff2
│   │     └── ...
│   ├── discover.css
│   ├── favicon.ico
│   └── recipe.css
└── README.md
```

---

# Filbeskrivelser

## Public

## src

### Pages

- index.astro – forsiden

### Components

- KunstnerKort.astro - Billede of navn på kunstner fører til om dem i programmet.

---

# Astro

## Komponenter

### Workflow

0. Pull seneste version
1. Lave en branch med et beskrivende feature-navn eller med eget navn
2. Kode en feature
3. Committe ændringer
4. Pushe til GitHub

Gentag til man er færdig.

5. Merge til main når det virkede

---

## Mulige forbedringer

- ***

## Gruppemedlemmer:

- Nicolai
- Joakim
- Sæthor
