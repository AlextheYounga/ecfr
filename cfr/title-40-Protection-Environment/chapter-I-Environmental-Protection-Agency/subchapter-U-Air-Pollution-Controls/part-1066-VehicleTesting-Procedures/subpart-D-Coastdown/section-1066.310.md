##### § 1066.310 Coastdown procedures for vehicles above 14,000 pounds GVWR. #####

This section describes coastdown procedures that are unique to vehicles above 14,000 pounds GVWR. These procedures are valid for calculating road-load coefficients for chassis and post-transmission powerpack testing. These procedures are also valid for calculating drag area (*C*d*A*) to demonstrate compliance with Phase 1 greenhouse gas emission standards under 40 CFR part 1037.

(a) Determine road-load coefficients by performing a minimum of 16 valid coastdown runs (8 in each direction).

(b) Follow the provisions of Sections 1 through 9 of SAE J1263 and SAE J2263 (incorporated by reference, see § 1066.1010), except as described in this paragraph (b). The terms and variables identified in this paragraph (b) have the meaning given in SAE J1263 or J2263 unless specified otherwise.

(1) The test condition specifications of SAE J1263 apply except as follows for wind and road conditions:

(i) We recommend that you do not perform coastdown testing on days for which winds are forecast to exceed 6.0 mi/hr.

(ii) The grade of the test track or road must not be excessive (considering factors such as road safety standards and effects on the coastdown results). Road conditions should follow Section 7.4 of SAE J1263, except that road grade may exceed 0.5%. If road grade is greater than 0.02% over the length of the test surface, you must incorporate into the analysis road grade as a function of distance along the length of the test surface. Use Section 11.5 of SAE J2263 to calculate the force due to grade.

(2) Operate the vehicle at a top speed above 70 mi/hr, or at its maximum achievable speed if it cannot reach 70 mi/hr. If a vehicle is equipped with a vehicle speed limiter that is set for a maximum speed below 70 mi/hr, you must disable the vehicle speed limiter. Start the test at or above 70 mi/hr, or at the vehicle's maximum achievable speed if it cannot reach 70 mi/hr. Collect data through a minimum speed at or below 15 mi/hr. Data analysis for valid coastdown runs must include the range of vehicle speeds specified in this paragraph (b)(2).

(3) Gather data regarding wind speed and direction, in coordination with time-of-day data, using at least one stationary electro-mechanical anemometer and suitable data loggers meeting the specifications of SAE J1263, as well as the following additional specifications for the anemometer placed adjacent to the test surface:

(i) Calibrate the equipment by running the zero-wind and zero-angle calibrations within 24 hours before conducting the coastdown procedures. If the coastdown procedures are not complete 24 hours after calibrating the equipment, repeat the calibration for another 24 hours of data collection.

(ii) Record the location of the anemometer using a GPS measurement device adjacent to the test surface (approximately) at the midway distance along the test surface used for coastdowns.

(iii) Position the anemometer such that it will be at least 2.5 but not more than 3.0 vehicle widths from the test vehicle's centerline as the test vehicle passes the anemometer.

(iv) Mount the anemometer at a height that is within 6 inches of half the test vehicle's maximum height.

(v) Place the anemometer at least 50 feet from the nearest tree and at least 25 feet from the nearest bush (or equivalent roadside features).

(vi) The height of the grass surrounding the stationary anemometer may not exceed 10% of the anemometer's mounted height, within a radius equal to the anemometer's mounted height.

(4) You may split runs as per Section 9.3.1 of SAE J2263, but we recommend whole runs. If you split a run, analyze each portion separately, but count the split runs as one run with respect to the minimum number of runs required.

(5) You may perform consecutive runs in a single direction, followed by consecutive runs in the opposite direction, consistent with good engineering judgment. Harmonize starting and stopping points to the extent practicable to allow runs to be paired.

(6) All valid coastdown run times in each direction must be within 2.0 standard deviations of the mean of the valid coastdown run times (from the specified maximum speed down to 15 mi/hr) in that direction. Eliminate runs outside this range. After eliminating these runs you must have at least eight valid runs in each direction. You may use coastdown run times that do not meet these standard deviation requirements if we approve it in advance. In your request, describe why the vehicle is not able to meet the specified standard deviation requirements and propose an alternative set of requirements.

(7) Analyze data for chassis and post-transmission powerpack testing or for use in the GEM simulation tool as follows:

(i) Follow the procedures specified in Section 10 of SAE J1263 or Section 11 of SAE J2263 to calculate coefficients for chassis and post-transmission powerpack testing.

(ii) Determine drag area, *C*d*A,* as follows instead of using the procedure specified in Section 10 of SAE J1263:

(A) Measure vehicle speed at fixed intervals over the coastdown run (generally at 10 Hz), including speeds at or above 15 mi/hr and at or below the specified maximum speed. Establish the elevation corresponding to each interval as described in SAE J2263 if you need to incorporate the effects of road grade.

(B) Calculate the vehicle's effective mass, *M*e, in kg by adding 56.7 kg to the measured vehicle mass, *M,* for each tire making road contact. This accounts for the rotational inertia of the wheels and tires.

(C) Calculate the road-load force for each measurement interval, *F*i, using the following equation:

![](/graphics/er28ap14.082.gif)Where:*i* = an interval counter, starting with *i* = 1 for the first interval. The designation (*i*-1) corresponds to the end of the previous interval or, for the first interval, to the start of the test run.*M*e = the vehicle's effective mass, expressed to at least the nearest 0.1 kg.*v* = vehicle speed at the beginning and end of the measurement interval.Δ*t* = elapsed time over the measurement interval, in seconds.

(D) Plot the data from all the coastdown runs on a single plot of *F*i vs. *v*i2 to determine the slope correlation, *D,* based on the following equation:

![](/graphics/er25oc16.254.gif)Where:*M* = the measured vehicle mass, expressed to at least the nearest 0.1 kg.*a*g = acceleration of Earth's gravity, as described in 40 CFR 1065.630.*Δh* = change in elevation over the measurement interval, in m. Assume *Δh* = 0 if you are not correcting for grade.*Δs* = distance the vehicle travels down the road during the measurement interval, in m.*A*m = the calculated value of the y-intercept based on the curve-fit.

(E) Calculate drag area, *C*d*A,* in m2 using the following equation:

![](/graphics/er25oc16.255.gif)Where:r = air density at reference conditions = 1.17 kg/m3.![](/graphics/er25oc16.256.gif)*T* = mean ambient absolute temperature during testing, in K.*P* = mean ambient pressuring during the test, in kPa.

(8) Determine the A, B, and C coefficients identified in § 1066.210 as follows:

(i) For chassis and post-transmission powerpack testing, follow the procedures specified in Section 10 of SAE J1263 or Section 12 of SAE J2263.

(ii) For the GEM simulation tool, use the following values:

A = *A*mB = 0C = *D*adj[79 FR 23823, Apr. 28, 2016, as amended at 81 FR 74202, Oct. 25, 2016; 89 FR 28211, Apr. 18, 2024]