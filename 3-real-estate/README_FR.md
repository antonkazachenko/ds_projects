# Analyse des annonces de ventes d’appartements

[English](README.md) | [Deutsch](README_DE.md) | Français | [Русский](README_RU.md)

### Description du projet

Le client peut être des agences immobilières, des banques ou des plateformes en ligne. Les données d’entrée proviennent de l’Archive des annonces immobilières de Yandex. Dans ce projet, j’analyse les facteurs (superficie, localisation, etc.) qui influencent les prix des biens immobiliers dans différentes régions de Saint-Pétersbourg.

### Description des données

- `children` - nombre d’enfants dans la famille
- `airports_nearest` - distance jusqu’au plus proche aéroport en mètres (m)
- `balcony` - nombre de balcons
- `ceiling_height` - hauteur sous plafond (m)
- `cityCenters_nearest` - distance jusqu’au centre-ville (m)
- `days_exposition` - nombre de jours pendant lesquels l’annonce est restée en ligne (de la publication au retrait)
- `first_day_exposition` - date de publication
- `floor` - étage
- `floors_total` - nombre total d’étages dans l’immeuble
- `is_apartment` - appartement (type booléen)
- `kitchen_area` - superficie de la cuisine en mètres carrés (m²)
- `last_price` - prix au moment du retrait de l’annonce
- `living_area` - superficie habitable en mètres carrés (m²)
- `locality_name` - nom de la localité
- `open_plan` - plan ouvert (type booléen)
- `parks_around3000` - nombre de parcs dans un rayon de 3 km
- `parks_nearest` - distance jusqu’au plus proche parc (m)
- `ponds_around3000` - nombre de plans d’eau dans un rayon de 3 km
- `ponds_nearest` - distance jusqu’au plus proche plan d’eau (m)
- `rooms` - nombre de pièces
- `studio` - studio (type booléen)
- `total_area` - superficie totale de l’appartement en mètres carrés (m²)
- `total_images` - nombre de photos de l’appartement dans l’annonce

### Objectif de l’étude

Cette étude vise à examiner le prix de l’immobilier à Saint-Pétersbourg et dans les localités voisines. Elle permettra la mise en place d’un système automatisé pour détecter les anomalies et les activités frauduleuses.

Deux types de données sont disponibles pour chaque appartement à vendre. Le premier est saisi par l’utilisateur, le second est obtenu automatiquement à partir des données de cartographie. Par exemple, la distance au centre-ville, à l’aéroport et à d’autres lieux est issue de services géospatiaux. Le nombre de parcs et de plans d’eau est également renseigné automatiquement, sans intervention de l’utilisateur.
