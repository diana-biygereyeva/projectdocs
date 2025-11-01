# Lost in Tra(i)nslation – Ontwerpdocumentatie

## Over het project

**Lost in Tra(i)nslation** is een ontwerpdocument dat het volledige ontwerpproces van een digitaal prototype documenteert.  
De focus ligt op **UX/UI-onderzoek, visuele hiërarchie, toegankelijkheid** en **consistentie** binnen de context van **treininformatie-schermen**.  
Het project werd opgebouwd in **HTML en CSS**, met aandacht voor leesbaarheid, structuur en navigatie.

**Auteur:** Diana Biygereyeva  
**Opleiding:** 1GDM2  
**Jaar:** 2025

---

## Structuur van de website

De website bestaat uit meerdere HTML-pagina’s – één per lesweek – die verbonden zijn via een navigatiemenu in de sidebar.

**Bestandsstructuur:**

```
project/
│
├── index.html
├── week1.html
├── week2.html
├── week3.html
├── week4.html
├── week5.html
├── week6.html
│
└── assets/
    └── styles.css
```

**Navigatie:**
De sidebar bevat links naar:

- Home
- Week 01 – Prototyping Tools
- Week 02 – Treinsamenstelling en iconen
- Week 03 – Annotaties en schetsverbeteringen
- Week 04 – HTML-prototyping en kleurthema’s
- Week 05 – Verbeterde layouts en iconentests
- Week 06 – Eindstructuur en consistentie

---

## Styling en layout

De CSS in `assets/styles.css` zorgt voor een moderne en toegankelijke vormgeving met nadruk op leesbaarheid.

### Belangrijkste kenmerken

- **Font:** Roboto (via Google Fonts)
- **Layout:** Flexbox, met sidebar-navigatie en hoofdinhoud naast elkaar
- **Kleurenpalet:**
  - **Primair:** wit `#FFFFFF`
  - **Secundair:** grijs `#F5F5F5` en donkergrijs `#333333`
- **Interactie:** Hover-effecten op navigatie en actieve paginaweergave
- **Toegankelijkheid:** `lang="nl"` en semantische HTML-tags (`header`, `main`, `footer`)

---

## Typografie

De website maakt gebruik van **Roboto**, een strak en goed leesbaar schreefloos lettertype dat ideaal is voor digitale interfaces.  
Het lettertype werd geïmporteerd via [Google Fonts](https://fonts.google.com/specimen/Roboto).

### Typografische hiërarchie

- **Koppen (h1, h2, h3):** Roboto Bold, lettergrootte variërend van 24px tot 32px
- **Hoofdtekst (p):** Roboto Regular, 16px
- **Navigatietekst:** Roboto Medium, 14px
- **Kleurencontrast:** Donkere tekst op lichte achtergrond voor optimale leesbaarheid

---

## Toekomstige stappen

- Toevoegen van interactieve elementen (hover, animatie, navigatie).
- Testen van iconenherkenbaarheid en contrasttoegankelijkheid.
- Screenshots van wegwijschermen erbij plaatsen.

---

## Technische specificaties

- HTML5 & CSS3
- Flexbox layout
- Responsief ontwerp
- Semantische HTML-tags
- Taalinstelling: `lang="nl"`
- Licentie: © 2025 Diana Biygereyeva – 1GDM2

---

## Samenvatting

Dit project toont de evolutie van een concept tot een digitaal prototype binnen een UX/UI-context.  
Het resultaat is een helder, toegankelijk en consistent ontwerpdocument dat de ontwerpbeslissingen van _Lost in Tra(i)nslation_ samenvat.
