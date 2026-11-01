# Freizeitticket Tracker – Installation

## Enthalten
- `index.html`: die App
- `manifest.webmanifest`: PWA-Metadaten
- `service-worker.js`: Offline-Funktion
- `icon-192.png` und `icon-512.png`: App-Symbole

## Schnell ausprobieren
Öffne `index.html` in einem modernen Browser. Die App funktioniert als lokaler Tracker. Je nach Handy/Browser sind Offline-Modus und Installation bei direktem Öffnen einer Datei eingeschränkt.

## Als richtige Handy-App installieren (empfohlen)
Eine installierbare PWA muss über HTTPS bereitgestellt werden. Eine einfache kostenlose Option ist GitHub Pages:
1. Lege ein GitHub-Repository an.
2. Lade alle Dateien aus diesem Ordner in das Repository hoch.
3. Aktiviere in den Repository-Einstellungen unter **Pages** die Bereitstellung aus dem `main`-Branch und dem Root-Ordner.
4. Öffne die angezeigte `https://...`-Adresse am Handy.
5. iPhone/Safari: Teilen → **Zum Home-Bildschirm**. Android/Chrome: Menü → **App installieren** bzw. **Zum Startbildschirm hinzufügen**.

## Wichtige Hinweise zu Preisen
Die Partnerliste orientiert sich an den offiziellen Sommer-/Winter-Angeboten des Freizeittickets Tirol. Die in der App hinterlegten Preise sind **Startwerte/Richtpreise**, nicht für jeden Partner ein bestätigter Saison-2026/27-Tarif. Viele Skigebiete haben dynamische Preise oder Sondertarife. Bitte prüfe den konkreten Einzelpreis und überschreibe den Preisvorschlag bei Bedarf. Die App speichert jede Nutzung mit dem tatsächlich eingetragenen Betrag.

## Datenschutz und Backups
Alle Nutzungsdaten werden lokal im Browser gespeichert. Es wird kein Konto benötigt und die App sendet keine Einträge an einen Server. Nutze im Verlauf regelmäßig **Daten exportieren**, um ein Backup zu speichern. Beim Löschen der Browserdaten können lokal gespeicherte Einträge verloren gehen.

Offizielle Quellen:
- https://www.freizeitticket.at/ticket/preise/
- https://www.freizeitticket.at/sommer/
- https://www.freizeitticket.at/winter/
- https://www.freizeitticket.at/agb/
