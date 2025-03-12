##### § 1.958 Distance computation. #####

The method given in this section must be used to compute the distance between any two locations, except that, for computation of distance involving stations in Canada and Mexico, methods for distance computation specified in the applicable international agreement, if any, must be used instead. The result of a distance calculation under parts 21 and 101 of this chapter must be rounded to the nearest tenth of a kilometer. The method set forth in this paragraph is considered to be sufficiently accurate for distances not exceeding 475 km (295 miles).

(a) Convert the latitudes and longitudes of each reference point from degree-minute-second format to degree-decimal format by dividing minutes by 60 and seconds by 3600, then adding the results to degrees.

![](/graphics/er13ap05.008.gif)

(b) Calculate the mean geodetic latitude between the two reference points by averaging the two latitudes:

![](/graphics/er13ap05.009.gif)

(c) Calculate the number of kilometers per degree latitude difference for the mean geodetic latitude calculated in paragraph (b) of this section as follows:

KPDlat = 111.13209 − 0.56605 cos 2ML + 0.00120 cos 4ML

(d) Calculate the number of kilometers per degree of longitude difference for the mean geodetic latitude calculated in paragraph (b) of this section as follows:

KPDlon = 111.41513 cos ML − 0.09455 cos 3ML + 0.00012 cos 5ML

(e) Calculate the North-South distance in kilometers as follows:

NS = KPDlat × (LAT1dd − LAT2dd)

(f) Calculate the East-West distance in kilometers as follows:

EW = KPDlon × (LON1dd − LON2dd)

(g) Calculate the distance between the locations by taking the square root of the sum of the squares of the East-West and North-South distances:

![](/graphics/er13ap05.010.gif)

(h) Terms used in this section are defined as follows:

(1) LAT1dd and LON1dd are the coordinates of the first location in degree-decimal format.

(2) LAT2dd and LON2dd are the coordinates of the second location in degree-decimal format.

(3) ML is the mean geodetic latitude in degree-decimal format.

(4) KPDlat is the number of kilometers per degree of latitude at a given mean geodetic latitude.

(5) KPDlon is the number of kilometers per degree of longitude at a given mean geodetic latitude.

(6) NS is the North-South distance in kilometers.

(7) EW is the East-West distance in kilometers.

(8) DIST is the distance between the two locations, in kilometers.

[70 FR 19306, Apr. 13, 2005, as amended at 79 FR 72150, Dec. 5, 2014]