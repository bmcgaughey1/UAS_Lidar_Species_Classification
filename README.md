# UAS_Lidar_Species_Classification
Data to support UAS lidar species classification to distinguish Douglas-fir and western hemlock in the Pacific Northwest, UAS.

These data support the following article:
McGaughey, R.J.; Kruper, A.; Bobsin, C.R.; Bormann, B.T. Tree Species Classification Based on Upper Crown Morphology Captured by
Uncrewed Aircraft System Lidar Data. Remote Sens. 2024, 16, 6, 603. [IDN](https://doi.org/10.3390/rs16040603)

## Data Organization
Data are organized into three folders: GroundModels, PointClouds, and ModelingData. The GroundModels folder contains ground surfaces
derived from the point cloud data stored in FUSION's .dtm format and GeoTiff format. The .dtm files can be read using the [fusionwrapr R package](https://github.com/bmcgaughey1/fusionwrapr). The
PointClouds folder contains point cloud data for the 27 plots used in the anlayses stored in LAZ format. The Modeling data includes 
an Excel spreadsheet containing the data used to train and validate the random forest classification model presented in the paper.
