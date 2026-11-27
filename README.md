# BG3 Companions

Persönliche Companion-Seiten für *Baldur's Gate 3* – Checkliste, Build-Wege, Level-Guide, Ausrüstung mit Upgrade-Pfaden, Alchemie, Kampf-Referenz und Atlas.

**Übersicht:** https://simmad20.github.io/bg3-companions/

| Companion | Seite | Ordner |
|---|---|---|
| Droughnir – Roter Drachenblütiger, Eidbrecher-Paladin | https://simmad20.github.io/bg3-companions/droughnir/ | `droughnir/` |
| Sylvaran – Druide (Beschwörer & Gestaltwandler) | https://simmad20.github.io/bg3-companions/sylvaran/ | `sylvaran/` |

## Aufbau

- `index.html` – Startseite: zeigt alle Companions mit Bild, Stufe, Weg und Checklisten-Fortschritt (liest den lokalen Speicher der Apps).
- `<name>/index.html` – die komplette App, eine eigenständige Datei.
- `droughnir/droughnir.png` – Droughnirs Charakterbild.
- `.nojekyll` – GitHub Pages liefert die Dateien 1:1 aus.

Jede App hat oben links den Button „Übersicht“ zurück zur Startseite. Alle Daten bleiben lokal im Browser; jeder Companion speichert unter eigenen Schlüsseln (`droughnir-bg3-…`, `druid-bg3-…`).

## Neuer Companion

Neuen Ordner anlegen (z. B. `magier/index.html`), eigene Speicher-Schlüssel verwenden und eine Karte in der Startseite ergänzen.
