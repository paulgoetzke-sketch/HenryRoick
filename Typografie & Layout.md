# Webdesign-Leitfaden: Typografie & Layout

  

*Basierend auf dem Video „The Only 5 Web Design Skills That Actually Matter“ von Chris Misterek (Self-Made Web Designer).*

  

---

  

## 📖 Einführung

Dieser Leitfaden fasst die essenziellen Erkenntnisse zum Thema **Typografie** und **Layout** zusammen. Die Anwendung dieser systematischen Prinzipien hebt Webdesigns von der breiten Masse ab und verleiht ihnen einen professionellen, harmonischen Charakter.

  

---

  

## 🅰️ Teil 1: Typografie (Typography) – Die wichtigste Fähigkeit

  

Text nimmt neben dem Leerraum (Whitespace) den größten Platz auf einer Website ein. Dennoch wird Typografie von vielen Designern stiefmütterlich behandelt. Um professionelle Designs zu erstellen, müssen Sie zwei Kernfragen beherrschen:

  

### 1. Wie wähle ich die passenden Schriftarten aus?

*   **Problem:** Die Nutzung allzu bekannter Standard-Schriftarten (wie z. B. mancher Standard Google Fonts) lässt Designs austauschbar wirken.

*   **Lösung:** Schriftarten aus weniger genutzten, hochwertigen Bibliotheken wählen:

    *   **[Fontshare](https://www.fontshare.com/):** Bietet saubere, hochqualitative und vollständig kostenlose Schriftarten.

    *   **[Uncut](https://uncut.wtf/):** Ideal für modernere, experimentellere und charakterstarke Designs.

  

### 2. Wie richte ich meine Schriftarten systematisch ein?

Profis würfeln Schriftgrößen nicht aus, sondern nutzen ein mathematisches System – das **Type-Scale-System**. Dieses definiert das harmonische Verhältnis zwischen den Überschriften und dem Fließtext.

  

| Element | Größe | Berechnung (Faktor 1.25 / Große Terz) |

| :--- | :--- | :--- |

| **Fließtext (Paragraph)** | 16px | Basisgröße (1rem) |

| **H6** | 20px | 16px * 1.25 |

| **H5** | 25px | 20px * 1.25 |

| **H4** | 31px | 25px * 1.25 |

| **H3** | 39px | 31px * 1.25 |

| **H2** | 49px | 39px * 1.25 |

| **H1** | 61px | 49px * 1.25 |

  

#### Wichtige Parameter für Schrifteinstellungen:

*   **Einheiten (REMs):** Nutzen Sie im Code `rem` statt `px` (z. B. `1rem` = 16px), um Barrierefreiheit und responsives Skalieren zu gewährleisten.

*   **Zeichenabstand (Letter Spacing):**

    *   *Fließtext:* Unverändert lassen (Standard).

    *   *Überschriften:* Je größer die Schrift, desto enger ziehen (bis zu `-2%` bei sehr großen Headings).

*   **Zeilenhöhe (Line Height):**

    *   *Fließtext:* Benötigt ca. `150%` (1.5) Zeilenhöhe für optimale Lesbarkeit.

    *   *Überschriften:* Zeilenhöhe bei zunehmender Größe verringern (engere Abstände erhöhen die visuelle Schlagkraft).

*   **Tool-Tipp:** Nutzen Sie [Typescale.com](https://typescale.com/), um diese Skalen automatisch zu generieren.

  

---

  

## 📐 Teil 2: Layout – Das unsichtbare Strukturgerüst

  

Das reine Platzieren nach Gefühl („Eyeballing“) führt zu visueller Unruhe. Ein professionelles Layout stützt sich auf drei klar definierte Säulen:

  

### Säule 1: Spalten-Raster & Das 8-Punkt-Grid

Das Spalten-Raster ordnet Elemente horizontal an:

*   **Desktop:** 12 Spalten (hohe Flexibilität, da durch 2, 3, 4 und 6 teilbar).

*   **Tablet:** 8 Spalten.

*   **Mobil:** 4 Spalten.

  

Für vertikale Abstände und Abstände innerhalb von Elementen nutzen Design-Teams (wie bei Google und Apple) das **8-Punkt-Rastersystem**:

*   Alle Abstände (Margins, Paddings, Gaps) werden ausschließlich in Schritten von **8px** gewählt (z. B. `8px`, `16px`, `24px`, `32px`, `48px`, `64px`).

*   Dies entfernt das Raten und bringt absolute Konsistenz in das Design.

  

### Säule 2: Abstände meistern (Master Spacing)

Whitespace gibt Inhalten Luft zum Atmen und erhöht die gefühlte Wertigkeit der Seite.

*   **Die goldene Regel:** Verdoppeln Sie den Abstand **zwischen** Sektionen im Vergleich zum Abstand **innerhalb** von Sektionen.

*   *Beispiel:* Wenn Elemente innerhalb einer Card 16px Abstand haben, nutzen Sie mindestens 32px (oder 64px) Abstand zwischen den Hauptabschnitten.

  

### Säule 3: Visuelle Hierarchie

Da Nutzer Webseiten scannen statt sie zu lesen, muss das Auge aktiv geführt werden. Dies gelingt durch vier Kernprinzipien:

1.  **Nähe (Proximity):** Zusammengehörige Elemente (z. B. Headline und Fließtext) stehen nah beieinander.

2.  **Größe (Size):** Die wichtigste Aussage muss das auffälligste und größte Element der Sektion sein.

3.  **Kontrast (Contrast):** Nutzen Sie deutliche Unterschiede in Helligkeit und Schriftschnitt (z. B. Bold vs. Regular).

4.  **Ausrichtung (Alignment):** Richten Sie Elemente exakt an den Grid-Linien aus. Präzision schafft visuelle Ruhe.

  

---

  

## 📋 Zusammenfassung & Aktionsplan

  

1.  **Typografie-System definieren:** Wählen Sie eine ausdrucksstarke Headline-Schriftart und eine hochlesbare Body-Schriftart. Setzen Sie die Größen im Verhältnis 1.25 an und nutzen Sie `rem`.

2.  **Rastersysteme implementieren:** Verwenden Sie das 12-Spalten-Raster auf Desktop und das 8px-System für jegliche Abstände (Margins, Paddings, Gaps).

3.  **Whitespace verdoppeln:** Sorgen Sie für ausreichend Freiraum. Nutzen Sie doppelt so viel Abstand zwischen Sektionen wie innerhalb von Sektionen.

4.  **Auf Conversion ausrichten:** Bedenken Sie bei jedem Layout das Ziel (z. B. Kauf, Anmeldung). Platzieren Sie strategisch und auffällig Ihre Calls-to-Action (CTAs).

  