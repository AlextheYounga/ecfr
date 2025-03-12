##### § 1037.560 Axle efficiency test. #####

This section describes a procedure for mapping axle efficiency through a determination of axle power loss.

(a) You may establish axle power loss maps based on testing any number of axle configurations within an axle family as specified in § 1037.232. You may share data across a family of axle configurations, as long as you test the axle configuration with the lowest efficiency from the axle family; this will generally involve testing the axle with the highest axle ratio. For vehicles with tandem drive axles, always test each drive axle separately. For tandem axles that can be disconnected, test both single-drive and tandem axle configurations. This includes 4×4 axles where one of the axles is disconnectable. Alternatively, you may analytically derive power loss maps for untested configurations within the same axle family as described in paragraph (h) of this section.

(b) Prepare an axle assembly for testing as follows:

(1) Select an axle assembly with less than 500 hours of operation before testing. Assemble the axle in its housing, along with wheel ends and bearings.

(2) If you have a family of axle assemblies with different axle ratios, you may test multiple configurations using a common axle housing, wheel ends, and bearings.

(3) Install the axle assembly on the dynamometer with an input shaft angle perpendicular to the axle.

(i) For axle assemblies with or without a locking main differential, test the axle assembly using one of the following methods:

(A) Lock the main differential and test it with one electric motor on the input shaft and a second electric motor on the output side of the output shaft that has the speed-reduction gear attached to it.

(B) Test with the main differential unlocked and with one electric motor on the input shaft and electric motors on the output sides of each of the output shafts.

(ii) For drive-through tandem-axle setups, lock the longitudinal and inter-wheel differentials.

(4) Add gear oil according to the axle manufacturer's instructions. If the axle manufacturer specifies multiple gear oils, select the one with the highest viscosity at operating temperature. You may use a lower-viscosity gear oil if we approve that as critical emission-related maintenance under § 1037.125. Fill the gear oil to a level that represents in-use operation. You may use an external gear oil conditioning system, as long as it does not affect measured values.

(5) Install equipment for measuring the bulk temperature of the gear oil in the oil sump or a similar location. Report temperature to the nearest 0.1 °C.

(6) Break in the axle assembly using good engineering judgment. Maintain gear oil temperature at or below 100 °C throughout the break-in period.

(7) You may drain the gear oil following the break-in procedure and repeat the filling procedure described in paragraph (b)(4) of this section. We will follow your practice for our testing.

(c) Measure input and output speed and torque as described in 40 CFR 1065.210(b). You must use a speed-measurement system that meets an accuracy of ±0.05% of point. Use torque transducers that meet an accuracy requirement of ±1.0 N·m for unloaded test points and ±0.2% of the maximum tested axle input torque or output torque, respectively, for loaded test points. Calibrate and verify measurement instruments according to 40 CFR part 1065, subpart D. Command speed and torque at a minimum of 10 Hz, and record all data, including bulk oil temperature, at a minimum of 1 Hz mean values.

(d) The test matrix consists of test points representing output torque and wheel speed values meeting the following specifications:

(1) Output torque includes both loaded and unloaded operation. For measurement involving unloaded output torque, also called spin loss testing, the wheel end is not connected to the dynamometer and is left to rotate freely; in this condition the input torque (to maintain constant wheel speed) equals the power loss. Test axles at a range of output torque values, as follows:

(i) 0, 500, 1000, 2000, 3000, and 4000 N·m for single drive axle applications for tractors and for vocational Heavy HDV with a single drive axle.

(ii) 0, 250, 500, 1000, 1500, and 2000 N·m for tractors, for vocational Heavy HDV with tandem drive axles, and for all vocational Light HDV or vocational Medium HDV.

(iii) You may exclude values that exceed your axle's maximum torque rating.

(2) Determine maximum wheel speed corresponding to a vehicle speed of 65 mi/hr based on the smallest tire (as determined using § 1037.520(c)(1)) that will be used with the axle. If you do not know the smallest tire size, you may use a default size of 650 r/mi. Use wheel angular speeds for testing that include 50 r/min and speeds in 100 r/min increments that encompass the maximum wheel speed (150, 250, etc.).

(3) You may test the axle assembly at additional speed and torque setpoints.

(e) Determine axle efficiency using the following procedure:

(1) Maintain ambient temperature between (15 and 35) °C throughout testing. Measure ambient temperature within 1.0 m of the axle assembly. Verify that critical axle settings (such as bearing preload, backlash, and oil sump level) are within specifications before and after testing.

(2) Maintain gear oil temperature at (81 to 83) °C. You may alternatively specify a lower range by shifting both temperatures down by the same amount for any or all test points. We will test your axle assembly using the same temperature range(s) you specify for your testing. If you use interpolation for mapping, use the same temperature range for all test points used in the interpolation. You may use an external gear oil conditioning system, as long as it does not affect measured values.

(3) Use good engineering judgment to warm up the axle assembly by operating it until the gear oil is within the specified temperature range.

(4) Stabilize operation at each point in the test matrix for at least 10 seconds, then measure the input torque, output torque, and wheel angular speed for at least 10 seconds. Record arithmetic mean values for all three parameters over the measurement period. Calculate power loss as described in paragraph (f) of this section based on these values for mean input torque, *T*in, mean output torque, *T*out, and mean wheel angular speed, *f*nwheel, at each test point.

(5) Perform the map sequence described in paragraph (e)(4) of this section three times. Remove torque from the input shaft and allow the axle to come to a full stop before each repeat measurement.

(6) You may need to perform additional testing at a given test point based on a calculation of a confidence interval to represent repeatability at a 95% confidence level for that test point. If the confidence limit is greater than 0.10% for loaded tests or greater than 0.05% for unloaded tests, perform another repeat of measurements at that test point and recalculate the repeatability for the whole set of test results. Continue testing until the confidence interval is at or below the specified values for all test points. Calculate a confidence interval representing the repeatability in establishing a 95% confidence level using the following equation:

![](/graphics/er29jn21.148.gif)Where:σPloss = standard deviation of power loss values at a given torque-speed setting (see 40 CFR 1065.602(c)).*N* = number of repeat tests.*P*max = maximum output torque setting from the test matrix.

Example:

σPloss = 0.1650 kW*N* = 3*P*max = 314.2000 kW![](/graphics/er29jn21.149.gif)*Confidence Interval* = 0.0594%

(f) Calculate the mean power loss, Ploss, at each test point as follows:

(1) Calculate *P*loss for each measurement at each test point as follows:

![](/graphics/er29jn21.150.gif)Where:*T*in = mean input torque from paragraph (e)(4) of this section.*f*nwheel = mean wheel angular speed from paragraph (e)(4) of this section in rad/s.*k*a = drive axle ratio, expressed to at least the nearest 0.001.*T*out = mean output torque from paragraph (e)(4) of this section. Let *T*out = 0 for all unloaded tests.

(2) Calculate Ploss as the mean power loss from all measurements at a given test point.

(3) The following example illustrates a calculation of Ploss:

*T*in,1 = 845.10 N·m*f*nwheel,1 = 100.0 r/min = 10.472 rad/s*k*a = 3.731*T*out,1 = 3000.00 N·m*P*loss,1 = 845.10 · 10.472 · 3.731 − 3000.00 · 10.472*P*loss,1 = 1602.9 W = 1.6029 kW*P*loss,2 = 1601.9 W = 1.6019 kW*P*loss,3 = 1603.9 W = 1.6039 kW![](/graphics/er29jn21.151.gif)

(g) Create a table with the mean power loss, Ploss, corresponding to each test point for input into GEM. Express wheel angular speed in r/min to one decimal place; express output torque in N·m to two decimal places; express power loss in kW to four decimal places.

![](/graphics/er29jn21.279.gif)

(2) Record declared mean power loss values at or above the corresponding value calculated in paragraph (f) of this section. Use good engineering judgment to select values that will be at or above the mean power loss values for your production axles. Vehicle manufacturers will use these declared mean power loss values for certification. For vehicles with tandem drive axles, the GEM input is the sum of the power loss and output torque from the individual axles. For vehicles with a disconnectable axle, GEM uses separate inputs for single and tandem drive axle configurations.

(h) You may analytically derive axle power loss maps for untested configurations within an axle family as follows:

(1) Test at least three axle assemblies within the same family representing at least the smallest axle ratio, the largest axle ratio, and an axle ratio closest to the arithmetic mean from the two other tested axle assemblies. Test each axle assembly as described in this section at the same speed and torque setpoints. Test all axle assemblies using the same gear oil temperature range for each setpoint as described in paragraph (e)(2) of this section.

(2) Perform a second-order least-squares regression between declared power loss and axle ratio using each speed and torque setpoint described in paragraph (d) of this section for your tested axle assemblies. Use the declared power loss values from paragraph (g) of this section; however, for purposes of analytically deriving power loss maps under this paragraph (h), you must select declared values for the largest and smallest axle ratios in the axle family that are adjusted relative to the calculated values for mean power loss by the same multiplier. If the coefficent of the second-order term is negative, include testing from additional axle ratios, or increase your declared power loss for the largest and smallest axle ratios by the same multiplier as needed for the second-order term to become positive.

(3) Determine Ploss of untested axles for each speed and torque setpoint based on a linear relationship between your declared power loss and axle ratio as follows:

(i) Determine the slope of the correlation line by connecting the declared power loss values for the smallest and largest axle ratios.

(ii) Fix the intercept for the correlation line by shifting it upward as needed so all the declared power loss values are on the correlation line or below it. Note that for cases involving three tested axle assemblies, the correlation line will always include the declared power loss for the smallest and largest axle ratio.

(4) Select declared values of Ploss for untested configurations that are at or above the values you determined in paragraph (h)(3) of this section.

[86 FR 34484, June 29, 2021; 87 FR 64864, Oct. 26, 2022, as amended at 88 FR 4652, Jan. 24, 2023; 89 FR 29787, Apr. 22, 2024]