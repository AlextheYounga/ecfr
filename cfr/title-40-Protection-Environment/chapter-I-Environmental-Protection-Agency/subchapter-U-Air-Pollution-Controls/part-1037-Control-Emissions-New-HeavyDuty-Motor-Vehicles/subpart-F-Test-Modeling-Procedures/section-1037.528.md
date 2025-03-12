##### § 1037.528 Coastdown procedures for calculating drag area (CdA). #####

This section describes the reference method for calculating drag area, *C*d*A*, for tractors using coastdown testing. Follow the provisions of Sections 1 through 9 of SAE J2263 (incorporated by reference, see § 1037.810), with the clarifications and exceptions described in this section. Several of the exceptions in this section are from SAE J1263 (incorporated by reference, see § 1037.810). The coastdown procedures in 40 CFR 1066.310 apply instead of the provisions of this section for Phase 1 tractors.

(a) The terms and variables identified in this section have the meaning given in SAE J1263 and SAE J2263 unless specified otherwise.

(b) To determine *C*d*A* values for a, perform coastdown testing with a tractor-trailer combination using the manufacturer's tractor and a standard trailer. Prepare the tractor-trailer combination for testing as follows:

(1) Install instrumentation for performing the specified measurements.

(2) After adding vehicle instrumentation, verify that there is no brake drag or other condition that prevents the wheels from rotating freely. Do not apply the parking brake at any point between this inspection and the end of the measurement procedure.

(3) Install tires mounted on steel rims in a dual configuration (except for steer tires). The tires must—

(i) Be SmartWay-Verified or have a coefficient of rolling resistance at or below 5.1 kg/metric ton.

(ii) Have accumulated at least 2,000 miles but have no less than 50 percent of their original tread depth, as specified for truck cabs in SAE J1263.

(iii) Not be retreads or have any apparent signs of chunking or uneven wear.

(iv) Be size 295/75R22.5 or 275/80R22.5.

(v) Be inflated to the proper tire pressure as specified in Sections 6.6 and 8.1 of SAE J2263.

(vi) Be of the same tire model for a given axle.

(4) Perform an inspection or wheel alignment for both the tractor and the trailer to ensure that wheel position is within the manufacturer's specifications.

(c) The test condition specifications described in Sections 7.1 through 7.4 of SAE J1263 apply, with certain exceptions and additional provisions as described in this paragraph (c). These conditions apply to each run separately.

(1) We recommend that you not perform coastdown testing if winds are expected to exceed 6.0 mi/hr.

(2) The average of the component of the wind speed parallel to the road must not exceed 6.0 mi/hr. This constraint is in addition to those in Section 7.3 of SAE J1263.

(3) If road grade is greater than 0.02% over the length of the test surface, you must determine elevation as a function of distance along the length of the test surface and incorporate this into the analysis.

(4) Road grade may exceed 0.5% for limited portions of the test surface as long as it does not affect coastdown results, consistent with good engineering judgment.

(5) The road surface temperature must be at or below 50 °C. Use good engineering judgment to measure road surface temperature.

(d) *C*d*A* calculations are based on measured speed values while the vehicle coasts down through a high-speed range from 70 to 60 mi/hr, and through a low-speed range from 20 to 10 mi/hr. Disable any vehicle speed limiters that prevent travel above 72 mi/hr. Measure vehicle speed at a minimum recording frequency of 10 Hz, in conjunction with time-of-day data. Determine vehicle speed using either of the following methods:

(1) *Complete coastdown runs.* Operate the vehicle at a top speed above 72.0 mi/hr and allow the vehicle to coast down to 8.0 mi/hr or lower. Collect data for the high-speed range over a test segment that includes speeds from 72.0 down to 58.0 mi/hr, and collect data for the low-speed range over a test segment that includes speeds from 22.0 down to 8.0 mi/hr.

(2) *Split coastdown runs.* Collect data during a high-speed coastdown while the vehicle coasts through a test segment that includes speeds from 72.0 mi/hr down to 58.0 mi/hr. Similarly, collect data during a low-speed coastdown while the vehicle coasts through a test segment that includes speeds from 22.0 mi/hr down to 8.0 mi/hr. Perform one high-speed coastdown segment or two consecutive high-speed coastdown segments in one direction, followed by the same number of low-speed coastdown segments in the same direction, and then perform that same number of measurements in the opposite direction. You may not split runs as described in Section 9.3.1 of SAE J2263 except as allowed under this paragraph (d)(2).

(e) Measure wind speed, wind direction, air temperature, and air pressure at a recording frequency of 10 Hz, in conjunction with time-of-day data. Use at least one stationary anemometer and suitable data loggers meeting SAE J1263 specifications, subject to the following additional specifications for the anemometer placed along the test surface:

(1) You must start a coastdown measurement within 24 hours after completing zero-wind and zero-angle calibrations.

(2) Place the anemometer at least 50 feet from the nearest tree and at least 25 feet from the nearest bush (or equivalent features). Position the anemometer adjacent to the test surface, near the midpoint of the length of the track, between 2.5 and 3.0 body widths from the expected location of the test vehicle's centerline as it passes the anemometer. Record the location of the anemometer along the test track, to the nearest 10 feet.

(3) Mount the anemometer at a height that is within 6 inches of half the test vehicle's body height.

(4) The height of vegetation surrounding the anemometer may not exceed 10% of the anemometer's mounted height, within a radius equal to the anemometer's mounted height.

(f) Measure air speed and relative wind direction (yaw angle) onboard the vehicle at a minimum recording frequency of 10 Hz, in conjunction with time-of-day data, using an anemometer and suitable data loggers that meet the requirements of Sections 5.4 of SAE J2263. The yaw angle must be measured to a resolution and accuracy of ±0.5°. Mount the anemometer such that it measures air speed at 1.5 meters above the top of the leading edge of the trailer. If obstructions at the test site do not allow for this mounting height, then mount the anemometer such that it measures air speed at least 0.85 meters above the top of the leading edge of the trailer.

(g) Perform the following calculations to filter and correct measured data:

(1) For any measured values not identified as outliers, use those measured values directly in the calculations specified in this section. Filter air speed, yaw angle, wind speed, wind direction, and vehicle speed measurements to replace outliers for every measured value as follows:

(i) Determine a median measured value to represent the measurement point and the measurements 3 seconds before and after that point. In the first and last three seconds of the coastdown run, use all available data to determine the median measured value. The measurement window for determining the median value will accordingly include 61 measurements in most cases, and will always include at least 31 measurements (for 10 Hz recording frequency).

(ii) Determine the median absolute deviation corresponding to each measurement window from paragraph (g)(1)(i) of this section. This generally results from calculating 61 absolute deviations from the median measured value and determining the median from those 61 deviations. Calculate the standard deviation for each measurement window by multiplying the median absolute deviation by 1.4826; calculate three standard deviations by multiplying the median absolute deviation by 4.4478. Note that the factor 1.4826 is a statistical constant that relates median absolute deviations to standard deviations.

(iii) A measured value is an outlier if the measured value at a given point differs from the median measured value by more than three standard deviations. Replace each outlier with the median measured value from paragraph (g)(1)(i) of this section. This technique for filtering outliers is known as the Hampel method.

(2) For each high-speed and each low-speed segment, correct measured air speed using the wind speed and wind direction measurements described in paragraph (e) of this section as follows:

(i) Calculate the theoretical air speed, *v*air,th, for each 10-Hz set of measurements using the following equation:

![](/graphics/er25oc16.094.gif)Where:*w* = filtered wind speed.*v* = filtered vehicle speed.*ø*w = filtered wind direction. Let *ø*w = 0° for air flow in the first travel direction, with values increasing counterclockwise. For example, if the vehicle starts by traveling eastbound, then *ø*w = 270° means a wind from the south.*ø*veh = the vehicle direction. Use *ø*veh = 0° for travel in the first direction, and use *ø*veh = 180° for travel in the opposite direction.Example:*w* = 7.1 mi/hr*v* = 64.9 mi/hr*ø*w = 47.0°*ø*veh = 0°![](/graphics/er25oc16.095.gif)*v*air,th = 69.93 mi/hr

(ii) Perform a linear regression using paired values of *v*air,th and measured air speed, *v*air,meas, to determine the air-speed correction coefficients, a0 and a1, based on the following equation:

![](/graphics/er25oc16.096.gif)

(iii) Correct each measured value of air speed using the following equation:

![](/graphics/er25oc16.097.gif)

(3) Correct measured air direction from all the high-speed segments using the wind speed and wind direction measurements described in paragraph (e) of this section as follows:

(i) Calculate the theoretical air direction, c;air,th, using the following equation:

![](/graphics/er25oc16.098.gif)Example:*w* = 7.1 mi/hr*v* = 64.9 mi/hr*ø*w = 47.0°*ø*veh = 0°![](/graphics/er25oc16.099.gif)cair,th = 4.26°

(ii) Perform a linear regression using paired values of cair,th and measured air direction, cair,meas, to determine the air-direction correction coefficients, b0 and b1, based on the following equation:

![](/graphics/er25oc16.100.gif)

(iii) Correct each measured value of air direction using the following equation:

![](/graphics/er25oc16.101.gif)

(h) Determine drag area, *C*d*A*, using the following procedure instead of the procedure specified in Section 10 of SAE J1263:

(1) Calculate the vehicle's effective mass, *M*e, to account for rotational inertia by adding 56.7 kg to the measured vehicle mass, *M,* (in kg) for each tire making road contact.

(2) Operate the vehicle and collect data over the high-speed range and low-speed range as specified in paragraph (d)(1) or (2) of this section. If the vehicle has a speed limiter that prevents it from exceeding 72 mi/hr, you must disable the speed limiter for testing.

(3) Calculate mean vehicle speed at each speed start point (70 and 20 mi/hr) and end point (60 and 10 mi/hr) as follows:

(i) Calculate the mean vehicle speed to represent the start point of each speed range as the arithmetic average of measured speeds throughout the continuous time interval that begins when measured vehicle speed is less than 2.00 mi/hr above the nominal starting speed point and ends when measured vehicle speed reaches 2.00 mi/hr below the nominal starting speed point, expressed to at least two decimal places. Calculate the timestamp corresponding to the starting point of each speed range as the average timestamp of the interval.

(ii) Repeat the calculations described in paragraph (h)(3)(i) of this section corresponding to the end point speed (60 or 10 mi/hr) to determine the time at which the vehicle reaches the end speed, and the mean vehicle speed representing the end point of each speed range.

(iii) If you incorporate grade into your calculations, use the average values for the elevation and distance traveled over each interval.

(4) Calculate the road-load force, *F,* for each speed range using the following equation:

![](/graphics/er25oc16.102.gif)Where:*M*e = the vehicle's effective mass.*v* = average vehicle speed at the start or end of each speed range, as described in paragraph (h)(3) of this section.*t* = timestamp at which the vehicle reaches the starting or ending speed expressed to at least one decimal place.*M* = the vehicle's measured mass.*a*g = acceleration of Earth's gravity, as described in 40 CFR 1065.630.*h* = average elevation at the start or end of each speed range expressed to at least two decimal places.*D* = distance traveled on the road surface from a fixed reference location along the road to the start or end of each speed range expressed to at least one decimal place.Example:*M*e = 17,129 kg (18 tires in contact with the road surface)*v*start = 69.97 mi/hr = 31.28 m/s*v*end = 59.88 mi/hr = 26.77 m/s*t*start = 3.05 s*t*end = 19.11 s*M* = 16,108 kg*a*g = 9.8061 m/s2*h*start = 0.044 m*h*end = 0.547 m*D*start = 706.8 ft = 215.4 m*D*end = 2230.2 ft = 697.8 m![](/graphics/er25oc16.103.gif)*F* = 4645.5 N

(5) Calculate the drive-axle spin loss force at high and low speeds, *F*spin[speed], and determine D*F*spin as follows:

(i) Use the results from the axle efficiency test described in § 1037.560 for the drive axle model installed in the tractor being tested for this coastdown procedure.

(ii) Perform a second-order regression of axle power loss in W from only the zero-torque test points with wheel speed, *f*nwheel, in r/s from the axle efficiency test to determine coefficients *c*0, *c*1, and *c*2.

![](/graphics/er25oc16.104.gif)

(iii) Calculate *F*spin[speed] using the following equation:

![](/graphics/er25oc16.105.gif)Where:*v*seg[speed] = the mean vehicle speed of all vehicle speed measurements in each low-speed and high-speed segment.*TRPM* = tire revolutions per mile for the drive tire model installed on the tractor being tested according to § 1037.520(c)(1).Example:*v*seghi = 28.86 m/s*v*seglo = 5.84 m/s*TRPM* = 508 r/mi = 0.315657 r/m*c*0 = −206.841 W*c*1 = 239.8279 W·s/r*c*2 = 21.27505 W·s2/r2![](/graphics/er25oc16.106.gif)*F*spinhi = 129.7 N*F*spinlo = 52.7 N

(iv) Calculate D*F*spin using the following equation:

D*F*spin = *F*spinhi−*F*spinloEq. 1037.528-10

*Example:*

D*F*spin = 129.7−52.7D*F*spin = 77.0 N

(6) Calculate the tire rolling resistance force at high and low speeds for steer, drive, and trailer axle positions, *F*TRR[speed,axle], and determine D*F*TRR, the rolling resistance difference between 65 mi/hr and 15 mi/hr, for each tire as follows:

(i) Conduct a stepwise coastdown tire rolling resistance test with three tires for each tire model installed on the vehicle using SAE J2452 (incorporated by reference in § 1037.810) for the following test points (which replace the test points in Table 3 of SAE J2452):

|Step Number|Load  <br/>(% of max)|Inflation  <br/>pressure  <br/>(% of max)|
|-----------|---------------------|-----------------------------------------|
|     1     |         20          |                   100                   |
|     2     |         55          |                   70                    |
|     3     |         85          |                   120                   |
|     4     |         85          |                   100                   |
|     5     |         100         |                   95                    |

(ii) Calculate FTRR[speed,axle] using the following equation:

![](/graphics/er29jn21.121.gif)Where:*n*t,[axle] = number of tires at the axle position.*p*[axle] = the inflation pressure set and measured on the tires at the axle position at the beginning of the coastdown test.*L*[axle] = the load over the axle at the axle position on the coastdown test vehicle.*α*[axle], *β*[axle], *a*[axle], *b*[axle], and *c*[axle] = regression coefficients from SAE J2452 that are specific to axle position.Example:*n*t,steer = 2*p*steer = 758.4 kPa*L*steer = 51421.2 N*α*steer = −0.2435*β*steer = 0.9576*a*steer = 0.0434*b*steer = 5.4·10−5*c*steer = 5.53·10−7*n*t,drive = 8*p*drive = 689.5 kPa*L*drive = 55958.4 N*α*drive = −0.3146*β*drive = 0.9914*a*drive = 0.0504*b*drive = 1.11·10−4*c*drive = 2.86·10−7*n*t,trailer = 8*p*trailer = 689.5 kPa*L*trailer = 45727.5 N*α*trailer = −0.3982*β*trailer = 0.9756*a*trailer = 0.0656*b*trailer = 1.51·10−4*c*trailer = 2.94·10−7*v*seghi = 28.86 m/s = 103.896 km/hr*v*seglo = 5.84 m/s = 21.024 km/hr![](/graphics/er29jn21.122.gif)*F*TRRhi,steer = 365.6 N*F*TRRhi,drive = 431.4 N*F*TRRhi,trailer = 231.7 N*F*TRRlo,steer = 297.8 N*F*TRRlo,drive = 350.7 N*F*TRRlo,trailer = 189.0 N

(iii) Calculate *F*TRR[speed] by summing the tire rolling resistance calculations at a given speed for each axle position:

![](/graphics/er29jn21.123.gif)Example:*F*TRRhi = 365.6 + 431.4 + 231.7 = 1028.7 N*F*TRRlo = 297.8 + 350.7 + 189.0 = 837.5 N

(iv) Adjust *F*TRR[speed] to the ambient temperature during the coastdown segment as follows:

![](/graphics/er29jn21.124.gif)Where:Tseg[speed] = the average ambient temperature during the coastdown segment, in °C.Example:*F*TRRhi = 1028.7 N*F*TRRlo = 837.5 NTseghi = 25.5 °CTseglo = 25.1 °C*F*TRRhi,adj = 1 + 0.006·(24−25.5)] = 1019.4 N*F*TRRlo,adj = 837.5·[1 + 0.006·(24−25.1] = 832.0 N

(v) Determine the difference in rolling resistance between 65 mph and 15 mph, Δ*F*TRR, for each tire. Use good engineering judgment to consider the multiple results. For example, you may ignore the test results for the tires with the highest and lowest differences and use the result from the remaining tire. Determine Δ*F*TRR as follows:

![](/graphics/er29jn21.125.gif)Example:*ΔF*TRR = 1019.4−832.0 = 187.4 N

(7) Square the air speed measurements and calculate average squared air speed during each speed range for each run,*v*2air,hi and *v*2air,lo.

(8) Average the *F*lo and *v*2air,lo values for each pair of runs in opposite directions. If running complete coastdowns as described in paragraph (d)(1) or one high-speed segment per direction as described in paragraph (d)(2), average every two *F*lo and *v*2air,lo values. If running two high-speed segments per direction as described in paragraph (d)(2), average every four *F*lo and *v*2air,lo values. Use these values as *F*lo,pair and *v*2air,lo,pair in the calculations in this paragraph (h) to apply to each of the two or four high-speed segments from the same runs as the low-speed segments used to determine *F*lo,pair and *v*2air,lo,pair.

(9) Calculate average air temperature *T* and air pressure *P*act during each high-speed run.

(10) Calculate drag area, *C*d*A,* in m2 for each high-speed segment using the following equation, expressed to at least three decimal places:

![](/graphics/er22ap24.216.gif)Eq. 1037.528-16Where:*F*hi = road load force at high speed determined from Eq. 1037.528-7.*F*lo,pair = the average of *F*lo values for a pair of opposite direction runs calculated as described in paragraph (h)(8) of this section.D*F*spin = the difference in drive-axle spin loss force between high-speed and low-speed coastdown segments as described in paragraph (h)(5) of this section.D*F*TRR = the difference in tire rolling resistance force between high-speed and low-speed coastdown segments as described in paragraph (h)(6) of this section.*v*2air,lo,pair = the average of *v*2air,lo values for a pair of opposite direction runs calculated as described in paragraph (h)(8) of this section.*R* = specific gas constant = 287.058 J/(kg·K).*T* = mean air temperature expressed to at least one decimal Place.*P*act = mean absolute air pressure expressed to at least one decimal place.

*Example:*

*F*hi = 4645.5 N*F*lo,pair = 1005.0 N*ΔF*spin = 77.0 N*ΔF*TRR = 187.4 N*v*2air,hi = 933.4 m2/s2*v*2air,lo,pair = 43.12 m2/s2*R* = 287.058 J/(kg·K)*T* = 285.97 KRact = 101.727 kPa = 101727 Pa![](/graphics/er22ap24.217.gif)

(11) Calculate your final *C*d*A* value from the high-speed segments as follows:

(i) Eliminate all points where there were known equipment problems or other measurement problems.

(ii) Of the remaining points, calculate the median of the absolute value of the yaw angles, cmed, and eliminate all *C*d*A* values that differ by more than 1.0° from cmed.

(iii) Of the remaining points, calculate the mean and standard deviation of *C*d*A* and eliminate all values that differ by more than 2.0 standard deviations from the mean value.

(iv) There must be at least 24 points remaining. Of the remaining points, recalculate the mean yaw angle. Round the mean yaw angle to the nearest 0.1°. This final result is the effective yaw angle, ceff, for coastdown testing.

(v) For the same set of points, recalculate the mean *C*d*A*. This is the final result of the coastdown test, *C*d*A*coastdown(ψeff).

(i) [Reserved]

(j) Include the following information in your application for certification:

(1) The name, location, and description of your test facilities, including background/history, equipment and capability, and track and facility elevation, along with the grade and size/length of the track.

(2) Test conditions for each test result, including date and time, wind speed and direction, ambient temperature and humidity, vehicle speed, driving distance, manufacturer name, test vehicle/model type, model year, applicable family, tire type and rolling resistance, weight of tractor-trailer (as tested), and driver identifier(s).

(3) Average *C*d*A* and yaw angle results and all the individual run results (including voided or invalid runs).

[81 FR 74048, Oct. 25, 2016, as amended at 86 FR 34474, June 29, 2021; 87 FR 64864, Oct. 26, 2022; 89 FR 29783, Apr. 22, 2024]