# Firma Soltani Web-App

## Dateien
- index.html = normale App
- admin.html = Admin-Bereich
- manifest.webmanifest = Installation auf iPhone/Android
- service-worker.js = Offline-Unterstützung

## Admin
Die Admin-Seite ist absichtlich nicht in der normalen App sichtbar.
Sie wird direkt über `/admin.html` aufgerufen.

Standard-PIN: `soltani`

Nach dem ersten Login kannst du die PIN ändern.

Im Admin-Bereich kannst du:
- Tourname und Tournummer ändern
- Stopps hinzufügen
- Stopps bearbeiten
- Stopps löschen
- Name und Typ (Apotheke/Optiker) ändern
- Adresse ändern
- Barcode ändern
- Schlüsselnummer ändern
- Schlüsselfarbe ändern
- GPS-Koordinaten ändern

Die Daten werden auf demselben Gerät/Browser gespeichert und von der normalen App verwendet.

## GitHub Pages
Lade alle Dateien dieses Ordners in ein GitHub-Repository.
Settings -> Pages -> Deploy from a branch -> main -> /(root).

Danach:
- normale App: `/`
- Admin: `/admin.html`

Wichtig: Das ist ein lokaler Admin-Schutz im Browser, keine echte Server-Authentifizierung.
Für einen echten, passwortgeschützten Admin mit zentraler Datenbank können wir später einen Server hinzufügen.
