# Names Site (l3on.ch / m3lissa.ch / r3nata.ch / h3nrique.ch)

Eine minimalistische statische Seite: zeigt je nach Domain den jeweiligen Namen, zentriert, mit zufälliger Hintergrundfarbe und kontrastierter Schrift. Ein Repo, **vier Domains**, ein Deployment (Azure Static Web Apps).

## Quick Start

1. **Repo clonen / öffnen** (VS Code oder GitHub Desktop).
2. **`index.html`** liegt im Repo-Root (siehe unten).
3. **Push auf `main`** → GitHub Action deployed automatisch zu Azure Static Web Apps.

### Lokale Vorschau
Einfach die `index.html` im Browser öffnen (Doppelklick)  
oder mit einem simplen Server starten:
```bash
npx serve .
# oder
python3 -m http.server 8081
