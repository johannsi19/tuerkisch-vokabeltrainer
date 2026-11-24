# Türkisch-Vokabeltrainer

Ein kostenloser, quelloffener Türkisch-Deutsch-Vokabeltrainer als statische Website.

## Funktionen
- Vokabelliste aus der bereitgestellten Excel-Datei (1.477 nicht leere Datensätze; ein Eintrag ist in der Quelldatei unvollständig)
- Türkisch → Deutsch und Deutsch → Türkisch
- Zufällige Abfrage, Lernfilter (fällig/alle/schwierig/neu)
- Karteikasten mit 5 Lernstufen und Wiederholungsintervallen
- Eigene Vokabeln direkt auf der Website hinzufügen
- Lernstatistik mit Lernserie, Tages- und Wochenverlauf, Trefferquote, Lernstufen und schwierigsten Wörtern
- Lokale Speicherung des Lernstands und eigener Wörter im Browser (localStorage)
- Export und Import einer JSON-Sicherung
- Keine Anmeldung, keine externen Bibliotheken, kein Tracking

## Lokal starten
Mit Python: `python -m http.server 8000` und dann `http://localhost:8000` öffnen.

Alternativ auf einen statischen Webhost wie GitHub Pages laden.

## Vokabeldaten
Die ursprüngliche Vokabelliste liegt komprimiert unter `data/vokabeln.json.gz`. Eigene Vokabeln werden lokal im Browser gespeichert. Sie können zusammen mit dem Lernfortschritt über „Sicherung exportieren“ gesichert und auf einem anderen Gerät importiert werden.

## Open Source
Lizenz: MIT. Siehe `LICENSE`.

## Datenschutz
Die Vokabelliste wird als statische Datei geladen. Lernfortschritt und eigene Vokabeln werden nur lokal im Browser gespeichert und nicht an einen Server gesendet. Regelmäßig eine Sicherung exportieren.
