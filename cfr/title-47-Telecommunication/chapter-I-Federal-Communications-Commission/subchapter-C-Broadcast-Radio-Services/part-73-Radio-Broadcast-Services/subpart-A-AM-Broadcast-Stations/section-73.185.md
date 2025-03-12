##### § 73.185 Computation of interfering signal. #####

(a) Measured values of radiation are not to be used in calculating overlap, interference, and coverage.

(1) In the case of an antenna which is intended to be non-directional in the horizontal plane, an ideal non-directional radiation pattern shall be used in determining interference, overlap, and coverage, even if the antenna is not actually non-directional.

(2) In the case of an antenna which is directional in the horizontal plane, the radiation which shall be used in determining interference, overlap, and coverage is that calculated pursuant to § 73.150 or § 73.152, depending on whether the station has a standard or modified standard pattern.

(3) In the case of calculation of interference or overlap to (not from) a foreign station, the notified radiation shall be used, even if the notified radiation differs from that in paragraphs (a) (1) or (2) of this section.

(b) For skywave signals from stations operating on all channels, interference shall be determined from the appropriate formulas and Figure 6a contained in § 73.190.

(c) The formulas in § 73.190(d) depicted in Figure 6a of § 73.190, entitled “Angles of Departure versus Transmission Range” are to be used in determining the angles in the vertical pattern of the antenna of an interfering station to be considered as pertinent to transmission by one reflection. To provide for variation in the pertinent vertical angle due to variations of ionosphere height and ionosphere scattering, the curves 2 and 3 indicate the upper and lower angles within which the radiated field is to be considered. The maximum value of field strength occurring between these angles shall be used to determine the multiplying factor to apply to the 10 percent skywave field intensity value determined from Formula 2 in § 73.190. The multiplying factor is found by dividing the maximum radiation between the pertinent angles by 100 mV/m.

(d) Example of the use of skywave curves and formulas: Assume a proposed new Class B station from which interference may be expected is located at a distance of 724 kilometers from a licensed Class B station. The proposed station specifies geographic coordinates of 40°00′00″ N and 100°00′00″ W and the station to be protected is located at an azimuth of 45° true at geographic coordinates of 44°26′05″ N and 93°32′54″ W. The critical angles of radiation as determined from Figure 6a of § 73.190 for use with Class B stations are 9.6° and 16.6°. If the vertical pattern of the antenna of the proposed station in the direction of the existing station is such that, between the angles of 9.6° and 16.6° above the horizon the maximum radiation is 260 mV/m at one kilometer, the value of the 50% field, as derived from Formula 1 of § 73.190, is 0.06217 mV/m at the location of the existing station. To obtain the value of the 10% field, the 50% value must be adjusted by a factor derived from Formula 2 of § 73.190. The value in this case is 8.42 dB. Thus, the 10% field is 0.1616 mV/m. Using this in conjunction with the co-channel protection ratio of 26 dB, the resultant nighttime limit from the proposed station to the licensed station is 3.232 mV/m.

(e) In the case of an antenna which is non-directional in the horizontal plane, the vertical distribution of the relative fields should be computed pursuant to § 73.160. In the case of an antenna which is directional in the horizontal plane, the vertical pattern in the great circle direction toward the point of reception in question must first be calculated. In cases where the radiation in the vertical plane, at the pertinent azimuth, contains a large lobe at a higher angle than the pertinent angle for one reflection, the method of calculating interference will not be restricted to that just described; each such case will be considered on the basis of the best knowledge available.

(f) In performing calculations to determine permissible radiation from stations operating presunrise or postsunset in accordance with § 73.99, calculated diurnal factors will be multiplied by the values of skywave field strength for such stations obtained from Formula 1 or 2 of § 73.190.

(1) The diurnal factor is determined using the time of day at the mid-point of path between the site of the interfering station and the point at which interference is being calculated. Diurnal factors are computed using the formula Df = a + bF + cF2 + dF3 where:

Df represents the diurnal factor,F is the frequency in MHz,a,b,c, and d are constants obtained from the tables in paragraph (k)(2)A diurnal factor greater than one will not be used in calculations and interpolation is to be used between calculated values where necessary. For reference purposes, curves for presunrise and postsunset diurnal factors are contained in Figures 13 and 14 of § 73.190.

(2) Constants used in calculating diurnal factors for the presunrise and postsunset periods are contained in paragraphs (f)(2) (i) and (ii) of this section respectively. The columns labeled Tmp represent the number of hours before and after sunrise and sunset at the path midpoint.

(i) Presunrise Constants

|T<sub>mp</sub>|  a   |  b   |  c   |  d   |
|--------------|------|------|------|------|
|      −2      |1.3084|.0083 |−.0155|.0144 |
|    −1.75     |1.3165|−.4919|.6011 |−.1884|
|     −1.5     |1.0079|.0296 |.1488 |−.0452|
|    −1.25     |.7773 |.3751 |−.1911|.0736 |
|      −1      |.6230 |.1547 |.2654 |−.1006|
|     −.75     |.3718 |.1178 |.3632 |−.1172|
|     −.5      |.2151 |.0737 |.4167 |−.1413|
|     −.25     |.2027 |−.2560|.7269 |−.2577|
|      SR      |.1504 |−.2325|.5374 |−.1729|
|    \+ .25    |.1057 |−.2092|.4148 |−.1239|
|    \+ 5.     |.0642 |−.1295|.2583 |−.0699|
|    \+ .75    |.0446 |−.1002|.1754 |−.0405|
|     \+ 1     |.0148 |.0135 |.0462 |.0010 |

(ii) Postsunset Constants

|T<sub>mp</sub>|  a   |  b   |  c   |  d   |
|--------------|------|------|------|------|
|     1.75     |.9495 |−.0187|.0720 |−.0290|
|     1.5      |.7196 |.3583 |−.2280|.0611 |
|     1.25     |.6756 |.1518 |.0279 |−.0163|
|     1.0      |.5486 |.1401 |.0952 |−.0288|
|     .75      |.3003 |.4050 |−.0961|.0256 |
|      .5      |.1186 |.4281 |−.0799|.0197 |
|     .25      |.0382 |.3706 |−.0673|.0171 |
|      SS      |.0002 |.3024 |−.0540|.0086 |
|     −.25     |.0278 |.0458 |.1473 |−.0486|
|     −.5      |.0203 |.0132 |.1166 |−.0340|
|     −.75     |.0152 |−.0002|.0786 |−.0185|
|     −1.0     |−.0043|.0452 |−.0040|.0103 |
|    −1.25     |.0010 |.0135 |.0103 |.0047 |
|     −1.5     |.0018 |.0052 |.0069 |.0042 |
|    −1.75     |−.0012|.0122 |−.0076|.0076 |
|     −2.0     |−.0024|.0141 |−.0141|.0091 |

Editorial Note:At 56 FR 64867, Dec. 12, 1991, § 73.185 was amended by redesignating paragraphs (d), (e), (h), and (k) as (c), (d), (e), and (f), resulting in two consecutive paragraph (f)'s. These paragraphs will be correctly designated by a Federal Communication Commission document published in the Federal Register at a later date.

(f) For stations operating on regional and local channels, interfering skywave field intensities shall be determined in accordance with the procedure specified in (d) of this section and illustrated in (e) of this section, except that Figure 2 of § 73.190 is used in place of Figure 1a and 1b and the formulas of § 73.190. In using Figure 2 of § 73.190, one additional parameter must be considered, *i.e.*, the variation of received field with the latitude of the path.

(g) Figure 2 of § 73.190, “10 percent Skywave Signal Range Chart,” shows the signal as a function of the latitude of the transmission path, which is defined as the geographic latitude of the midpoint between the transmitter and receiver. When using Figure 2 of § 73.190, latitude 35° should be used in case the mid-point of the path lies below 35° North and latitude 50° should be used in case the mid-point of the path lies above 50° North.

[30 FR 13783, Oct. 29, 1965, as amended at 33 FR 15420, Oct. 17, 1968; 46 FR 11995, Feb. 12, 1981; 48 FR 42958, Sept. 20, 1983; 50 FR 18843, May 2, 1985; 56 FR 64867, Dec. 12, 1991]