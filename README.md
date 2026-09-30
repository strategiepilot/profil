# Andreas Barth – Executive Interim Management & Strategic Advisory Profile

Modernes, modulares DIN-A4 2-Pager Master-Template für Interim-Management- und Strategic-Advisor-Mandate. Entwickelt für Interim-Provider (Atreus, Taskforce, Valtus etc.), Matching-Plattformen und den direkten Live-Einsatz via Vercel.

Repository: `https://github.com/strategiepilot/profil`

---

## Highlights & Features

- **Exakt 2 Seiten DIN-A4**: Präzises Layout (`210mm × 297mm`) mit CSS Paged Media (`@page { size: A4 portrait; margin: 0; }`) und exakter Umbruchsteuerung (`break-after: page;`). Garantiert keine leere 3. Seite beim PDF-Export.
- **Exakt 2 Seiten DIN-A4**: Präzises Layout (`210mm × 297mm`) mit CSS Paged Media (`@page { size: A4 portrait; margin: 0; }`) und exakter Umbruchsteuerung (`break-after: page;`). Garantiert keine leere 3. Seite beim PDF-Export.
- **Beruhigtes 2-Farben-Design**: Konsequent reduziertes, minimalistisches Farbschema aus **Executive Slate (`#0F172A`)** und **Deep Blue (`#1E40AF`)** auf dezenten Slate-Grays. Keine unruhigen bunten Badges mehr.
- **Strukturiertes Flaggschiff-Mandat (Seite 1)**:
  - **september Strategie & Forschung** (2022–2025/heute): Digital Transformation Architect & Product Owner · später General Manager *„Emotion Engine“* (KI- & Machine-Learning-Plattform, Transformation psychologischer Modelle in skalierbare Datenprodukte).
- **Fortlaufender Track Record (Seite 2)**:
  - Chronologische Übersicht aller Management- und Advisory-Stationen: *Burger King Corp.* (8 Mrd. $+ P&L / 300 Mio. $+ Budget), *Fitness First Germany*, *STRATEGIEPILOT*, *Bavaria Consulting*, *LEGOLAND Deutschland*, *McDonald's Deutschland* sowie *Danone* und *Esprit Consulting*.
- **Methodik & Kernkompetenzen (3 Kacheln)**:
  - *Leadership & Transformation*, *Profitable Growth Strategy* und *Data Science & Generative AI*.
- **Modern AI & Data Science Stack**:
  - Genau abgestimmte Kompetenz-Tags: GenAI & LLM-Architekturen, RAG & Agentic AI, Machine Learning & MLOps, Python & PyTorch, Cloud AI (AWS / Azure / GCP), Predictive Analytics & Forecasting, Data & AI Governance (EU AI Act), SQL, R & Modern Data Stack.
- **Reale monochrome Markenlogos**:
  - Reale Vektorgrafiken von *McDonald's*, *Burger King*, *LEGOLAND*, *Fitness First* und *Danone* in dezentem Slate-Stil mit vollständigen `title`- und `aria-label`-Attributen.
- **Foto-Implementierung & einzeiliger Header**:
  - Runder Container (`w-24 h-24`) mit Porträt `Foto_Andreas.png` (Fallback: `avatar.svg`) und einzeiliger Subline mit klarem Fokus auf KI- und Digitale Transformation.
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
