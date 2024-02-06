# UAS_Lidar_Species_Classification
Data to support UAS lidar species classification to distinguish Douglas-fir and western hemlock in the Pacific Northwest, UAS.

These data support the following article:
McGaughey, R.J.; Kruper, A.; Bobsin, C.R.; Bormann, B.T. Tree Species Classification Based on Upper Crown Morphology Captured by
Uncrewed Aircraft System Lidar Data. Remote Sens. 2024, 16, 6, 603. [IDN](https://doi.org/10.3390/rs16040603)

## Data Organization
Data are organized into three folders as shown in the table below:

| Folder       | Content                                                                                                              |
|--------------|----------------------------------------------------------------------------------------------------------------------|
| GroundModels | Ground surfaces derived from the lidar point cloud. Stored in FUSION's .dtm and GeoTiff formats.                     |
| PointClouds  | Point cloud data for the 27 plots used in the analyses. Stored in LAZ format.                                        |
| ModelingData | Excel spreadsheet and CSV file containing field measurements and lidar metrics used to train a classification model. |

The .dtm files can be read using the [fusionwrapr R package](https://github.com/bmcgaughey1/fusionwrapr).

Columns/fields in the modeling data are described in [ColumnDescriptions](ColumnDescriptions.md).

[FUSION software](https://forsys.sefs.uw.edu/fusion/fusionlatest.html)
