# Väth Handball Coach – PWA-Vorbereitung (ohne Spielerinnendaten)

Dieses Paket enthält die aktuelle App als installierbare Progressive Web App (PWA).

## Enthaltene Dateien
- `index.html` – App-Oberfläche und Funktionen
- `manifest.webmanifest` – Name, Startpfad und Installationsdarstellung
- `sw.js` – Service Worker für App-Shell-/Offline-Grundfunktionen
- `icon.svg` – App-Symbol

## Datenschutz / Spielerinnendaten
Dieses Paket enthält keine vorbefüllten Spielerinnen, Bewertungen, Fotos oder Teamchemie-Daten. Die App startet mit leerem Kader. Eingegebene Daten werden weiterhin lokal im Browser gespeichert. Sie werden nicht automatisch an GitHub hochgeladen.

Wichtig: GitHub Pages ist öffentlich. Nur die App-Dateien sollten in das öffentliche Repository kommen; keine exportierten Sicherungen, Fotos oder Spielerdaten hochladen.

## Kostenlos auf GitHub Pages veröffentlichen
1. Bei GitHub anmelden.
2. Ein neues **Public** Repository erstellen, zum Beispiel `vaeth-handball-coach`.
3. Die vier App-Dateien aus diesem Ordner direkt in das Repository hochladen.
4. Im Repository **Settings → Pages** öffnen.
5. Bei **Build and deployment** `Deploy from a branch` wählen.
6. Branch `main`, Ordner `/(root)` wählen und speichern.
7. Nach Abschluss die angezeigte Pages-Adresse öffnen.

## Installation
- iPhone: veröffentlichte Website in Safari öffnen → Teilen → „Zum Home-Bildschirm“.
- Android: Website in Chrome öffnen → Menü → „App installieren“ oder „Zum Startbildschirm hinzufügen“.

Die Offline-Funktion funktioniert nach erfolgreichem ersten Laden und nachdem der Service Worker aktiviert wurde. App-Store-Veröffentlichungen und bezahlte Dienste sind nicht Teil dieses kostenlosen Setups.
