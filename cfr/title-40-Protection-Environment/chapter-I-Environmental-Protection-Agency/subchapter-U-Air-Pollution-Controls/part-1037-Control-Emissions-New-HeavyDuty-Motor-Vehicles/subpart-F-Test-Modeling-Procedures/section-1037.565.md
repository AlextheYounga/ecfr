##### § 1037.565 Transmission efficiency test. #####

This section describes a procedure for mapping transmission efficiency through a determination of transmission power loss.

(a) You may establish transmission power loss maps based on testing any number of transmission configurations within a transmission family as specified in § 1037.232. You may share data across any configurations within the family, as long as you test the transmission configuration with the lowest efficiency from the transmission family. Alternatively, you may ask us to approve analytically derived power loss maps for untested configurations within the same transmission family (see § 1037.235(h)).

(b) Prepare a transmission for testing as follows:

(1) Select a transmission with less than 500 hours of operation before testing.

(2) Mount the transmission to the dynamometer such that the geared shaft in the transmission is aligned with the input shaft from the dynamometer.

(3) Add transmission oil according to the transmission manufacturer's instructions. If the transmission manufacturer specifies multiple transmission oils, select the one with the highest viscosity at operating temperature. You may use a lower-viscosity transmission oil if we approve it as critical emission-related maintenance under § 1037.125. Fill the transmission oil to a level that represents in-use operation. You may use an external transmission oil conditioning system, as long as it does not affect measured values.

(4) Include any internal and external pumps for hydraulic fluid and lubricating oil in the test. Determine the work required to drive an external pump according to 40 CFR 1065.210.

(5) Install equipment for measuring the bulk temperature of the transmission oil in the oil sump or a similar location.

(6) If the transmission is equipped with a torque converter, lock it for all testing performed in this section.

(7) Break in the transmission using good engineering judgment. Maintain transmission oil temperature at (87 to 93) °C for automatic transmissions and transmissions having more than two friction clutches, and at (77 to 83) °C for all other transmissions. You may ask us to approve a different range of transmission oil temperatures if you have data showing that it better represents in-use operation.

(c) Measure input and output shaft speed and torque as described in 40 CFR 1065.210(b). You must use a speed measurement system that meets an accuracy of ±0.05% of point. Accuracy requirements for torque transducers depend on the highest loaded transmission input and output torque as described in paragraph (d)(2) of this section. Use torque transducers for torque input measurements that meet an accuracy requirement of ±0.2% of the highest loaded transmission input for loaded test points and ±0.1% of the highest loaded transmission input torque for unloaded test points. For torque output measurements, torque transducers must meet an accuracy requirement of ±0.2% of the highest loaded transmission output torque for each gear ratio. Calibrate and verify measurement instruments according to 40 CFR part 1065, subpart D. Command speed and torque at a minimum of 10 Hz, and record all data, including bulk oil temperature, at a minimum of 1 Hz mean values.

(d) Test the transmission at input shaft speeds and torque setpoints as described in this paragraph (d). You may exclude lower gears from testing; however, you must test all the gears above the highest excluded gear. GEM will use default values for any untested gears. The test matrix consists of test points representing transmission input shaft speeds and torque setpoints meeting the following specifications for each tested gear:

(1) Test at the following transmission input shaft speeds:

(i) 600.0 r/min or transmission input shaft speed when paired with the engine operating at idle.

(ii) The transmission's maximum rated input shaft speed. You may alternatively select a value representing the highest expected in-use transmission input shaft speed.

(iii) Three equally spaced intermediate speeds. The intermediate speed points may be adjusted to the nearest 50 or 100 r/min. You may test any number of additional speed setpoints to improve accuracy.

(2) Test at certain transmission input torque setpoints as follows:

(i) Include one unloaded (zero-torque) setpoint.

(ii) Include one loaded torque setpoint between 75% and 105% of the transmission's maximum rated input shaft torque. However, you may use a lower torque setpoint as needed to avoid exceeding dynamometer torque limits, as long as testing accurately represents in-use performance. If your loaded torque setpoint is below 75% of the transmission's maximum rated input shaft torque, you must demonstrate that the sum of time for all gears where demanded engine torque is between your maximum torque setpoint and 75% of the transmission's maximum rated input shaft torque is no more than 10% of the time for each vehicle drive cycle specified in subpart F of this part. This demonstration must be made available upon request.

(iii) You may test at any number of additional torque setpoints to improve accuracy.

(iv) Note that GEM calculates power loss between tested or default values by linear interpolation, except that GEM may extrapolate outside of measured values to account for testing at torque setpoints below 75% as specified in paragraph (d)(2)(ii) of this section.

(3) In the case of transmissions that automatically go into neutral when the vehicle is stopped, also perform tests at 600 r/min and 800 r/min with the transmission in neutral and the transmission output fixed at zero speed.

(e) Determine transmission efficiency using the following procedure:

(1) Maintain ambient temperature between (15 and 35) °C throughout testing. Measure ambient temperature within 1.0 m of the transmission.

(2) Maintain transmission oil temperature as described in paragraph (b)(7) of this section.

(3) Use good engineering judgment to warm up the transmission according to the transmission manufacturer's specifications.

(4) Perform unloaded transmission tests by disconnecting the transmission output shaft from the dynamometer and letting it rotate freely. If the transmission adjusts pump pressure based on whether the vehicle is moving or stopped, set up the transmission for unloaded tests to operate as if the vehicle is moving.

(5) For transmissions that have multiple configurations for a given gear ratio, such as dual-clutch transmissions that can pre-select an upshift or downshift, set the transmission to operate in the configuration with the greatest power loss. Alternatively, test in each configuration and use good engineering judgment to calculate a weighted power loss for each test point under this section based on field data that characterizes the degree of in-use operation in each configuration.

(6) For a selected gear, operate the transmission at one of the test points from paragraph (d) of this section for at least 10 seconds. Measure the speed and torque of the input and output shafts for at least 10 seconds. You may omit measurement of output shaft speeds if your transmission is configured to not allow slip. Calculate arithmetic mean values for mean input shaft torque, *T*in, mean output shaft torque, *T*out, mean input shaft speed, *f*nin, and mean output shaft speed, *f*nout, for each point in the test matrix for each test. Repeat this stabilization, measurement, and calculation for the other speed and torque setpoints from the test matrix for the selected gear in any sequence. Calculate power loss as described in paragraph (f) of this section based on mean speed and torque values at each test point.

(7) Repeat the procedure described in paragraph (e)(6) of this section for all gears, or for all gears down to a selected gear. This section refers to an “operating condition” to represent operation at a test point in a specific gear.

(8) Perform the test sequence described in paragraphs (e)(6) and (7) of this section three times. You may do this repeat testing at any given test point before you perform measurements for the whole test matrix. Remove torque from the transmission input shaft and bring the transmission to a complete stop before each repeat measurement.

(9) You may need to perform additional testing at a given operating condition based on a calculation of a confidence interval to represent repeatability at a 95% confidence level at that operating condition. If the confidence interval is greater than 0.10% for loaded tests or greater than 0.05% for unloaded tests, perform another measurement at that operating condition and recalculate the repeatability for the whole set of test results. Continue testing until the confidence interval is at or below the specified values for all operating conditions. As an alternative, for any operating condition that does not meet this repeatability criterion, you may determine a maximum power loss instead of calculating a mean power loss as described in paragraph (g) of this section. Calculate a confidence interval representing the repeatability in establishing a 95% confidence level using the following equation:

![](/graphics/er23se21.000.gif)Where:σPloss = standard deviation of power loss values at a given operating condition (see 40 CFR 1065.602(c)).*N* = number of repeat tests for an operating condition.*P*rated = the transmission's rated input power for a given gear. For testing in neutral, use the value of *P*rated for the top gear.Example:σPloss = 0.1200 kW*N* = 3*P*rated = 314.2000 kW![](/graphics/er23se21.001.gif)*Confidence Interval* = 0.0432%

(f) Calculate the mean power loss, Ploss, at each operating condition as follows:

(1) Calculate *P*loss for each measurement at each operating condition as follows:

![](/graphics/er23se21.008.gif)Where:*T*in = mean input shaft torque from paragraph (e)(6) of this section.*f*nin = mean input shaft speed from paragraph (e)(6) of this section in rad/s.*T*out = mean output shaft torque from paragraph (e)(6) of this section. Let *T*out = 0 for all unloaded tests.*f*nout = mean output shaft speed from paragraph (e)(6) of this section in rad/s. Let fnout = 0 for all tests with the transmission in neutral. See paragraph (f)(2) of this section for calculating fnout as a function of fnin instead of measuring *f*nout.

(2) For transmissions that are configured to not allow slip, you may calculate fnout based on the gear ratio using the following equation:

![](/graphics/er23se21.002.gif)Where:*k*g = transmission gear ratio, expressed to at least the nearest 0.001.

(3) Calculate Ploss as the mean power loss from all measurements at a given operating condition.

(4) The following example illustrates a calculation of Ploss:

*T*in,1 = 1000.0 N·m*f*nin,1 = 1000 r/min = 104.72 rad/sec*T*out,1 = 2654.5 N·m*f*nout,1 = 361.27 r/min = 37.832 rad/s*P*loss,1 = 1000.0·104.72−2654.5·37.832*P*loss,1 = 4295 W = 4.295 kW*P*loss,2 = 4285 W = 4.285 kW*P*loss,3 = 4292 W = 4.292 kW![](/graphics/er23se21.003.gif)

(g) Create a table with the mean power loss, Ploss, corresponding to each operating condition for input into GEM. Also include power loss in neutral for each tested engine's speed, if applicable. Express transmission input speed in r/min to one decimal place; express input torque in N·m to two decimal places; express power loss in kW to four decimal places. Record the following values:

![](/graphics/er23se21.009.gif)

(2) For any operating condition not meeting the repeatability criterion in paragraph (e)(9) of this section, record the maximum value of *P*loss for that operating condition along with the corresponding values of *T*in and *f*nin.

(h) Record declared power loss values at or above the corresponding value calculated in paragraph (f) of this section. Use good engineering judgment to select values that will be at or above the mean power loss values for your production transmissions. Vehicle manufacturers will use these declared mean power loss values for certification.

[86 FR 34486, June 29, 2021; 86 FR 52833, Sept. 23, 2021; 87 FR 64864, Oct. 26, 2022]