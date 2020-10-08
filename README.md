# old-gre-data

This repo contains datasets related to the locations of Gardens of the Roman Empire.

The **roman_gardens_cleaned .csv and .gpkg files** are a cleaned-up version of the GRE data from Carto, with extraneous fields removed, and Pleiades IDs added where possible.  Note that after the initial list of garden location names were geocoded to Pleiades points, the point locations may have been moved in many cases to match satellite imagery.  When students reviewed the points, they used the "verified" field to indicate the accuracy of the location (verified, rough, approximate, wrong, etc.)  In some cases, the original Pleidades match may not have been correct, so each Pleaides place ID should be checked before linking to a particular garden.  Note that there are 173 records that have no coordinates (0,0) that will need more work to determine the actual location.


Additional data for the cities of Rome and Pompeii can be found under the `original-files`, and will eventually be merged into the larger datasets of gardens.

