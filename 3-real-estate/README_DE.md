# Analyse von Wohnungsverkaufsangeboten

[English](README.md) | Deutsch | [Français](README_FR.md) | [Русский](README_RU.md)

### Projektbeschreibung

Der Kunde könnte ein Immobilienmakler, eine Bank oder eine Online-Plattform sein. Die Eingabedaten sind das Archiv von Yandex-Immobilienangeboten.
In diesem Projekt analysiere ich Faktoren (Gebiet, Lage, etc.), die die Immobilienpreise in verschiedenen Regionen von St. Petersburg beeinflussen.

### Daten Beschreibung
- `children` - Anzahl der Kinder in der Familie
- `airports_nearest` - Entfernung zum nächstgelegenen Flughafen in Metern (m)
- `balcony` - Anzahl der Balkone
- `ceiling_height` - Höhe der Decken (m)
- `cityCenters_nearest` - Entfernung zum Stadtzentrum (m)
- `days_exposition` - wie viele Tage die Anzeige veröffentlicht wurde (von der Veröffentlichung bis zur Entfernung)
- `first_day_exposition` - Datum der Veröffentlichung
- `floor` - Fußboden
- `floors_total` - Gesamtzahl der Stockwerke im Haus
- `is_apartment` - apartment (boolescher Typ)
- `kitchen_area` - Küchenfläche in Quadratmetern (m²)
- `last_price` - Preis zum Zeitpunkt der Rücknahme von der Veröffentlichung
- `living_area` - Wohnfläche in Quadratmetern (m²)
- `locality_name` - Name der Ortschaft
- `open_plan` - freies Layout (boolescher Typ)
- `parks_around3000` - Anzahl der Parks im Umkreis von 3 km
- `parks_nearest` - Entfernung zum nächstgelegenen Park (m)
- `ponds_around3000` - Anzahl der Wasserkörper im Umkreis von 3 km
- `ponds_nearest` - Entfernung zum nächstgelegenen Gewässer (m)
- `rooms` - Anzahl der Zimmer
- `studio` - studio apartment (Boolescher Typ)
- `total_area` - Gesamtfläche der Wohnung in Quadratmetern (m²)
- `total_images` - Anzahl der Fotos der Wohnung in der Anzeige

### Zweck der Studie
Diese Studie zielt darauf ab, die Preisgestaltung von Immobilien in St. Petersburg und den umliegenden Gemeinden zu untersuchen, um so
den Aufbau eines automatisierten Systems, das Anomalien und betrügerische Aktivitäten aufspüren kann.

Für jede zum Verkauf stehende Wohnung sind zwei Arten von Daten verfügbar. Die erste wird vom Benutzer eingegeben, die zweite wird 
automatisch auf der Grundlage von Kartendaten ermittelt. Zum Beispiel die Entfernung zum Zentrum, zum Flughafen und zu anderen Objekten - diese Daten 
werden automatisch von Geodiensten bezogen. Auch die Anzahl der Parks und Gewässer wird ohne Benutzereingabe eingetragen.


