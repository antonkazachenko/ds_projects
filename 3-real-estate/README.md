# Apartment Sale Listings Analysis

English | [Deutsch](README_DE.md) | [Français](README_FR.md) | [Русский](README_RU.md)

### Project Description

The client could be Real Estate Agencies, Banks or Online Platforms. The input data is the Archive of Yandex Real Estate listings.
In this project I am analyzing factors (area, location, etc.) that affect property prices in various regions of St. Petersburg

### Data Description
- `children` - number of children in the family
- `airports_nearest` - distance to the nearest airport in meters (m)
- `balcony` - number of balconies
- `ceiling_height` - height of ceilings (m)
- `cityCenters_nearest` - distance to the city center (m)
- `days_exposition` - how many days the ad has been posted (from posting to removal)
- `first_day_exposition` - date of publication
- `floor` - floor
- `floors_total` - total number of floors in the house
- `is_apartment` - apartment (Boolean type)
- `kitchen_area` - kitchen area in square meters (m²)
- `last_price` - price at the moment of withdrawal from publication
- `living_area` - living area in square meters (m²)
- `locality_name` - name of the locality
- `open_plan` - free layout (Boolean type)
- `parks_around3000` - number of parks within 3 km radius
- `parks_nearest` - distance to the nearest park (m)
- `ponds_around3000` - number of water bodies within 3 km radius
- `ponds_nearest` - distance to the nearest body of water (m)
- `rooms` - number of rooms
- `studio` - studio apartment (Boolean type)
- `total_area` - total area of the apartment in square meters (m²)
- `total_images` - number of photos of the apartment in the ad

### Purpose of the Study
This study aims to investigate the pricing of real estate in St. Petersburg and neighboring communities, this will allow
the construction of an automated system that can track anomalies and fraudulent activity.

Two types of data are available for each apartment for sale. The first is entered by the user, the second is obtained 
automatically on the basis of map data. For example, the distance to the center, airport and other objects - this data 
is automatically obtained from geoservices. The number of parks and water bodies is also filled in without user input.

