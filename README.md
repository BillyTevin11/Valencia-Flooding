
![Precipitation_rate_map_over_Spain_pillars](https://github.com/user-attachments/assets/5464fb89-a9b0-493a-b693-3a519e6ac01b)


# <ins>Mapping The Valencia Flooding in Late 2024</ins>
The Valencia Flooding project focuses on analyzing precipitation patterns and detecting flood events in the _Comunitat Valenciana_ region of Spain using Earth observation data and geospatial analysis tools. This project leverages the Google Earth Engine (GEE) platform to process satellite imagery and derive insights into rainfall trends and flood impacts during the year 2024.

The first phase of the project involves the setup and delineation of the study area by filtering the FAO's administrative boundaries dataset to isolate _Comunitat Valenciana_. Using the CHIRPS Daily Precipitation dataset, the project computes average daily precipitation for each month of 2024. These values are visualized through a bar chart with an overlaid trend line to identify patterns in rainfall variability, which is crucial for anticipating flood risk and water resource management.

The second phase focuses on flood detection using radar imagery from the Sentinel-1 satellite. By comparing median VH-band backscatter values from two time periods — before (October 1–8, 2024) and after (October 21–November 1, 2024) — the project identifies areas with significant changes that may indicate surface water or inundation. A differential image is generated to visualize these changes and enhance flood detection.

Additionally, optical imagery from Sentinel-2 is utilized to provide a visual assessment of the landscape before and after the suspected flood event. Cloud masking is applied to ensure data quality, and false-color composites are created to highlight vegetation, water, and urban areas, aiding in understanding flood extent and its impact on land cover.

Overall, the project combines precipitation analysis with radar and optical satellite imagery to build a comprehensive picture of flooding events in Valencia. It serves as a valuable tool for environmental monitoring, emergency response, and policy-making in the face of climate variability and extreme weather events.






