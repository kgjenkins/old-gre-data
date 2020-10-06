# old-gre-data

This repo contains datasets related to the locations of Gardens of the Roman Empire.

The **roman_gardens_cleaned .csv and .gpkg files** are a cleaned-up version of the GRE data from Carto, with extraneous fields removed, and Pleiades IDs added where possible.  Note that after the initial list of garden location names were geocoded to Pleiades points, the point locations may have been moved in many cases to match satellite imagery.  When students reviewed the points, they used the "verified" field to indicate the accuracy of the location (verified, rough, approximate, wrong, etc.)  In some cases, the original Pleidades match may not have been correct, so each Pleaides place ID should be checked before linking to a particular garden.  Note that there are ~174 records that have no coordinates (0,0) that will need more work to determine the actual location.

This data comes from some the following sources:

* Point data for locations that could be matched to Pleiades locations, later verified by students (2016):  
https://cornell.carto.com/u/cornell-admin/builder/51b15d5a-e55f-11e5-8084-0e674067d321/embed  

* Point and polygen data for locations in Rome, digitized by students (2018):  
https://cornell.carto.com/u/cornell-admin/builder/ef5c9643-0875-4882-9cbf-458aa906159a/embed  
TODO: need to merge into larger dataset above

* Pompeii locations digitized in QGIS (2019)  
TODO: need to collate data and merge into larger dataset above

