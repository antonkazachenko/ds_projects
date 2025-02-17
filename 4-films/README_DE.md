# Untersuchung des russischen Filmvertriebs

[English](README.md) | Deutsch | [Français](README_FR.md) | [Русский](README_RU.md)

### Projektbeschreibung

In diesem Projekt werde ich versuchen, den russischen Filmvertriebsmarkt zu untersuchen und aktuelle Trends zu identifizieren. Ich werde mich auf Filme konzentrieren, die staatliche Unterstützung erhalten haben, und versuchen, die Frage zu beantworten, wie interessant diese Filme für das Publikum sind.

Die Daten, mit denen ich arbeiten werde, sind auf dem Open-Data-Portal des Kulturministeriums veröffentlicht. Der Datensatz enthält Informationen zu Filmvertriebsbescheinigungen, Einspielergebnissen und staatlicher Unterstützung für Filme sowie Daten von der KinoPoisk-Website.

### Datenbeschreibung

Die Tabelle `mkrf_movies` enthält Informationen aus dem Register der Filmvertriebsbescheinigungen. Ein Film kann mehrere Vertriebsbescheinigungen haben.

- `title` — Filmtitel;
- `puNumber` — Nummer der Vertriebsbescheinigung;
- `show_start_date` — Filmpremiere;
- `type` — Filmtyp;
- `film_studio` — Produktionsstudio;
- `production_country` — Produktionsland;
- `director` — Regisseur;
- `producer` — Produzent;
- `age_restriction` — Altersfreigabe;
- `refundable_support` — Höhe der rückzahlbaren staatlichen Unterstützung;
- `nonrefundable_support` — Höhe der nicht rückzahlbaren staatlichen Unterstützung;
- `financing_source` — Quelle der staatlichen Finanzierung;
- `budget` — Gesamtbudget des Films;
- `ratings` — Filmbewertung auf KinoPoisk;
- `genres` — Filmgenre.

Die Tabelle `mkrf_shows` enthält Informationen zu den Vorführungen von Filmen in russischen Kinos.

- `puNumber` — Nummer der Vertriebsbescheinigung;
- `box_office` — Einspielergebnis in Rubel.

### Forschungsziele

Aktuelle Trends auf dem russischen Filmvertriebsmarkt identifizieren, Filme untersuchen, die staatliche Unterstützung erhalten haben, und feststellen, wie interessant sie für das Publikum sind.
