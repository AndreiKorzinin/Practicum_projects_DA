## apartment market examination

Based on Yandex service data of various types of real estate objects, typical parameters of apartments, depending on 
the distance from the center, is determined. Data preprocessing was carried out. New data has been added.
Histograms, boxplots, and scatter diagrams are constructed.

## Data:
- `airports_nearest` — distance to the nearest airport in meters (m);
- `balcony` — number of balconies;
- `ceiling_height` — ceiling height (m);
- `cityCenters_nearest` — distance to the city center (m);
- `days_exposition` — how many days the ad was placed (from publication to removal);
- `first_day_exposition` — date of publication;
- `floor` — floor;
- `floors_total` — total floors in the house;
- `is_apartment` — apartments (boolean type);
- `kitchen_area` — kitchen area in square meters (m2);
- `last_price` — price at the time of withdrawal from publication;
- `living_area` — living area in square meters (m2);
- `locality_name` — name of the locality;
- `open_plan` — free layout (boolean type);
- `parks_around3000` — number of parks within a 3 km radius;
- `parks_nearest` — distance to the nearest park (m);
- `ponds_around3000` — number of reservoirs within a radius of 3 km;
- `ponds_nearest` — distance to the nearest reservoir (m);
- `rooms` — number of rooms;
- `studio` — studio apartment (boolean type);
- `total_area` — the area of the apartment in square meters (m2);
- `total_images` — the number of photos of the apartment in the ad.

## Results

In the course of the work done to identify the dependencies of apartment prices in the region of St. Petersburg and its environs, the following dependencies were worked out that affect pricing. Namely, the influence of the area of the apartment, number of rooms, floor, distance from the center on the price of the apartment. The constructed graphs indicate that with the increase in the area of the apartment, the price also increases. According to the obtained correlation coefficient, we can say that there is a connection between these characteristics. The first floor is in less demand among buyers. Apartments in the center are correspondingly expensive, but after 3km the price starts to rise, perhaps this is due to the presence of shops and convenient transport interchanges. There are also apartments with a total area of around 60m2 most in the center. And a significant number of apartments is in the range of a total area from 40m2 to 100m2.

We have 7 peaks in the range from 0 to 100 of the range of the period of sale of apartments:

- The first peak is 0 days. Most likely, this is a data bug, it cannot be that apartments would be sold so quickly in such a quantity. When determining fast and slow sales, we will not take into account this peak

- The fifth peak is 60 days. The second most important, about which we can say if the apartment was not sold before this period, is a long sale.
- The sixth peak is 74 days. The smallest peak of all described.
- The seventh peak is 90 days. Comparable in terms of sales with the second and third peaks.

All the voiced characteristics and dependencies are presented in the form of graphs in this project work.

## Stage

Project is fully completed
