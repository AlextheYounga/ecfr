##### § 1066.250 Base inertia verification. #####

(a) *Overview.* This section describes how to verify the dynamometer's base inertia.

(b) *Scope and frequency.* Perform this verification upon initial installation and after major maintenance, such as maintenance that could affect roll inertia.

(c) *Procedure.* Verify the base inertia using the following procedure:

(1) Warm up the dynamometer according to the dynamometer manufacturer's instructions. Set the dynamometer's road-load inertia to zero, turning off any electrical simulation of road load and inertia so that the base inertia of the dynamometer is the only inertia present. Motor the rolls to 5 mi/hr. Apply a constant force to accelerate the roll at a nominal rate of 1 (mi/hr)/s. Measure the elapsed time to accelerate from 10 to 40 mi/hr, noting the corresponding speed and time points to the nearest 0.01 mi/hr and 0.01 s. Also determine mean force over the measurement interval.

(2) Starting from a steady roll speed of 45 mi/hr, apply a constant force to the roll to decelerate the roll at a nominal rate of 1 mi/hr/s. Measure the elapsed time to decelerate from 40 to 10 mi/hr, noting the corresponding speed and time points to the nearest 0.01 mi/hr and 0.01 s. Also determine mean force over the measurement interval.

(3) Repeat the steps in paragraphs (c)(1) and (2) of this section for a total of five sets of results at the nominal acceleration rate and the nominal deceleration rate.

(4) Use good engineering judgment to select two additional acceleration and deceleration rate pairs that cover the middle and upper rates expected during testing. Repeat the steps in paragraphs (c)(1) through (3) of this section at each of these additional acceleration and deceleration rates.

(5) Determine the base inertia, *I*b, for each measurement interval using the following equation:

![](/graphics/er25oc16.238.gif)Where:*F* = mean dynamometer force over the measurement interval as measured by the dynamometer.*v*final = roll surface speed at the end of the measurement interval to the nearest 0.01 mi/hr.*v*init = roll surface speed at the start of the measurement interval to the nearest 0.01 mi/hr.Δ*t* = elapsed time during the measurement interval to the nearest 0.01 s.Example:*F* = 1.500 lbf = 48.26 ft·lbm/s2*v*final = 40.00 mi/hr = 58.67 ft/s*v*init = 10.00 mi/hr = 14.67 ft/sΔ*t* = 30.00 s![](/graphics/er25oc16.239.gif)*I*b = 32.90 lbm

(6) Calculate the base inertia error, *I*berror, for each of the thirty measured base inertia values, *I*b, by comparing it to the manufacturer's stated base inertia, *I*bref, using the following equation:

![](/graphics/er28ap14.069.gif)Example:*I*bref = 32.96 lbm*I*bact = 32.90 lbm (from paragraph (c)(5) of this section)![](/graphics/er28ap14.070.gif)

(7) Determine the base inertia mean value *i*b, from the ten acceleration and deceleration interval base inertia values for each of the three acceleration/deceleration rates. Then determine the base inertia mean value, *i*b, from the base inertia values corresponding to acceleration/deceleration rates. Calculate base inertia mean values as described in 40 CFR 1065.602(b)

(8) Calculate the inertia error for the final base inertia mean value from paragraph (c)(7) of this section. Use Eq. 1066.250-2, substituting the final base inertia mean value from paragraph (c)(7) of this section for the individual base inertia.

(d) *Performance evaluation.* The dynamometer must meet the following specifications to be used for testing under this part:

(1) All base inertia errors determined under paragraph (c)(6) of this section may not exceed ±1.0%.

(2) The inertia error for the final base inertia mean value determined under paragraph (c)(8) of this section may not exceed ±0.20%.

[79 FR 23823, Apr. 28, 2014, as amended at 81 FR 74199, Oct. 25, 2016]