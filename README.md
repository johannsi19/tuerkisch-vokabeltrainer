# Türkisch-Vokabeltrainer

Ein kostenloser, quelloffener Türkisch-Deutsch-Vokabeltrainer als statische Website.

## Inhalt
- 1476 Vokabelpaare aus der bereitgestellten Excel-Liste
- Türkisch → Deutsch und Deutsch → Türkisch
- Zufällige Abfrage, Lernfilter (fällig/alle/schwierig/neu)
- Karteikasten mit 5 Lernstufen und Wiederholungsintervallen
- lokale Speicherung des Lernstands im Browser (localStorage)
- Suche, Statistik sowie Export/Import des Lernstands als JSON
- keine Anmeldung, keine externen Bibliotheken, kein Tracking

## Lokal starten
Mit Python: `python -m http.server 8000` und dann `http://localhost:8000` öffnen.

Alternativ auf einen statischen Webhost wie GitHub Pages laden.

## Daten ändern
Die Vokabeln liegen in `data/vokabeln.json` als Liste von Objekten mit `tr` und `de`.

## Open Source
Lizenz: MIT. Siehe `LICENSE`.

## Datenschutz
Die Vokabelliste wird als statische Datei geladen. Der Lernfortschritt wird nur lokal im Browser gespeichert und nicht an einen Server gesendet. Regelmäßig über „Fortschritt sichern“ exportieren.