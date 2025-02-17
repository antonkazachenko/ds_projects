# Recherche sur la distribution cinématographique russe

[English](README.md) | [Deutsch](README_DE.md) | Français | [Русский](README_RU.md)

### Description du projet

Dans ce projet, j'essaierai d'étudier le marché de la distribution cinématographique russe et d'identifier les tendances actuelles. Je me concentrerai sur les films ayant bénéficié d'un soutien de l'État et j'essaierai de répondre à la question de savoir à quel point ces films intéressent le public.

Les données avec lesquelles je travaillerai sont publiées sur le portail de données ouvertes du Ministère de la Culture. L'ensemble de données contient des informations sur les certificats de distribution, les recettes au box-office et le soutien de l'État pour les films, ainsi que des données provenant du site KinoPoisk.

### Description des données

La table `mkrf_movies` contient des informations provenant du registre des certificats de distribution. Un film peut avoir plusieurs certificats de distribution.

- `title` — titre du film ;
- `puNumber` — numéro du certificat de distribution ;
- `show_start_date` — date de la première du film ;
- `type` — type de film ;
- `film_studio` — studio de production ;
- `production_country` — pays de production ;
- `director` — réalisateur ;
- `producer` — producteur ;
- `age_restriction` — classification par âge ;
- `refundable_support` — montant du soutien étatique remboursable ;
- `nonrefundable_support` — montant du soutien étatique non remboursable ;
- `financing_source` — source de financement de l'État ;
- `budget` — budget total du film ;
- `ratings` — note du film sur KinoPoisk ;
- `genres` — genre du film.

La table `mkrf_shows` contient des informations sur les projections des films dans les cinémas russes.

- `puNumber` — numéro du certificat de distribution ;
- `box_office` — recettes au box-office en roubles.

### Objectifs de la recherche

Identifier les tendances actuelles sur le marché de la distribution cinématographique russe, étudier les films ayant bénéficié d'un soutien de l'État et déterminer à quel point ils intéressent le public.
