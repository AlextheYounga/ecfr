##### § 1037.534 Constant-speed procedure for calculating drag area (CdA). #####

This section describes an alternate method for calculating drag area, *C*dA, for tractors using constant-speed aerodynamic drag testing.

(a) *Test track.* Select a test track that meets the specifications described in § 1037.528(c)(3).

(b) *Ambient conditions.* At least two tests are required. For one of the tests, ambient conditions must remain within the specifications described in § 1037.528(c) throughout the preconditioning and measurement procedure. The other tests must also meet those specifications except for the wind conditions. The wind conditions must be such that 80 percent of the values of yaw angle, ψair, from the 50 mi/hr and 70 mi/hr test segments are between 4° and 10° or between −4° and −10°.

(c) *Vehicle preparation.* Perform testing with a tractor-trailer combination using the manufacturer's tractor and a standard trailer. Prepare the tractor-trailer combination for testing as described in § 1037.528(b). Install measurement instruments meeting the requirements of 40 CFR part 1065, subpart C, that have been calibrated as described in 40 CFR part 1065, subpart D, as follows:

(1) Measure torque at each of the drive wheels using a hub torque meter or a rim torque meter. If testing a tractor with two drive axles, you may disconnect one of the drive axles from receiving torque from the driveshaft, in which case you would measure torque at only the wheels that receive torque from the driveshaft. Set up instruments to read engine speed for calculating angular speed at the point of the torque measurements, or install instruments for measuring the angular speed of the wheels directly.

(2) Install instrumentation to measure vehicle speed at 10 Hz, with an accuracy and resolution of 0.1 mi/hr. Also install instrumentation for reading engine speed from the engine's onboard computer.

(3) Mount an anemometer on the trailer as described in § 1037.528(f).

(4) Fill the vehicle's fuel tanks so they are at maximum capacity at the start of the measurement procedure.

(5) Measure the weight over each axle to the nearest 20 kg, with a full fuel tank, including the driver and any passengers that will be in the vehicle during the test.

(d) *Measurement procedure.* The measurement sequence consists of vehicle preconditioning followed by stabilization and measurement over five consecutive constant-speed test segments with three different speed setpoints (10, 50, and 70 mi/hr). Each test segment is divided into smaller increments for data analysis.

(1) Precondition the vehicle and zero the torque meters as follows:

(i) If you are using rim torque meters, zero the torque meters by lifting each instrumented axle and recording torque signals for at least 30 seconds, and then drive the vehicle at 50 mi/hr for at least 30 minutes.

(ii) If you are using any other kind of torque meter, drive the vehicle at 50 mi/hr for at least 30 minutes, and then allow the vehicle to coast down from full speed to a complete standstill while the clutch is disengaged or the transmission is in neutral, without braking. Zero the torque meters within 60 seconds after the vehicle stops moving by recording the torque signals for at least 30 seconds, and directly resume vehicle preconditioning at 50 mi/hr for at least 1.25 mi.

(iii) You may calibrate instruments during the preconditioning drive.

(2) Perform testing as described in paragraph (d)(3) of this section over a sequence of test segments at constant vehicle speed as follows:

(i) (300 ±30) seconds in each direction at 10 mi/hr.

(ii) (450 ±30) seconds in each direction at 70 mi/hr.

(iii) (450 ±30) seconds in each direction at 50 mi/hr.

(iv) (450 ±30) seconds in each direction at 70 mi/hr.

(v) (450 ±30) seconds in each direction at 50 mi/hr.

(vi) (300 ±30) seconds in each direction at 10 mi/hr.

(3) When the vehicle preconditioning described in paragraph (d)(1) of this section is complete, stabilize the vehicle at the specified speed for at least 200 meters and start taking measurements. The test segment starts when you start taking measurements for all parameters.

(4) During the test segment, continue to operate the vehicle at the speed setpoint, maintaining constant speed and torque within the ranges specified in paragraph (e) of this section. Drive the vehicle straight with minimal steering; do not change gears. Perform measurements as follows during the test segment:

(i) Measure the angular speed of the driveshaft, axle, or wheel where the torque is measured, or calculate it from engine speed in conjunction with gear and axle ratios, as applicable.

(ii) Measure vehicle speed in conjunction with time-of-day data.

(iii) Measure ambient conditions, air speed, and air direction as described in § 1037.528(e) and (f). Correct air speed and air direction as described in paragraphs (f)(1) and (2) of this section.

(5) You may divide a test segment into multiple passes by suspending and resuming measurements. Stabilize vehicle speed before resuming measurements for each pass as described in paragraph (d)(3) of this section. Analyze the data from multiple passes by combining them into a single sequence of measurements for each test segment.

(6) Divide measured values into even 10 second increments. If the last increment for each test segment is less than 10 seconds, disregard measured values from that increment for all calculations under this section.

(e) *Validation criteria.* Analyze measurements to confirm that the test is valid. Analyze vehicle speed and drive torque by calculating the mean speed and torque values for each successive 1 second increment, for each successive 10 second increment, and for each test segment. The test is valid if the data conform to all the following specifications:

(1) *Vehicle speed.* The mean vehicle speed for the test segment must be within 1.00 mi/hr of the speed setpoint. In addition, for testing at 50 mi/hr and 70 mi/hr, all ten of the 1 second mean vehicle speeds used to calculate a corresponding 10 second mean vehicle speed must be within ±0.2 mi/hr of that 10 second mean vehicle speed. Perform the same data analysis for testing at 10 mi/hr, but apply a validation threshold of ±0.1 mi/hr.

(2) *Drive torque.* All ten of the 1 second mean torque values used to calculate a corresponding 10 second mean torque value must be within ±50% of that 10 second mean torque value.

(3) *Torque drift.* Torque meter drift may not exceed ±1%. Determine torque meter drift by repeating the procedure described in paragraph (d)(1) of this section after testing is complete, except that driving the vehicle is necessary only to get the vehicle up to 50 mi/hr as part of coasting to standstill.

(f) *Calculations.* Analyze measured data for each time segment after time-aligning all the data. Use the following calculations to determine *C*d*A*:

(1) *Onboard air speed.* Correct onboard anemometer measurements for air speed using onboard measurements and measured ambient conditions as described in § 1037.528(f), except that you must first divide the test segment into consecutive 10 second increments. Disregard data from the final increment of the test segment if it is less than 10 seconds. This analysis results in the following equation for correcting air speed measurements:

![](/graphics/er25oc16.116.gif)

(2) *Yaw angle.* Correct the onboard anemometer measurements for air direction for each test segment as follows:

(i) Calculate arithmetic mean values for vehicle speed, *v*, wind speed, *w*, and wind direction, *ϕ*w, over each 10 second increment for each test segment. Disregard data from the final increment of the test segment if it is less than 10 seconds.

(ii) Calculate the theoretical air direction, ψair,th, for each 10 second increment using the following equation:

![](/graphics/er25oc16.117.gif)Where:*ϕ*veh = the vehicle direction, as described in § 1037.528(f)(2).Example:*w* = 7.1 mi/hr*v* = 69.9 mi/hr*ϕ*w = 47.0°*ϕ*veh = 0°![](/graphics/er25oc16.118.gif)ψair,th = 3.97°

(iii) Perform a linear regression using paired values of ψair,th and measured air direction, ψair,meas, from each 10 second increment for all 50 mi/hr and 70 mi/hr test segments to determine the air-direction correction coefficients, b0 and b1, based on the following equation:

![](/graphics/er25oc16.119.gif)

(iv) For all 50 mi/hr and 70 mi/hr test segments, correct each measured value of air direction using the following equation:

![](/graphics/er25oc16.120.gif)

(3) *Road load force.* (i) Average the sum of the corrected torques, the average of the wheel speed measurements, and the vehicle speed over every 10 second increment to determine, *T*total, *f*nwheel, and *v*.

(ii) Calculate a mean road load force, *F*RL[speed], for each 10 second increment using the following equation:

![](/graphics/er25oc16.121.gif)Where:*T*total = mean of all corrected torques at a point in time.*v* = mean vehicle speed.*f*nwheel = mean wheel speed.*M* = the measured vehicle mass.*a*g = acceleration of Earth's gravity, as described in 40 CFR 1065.630.*h*inc = elevation at the start or end of each 10 second increment expressed to at least two decimal places.*D*inc = distance traveled on the road surface from a fixed reference location along the road to the start or end of each 10 second increment, expressed to at least one decimal place.Example:*T*total = 2264.9 N·m*v* = 31.6 m/s*f*nwheel =598.0 r/min*M* = 16508 kg*a*g = 9.8061 m/s2*h*inc,start = 0.044 m*h*inc,end = 0.574 m*D*inc,start = 215.4 m*D*inc,end = 697.8 m![](/graphics/er25oc16.122.gif)*F*RL70 = 4310.6 N

(4) *Determination of drag area.* Calculate a vehicle's drag area as follows:

(i) Calculate the mean road load force from all 10 second increments from the 10 mi/hr test segments from the test that was within the wind limits specified in § 1037.528(c), *F*RL10,test. This value represents the mechanical drag force acting on the vehicle.

(ii) Calculate the mean aerodynamic force for each 10 second increment, *F*aero[speed], from the 50 mi/hr and 70 mi/hr test segments by subtracting *F*RL10,test from *F*RL[speed].

(iii) Average the corrected air speed and corrected yaw angle over every 10 second segment from the 50 mi/hr and 70 mi/hr test segments to determine *v*air and ψair.

(iv) Calculate *C*d*A* for each 10 second increment from the 50 mi/hr and 70 mi/hr test segments using the following equation:

![](/graphics/er29jn21.126.gif)Where:*C*d*A*i[speed] = the mean drag area for each 10 second increment, *i.*Faero[speed] = mean aerodynamic force over a given 10 second increment = FRL[speed] −FRL10,test.Vair[speed] = mean aerodynamic force over a given 10 second increment.*R* = specific gas constant = 287.058 J/(kg·K).T = mean air temperature.pact = mean absolute air pressure.Example:FRL70 = 4310.6 NFRL10,test = 900.1 NFaero70 = 4310.6−900.1 = 3410.5 NV2air70 = 1089.5 m2/s2*R* = 287.058 J/(kg·K)T = 293.68 Kpact = 101300 Pa![](/graphics/er29jn21.127.gif)*C*d*A*i70 = 5.210 m2

(v) Plot all *C*d*A* values from the 50 mi/hr and 70 mi/hr test segments against the corresponding values for corrected yaw angle for each 10 second increment. Create a regression based on a fourth-order polynomial regression equation of the following form:

![](/graphics/er25oc16.125.gif)

(vi) Determine *C*d*A*wa-alt as the average of *C*d*A* values at 4.5° and −4.5° by applying Eq. 1037.534-7 at those angles.

(g) *Documentation.* Keep the following records related to the constant-speed procedure for calculating drag area:

(1) The measurement data for calculating *C*d*A* as described in this section.

(2) A general description and pictures of the vehicle tested.

(3) The vehicle's maximum height and width.

(4) The measured vehicle mass.

(5) Mileage at the start of the first test segment and at the end of the last test segment.

(6) The date of the test, the starting time for the first test segment, and the ending time for the last test segment.

(7) The transmission gear used for each test segment.

(8) The data describing how the test was valid relative to the specifications and criteria described in paragraphs (b) and (e) of this section.

(9) A description of any unusual events, such as a vehicle passing the test vehicle, or any technical or human errors that may have affected the *C*d*A* determination without invalidating the test.

[81 FR 74048, Oct. 25, 2016, as amended at 86 FR 34476, June 29, 2021; 88 FR 4642, Jan. 24, 2023; 89 FR 29785, Apr. 22, 2024]