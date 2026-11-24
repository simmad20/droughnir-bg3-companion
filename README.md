# Droughnir – BG3 Companion

Persönlicher Companion für **Droughnir** (Roter Drachenblütiger, Eidbrecher-Paladin) in *Baldur's Gate 3*:
Live-Checkliste, Build-Wege, Level-Guide, Ausrüstung mit Upgrade-Pfaden, Kampf-Referenz, Atlas und Detail-Popups.

**Live:** https://simmad20.github.io/droughnir-bg3-companion/

## Dateien

| Datei | Zweck |
|---|---|
| `index.html` | Die komplette App – eine eigenständige Datei, alle Pfade relativ |
| `droughnir.png` | Dein Charakterbild (Porträt in Kopfleiste und Charakterbogen) |
| `.nojekyll` | GitHub Pages liefert die Dateien ohne Jekyll-Verarbeitung aus |

## Eigenes Charakterbild

- **Im Repo:** Bild als `droughnir.png` ins Root-Verzeichnis legen (überschreibt das aktuelle).
- **Nur im Browser:** Auf der Website „Charakterbild hochladen“ klicken oder ein Bild aufs Porträt ziehen. Eigene Uploads liegen in der IndexedDB deines Browsers und haben immer Vorrang.

## Bilder & Icons

Items, Zauber, Tränke und Porträts werden automatisch über `https://bg3.wiki/wiki/Special:FilePath/…` geladen.
Findet die Seite unter keinem der hinterlegten Dateinamen ein Bild, erscheint automatisch ein Vektor-Icon – nie ein kaputtes Bild.
Über **Bilder** in der Kopfleiste siehst du, welche Bilder automatisch geladen wurden, und kannst jedes durch ein eigenes ersetzen.

Bilder von bg3.wiki stehen unter CC BY-NC-SA; Spielinhalte © Larian Studios.

## Daten

Fortschritt, Einstellungen und Notizen werden im `localStorage` deines Browsers gespeichert.
Über **Daten / Backup** in der Kopfleiste kannst du alles als JSON exportieren und auf einem anderen Gerät wieder importieren.

## GitHub Pages aktivieren

Settings → Pages → *Build and deployment* → Source: **Deploy from a branch** → Branch: **main** / **(root)** → Save.
