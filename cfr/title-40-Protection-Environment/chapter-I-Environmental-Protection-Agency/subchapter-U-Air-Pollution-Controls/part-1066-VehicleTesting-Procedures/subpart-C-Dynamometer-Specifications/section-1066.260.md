##### § 1066.260 Parasitic friction compensation evaluation. #####

(a) *Overview.* This section describes how to verify the accuracy of the dynamometer's friction compensation.

(b) *Scope and frequency.* Perform this verification upon initial installation, after major maintenance, and upon failure of a verification in either § 1066.270 or § 1066.275. Note that this procedure relies on proper verification of speed and torque, as described in §§ 1066.235 and 1066.240. You must also first verify the dynamometer's parasitic loss curve as specified in § 1066.255.

(c) *Procedure.* Use the following procedure to verify the accuracy of the dynamometer's friction compensation:

(1) Warm up the dynamometer as specified by the dynamometer manufacturer.

(2) Perform a torque verification as specified by the dynamometer manufacturer. For torque verifications relying on shunt procedures, if the results do not conform to specifications, recalibrate the dynamometer using NIST-traceable standards as appropriate until the dynamometer passes the torque verification. Do not change the dynamometer's base inertia to pass the torque verification.

(3) Set the dynamometer inertia to the base inertia with the road-load coefficients A, B, and C set to 0. Set the dynamometer to speed-control mode with a target speed of 50 mi/hr or a higher speed recommended by the dynamometer manufacturer. Once the speed stabilizes at the target speed, switch the dynamometer from speed-control to torque-control and allow the roll to coast for 60 seconds. Record the initial and final speeds and the corresponding start and stop times. If friction compensation is executed perfectly, there will be no change in speed during the measurement interval.

(4) Calculate the power equivalent of friction compensation error, *FC*error, using the following equation:

![](/graphics/er29jn21.265.gif)Where:*I* = dynamometer inertia setting.*t* = duration of the measurement interval, accurate to at least 0.01 s.*v*init = the roll speed corresponding to the start of the measurement interval, accurate to at least 0.05 mi/hr.*v*final = the roll speed corresponding to the end of the measurement interval, accurate to at least 0.05 mi/hr.Example:*I* = 2000 lbm = 62.16 lbf·s2/ft*t* = 60.0 s*v*init = 9.2 mi/hr = 13.5 ft/s*v*final = 10.0 mi/hr = 14.7 ft/s![](/graphics/er29jn21.266.gif)*FC*error = -17.5 ft·lbf/s =−0.032 hp

(5) The friction compensation error may not exceed ±0.15 hp for dynamometers capable of testing vehicles at or below 20,000 pounds GVWR, or ±0.6 hp for dynamometers not capable of testing vehicles at or below 20,000 pounds GVWR.

[79 FR 23823, Apr. 28, 2014, as amended at 81 FR 74200, Oct. 25, 2016; 86 FR 34581, June 29, 2021]