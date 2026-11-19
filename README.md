# AI Onderzoeksacademie — testbranch

Deze versie bevat zeven zelfstandige lessen met verdiepte theorie, casusmateriaal, productopdrachten, rubrics, zelfbeoordeling, oefendata, controleuitkomsten, bronverwijzingen en een docentenhandleiding.

## Starten

Open `index.html` via GitHub Pages of een eenvoudige lokale server: `python -m http.server 8000` en open `http://localhost:8000`. De bestanden laden relatief; geen bundler en geen backend nodig.

## Structuur

- `index.html`: toegankelijke website-skelet
- `style.css`: opmaak en mobiele weergave
- `app.js`: navigatie, kennischecks, voortgang en export
- `data/lessons.js`: bewerkbare inhoud van zeven lessen
- `data/oefendata.csv` + `data/codeboek.md`: synthetische analyse-oefening
- `data/broncontrole-oefening.md`: audit-claims en primaire bronlocaties
- `docs/docentenhandleiding.md`: begeleiding en beoordelingskaders
- `docs/bronnen.md`: bronbasis en beperkingen

## Privacy en leerstatus

Antwoorden blijven op dit apparaat in `localStorage`; exporteer het portfolio als JSON. De status 'zelf beoordeeld' is geen onafhankelijke beoordeling. Geen inlog, centrale opslag of echte uploads.

## Publicatie

Dit is een testbranch. `main` blijft ongewijzigd. GitHub Pages met alleen `main` publiceert deze variant **niet automatisch**: gebruik een afzonderlijke previewdeployment of test lokaal na downloaden/branch-clone.

## Bekende grenzen

Geen integratie met AI-provider of LMS, geen servermatige inlevering, geen automatisch inhoudelijk cijfer. Methodologische voorbeeldantwoorden en tijdsbelasting zijn nog niet empirisch gevalideerd. Controleer zowel inhoud als toegankelijkheid met een studentpilot.