HOTEL EGERKINGEN – INTERAKTIVE KARTE (Pilot)
=============================================

Dieser Ordner ist die produktisierte Adaption der interaktiven Karte
(urspruenglich "Garden Park Guest House / Grantown-on-Spey") fuer einen
neuen Standort: Hotel Egerkingen, Oltnerstrasse 22, 4622 Egerkingen (SO),
Schweiz.

WICHTIG: Komplett getrennt vom Originalmaterial (Garden Park). Keine
gemeinsamen Dateien.

INHALT
------
map.html
    Die interaktive Karte. Eine einzige, eigenstaendige Datei -
    kein Setup, keine Datenbank, keine Abhaengigkeiten. Einfach auf
    den Webserver hochladen.

    INTERNER AUFBAU (produktisiert):
    - CONFIG-Block ganz oben: Hotelname, Ankerkoordinate, Farben,
      Sprachen, Kartenzentrum. -> pro Kunde anpassen.
    - DATA-Block: die Orts-Listen (POIs). -> pro Region austauschen.
    - ENGINE: Karte, Filter, Wetter, Planer, Route. -> bleibt gleich.

    So wird der naechste Kunde zum reinen Datentausch, nicht Neubau.

FEATURES (wie im Original)
--------------------------
- Leaflet-Karte + OpenStreetMap/CARTO-Kacheln (kostenlos, kein Key)
- Kategorie-Filter + Filter nach max. Fahrzeit
- Popups mit PLZ, Telefon, Website
- Live-Wetter (open-meteo.com, kostenlos, kein Key) fuer Egerkingen
- "Mein Tag planen" (Tagesplaner, regenbewusst)
- Route in Google Maps oeffnen / teilen / drucken
- 4 Sprachen: DE / FR / EN / IT (Schweiz-Fokus)

STATUS
------
PILOT - Orts-Daten muessen vor Go-Live von jemandem mit Ortskenntnis
geprueft werden (Koordinaten, Telefonnummern, "existiert noch?").
Jeder POI hat intern ein Feld coordConfidence als Hinweis.
