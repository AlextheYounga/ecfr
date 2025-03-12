##### § 1036.530 Test procedures for off-cycle testing. #####

(a) *General.* This section describes the measurement and calculation procedures to perform field testing and determine whether tested engines and engine families meet emission standards under subpart E of this part. Calculate mass emission rates as specified in 40 CFR part 1065, subpart G. Use good engineering judgment to adapt these procedures for simulating vehicle operation in the laboratory.

(b) *Vehicle preparation and measurement procedures.* (1) Set up the vehicle for testing with a portable emissions measurement system (PEMS) as specified in 40 CFR part 1065, subpart J.

(2) Begin emission sampling and data collection as described in 40 CFR 1065.935(c)(3) before starting the engine at the beginning of the shift-day. Start the engine only after confirming that engine coolant temperature is at or below 40 °C.

(3) Measure emissions over one or more shift-days as specified in subpart E of this part.

(4) For engines subject to compression-ignition standards, record 1 Hz measurements of ambient temperature near the vehicle.

(c) *Test Intervals.* Determine the test intervals as follows:

(1) *Spark-ignition.* Create a single test interval that covers the entire shift-day for engines subject to spark-ignition standards. The test interval starts with the first pair of consecutive data points with no exclusions as described in paragraph (c)(3) of this section after the start of the shift-day and ends with the last pair of consecutive data points with no exclusions before the end of the shift day.

(2) *Compression-ignition.* Create a series of 300 second test intervals for engines subject to compression-ignition standards (moving-average windows) as follows:

(i) Begin and end each test interval with a pair of consecutive data points with no exclusions as described in paragraph (c)(3) of this section. Select the last data point of each test interval such that the test interval includes 300 seconds of data with no exclusions, as described in paragraph (d) of this section. The test interval may be a fraction of a second more or less than 300 seconds to account for the precision of the time stamp in recording 1 Hz data. A test interval may include up to 599 seconds of data with continuous exclusions; invalidate any test interval that includes at least 600 seconds of continuous sampling with excluded data.

(ii) The first 300 second test interval starts with the first pair of consecutive data points with no exclusions. Determine the start of each subsequent 300 second test interval by finding the first pair of consecutive data points with no exclusions after the initial data point of the previous test interval.

(iii) The last 300 second test interval ends with the last pair of consecutive data points with no exclusions before the end of the shift day.

(3) *Excluded data.* Exclude data from test intervals for any period meeting one or more of the following conditions:

(i) An analyzer or flow meter is performing zero and span drift checks or zero and span calibrations, including any time needed for the analyzer to stabilize afterward, consistent with good engineering judgment.

(ii) The engine is off, except as specified in § 1036.415(g).

(iii) The engine is performing an infrequent regeneration. Do not exclude data related to any other AECDs, except as specified in paragraph (c)(3)(vi) of this section.

(iv) The recorded ambient air temperature is below 5 °C or above the temperature calculated using the following equation.

![](/graphics/er24ja23.041.gif)Where:*h* = recorded elevation of the vehicle in feet above sea level (h is negative for elevations below sea level).Example:*h* = 2679 ft*T*max = −0.0014·2679 + 37.78*T*max = 34.0 °C

(v) The vehicle is operating at an elevation more than 5,500 feet above sea level.

(vi) An engine has one or more active AECDs for emergency vehicles under § 1036.115(h)(4).

(vii) A single data point does not meet any of the conditions specified in paragraphs (c)(3)(i) through (vi) of this section, but it is preceded and followed by data points that both meet one or more of the specified exclusion conditions.

(d) *Assembling test intervals.* A test interval may include multiple subintervals separated by periods with one or more exclusions under paragraph (c)(3) of this section.

(1) Treat these test subintervals as continuous for calculating duration of the test interval for engines subject to compression-ignition standards.

(2) Calculate emission mass during each test subinterval and sum those subinterval emission masses to determine the emission mass over the test interval. Calculate emisson mass as described in 40 CFR 1065.650(c)(2)(i), with the following exceptions and clarifications:

(i) Correct NOX emissions for humidity as specified in 40 CFR 1065.670. Calculate corrections relative to ambient air humidity as measured by PEMS.

(ii) Disregard the provision in 40 CFR 1065.650(g) for setting negative emission mass to zero for test intervals and subintervals.

(iii) Calculation of emission mass in 40 CFR 1065.650 assumes a constant time interval, Δ*t.* If it is not appropriate to assume Δ*t* is constant for testing under this section, use good engineering judgment to record time at each data point and adjust the mass calculation from Eq. 1065.650-4 by treating Δ*t* as a variable.

(e) *Normalized CO*2*emission mass over a 300 second test interval.* For engines subject to compression-ignition standards, determine the normalized CO2 emission mass over each 300 second test interval, *m*CO2,norm,testinterval, to the nearest 0.01% using the following equation:

![](/graphics/er24ja23.042.gif)Where:*m*CO2,testinterval = total CO2 emission mass over the test interval.*e*CO2FTPFCL = the engine's FCL for CO2 over the FTP duty cycle. If the engine family includes no FTP testing, use the engine's FCL for CO2 over the SET duty cycle.*P*max = the highest value of rated power for all the configurations included in the engine family.*t*testinterval = duration of the test interval. Note that the nominal value is 300 seconds.Example:*m*CO2,testinterval = 3948 g*e*CO2FTPFCL = 428.2 g/hp·hr *P*max = 406.5 hp*t*testinterval = 300.01 s = 0.08 hr![](/graphics/er24ja23.043.gif)*m*CO2,norm,testinterval = 0.2722 = 27.22%

(f) *Binning 300 second test intervals.* For engines subject to compression-ignition standards, identify the appropriate bin for each of the 300 second test intervals based on its normalized CO2 emission mass, *m*CO2,norm,testinterval, as follows:

| Bin |Normalized CO<sub>2</sub> emission mass over the 300 second test interval|
|-----|-------------------------------------------------------------------------|
|Bin 1|               m<sub>CO2,norm,testinterval</sub> ≤ 6.00%.                |
|Bin 2|               m<sub>CO2,norm,testinterval</sub> \> 6.00%.               |

(g) *Off-cycle emissions quantities.* Determine the off-cycle emissions quantities as follows:

(1) *Spark-ignition.* For engines subject to spark-ignition standards, the off-cycle emission quantity, *e*[emission],offcycle, is the value for CO2-specific emission mass for a given pollutant over the test interval representing the shift-day converted to a brake-specific value, as calculated for each measured pollutant using the following equation:

![](/graphics/er22ap24.172.gif)Eq. 1036.530-3Where:*m*[emission] = total emission mass for a given pollutant over the test interval as determined in paragraph (d)(2) of this section.*m*CO2 = total CO2 emission mass over the test interval as determined in paragraph (d)(2) of this section.*e*CO2FTPFCL = the engine's FCL for CO2 over the FTP duty cycle.

*Example:*

![](/graphics/er22ap24.173.gif)

(2) *Compression-ignition.* For engines subject to compression-ignition standards, determine the off-cycle emission quantity for each bin. When calculating mean bin emissions from ten engines to apply the pass criteria for engine families in § 1036.425(c), set any negative off-cycle emissions quantity to zero before calculating mean bin emissions.

(i) *Off-cycle emissions quantity for bin 1.* The off-cycle emission quantity for bin 1, *m*NOx,offcycle,bin1, is the mean NOX mass emission rate from all test intervals associated with bin 1 as calculated using the following equation:

![](/graphics/er24ja23.046.gif)Where:*i* = an indexing variable that represents one 300 second test interval.*N* = total number of 300 second test intervals in bin 1.*m*NOXtestinterval,i = total NOX emission mass over the test interval *i* in bin 1 as determined in paragraph (d)(2) of this section.*t*testinterval,i = total time of test interval *i* in bin 1 as determined in paragraph (d)(1) of this section. Note that the nominal value is 300 seconds.Example:*N* = 10114*m*NOX,testinterval,1 = 0.021 g*m*NOX,testinterval,2 = 0.025 g*m*NOX,testinterval,3 = 0.031 g*t*testinterval,1 = 299.99 s*t*testinterval,2 = 299.98 s*t*testinterval,3 = 300.04 s![](/graphics/er24ja23.047.gif)*m*NOoffcycle,bin1, = 0.000285 g/s = 1.026 g/hr

(ii) *Off-cycle emissions quantity for bin 2.* The off-cycle emission quantity for bin 2, *e*[emission],offcycle,bin2, is the value for CO2-specific emission mass for a given pollutant of all the 300 second test intervals in bin 2 combined and converted to a brake-specific value, as calculated for each measured pollutant using the following equation:

![](/graphics/er22ap24.174.gif)Eq. 1036.530-5Where:*i* = an indexing variable that represents one 300 second test interval.*N* = total number of 300 second test intervals in bin 2.*m*[emission],testinterval,i = total emission mass for a given pollutant over the test interval *i* in bin 2 as determined in paragraph (d)(2) of this section.*m*CO2,testinterval,i = total CO2 emission mass over the test interval *i* in bin 2 as determined in paragraph (d)(2) of this section.*e*CO2,FTP,FCL = the engine's FCL for CO2 over the FTP duty cycle.

*Example:*

*N* = 15439*m*NOx1 = 0.546 g*m*NOx2 = 0.549 g*m*NOx3 = 0.556 g*m*CO2,1 = 10950.2 g*m*CO2,2 = 10961.3 g*m*CO2,3 = 10965.3 g*e*CO2,FTP,FCL = 428.1 g/hp·hr![](/graphics/er22ap24.175.gif)

(h) *Shift-day ambient temperature.* For engines subject to compression-ignition standards, determine the mean shift-day ambient temperature, *T*amb, considering only temperature readings corresponding to data with no exclusions under paragraph (c)(3) of this section.

(i) *Graphical illustration.* Figure 1 of this section illustrates a test interval with interruptions of one or more data points excluded under paragraph (c)(3) of this section. The x-axis is time and the y-axis is the mass emission rate at each data point, *m**(t)* The data points coincident with any exclusion are illustrated with open circles. The shaded area corresponding to each group of closed circles represents the total emission mass over that test subinterval. Note that negative values of *m**(t)* are retained and not set to zero in the numerical integration calculation. The first group of data points without any exclusions is referred to as the first test subinterval and so on.

Figure 1 to Paragraph (i) of § 1036.530—Illustration of Integration of Mass of Emissions Over a Test Interval With Exclude Data Points![](/graphics/er24ja23.050.gif)

(j) *Fuel other than carbon-containing.* The following procedures apply for testing engines using at least one fuel that is not a carbon-containing fuel:

(1) Use the following equation to determine the normalized equivalent CO2 emission mass over each 300 second test interval instead of Eq. 1036.530-2:

![](/graphics/er22ap24.176.gif)Eq. 1036.530-6Where:*W*testinterval = total positive work over the test interval from both the engine and hybrid components, if applicable, as determined in 40 CFR 1065.650.*P*max = the highest value of rated power for all the configurations included in the engine family.*t*testinterval = duration of the test interval. Note that the nominal value is 300 seconds.

*Example:*

*W*testinterval = 8.95 hp·hr*P*max = 406.5 hp*t*testinterval = 300.01 s = 0.08 hr![](/graphics/er22ap24.177.gif)

(2) Determine off-cycle emissions quantities as follows:

(i) For engines subject to spark-ignition standards, use the following equation to determine the off-cycle emission quantity instead of Eq. 1036.530-3:

![](/graphics/er22ap24.178.gif)Eq. 1036.530-7Where:

*m*[emission] = total emission mass for a given pollutant over the test interval as determined in paragraph (d)(2) of this section.

*W*testinterval = total positive work over the test interval as determined in 40 CFR 1065.650.

Example:

![](/graphics/er22ap24.179.gif)

(ii) For engines subject to compression-ignition standards, use Eq. 1036.530-4 to determine the off-cycle emission quantity for bin 1.

(iii) For engines subject to compression-ignition standards, use the following equation to determine the off-cycle emission quantity for bin 2 instead of Eq. 1036.530-5:

![](/graphics/er22ap24.180.gif)Eq. 1036.530-8Where:*i* = an indexing variable that represents one 300 second test interval.*N* = total number of 300 second test intervals in bin 2.*m*[emission],testinterval,i = total emission mass for a given pollutant over the test interval *i* in bin 2 as determined in paragraph (d)(2) of this section.*W*testinterval,i = total positive work over the test interval *i* in bin 2 as determined in 40 CFR 1065.650.

*Example:*

*N* = 15439*m*NOx1 = 0.546 g*m*NOx2 = 0.549 g*m*NOx3 = 0.556 g*W*testinterval1 = 8.91 hp·hr*W*testinterval2 = 8.94 hp·hr*W*testinterval3 = 8.89 hp·hr![](/graphics/er22ap24.181.gif)[88 FR 4487, Jan. 24, 2023, as amended at 89 FR 29748, Apr. 22, 2024]