# Session Context — Wireframe-System

## Wer ist der User?

- **Name:** Paul (paul.goetzke@googlemail.com)
- **Erfahrung:** ~3 Monate Webdesign, arbeitet mit Claude Code (Opus 4.8 / Sonnet)
- **Ziel:** Schneller werden bei steigender Qualität
- **Haupt-Problem:** „Pixel schieben statt Konzept" — einzelne kleine Anpassungen kosten unverhältnismäßig viel Zeit (1–2 Wochen pro Seite bei 1–2h/Tag)
- **Fokus:** Landing Pages, Business Pages, E-Commerce Stores

---

## Was wurde gebaut

Ein wiederverwendbares **Wireframe-System** mit 4 Dateien:

| Datei | Inhalt |
|-------|--------|
| `wireframes/wireframe.css` | Zentrales Token-System — 4 Zeilen oben anpassen = ganzes Design ändert sich |
| `wireframes/landing.html` | Landing Page · 7 Blöcke: Hero → Problem → Lösung → Features → Social Proof → CTA → Footer |
| `wireframes/business.html` | Business Page · 8 Blöcke: Hero → Über uns → Leistungen → Warum wir → Team → Referenzen → Kontakt → Footer |
| `wireframes/ecommerce.html` | E-Commerce · 9 Blöcke: Hero → Kategorien → Featured → USPs → Bestseller → Reviews → Newsletter → FAQ → Footer |

### Das clevere Detail: Wireframe-Modus

- `<body class="wireframe">` = Skizzen-Modus: Sektion-Labels + gestreifte Platzhalter-Boxen sichtbar
- Klasse entfernen = fertiges Design ohne Hilfsmarkierungen
- Dieselbe Datei ist gleichzeitig Wireframe und fertige Seite

### CSS-Tokens (oben in wireframe.css anpassen)

```css
--color-primary:  #7c3aed;   /* Hauptfarbe — Paul hat es schon auf Lila geändert */
--color-accent:   #f4a261;
--font-heading:   "Inter", system-ui, sans-serif;
--font-body:      "Inter", system-ui, sans-serif;
```

---

## Wo wir aufgehört haben

**Nächster Schritt:** Ein Wireframe mit echtem Projekt-Inhalt befüllen.

Paul wollte in einem neuen Projekt folgendes angeben:
- **Was?** (z.B. „Landing Page für Fitness-App")
- **Farbe + Schrift** (oder Claude schlägt passend vor)
- **Ton** (verspielt / seriös / edel / technisch)

Dann: passende Vorlage komplett befüllen + Wireframe-Modus ausschalten → fertiges Ergebnis in der Vorschau.

---

## Claude-Prompt-Vorlage zum Weitermachen

```
Lies SESSION-CONTEXT.md — wir machen genau dort weiter.

Nutze wireframes/[landing|business|ecommerce].html als Struktur.
Kunde: [Beschreibung]
Farbe: [Hauptfarbe] primär, [Zweitfarbe] hell
Schrift: [Heading-Font] (Headlines) + [Body-Font] (Text)
Ton: [verspielt / seriös / edel / technisch]
Fülle alle Platzhalter mit realistischem Inhalt und
entferne den Wireframe-Modus (class="wireframe" vom body).
```
