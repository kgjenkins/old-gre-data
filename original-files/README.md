# original-files

## Gardens in the Roman Empire

Initially, we had two lists of gardens in the Roman Empire, one for Italy and one for the rest of the Roman Empire.  These lists are archived here as PDFs.

In 2016, these names were geocoded using data from Pleiades, assigning the Pleiades location coordinates in cases where the placename could be reasonably matched.  After loading this data into [a Carto dataset](https://cornell.carto.com/u/cornell-admin/dataset/roman_gardens), students used basemaps and aerial imagery to evaluate the accuracy of these matched locations, indicating in the "verified" column the accuracy of the match with values like "verified", "wrong", "approximate", "locality" (meaning the point matched the placename associated with the garden, but not the garden itself), etc.  In many cases, the actual garden site could be determined using aerial imagery, in which case the point location was moved to the garden site and marked as "exact".

This data has been exported from Carto, further cleaned up, and provided here:
* roman_gardens.gpkg


## Gardens in the City of Rome

In 2018, students manually digitized garden locations in the city of Rome using Carto.  Depending on the garden, these were digitized in Carto as [points](https://cornell.carto.com/u/cornell-admin/dataset/la5450_points) and [polygons](https://cornell.carto.com/u/cornell-admin/dataset/la5450_polygons).

This data has been exported from Carto, and provided here:
* rome_city_points.gpkg
* rome_city_polygons.gpkg


## Gardens in Pompeii

In 2019, students manually digitized locations in Pompeii using QGIS.  These files have been merged together and provided here:
* pompeii_points.gpkg


