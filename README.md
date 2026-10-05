# Gebietzeiten

Eine kleine Web-App, die die täglichen Gebetszeiten für ausgewählte Städte in Saudi-Arabien anzeigt. Die Zeiten und das Datum werden über die [AlAdhan API](https://aladhan.com/prayer-times-api) geladen.

## Städte

Makkah al Mukarramah, Riyadh, Jeddah, Dammam, Medina, Khobar, Tabuk, Hail, Abha und Najran.

## Starten

Das Projekt besteht aus statischen HTML-, CSS- und JavaScript-Dateien. Öffne `index.html` in einem Browser oder starte im Projektordner einen lokalen Webserver, zum Beispiel:

```bash
npx serve .
```

Die Anwendung benötigt eine Internetverbindung, um die Gebetszeiten von der API abzurufen. Axios wird aktuell aus `node_modules` geladen; installiere die Abhängigkeiten bei Bedarf mit `npm install`.

## Projektdateien

- `index.html` – Oberfläche, Stadtauswahl und Abruf der Gebetszeiten
- `index.css` – Gestaltung
- `awiat.html` – separate Seite mit Beispielen für asynchrone Datenabfragen
- `package.json` – Projektmetadaten und Abhängigkeiten

## Hinweis

`npm test` ist derzeit nur ein Platzhalter und führt keine Tests aus.
