# Research on Russian Film Distribution

English | [Deutsch](README_DE.md) | [Français](README_FR.md) | [Русский](README_RU.md)

### Project Description

In this project, I will try to study the Russian film distribution market and identify current trends. I will focus on films that have received state support and attempt to answer the question of how interesting these films are to the audience.

The data I will work with is published on the open data portal of the Ministry of Culture. The dataset contains information on film distribution certificates, box office revenues, and state support for films, as well as data from the KinoPoisk website.

### Data Description

The `mkrf_movies` table contains information from the registry of film distribution certificates. One film may have several distribution certificates.

- `title` — film title;
- `puNumber` — distribution certificate number;
- `show_start_date` — film premiere date;
- `type` — type of film;
- `film_studio` — producing studio;
- `production_country` — country of production;
- `director` — director;
- `producer` — producer;
- `age_restriction` — age rating;
- `refundable_support` — amount of refundable state support funds;
- `nonrefundable_support` — amount of non-refundable state support funds;
- `financing_source` — source of state financing;
- `budget` — total film budget;
- `ratings` — film rating on KinoPoisk;
- `genres` — film genre.

The `mkrf_shows` table contains information on film screenings in Russian cinemas.

- `puNumber` — distribution certificate number;
- `box_office` — box office revenue in rubles.

### Research Goals

Identify current trends in the Russian film distribution market, study films that have received state support, and determine how interesting they are to the audience.
