# navid_chip_de - Unternehmenswebseite

Scrum-Projekt zum Aufbau der Unternehmenswebseite fuer **www.navid.chip.de**.

## Team

| Rolle | Person |
|---|---|
| Product Owner | Navid |
| Scrum Master | Dominic |
| UX/UI-Design | Julia |
| Frontend-Entwicklung | Jean Martin |
| Backend-Entwicklung | Arasch |
| Qualitaetssicherung | Bircan |

## Sprint 1 - Fundament & Design

Dieser Stand enthaelt das technische Fundament aus Sprint 1:

- **PB-05 - Projekt-Setup & Repository**: Ordnerstruktur, `package.json`, `.gitignore`, lauffaehiger Basis-Build.
- **PB-06 - Hosting- & Domain-Einrichtung**: GitHub-Pages-Workflow als Staging-Umgebung, `CNAME` fuer `www.navid.chip.de`.
- **PB-07 - Responsives Grundlayout**: Header, Navigation (inkl. mobilem Menue), Footer - fuer Desktop, Tablet und Mobile ausgelegt.

## Projektstruktur

```
.
+-- index.html                    # Grundlayout: Header, Navigation, Footer
+-- css/
|   +-- styles.css                # Styleguide-Variablen (PB-04) + responsives Layout
+-- js/
|   +-- main.js                   # Mobiles Navigations-Menue
+-- .github/workflows/
|   +-- deploy.yml                # Deployment auf GitHub Pages (Staging)
+-- CNAME                         # Domain: www.navid.chip.de
```

## Lokale Entwicklung

```bash
npm install
npm start
```

Startet einen lokalen Server unter `http://localhost:3000`.

## Status

Sprint 1 abgeschlossen - Konzept und technisches Fundament stehen bereit. Die inhaltliche Umsetzung (Startseite, Ueber uns, Leistungen) folgt in Sprint 2.
