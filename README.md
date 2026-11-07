# Jonas Vertrag Kager 33

Eine für das iPhone optimierte Web-App für Gartenarbeiten mit Kalender, Arbeitsstunden, Einnahmen und Monats-/Jahresauswertung.

## Auf GitHub Pages veröffentlichen

1. Erstelle auf https://github.com/new ein neues **öffentliches** Repository, zum Beispiel `jonas-kager-33`.
2. Entpacke die ZIP-Datei auf deinem Computer.
3. Öffne das Repository und wähle **Add file → Upload files**. Lade alle entpackten App-Dateien direkt in das Hauptverzeichnis hoch, insbesondere `index.html`, `app.js`, `sw.js`, `manifest.json` und `icon.svg`. Lade nicht nur die ZIP-Datei und nicht den umschließenden Ordner hoch.
4. Klicke auf **Commit changes**.
5. Öffne **Settings → Pages**. Wähle unter **Build and deployment** die Quelle **Deploy from a branch**, den Branch **main** und den Ordner **/ (root)**. Klicke **Save**.
6. Nach einigen Minuten erscheint dort die öffentliche Adresse: `https://DEIN-GITHUB-NAME.github.io/REPOSITORY-NAME/`.

Es sind weder eine Installation von Entwicklungswerkzeugen noch ein Build oder ein ChatGPT-Konto für Besucher nötig. Die App funktioniert auch unter dem Unterverzeichnis eines GitHub-Pages-Projekts.

## Auf dem iPhone

Öffne die öffentliche Adresse in Safari und wähle **Teilen → Zum Home-Bildschirm**.

## Daten und Sicherungen

Die Einträge und ein selbst ausgewähltes Hintergrundfoto werden lokal im Browser auf dem jeweiligen Gerät gespeichert. Es gibt keine Synchronisierung zwischen Geräten. Die Repository-Dateien enthalten keine persönlichen Arbeitseinträge.

**Vor dem Wechsel von der bisherigen App zu GitHub Pages:** Öffne in der bisherigen App **Einträge → Sicherung exportieren**. Öffne danach die neue GitHub-Pages-Adresse und wähle **Einträge → Sicherung importieren**. Browser-Speicher ist an die jeweilige Internetadresse gebunden; Einträge werden beim Umzug nicht automatisch übernommen. Ein eigenes Hintergrundfoto bitte neu auswählen.

Exportiere regelmäßig eine Sicherung. Beim Löschen der Browserdaten können lokal gespeicherte Einträge verloren gehen.

## Hintergrund und Schrift

Das voreingestellte Gartenfoto wird von Unsplash geladen, die Schriften von Google Fonts. Dafür wird eine Internetverbindung benötigt. Grundfunktionen und lokal gespeicherte Einträge können nach dem ersten Laden offline verfügbar sein; die Offline-Unterstützung hängt vom Browser ab.

## Enthaltene Dateien

- `index.html`: Oberfläche und Gestaltung
- `app.js`: Kalender, Einträge, Auswertung, Import/Export und Fotoauswahl
- `manifest.json`: Darstellung als Web-App
- `sw.js`: Offline-Zwischenspeicher
- `icon.svg`: App-Symbol
- `.nojekyll`: statische Veröffentlichung über GitHub Pages
