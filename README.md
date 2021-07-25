# Light_PH

Annual Philippine Provinces Light Dataset

This dataset contains median, mean, maximum, and minimum values of the VIIRS dataset available
from Google Earth for sample Philippine provinces for 2015 to 2020:

https://developers.google.com/earth-engine/datasets/catalog/NOAA_VIIRS_DNB_MONTHLY_V1_VCMCFG

The mining occurred roughly in June 2021 using javascript code on Earth Engine.
The median of 'avg_rad' variable was first selected for each province. Descriptive statistics were
further compiled based on these median values.
Scale value was started at 10; however, in getting descriptive statistics, the 'bestEffort' variable
was set to true. As such, scales may have been adjusted as necessary to allow for efficient computing.

The author wishes to upload a sample of the code used, but hopes he does not forget. :)

The shapefiles used were by GADM (version 3.6):

https://gadm.org/download_country_v3.html

Unfortunately, for a few provinces, there was difficulty in getting the correct shapefile applied; as such,
a few provinces are not represented here. :(

Original use was limited to non-commercial, research purposes. As such, users are solely responsible for ensuring
that their use complies with the policies of the owners of the raw data and shapefiles used,
even though the output here is already derivative work.

This dataset is being provided to the global community in case some variables may aid in research for
the Philippines, or development in general. Users are soley responsible for any consequences resulting
from the use of this data.

Jose Eduardo P. Sto. Domingo
July 25, 2021
