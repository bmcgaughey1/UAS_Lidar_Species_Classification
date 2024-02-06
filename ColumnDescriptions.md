| Column   name                    | Description                                                                                        |
|----------------------------------|----------------------------------------------------------------------------------------------------|
| Plot_Number                      | Plot number (numeric version of PlotID)                                                            |
| Tag_Num                          | Tree number                                                                                        |
| Tree.ID                          | Tree identifier constructed from Plot_Number, Tag_Num, and Species                                 |
|                                  |                                                                                                    |
|                                  | Adjusted locations for person 1                                                                    |
| X.Person1                        | Base location X                                                                                    |
| Y.Person1                        | Base location Y                                                                                    |
| Elevation.Person1                | Base elevation                                                                                     |
| Total.Height.Person1             | Total tree height                                                                                  |
| Height.To.Crown.Base.Person1     | Height to base of crown                                                                            |
| Max.Crown.Diameter.Person1       | Crown diameter (all crowns were measured as circles so Max and Min are   the same)                 |
| Min.Crown.Diameter.Person1       | Crown diameter                                                                                     |
| Crown.Rotation.Person1           | Crown rotation (all are 0.0)                                                                       |
| R.Person1                        | Crown color                                                                                        |
| G.Person1                        | Crown color                                                                                        |
| B.Person1                        | Crown color                                                                                        |
| DBH.Person1                      | Tree DBH (cm) (copied from actual measured DBH)                                                    |
| Lean.Angle.From.Vertical.Person1 | Lean angle (degrees)                                                                               |
| Lean.Azimuth.Person1             | Lean azimuth (degrees)                                                                             |
| Status.Code.Person1              | Status code (same for both people)                                                                 |
| TopX.Person1                     | Top location X (computed using base location, tree lean, and lean   azimuth)                       |
| TopY.Person1                     | Top location Y (computed using base location, tree lean, and lean   azimuth)                       |
|                                  |                                                                                                    |
|                                  | Adjusted locations for person 2                                                                    |
| X.Person2                        | Base location X                                                                                    |
| Y.Person2                        | Base location Y                                                                                    |
| Elevation.Person2                | Base elevation                                                                                     |
| Total.Height.Person2             | Total tree height                                                                                  |
| Height.To.Crown.Base.Person2     | Height to base of crown                                                                            |
| Max.Crown.Diameter.Person2       | Crown diameter (all crowns were measured as circles so Max and Min are   the same)                 |
| Min.Crown.Diameter.Person2       | Crown diameter                                                                                     |
| Crown.Rotation.Person2           | Crown rotation (all are 0.0)                                                                       |
| R.Person2                        | Crown color                                                                                        |
| G.Person2                        | Crown color                                                                                        |
| B.Person2                        | Crown color                                                                                        |
| DBH.Person2                      | Tree DBH (cm) (copied from actual measured DBH)                                                    |
| Lean.Angle.From.Vertical.Person2 | Lean angle (degrees)                                                                               |
| Lean.Azimuth.Person2             | Lean azimuth (degrees)                                                                             |
| Status.Code.Person2              | Status code (same for both people)                                                                 |
| TopX.Person2                     | Top location X (computed using base location, tree lean, and lean   azimuth)                       |
| TopY.Person2                     | Top location Y (computed using base location, tree lean, and lean   azimuth)                       |
|                                  |                                                                                                    |
|                                  | Differences between adjusted locations for two people                                              |
| diffX                            | Base X difference between adjustments for two people                                               |
| diffY                            | Base Y difference between adjustments for two people                                               |
| diffTopX                         | Top X difference between adjustments for two people                                                |
| diffTopY                         | Top Y difference between adjustments for two people                                                |
| diff                             | Base horizontal difference between adjustments for two people                                      |
| diffTop                          | Top horizontal difference between adjustments for two people                                       |
|                                  |                                                                                                    |
|                                  | Field measurements                                                                                 |
| PlotID                           | Plot identifier (number)                                                                           |
| Study                            | Study identifier (T3 for all trees)                                                                |
| Year                             | Measurement year (2021 for all trees)                                                              |
| Plot_Name                        | Plot name (contains information describing treatment)                                              |
| Species                          | Species code (PSME=Douglas-fir, TSHE=western hemlock)                                              |
| DBH_cm                           | DBH (cm)                                                                                           |
| LiDAR_visible                    | Flag indicating tree is visible from above (all trees are "Y")                                     |
| Distance                         | Distance from plot reference point (m)                                                             |
| Azimuth                          | Azimuth from plot reference point to tree (degrees)                                                |
| Anomaly_Num                      | Anomaly code from field data sheet (all 0)                                                         |
| Anomaly1                         | First anomaly code (extracted from Anomaly_Num, all "NA")                                          |
| Anomaly2                         | Second anomaly code (extracted from Anomaly_Num, all "NA")                                         |
| Anomaly3                         | Third anomaly code (extracted from Anomaly_Num, all "NA")                                          |
| Bear_damage_percent              | Bear damage code (all NA)                                                                          |
| Note                             | Field notes                                                                                        |
|                                  |                                                                                                    |
|                                  | Tree location                                                                                      |
| Xfield                           | Original field X based on GPS position for plot reference point and   azimuth and distance to tree |
| Yfield                           | Original field Y based on GPS position for plot reference point and   azimuth and distance to tree |
| hanusHt                          | Predicted height using Hanus, et al. equations                                                     |
| fvsHt                            | Predicted height using FVS-PN variant equations                                                    |
| origdiffX.Person1                | Base X difference between person 1 adjusted location and field location                            |
| origdiffY.Person1                | Base Y difference between person 1 adjusted location and field location                            |
| origdiff.Person1                 | Base horizontal difference between person 1 adjusted location and field   location                 |
| origdiffX.Person2                | Base X difference between person 2 adjusted location and field location                            |
| origdiffY.Person2                | Base Y difference between person 2 adjusted location and field location                            |
| origdiff.Person2                 | Base horizontal difference between person 2 adjusted location and field   location                 |
| heightdiff                       | Height difference between person 1 and person 2                                                    |
|                                  |                                                                                                    |
|                                  | Differences between adjusted and original tree locations                                           |
| aveBaseX                         | Average base X for persons 1 and 2                                                                 |
| aveBaseY                         | Average base Y for persons 1 and 2                                                                 |
| aveBaseElevation                 | Average base elevation for persons 1 and 2                                                         |
| aveHeight                        | Average height Height for persons 1 and 2                                                          |
| aveTopX                          | Average top X for persons 1 and 2                                                                  |
| aveTopY                          | Average top Y for persons 1 and 2                                                                  |
| topElevation                     | Average top elevation for persons 1 and 2                                                          |
| aveCrownDia                      | Average crown dia for persons 1 and 2                                                              |
|                                  |                                                                                                    |
|                                  | Point-cloud metrics                                                                                |
| DataFile                         | Point data file for upper 3 m of 1 m radius cylinder of points                                     |
| FileTitle                        | File title extracted from DataFile                                                                 |
| Total.return.count               | Total number of returns                                                                            |
| Return.1.count                   | Number of return 1 points                                                                          |
| Return.2.count                   | Number of return 2 points                                                                          |
| Return.3.count                   | Number of return 3 points                                                                          |
| Return.4.count                   | Number of return 4 points                                                                          |
| Return.5.count                   | Number of return 5 points                                                                          |
| Return.6.count                   | Number of return 6 points                                                                          |
| Return.7.count                   | Number of return 7 points                                                                          |
| Return.8.count                   | Number of return 8 points                                                                          |
| Return.9.count                   | Number of return 9 points                                                                          |
| Other.return.count               | Number of other return points                                                                      |
| Elev.minimum                     | Minimum point height (should be very close to 0.0)                                                 |
| Elev.maximum                     | Maximum point height (should be close to 3m)                                                       |
| Elev.mean                        | Average point height                                                                               |
| Elev.mode                        | Mode of point height values                                                                        |
| Elev.stddev                      | Standard deviation of point heights                                                                |
| Elev.variance                    | Variance of point heights                                                                          |
| Elev.CV                          | Coefficient of variation of point heights                                                          |
| Elev.IQ                          | Interquartile distance of point heights                                                            |
| Elev.skewness                    | Skewness of point heights                                                                          |
| Elev.kurtosis                    | Kurtosis of point heights                                                                          |
| Elev.AAD                         | Average absolute difference from mean                                                              |
| Elev.MAD.median                  | Median absolute difference from median                                                             |
| Elev.MAD.mode                    | Median absolute difference from mode                                                               |
| Elev.L1                          | First L moment of point height                                                                     |
| Elev.L2                          | Second L moment of point height                                                                    |
| Elev.L3                          | Third L moment of point height                                                                     |
| Elev.L4                          | Fourth L moment of point height                                                                    |
| Elev.L.CV                        | L-moment coefficient of variation (L2 / L1)                                                        |
| Elev.L.skewness                  | L-moment skewness (L3 / L1)                                                                        |
| Elev.L.kurtosis                  | L-moment kurtosis (L4 / L1)                                                                        |
| Elev.P01                         | Percentile height (1%)                                                                             |
| Elev.P05                         | Percentile height (5%)                                                                             |
| Elev.P10                         | Percentile height (10%)                                                                            |
| Elev.P20                         | Percentile height (20%)                                                                            |
| Elev.P25                         | Percentile height (25%)                                                                            |
| Elev.P30                         | Percentile height (30%)                                                                            |
| Elev.P40                         | Percentile height (40%)                                                                            |
| Elev.P50                         | Percentile height (50% also median value)                                                          |
| Elev.P60                         | Percentile height (60%)                                                                            |
| Elev.P70                         | Percentile height (70%)                                                                            |
| Elev.P75                         | Percentile height (75%)                                                                            |
| Elev.P80                         | Percentile height (80%)                                                                            |
| Elev.P90                         | Percentile height (90%)                                                                            |
| Elev.P95                         | Percentile height (95%)                                                                            |
| Elev.P99                         | Percentile height (99%)                                                                            |
| Canopy.relief.ratio              | (Elev.mean - Elev.minimum) / (Elev.maximum - Elev.minimum)                                         |
| Elev.SQRT.mean.SQ                | Square root of the average squared height                                                          |
| Elev.CURT.mean.CUBE              | Cube root of the average cubed height                                                              |
| Int.minimum                      | Minimum point intensity                                                                            |
| Int.maximum                      | Maximum point intensity                                                                            |
| Int.mean                         | Average point intensity                                                                            |
| Int.mode                         | Mode of point intensity values                                                                     |
| Int.stddev                       | Standard deviation of intensity heights                                                            |
| Int.variance                     | Variance of point intensity                                                                        |
| Int.CV                           | Coefficient of variation of point intensity                                                        |
| Int.IQ                           | Interquartile distance of point intensity                                                          |
| Int.skewness                     | Skewness of point intensity                                                                        |
| Int.kurtosis                     | Kurtosis of point intensity                                                                        |
| Int.AAD                          | Average absolute difference from mean intensity                                                    |
| Int.L1                           | First L moment of point intensity                                                                  |
| Int.L2                           | Second L moment of point intensity                                                                 |
| Int.L3                           | Third L moment of point intensity                                                                  |
| Int.L4                           | Fourth L moment of point intensity                                                                 |
| Int.L.CV                         | L-moment coefficient of variation (L2 / L1)                                                        |
| Int.L.skewness                   | L-moment skewness (L3 / L1)                                                                        |
| Int.L.kurtosis                   | L-moment kurtosis (L4 / L1)                                                                        |
| Int.P01                          | Percentile of intensity (1%)                                                                       |
| Int.P05                          | Percentile of intensity (5%)                                                                       |
| Int.P10                          | Percentile of intensity (10%)                                                                      |
| Int.P20                          | Percentile of intensity (20%)                                                                      |
| Int.P25                          | Percentile of intensity (25%)                                                                      |
| Int.P30                          | Percentile of intensity (30%)                                                                      |
| Int.P40                          | Percentile of intensity (40%)                                                                      |
| Int.P50                          | Percentile of intensity (50% also median value)                                                    |
| Int.P60                          | Percentile of intensity (60%)                                                                      |
| Int.P70                          | Percentile of intensity (70%)                                                                      |
| Int.P75                          | Percentile of intensity (75%)                                                                      |
| Int.P80                          | Percentile of intensity (80%)                                                                      |
| Int.P90                          | Percentile of intensity (90%)                                                                      |
| Int.P95                          | Percentile of intensity (95%)                                                                      |
| Int.P99                          | Percentile of intensity (99%)                                                                      |
| Profile.area                     | See FUSION manual for definition and reference (not used for this   analysis)                      |
