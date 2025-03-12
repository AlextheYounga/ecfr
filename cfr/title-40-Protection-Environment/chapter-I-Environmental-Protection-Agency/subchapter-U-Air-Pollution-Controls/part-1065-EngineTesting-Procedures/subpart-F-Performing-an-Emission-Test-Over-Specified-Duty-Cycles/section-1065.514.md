##### § 1065.514 Cycle-validation criteria for operation over specified duty cycles. #####

Validate the execution of your duty cycle according to this section unless the standard-setting part specifies otherwise. This section describes how to determine if the engine's operation during the test adequately matched the reference duty cycle. This section applies only to speed, torque, and power from the engine's primary output shaft. Other work inputs and outputs are not subject to cycle-validation criteria. You must compare the original reference duty cycle points generated as described in § 1065.512 to the corresponding feedback values recorded during the test. You may compare reference duty cycle points recorded during the test to the corresponding feedback values recorded during the test as long as the recorded reference values match the original points generated in § 1065.512. The number of points in the validation regression are based on the number of points in the original reference duty cycle generated in § 1065.512. For example if the original cycle has 1199 reference points at 1 Hz, then the regression will have up to 1199 pairs of reference and feedback values at the corresponding moments in the test. The feedback speed and torque signals may be filtered—either in real-time while the test is run or afterward in the analysis program. Any filtering that is used on the feedback signals used for cycle validation must also be used for calculating work. Feedback signals for control loops may use different filtering.

(a) *Testing performed by EPA.* Our tests must meet the specifications of paragraph (f) of this section, unless we determine that failing to meet the specifications is related to engine performance rather than to shortcomings of the dynamometer or other laboratory equipment.

(b) *Testing performed by manufacturers.* Emission tests that meet the specifications of paragraph (f) of this section satisfy the standard-setting part's requirements for duty cycles. You may ask to use a dynamometer or other laboratory equipment that cannot meet those specifications. We will approve your request as long as using the alternate equipment does not adversely affect your ability to show compliance with the applicable emission standards.

(c) *Time-alignment.* Because time lag between feedback values and the reference values may bias cycle-validation results, you may advance or delay the entire sequence of feedback engine speed and torque pairs to synchronize them with the reference sequence. If you advance or delay feedback signals for cycle validation, you must make the same adjustment for calculating work. You may use linear interpolation between successive recorded feedback signals to time shift an amount that is a fraction of the recording period.

(d) *Omitting additional points.* Besides engine cranking, you may omit additional points from cycle-validation statistics as described in the following table:

|                              When operator demand is at its . . .                               |       you may omit . . .       |                                                                                      if . . .                                                                                      |
|-------------------------------------------------------------------------------------------------|--------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**For reference duty cycles that are specified in terms of speed and torque (** fnref, Tref **)**|                                |                                                                                                                                                                                    |
|                                             minimum                                             |        power and torque        |                                                                         T<sub>ref</sub> \< 0% (motoring).                                                                          |
|                                             minimum                                             |        power and speed         |f<sub>nref</sub> = 0% (idle speed) and T<sub>ref</sub> = 0% (idle torque) and T<sub>ref</sub>−(2% · T<sub>max mapped</sub>) \< T \< T<sub>ref</sub> + (2% · T<sub>max mapped</sub>).|
|                                             minimum                                             |        power and speed         |                                                  f<sub>nref</sub> \< enhanced-idle speed <sup>a</sup> and T<sub>ref</sub> \> 0%.                                                   |
|                                             minimum                                             |power and either torque or speed|     f<sub>n</sub> \> f<sub>nref</sub> or T \> T<sub>ref</sub> but not if f<sub>n</sub> \> (f<sub>nref</sub> · 102%) and T \> T<sub>ref +</sub> (2% · T<sub>max mapped</sub>).      |
|                                             maximum                                             |power and either torque or speed|       f<sub>n</sub> \< f<sub>nref</sub> or T \< T<sub>ref</sub> but not if f<sub>n</sub> \< (f<sub>nref</sub> · 98%) and T \< T<sub>ref</sub>−(2% · T<sub>max mapped</sub>).       |
|**For reference duty cycles that are specified in terms of speed and power (** fnref, Pref **)** |                                |                                                                                                                                                                                    |
|                                             minimum                                             |        power and torque        |                                                                         P<sub>ref</sub> \< 0% (motoring).                                                                          |
|                                             minimum                                             |        power and speed         |f<sub>nref</sub> = 0% (idle speed) and P<sub>ref</sub> = 0% (idle power) and P<sub>ref</sub>−(2% · P<sub>max mapped</sub>) \< P \< P<sub>ref</sub> + (2% · P<sub>max mapped</sub>). |
|                                             minimum                                             |power and either torque or speed|     f<sub>n</sub> \> f<sub>nref</sub> or P \> P<sub>ref</sub> but not if f<sub>n</sub> \> (f<sub>nref</sub> · 102%) and P \> P<sub>ref</sub> + (2% · P<sub>max mapped</sub>).      |
|                                             maximum                                             |power and either torque or speed|            f<sub>n</sub> \< f<sub>nref</sub> or P \< Pref but not if f<sub>n</sub> \< (f<sub>nref</sub> · 98%) and P \< P<sub>ref</sub>−(2% · P<sub>max mapped</sub>).             |
|       <sup>a</sup> Determine enhanced-idle speed from ECM broadcast or a practice cycle.        |                                |                                                                                                                                                                                    |

(e) *Statistical parameters.* Use the remaining points to calculate regression statistics for a floating intercept as described in § 1065.602. Round calculated regression statistics to the same number of significant digits as the criteria to which they are compared. Refer to Table 2 of this section for the default criteria and refer to the standard-setting part to determine if there are other criteria for your engine. Calculate the following regression statistics:

(1) Slopes for feedback speed, *a*1fn, feedback torque, *a*1T, and feedback power *a*1P.

(2) Intercepts for feedback speed, *a*0fn, feedback torque, *a*0T, and feedback power *a*0P.

(3) Standard error of the estimate for feedback speed, SEEfn, feedback torque, SEET, and feedback power SEEP.

(4) Coefficients of determination for feedback speed, *r*2fn, feedback torque, *r*2T, and feedback power *r*2P.

(f) *Cycle-validation criteria.* Unless the standard-setting part specifies otherwise, use the following criteria to validate a duty cycle:

(1) For variable-speed engines, apply all the statistical criteria in Table 2 of this section.

(2) For constant-speed engines, apply only the statistical criteria for torque in Table 2 of this section.

(3) For discrete-mode steady-state testing, apply cycle-validation criteria by treating the sampling periods from the series of test modes as a continuous sampling period, analogous to ramped-modal testing and apply statistical criteria as described in paragraph (f)(1) or (2) of this section. Note that if the gaseous and particulate test intervals are different periods of time, separate validations are required for the gaseous and particulate test intervals. Table 2 follows:

|                 Parameter                  |            Speed            |            Torque            |            Power             |
|--------------------------------------------|-----------------------------|------------------------------|------------------------------|
|            Slope, a<sub>1</sub>            |0.950 ≤ a<sub>1</sub> ≤ 1.030|0.830 ≤ a<sub>1</sub> ≤ 1.030 |0.830 ≤ a<sub>1</sub> ≤ 1.030.|
|Absolute value of intercept, |a<sub>0</sub>||     ≤ 10% of warm idle      |≤ 2% of maximum mapped torque |≤ 2% of maximum mapped power. |
|    Standard error of the estimate, SEE     | ≤ 5% of maximum test speed  |≤ 10% of maximum mapped torque|≤ 10% of maximum mapped power.|
|Coefficient of determination, r<sub>2</sub> |           ≥ 0.970           |           ≥ 0.850            |           ≥ 0.910.           |

[73 FR 37318, June 30, 2008, as amended at 73 FR 59330, Oct. 8, 2008; 75 FR 23042, Apr. 30, 2010; 76 FR 57450, Sept. 15, 2011; 86 FR 34546, June 29, 2021; 88 FR 4678, Jan. 24, 2023]