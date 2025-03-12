##### § 1066.265 Acceleration and deceleration verification. #####

(a) *Overview.* This section describes how to verify the dynamometer's ability to achieve targeted acceleration and deceleration rates. Paragraph (c) of this section describes how this verification applies when the dynamometer is programmed directly for a specific acceleration or deceleration rate. Paragraph (d) of this section describes how this verification applies when the dynamometer is programmed with a calculated force to achieve a targeted acceleration or deceleration rate.

(b) *Scope and frequency.* Perform this verification or an equivalent procedure upon initial installation and after major maintenance that could affect acceleration and deceleration accuracy. Note that this procedure relies on proper verification of speed as described in § 1066.235.

(c) *Verification of acceleration and deceleration rates.* Activate the dynamometer's function generator for measuring roll revolution frequency. If the dynamometer has no such function generator, set up a properly calibrated external function generator consistent with the verification described in this paragraph (c). Use the function generator to determine actual acceleration and deceleration rates as the dynamometer traverses speeds between 10 and 40 mi/hr at various nominal acceleration and deceleration rates. Verify the dynamometer's acceleration and deceleration rates as follows:

(1) Set up start and stop frequencies specific to your dynamometer by identifying the roll-revolution frequency, *f*, in revolutions per second (or Hz) corresponding to 10 mi/hr and 40 mi/hr vehicle speeds, accurate to at least four significant figures, using the following equation:

![](/graphics/er25oc16.242.gif)Where:*v* = the target roll speed, in inches per second (corresponding to drive speeds of 10 mi/hr or 40 mi/hr).*n* = the number of pulses from the dynamometer's roll-speed sensor per roll revolution.*d*roll = roll diameter, in inches.

(2) Program the dynamometer to accelerate the roll at a nominal rate of 1 mi/hr/s from 10 mi/hr to 40 mi/hr. Measure the elapsed time to reach the target speed, to the nearest 0.01 s. Repeat this measurement for a total of five runs. Determine the actual acceleration rate for each run, *a*act, using the following equation:

![](/graphics/er25oc16.243.gif)Where:*a*act = acceleration rate (decelerations have negative values).*v*final = the target value for the final roll speed.*v*init = the setpoint value for the initial roll speed.*t* = time to accelerate from *v*init to *v*final.Example:*v*final = 40 mi/hr*v*init = 10 mi/hr*t* = 30.003 s![](/graphics/er25oc16.244.gif)*a*act = 0.999 (mi/hr)/s

(3) Program the dynamometer to decelerate the roll at a nominal rate of 1 (mi/hr)/s from 40 mi/hr to 10 mi/hr. Measure the elapsed time to reach the target speed, to the nearest 0.01 s. Repeat this measurement for a total of five runs. Determine the actual acceleration rate, *a*act, using Eq. 1066.265-2.

(4) Repeat the steps in paragraphs (c)(2) and (3) of this section for additional acceleration and deceleration rates in 1 (mi/hr)/s increments up to and including one increment above the maximum acceleration rate expected during testing. Average the five repeat runs to calculate a mean acceleration rate, aact, at each setting.

(5) Compare each mean acceleration rate, aact, to the corresponding nominal acceleration rate, *a*ref, to determine values for acceleration error, *a*error, using the following equation:

![](/graphics/er25oc16.245.gif)Example:aact = 0.999 (mi/hr)/s*a*ref = 1 (mi/hr)/s![](/graphics/er25oc16.246.gif)*a*error = −0.100%

(d) *Verification of forces for controlling acceleration and deceleration.* Program the dynamometer with a calculated force value and determine actual acceleration and deceleration rates as the dynamometer traverses speeds between 10 and 40 mi/hr at various nominal acceleration and deceleration rates. Verify the dynamometer's ability to achieve certain acceleration and deceleration rates with a given force as follows:

(1) Calculate the force setting, *F*, using the following equation:

![](/graphics/er29jn21.267.gif)Where:*I*b = the dynamometer manufacturer's stated base inertia, in lbf·s2/ft.*a* = nominal acceleration rate, in ft/s2.Example:*I*b = 2967 lbm = 92.217 lbf·s2/ft*a* = 1 (mi/hr)/s = 1.4667 ft/s2*F* = 92.217·|1.4667|*F* = 135.25 lbf

(2) Set the dynamometer to road-load mode and program it with a calculated force to accelerate the roll at a nominal rate of 1 (mi/hr)/s from 10 mi/hr to 40 mi/hr. Measure the elapsed time to reach the target speed, to the nearest 0.01 s. Repeat this measurement for a total of five runs. Determine the actual acceleration rate, *a*act, for each run using Eq. 1066.265-2. Repeat this step to determine measured “negative acceleration” rates using a calculated force to decelerate the roll at a nominal rate of 1 (mi/hr)/s from 40 mi/hr to 10 mi/hr. Average the five repeat runs to calculate a mean acceleration rate, aact, at each setting.

(3) Repeat the steps in paragraph (d)(2) of this section for additional acceleration and deceleration rates as specified in paragraph (c)(4) of this section.

(4) Compare each mean acceleration rate, aact, to the corresponding nominal acceleration rate, aref, to determine values for acceleration error, aerror, using Eq. 1066.265-3.

(e) *Performance evaluation.* The acceleration error from paragraphs (c)(5) and (d)(4) of this section may not exceed ±1.0%.

[79 FR 23823, Apr. 28, 2014, as amended at 81 FR 74200, Oct. 25, 2016; 86 FR 34582, June 29, 2021]