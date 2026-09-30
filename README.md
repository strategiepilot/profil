# Andreas Barth – Executive Interim Management & Strategic Advisory Profile

Modernes, modulares DIN-A4 2-Pager Master-Template für Interim-Management- und Strategic-Advisor-Mandate. Entwickelt für Interim-Provider (Atreus, Taskforce, Valtus etc.), Matching-Plattformen und den direkten Live-Einsatz via Vercel.

Repository: `https://github.com/strategiepilot/profil`

---

## Highlights & Features

- **Exakt 2 Seiten DIN-A4**: Präzises Layout (`210mm × 297mm`) mit CSS Paged Media (`@page { size: A4 portrait; margin: 0; }`) und exakter Umbruchsteuerung (`break-after: page;`). Garantiert keine leere 3. Seite beim PDF-Export.
- **Executive Navy / Slate Design**: Farbpalette `#0F172A`, subtile Akzente, gestochen scharfe Typografie in **Inter** mit Tabellenziffern und klaren Hierarchien.
- **Prominentes Leuchtturm-Mandat**:
  - **september Strategie & Forschung** (2022–heute): Digital Transformation Architect & Product Owner *„Emotion Engine“* (KI- & Machine-Learning-Plattform, Transformation psychologischer Modelle in skalierbare Datenprodukte).
- **CAR-Format für Flaggschiff-Turn-Arounds**:
  - **Burger King Corp. (Miami/USA)**: P&L-Turn-Around, >7.000 Restaurants, Sanierung der Preispromotions.
  - **Fitness First Germany**: Relaunch, Digitalisierung der Lead-Kanäle (300k+ Leads p.a., >20% Zuwachs).
- **Foto-Implementierung (Flexibel & Anglo-American Ready)**:
  - Runder Container (`w-24 h-24`, dezent gerahmt) mit automatischer Fallback-Unterstützung auf `avatar.svg` oder echtes Foto via `./avatar.jpg`.
  - Kann über den Schalter *"Foto"* in der Aktionsleiste oder via CSS-Klasse `.no-photo` / `.hidden` für internationale / angloamerikanische Märkte ohne Layout-Verschiebung ausgeblendet werden.
- **Monochrome Trust-Logobar**:
  - Direkt unter dem Key-Metrics-Grid als visueller Markenanker platziert.
  - Vektor-Markenzeichen von *McDonald's*, *Burger King*, *LEGOLAND*, *Fitness First* und *Danone* in elegantem Slate-Look mit vollständigen `title`- und `aria-label`-Attributen für Barrierefreiheit und ATS-Parser.
- **Modularer Provider-Modus (Blindprofil)**:
  - Über den Schalter in der schwebenden Aktionsleiste kann das Profil mit einem Klick in ein anonymisiertes Provider-Exposé umgeschaltet werden (Name & Kontaktdaten werden durch eine neutrale Kennung ersetzt, Foto wird automatisch ausgeblendet).
- **Direkter PDF-Druck**: Schwebender Action-Button oben rechts (`window.print()`), im Druckdialog automatisch via `print:hidden` ausgeblendet.

---

## Lokale Vorschau

Ein einfacher HTTP-Server reicht aus:

```bash
# Python 3
python3 -m http.server 8080
```

Anschließend im Browser öffnen: `http://localhost:8080`

### PDF-Export im Browser (`Cmd + P` / `Strg + P`):
1. **Ziel**: *Als PDF speichern*
2. **Papierformat**: *A4*
3. **Ränder**: *Standard* oder *Keine*
4. **Optionen**: Häkchen bei *Hintergrundgrafiken aktivieren* setzen

---

## Deployment auf Vercel

Das Projekt ist mit `vercel.json` für saubere URLs und empfohlene Sicherheitsheader vorkonfiguriert.

Nach dem Push auf GitHub (`https://github.com/strategiepilot/profil`):
1. Auf [vercel.com](https://vercel.com) importieren.
2. Framework-Preset: *Other* (reines statisches HTML).
3. Direkt deployen.
