# Wireframe-System

Drei wiederverwendbare HTML-Wireframes mit gemeinsamem Token-System.
Ziel: Neue Seiten = Ausfüllen statt bei null anfangen.

## Dateien

| Datei | Zweck | Blöcke |
|-------|-------|--------|
| `wireframe.css`  | Zentrale Styles + Design-Tokens (1× pro Projekt anpassen) | — |
| `landing.html`   | Landing Page | Hero → Problem → Lösung → Features → Social Proof → CTA → Footer |
| `business.html`  | Business / Dienstleister | Hero → Über uns → Leistungen → Warum wir → Team → Referenzen → Kontakt → Footer |
| `ecommerce.html` | Online-Shop | Hero → Kategorien → Featured → USPs → Bestseller → Reviews → Newsletter → FAQ → Footer |

## Workflow (so wirst du schnell)

**1. Datei kopieren** — passende `.html` + `wireframe.css` ins neue Projekt.

**2. Tokens anpassen** — in `wireframe.css` ganz oben nur diesen Block:
```css
--color-primary:  #2c5f8a;   /* deine Hauptfarbe */
--color-accent:   #f4a261;   /* deine Zweitfarbe */
--font-heading:   "Inter";   /* Überschriften */
--font-body:      "Inter";   /* Fließtext */
```
Das ganze Design zieht automatisch nach.

**3. Inhalte füllen** — Platzhaltertexte ersetzen, `.ph`-Boxen durch echte `<img>` tauschen.

**4. Skizzen-Modus aus** — wenn fertig, am `<body>` die Klasse `wireframe` entfernen.
Dann verschwinden Labels + gestreifte Platzhalter, übrig bleibt das echte Design.

## Claude-Prompt-Vorlage

Statt „bau mir eine Seite“ — gib Kontext, dann geht's in einem Rutsch:

```
Nutze wireframes/landing.html als Struktur.
Kunde: Zahnarztpraxis Dr. Müller, Köln
Farbe: #1B7FA8 primär, #E8F4F8 hell
Schrift: Poppins (Headlines) + Inter (Text)
Ton: vertrauensvoll, sauber, modern
Fülle alle Platzhalter mit realistischem Inhalt und
entferne den Wireframe-Modus.
```

## Spickzettel CSS-Klassen

- Layout: `.container`, `.section`, `.section--surface`, `.split`, `.grid grid-2|3|4`
- Text: `.eyebrow`, `.lead`, `.center`
- Buttons: `.btn`, `.btn--ghost`, `.btn--lg`
- Boxen: `.card`, `.ph` (Platzhalter), `.ph--sm|lg|circle`
- Sektion-Label: `data-label="HERO"` am `<section>`
