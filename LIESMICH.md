# Masterarbeitsfinder – Handy-App (PWA)

Die App hilft Studierenden in Maschinenbau, Elektrotechnik, Fahrzeugtechnik und Raumplanung, betrieblich unterstützte Masterarbeiten (Start 2026–2028) zu finden. Hochschulen aus NRW, Rheinland-Pfalz, Hessen, Saarland und Niedersachsen stehen zur Auswahl. Die App erstellt den Suchauftrag. Die Recherche läuft im kostenlosen Claude-Chat mit eingeschalteter Websuche.

## Inhalt

- index.html – die App
- manifest.webmanifest – Name, Farben, Symbole
- sw.js – Offline-Funktion
- icons/ – App-Symbole

## Veröffentlichen auf GitHub Pages

So wie beim Ausbildungsfinder:

1. Auf github.com oben rechts **+** → **New repository** klicken, Name z. B. `Masterarbeitsfinder`, **Public** auswählen, **Create repository** klicken.
2. Den Link **uploading an existing file** klicken. Den Inhalt dieses Ordners, einschließlich `icons`, hineinziehen und **Commit changes** klicken.
3. **Settings** öffnen (eventuell unter **More**), dann **Pages**. Bei **Branch** `main` und `/ (root)` wählen und **Save** klicken.
4. Nach 1–3 Minuten ist die App erreichbar unter `https://wimmi66-code.github.io/Masterarbeitsfinder/`.

## Installieren

- **iPhone:** Link in Safari öffnen → **Teilen** → **Zum Home-Bildschirm**.
- **Android:** Link in Chrome öffnen → **App installieren**.

## Aktualisieren

Geänderte Dateien erneut hochladen und in `sw.js` die Version hochzählen (`masterarbeitsfinder-v2` …).

## Hinweis zur Hochschulliste

Die Liste der Hochschulen und Studiengänge ist eine Auswahl (Stand Oktober 2026). Claude prüft zu Beginn jeder Suche, ob der Master an der gewählten Hochschule angeboten wird.
