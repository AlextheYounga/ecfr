##### § 1036.520 Determining power and vehicle speed values for powertrain testing. #####

This section describes how to determine the system peak power and continuous rated power of hybrid and nonhybrid powertrain systems and the vehicle speed for carrying out duty-cycle testing under this part and § 1036.545.

(a) You must map or re-map an engine before a test if any of the following apply:

(1) If you have not performed an initial engine map.

(2) If the atmospheric pressure near the engine's air inlet is not within ±5 kPa of the atmospheric pressure recorded at the time of the last engine map.

(3) If the engine or emission-control system has undergone changes that might affect maximum torque performance. This includes changing the configuration of auxiliary work inputs and outputs.

(4) If you capture an incomplete map on your first attempt or you do not complete a map within the specified time tolerance. You may repeat mapping as often as necessary to capture a complete map within the specified time.

(b) Set up the powertrain test according to § 1036.545, with the following exceptions:

(1) Use vehicle parameters, other than power, as specified in § 1036.510(b)(2). Use the applicable automatic transmission as specified in § 1036.540(c)(2).

(2) Select a manufacturer-declared value for *P*contrated to represent system peak power.

(c) Verify the following before the start of each test interval:

(1) The state-of-charge of the rechargeable energy storage system (RESS) must be at or above 90% of the operating range between the minimum and maximum RESS energy levels specified by the manufacturer.

(2) The conditions of all hybrid system components must be within their normal operating range as declared by the manufacturer, including ensuring that no features are actively limiting power or vehicle speed.

(d) Carry out the test as described in this paragraph (d). Warm up the powertrain by operating it. We recommend operating the powertrain at any vehicle speed and road grade that achieves approximately 75% of its expected maximum power. Continue the warm-up until the engine coolant, block, lubricating oil, or head absolute temperature is within ±2% of its mean value for at least 2 min or until the engine thermostat controls engine temperature. Within 90 seconds after concluding the warm-up, operate the powertrain over a continuous trace meeting the following specifications:

(1) Bring the vehicle speed to 0 mi/hr and let the powertrain idle at 0 mi/hr for 50 seconds.

(2) Set maximum driver demand for a full load acceleration at 6.0% road grade with an initial vehicle speed of 0 mi/hr, continuing for 268 seconds. You may increase initial vehicle speed up to 5 mi/hr to minimize clutch slip.

(3) Linearly ramp the grade from 6.0% down to 0.0% over 300 seconds. Stop the test after the acceleration is less than 0.02 m/s2.

(e) Record the powertrain system angular speed and torque values measured at the dynamometer at 100 Hz and use these in conjunction with the vehicle model to calculate vehicle system power, *P*sys,vehicle. Note that *P*sys, is the corresponding value for system power at a location that represents the transmission input shaft on a conventional powertrain.

(f) Calculate the system power, *P*sys, for each data point as follows:

(1) For testing with the speed and torque measurements at the transmission input shaft, *P*sys is equal to the calculated vehicle system power, *P*sys,vehicle, determined in paragraphs (d) and (e) of this section.

(2) For testing with the speed and torque measurements at the axle input shaft or the wheel hubs, determine *P*sys for each data point using the following equation:

![](/graphics/er24ja23.037.gif)Where:*P*sys,vehicle = the calculated vehicle system power for each 100-Hz data point.*ε*trans = the default transmission efficiency = 0.95.*ε*axle = the default axle efficiency. Set this value to 1 for speed and torque measurement at the axle input shaft or to 0.955 at the wheel hubs.Example:*P*sys,vehicle = 317.6 kW![](/graphics/er24ja23.038.gif)*P*sys = 350.1 kW

(g) For each 200-ms (5-Hz) time step, *t,* determine the coefficient of variation (COV) of as follows:

(1) Calculate the standard deviation, *σ*(*t*) of the 20 100-Hz data points in each 5-Hz measurement interval using the following equation:

![](/graphics/er24ja23.039.gif)Where:*N* = the number of data points in each 5-Hz measurement interval = 20.*P*sysi = the 100-Hz values of Psys within each 5-Hz measurement interval.*P*sys*(t)* = the mean power from each 5-Hz measurement interval.

(2) Calculate the 5-Hz values for *COV*(*t*) for each time step, *t,* as follows:

![](/graphics/er24ja23.040.gif)

(h) Determine rated power, *P*rated, as the maximum measured power from the data collected in paragraph (d)(2) of this section where the COV determined in paragraph (g) of this section is less than 2%.

(i) Determine continuous rated power, *P*contrated, as follows:

(1) For nonhybrid powertrains, *P*contrated equals *P*rated.

(2) For hybrid powertrains, *P*contrated is the maximum measured power from the data collected in paragraph (d)(3) of this section where the COV determined in paragraph (g) of this section is less than 2%.

(j) Determine vehicle C speed, *v*refC, as follows:

(1) If the maximum *P*sys(*t*) in the highest gear during the maneuver in paragraph (d)(3) of this section is greater than 0.98·*P*contrated, *v*refC is the average of the minimum and maximum vehicle speeds where *P*sys(*t*) is equal to 0.98·*P*contrated during the maneuver in paragraph (d)(3) where the transmission is in the highest gear, using linear interpolation, as appropriate. If *P*sys(*t*) at the lowest vehicle speed where the transmission is in the highest gear is greater than 0.98·*P*contrated, use the lowest vehicle speed where the transmission is in the highest gear as the minimum vehicle speed input for calculating *v*refC.

(2) Otherwise, *v*refC is the maximum vehicle speed during the maneuver in paragraph (d)(3) of this section where the transmission is in the highest gear.

(3) You may use a declared *v*refC instead of measured *v*refC if the declared *v*refC is within (97.5 to 102.5)% of the corresponding measured value.

(4) Manufacturers may request approval to use an alternative vehicle C speed in place of the measured vehicle C speed determined in this paragraph (j) for series hybrid applications. Approval will be contingent upon justification that the measured vehicle C speed is not representative of the expected real-world cruise speed.

(k) If *P*contrated as determined in paragraph (i) of this section is within ±3% of the manufacturer-declared value for *P*contrated, use the manufacturer-declared value. Otherwise, repeat the procedure in paragraphs (b) through (j) of this section and use *P*contrated from paragraph (i) instead of the manufacturer-declared value.

[88 FR 4487, Jan. 24, 2023, as amended at 89 FR 29747, Apr. 22, 2024]