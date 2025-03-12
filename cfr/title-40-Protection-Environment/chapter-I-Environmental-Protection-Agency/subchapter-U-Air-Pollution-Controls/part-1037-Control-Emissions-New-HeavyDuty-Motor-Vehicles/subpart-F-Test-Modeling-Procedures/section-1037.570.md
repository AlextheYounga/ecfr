##### § 1037.570 Procedures to characterize torque converters. #####

GEM includes input values related to torque converters. This section describes a procedure for mapping a torque converter's capacity factors and torque ratios over a range of operating conditions. You may ask us to approve analytically derived input values based on this testing for additional untested configurations as described in § 1037.235(h).

(a) Prepare a torque converter for testing as follows:

(1) Select a torque converter with less than 500 hours of operation before the start of testing.

(2) If the torque converter has a locking feature, unlock it for all testing performed under this section. If the torque converter has a slipping lockup clutch, you may ask us to approve a different strategy based on data showing that it represents better in-use operation.

(3) Mount the torque converter with a transmission to the dynamometer in series or parallel arrangement or mount the torque converter without a transmission to represent a series configuration.

(4) Add transmission oil according to the torque converter manufacturer's instructions, with the following additional specifications:

(i) If the torque converter manufacturer specifies multiple transmission oils, select the one with the highest viscosity at operating temperature. You may use a lower-viscosity transmission oil if we approve that as critical emission-related maintenance under § 1037.125.

(ii) Fill the transmission oil to a level that represents in-use operation. If you are testing the torque converter without the transmission, keep output pressure and the flow rate of transmission oil into the torque converter within the torque converter manufacturer's limits.

(iii) You may use an external transmission oil conditioning system, as long as it does not affect measured values.

(5) Install equipment for measuring the bulk temperature of the transmission oil in the oil sump or a similar location and at the torque converter inlet. If the torque converter is tested without a transmission, measure the oil temperature at the torque converter inlet.

(6) Break in the torque converter and transmission (if applicable) using good engineering judgment. Maintain transmission oil temperature at (87 to 93) °C. You may ask us to approve a different range of transmission oil temperatures if you have data showing that it better represents in-use operation.

(b) Measure pump and turbine shaft speed and torque as described in 40 CFR 1065.210(b). You must use a speed measurement system that meets an accuracy of ±0.1% of point or ±1 r/min, whichever is greater. Use torque transducers that meet an accuracy of ±1.0% of the torque converter's maximum rated input and output torque, respectively. Calibrate and verify measurement instruments according to 40 CFR part 1065, subpart D. Command speed and torque at a minimum of 10 Hz. Record all speed and torque data at a minimum of 1 Hz mean values. Note that this section relies on the convention of describing the input shaft as the pump and the output shaft as the turbine shaft.

(c) Determine torque converter characteristics based on a test matrix using either constant input speed or constant input torque as follows:

(1) *Constant input speed.* Test at constant input speed as follows:

(i) Select a fixed pump speed, ƒnpum, between (1000 and 2000) r/min.

(ii) Test the torque converter at multiple speed ratios, *v,* in the range of *v* = 0.00 to *v* = 0.95. Use a step width of 0.10 for the range of *v* = 0.00 to 0.60 and 0.05 for the range of *v* = 0.60 to 0.95. Calculate speed ratio, *v,* as turbine shaft speed divided by pump speed.

(2) *Constant input torque.* Test at constant input torque as follows:

(i) Set the pump torque, *T*pum, to a fixed positive value at ƒnpum = 1000 r/min with the torque converter's turbine shaft locked in a non-rotating state (*i.e.,* turbine's speed, *n*tur, = 0 r/min).

(ii) Test the torque converter at multiple speed ratios, *v,* in the range of *v* = 0.00 up to a value of ƒntur that covers the usable range of *v*. Use a step width of 0.10 for the range of *v* = 0.00 to 0.60 and 0.05 for the range of *v* = 0.60 to 0.95.

(3) You may limit the maximum speed ratio to a value below 0.95 if you have data showing this better represents in-use operation. You must use the step widths defined in paragraph (c)(1) or (2) of this section and include the upper limit as a test point. If you choose a value less than 0.60, you must test at least seven evenly distributed points between *v* = 0 and your new upper speed ratio.

(d) Characterize the torque converter using the following procedure:

(1) Maintain ambient temperature between (15 and 35) °C throughout testing. Measure ambient temperature within 1.0 m of the torque converter.

(2) Maintain transmission oil temperature as described in paragraph (a)(6) of this section. You may use an external transmission oil conditioning system, as long as it does not affect measured values.

(3) Use good engineering judgment to warm up the torque converter according to the torque converter manufacturer's specifications.

(4) Test the torque converter at constant input speed or constant input torque as described in paragraph (c) of this section. Operate the torque converter at *v* = 0.00 for (5 to 60) seconds, then measure pump torque, turbine shaft torque, angular pump speed, angular turbine shaft speed, and the transmission oil temperature at the torque converter inlet for (5 to 15) seconds. Calculate arithmetic mean values for pump torque, *T*pum, turbine shaft torque, *T*tur, angular pump speed, *f*npum, and angular turbine shaft speed, *f*ntur, over the measurement period. Repeat this stabilization, measurement, and calculation for the other speed ratios from the test matrix in order of increasing speed ratio. Adjust the speed ratio by increasing the angular turbine shaft speed.

(5) Complete a test run by performing the test sequence described in paragraph (d)(4) of this section two times.

(6) Invalidate the test run if the difference between the pair of mean torque values for the repeat tests at any test point differ by more than ±1 N·m or by more than ±5% of the average of those two values. This paragraph (d)(6) applies separately for mean pump torque and mean turbine shaft torque at each test point.

(7) Invalidate the test run if any calculated value for mean angular pump speed does not stay within ±5 r/min of the speed setpoint or if any calculated value for mean pump torque does not stay within ±5 N·m of the torque setpoint.

(e) Calculate the mean torque ratio, l, at each tested speed ratio, *v*, as follows:

(1) Calculate µ at each tested speed ratio as follows:

![](/graphics/er23se21.004.gif)Where:*T*tur = mean turbine shaft torque from paragraph (d)(4) of this section.*T*pum = mean pump torque from paragraph (d)(4) of this section.

(2) Calculate l as the average of the two values of µ at each tested speed ratio.

(3) The following example illustrates a calculation of l:

*T*tur,v=0,1 = 332.4 N·m*T*pum,v=0,1 = 150.8 N·m*T*tur,v=0,2 = 333.6 N·m*T*pum,v=0,2 = 150.3 N·m![](/graphics/er23se21.005.gif)

(f) Calculate the mean capacity factor, k, at each tested speed ratio, n, as follows:

(1) Calculate K at each tested speed ratio as follows:

![](/graphics/er23se21.006.gif)Where:*f*npum = mean angular pump speed from paragraph (d)(4) of this section.*T*pum = mean pump torque from paragraph (d)(4) of this section.

(2) Calculate k as the average of the two values of K at each tested speed ratio.

(3) The following example illustrates a calculation of k:

*f*npum,v=0,1 = *f*npum,v=0,2 = 1000.0 r/min*T*pum,v=0,1 = 150.8 N·m![](/graphics/er23se21.007.gif)

(g) Create a table of GEM inputs showing l and k at each tested speed ratio, n. Express l to two decimal places; express k to one decimal place; express n to two decimal places.

[86 FR 34488, June 29, 2021; 86 FR 52835, Sept. 23, 2021; 87 FR 64864, Oct. 28, 2022]