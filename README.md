# Clarisa Saade — QA Automation Engineer · Personal CV Website

A personal portfolio/CV website built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies, no build step                          — just two standalone files ready to deploy anywhere.

---

## Project Structure

```
├── clarisa-saade-cv-es.html   # Spanish version
├── clarisa-saade-cv-en.html   # English version
└── README.md
```

---

## Files

### `clarisa-saade-cv-es.html` — Spanish Version

The primary version of the CV, written in Spanish.

**Sections (in order):**
1. Hero — name, animated typing title, location, CTA buttons and key stats
2. Sobre mí — professional profile and highlight cards
3. Herramientas y habilidades — full technology stack organized by category
4. Idiomas — language proficiency with animated progress bars
5. Trayectoria profesional — work history timeline (Globant, G&L Group, Qualis Lab)
6. Educación — academic background (EducacionIT, Universidad Nacional del Sur)
7. Intereses y hobbies — personal interests
8. Contacto — contact form (opens native email client) + links

**Key features:**
- Navigation bar with anchor links, Download CV button and a language switch button (`🇺🇸 EN`) that links to the English version
- On mobile, the language switch button is hidden from the navbar and shown as a highlighted green item inside the hamburger menu instead
- Download CV button generates an ATS-friendly PDF in Spanish on the fly using jsPDF (no server required)
- Contact form validates name, email and message, then opens the user's default mail client

---

### `clarisa-saade-cv-en.html` — English Version

Identical in design and functionality to the Spanish version. All content translated to English, sourced from the official English CV.

**Sections (in order):**
1. Hero
2. About me
3. Tools & Skills
4. Languages
5. Professional Experience
6. Education
7. Interests & Hobbies
8. Contact

**Key features:**
- Navigation bar with a language switch button (`🇦🇷 ES`) that links back to the Spanish version
- Same mobile behavior: language button hidden in navbar, shown as a highlighted green item in the hamburger menu
- Download CV button generates an ATS-friendly PDF in English on the fly
- Contact form addressed to user's mail client

---

## Language Switch

The two files link to each other. For the switch to work correctly, **both files must be in the same folder** — whether on a local server or deployed to a hosting provider.

```
clarisa-saade-cv-es.html  →  [🇺🇸 EN] button  →  clarisa-saade-cv-en.html
clarisa-saade-cv-en.html  →  [🇦🇷 ES] button  →  clarisa-saade-cv-es.html
```

No configuration needed — it's a plain HTML link between two files.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, animations) |
| Scripting | Vanilla JavaScript |
| PDF generation | [jsPDF 2.5.1](https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js) via CDN |
| Fonts | Google Fonts — DM Serif Display, IBM Plex Mono, Outfit |

No npm, no bundler, no framework. Both files are fully self-contained and work by opening them directly in a browser.

---

## Design

- **Color scheme:** dark background (`#060A12`) with teal accent (`#00D4AA`) and amber highlight (`#F5A623`)
- **Typography:** DM Serif Display (headings) · IBM Plex Mono (labels/code) · Outfit (body)
- **Responsive:** mobile-first layout, breakpoints at 900px, 768px and 480px
- **Animations:** scroll-triggered reveal, typing effect, language bar fill on scroll

---

## Deployment

These are static files — no server-side logic required. 

**GitHub Pages**


**Custom domain setup**


---

## Contact

**Clarisa Saade**
QA Automation Engineer · Buenos Aires, Argentina

📩 tae.clarisa@gmail.com

IN_es: https://www.linkedin.com/in/clarisaade/?locale=es-ES 

IN_en: https://www.linkedin.com/in/clarisaade/?locale=en-US
