# Miniwelt – Tamagotchi-Webspiel

Eine eigenständige, deutschsprachige Tamagotchi-inspirierte Web-App für GitHub Pages.

## Enthalten
- `index.html` – vollständiges Spiel (HTML, CSS und JavaScript)
- `charakter.jpg` – lokale Charaktergrafik

## Direkt auf GitHub Pages veröffentlichen
1. Erstelle ein neues GitHub-Repository.
2. Lade `index.html` und `charakter.jpg` aus diesem Ordner ins Stammverzeichnis hoch.
3. Öffne **Settings → Pages**.
4. Unter **Build and deployment**: **Deploy from a branch** auswählen.
5. Branch `main`, Ordner `/ (root)` wählen und speichern.
6. Nach dem Deployment zeigt GitHub Pages die URL deines Spiels an.

Alternativ kannst du den Inhalt dieses ZIPs vollständig ins Repository entpacken und hochladen.

## Spielstand
Der Spielstand wird mit `localStorage` lokal im Browser gespeichert. Es gibt keine Anmeldung und keinen Server. Ein Spielstand wird nicht automatisch zwischen Geräten synchronisiert. Der Charakter und alle anderen Assets liegen lokal im Repository, daher funktioniert das Spiel ohne externe Bild- oder Script-CDNs.

## Bedienung
- **Füttern, Spielen, Waschen, Schlafen, Leckerli, Aufräumen**: Bedürfnisse pflegen.
- **Tagesgeschenk**: einmal pro Kalendertag Münzen abholen.
- **Laden**: Deko kaufen.
- **Sammlung**: gekaufte Gegenstände aufstellen.
- **Tagebuch**: gemeinsame Erlebnisse ansehen.
- **Einstellungen**: Namen ändern oder einen neuen Spielstand beginnen.

## Technischer Hinweis
Statische Website ohne Build-Schritt: kein npm, keine API-Schlüssel, kein Backend.
