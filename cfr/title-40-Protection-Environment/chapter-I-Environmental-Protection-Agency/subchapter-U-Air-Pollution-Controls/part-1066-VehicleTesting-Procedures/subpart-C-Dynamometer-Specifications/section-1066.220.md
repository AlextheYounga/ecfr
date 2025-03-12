##### § 1066.220 Linearity verification for chassis dynamometer systems. #####

(a) *Scope and frequency.* Perform linearity verification for dynamometer speed and torque at least as frequently as indicated in Table 1 of § 1066.215. The intent of linearity verification is to determine that the system responds accurately and proportionally over the measurement range of interest. Linearity verification generally consists of introducing a series of at least 10 reference values to a measurement system. The measurement system quantifies each reference value. The measured values are then collectively compared to the reference values by using a least-squares linear regression and the linearity criteria specified in Table 1 of this section.

(b) *Performance requirements.* If a measurement system does not meet the applicable linearity criteria in Table 1 of this section, correct the deficiency by re-calibrating, servicing, or replacing components as needed. Repeat the linearity verification after correcting the deficiency to ensure that the measurement system meets the linearity criteria. Before you may use a measurement system that does not meet linearity criteria, you must demonstrate to us that the deficiency does not adversely affect your ability to demonstrate compliance with the applicable standards in this chapter.

(c) *Procedure.* Use the following linearity verification protocol, or use good engineering judgment to develop a different protocol that satisfies the intent of this section, as described in paragraph (a) of this section:

(1) In this paragraph (c), the letter “y” denotes a generic measured quantity, the superscript over-bar denotes an arithmetic mean (such as *y*), and the subscript “ref” denotes the known or reference quantity being measured.

(2) Operate the dynamometer system at the specified operating conditions. This may include any specified adjustment or periodic calibration of the dynamometer system.

(3) Set dynamometer speed and torque to zero.

(4) Verify the dynamometer speed or torque signal based on the dynamometer manufacturer's recommendations.

(5) After verification, check for zero speed and torque. Use good engineering judgment to determine whether or not to rezero or re-verify speed and torque before continuing.

(6) For both speed and torque, use the dynamometer manufacturer's recommendations and good engineering judgment to select reference values, *y*refi, that cover a range of values that you expect would prevent extrapolation beyond these values during emission testing. We recommend selecting zero speed and zero torque as reference values for the linearity verification.

(7) Use the dynamometer manufacturer's recommendations and good engineering judgment to select the order in which you will introduce the series of reference values. For example, you may select the reference values randomly to avoid correlation with previous measurements and to avoid the influence of hysteresis; you may select reference values in ascending or descending order to avoid long settling times of reference signals; or you may select values to ascend and then descend to incorporate the effects of any instrument hysteresis into the linearity verification.

(8) Set the dynamometer to operate at a reference condition.

(9) Allow time for the dynamometer to stabilize while it measures the reference values.

(10) At a recording frequency of at least 1 Hz, measure speed and torque values for 30 seconds and record the arithmetic mean of the recorded values,. Refer to 40 CFR 1065.602 for an example of calculating an arithmetic mean.

(11) Repeat the steps in paragraphs (c)(8) though (10) of this section until you measure speeds and torques at each of the reference settings.

(12) Use the arithmetic means, *y*i, and reference values, *y*refi, to calculate least-squares linear regression parameters and statistical values to compare to the minimum performance criteria specified in Table 1 of this section. Use the calculations described in 40 CFR 1065.602. Using good engineering judgment, you may weight the results of individual data pairs (i.e., (*y*refi,*y*i)), in the linear regression calculations. Table 1 follows:

|                  Measurement system                  |  Quantity   |   Linearity criteria   |             |                     |      |
|------------------------------------------------------|-------------|------------------------|-------------|---------------------|------|
||y<sub>min</sub> · (a<sub>1</sub>−1) + a<sub>0</sub> ||a<sub>1</sub>|          SEE           |r<sup>2</sup>|                     |      |
|                        Speed                         |      n      |≤0.05% · n<sub>max</sub>|  0.98-1.02  |≤2% · n<sub>max</sub>|≥0.990|
|                    Torque (load)                     |      T      | ≤1% · T<sub>max</sub>  |  0.99-1.01  |≤1% · T<sub>max</sub>|≥0.990|

(d) *Reference signals.* Generate reference values for the linearity-verification protocol in paragraph (c) of this section as described for speed and torque in 40 CFR 1065.307(d).

[79 FR 23823, Apr. 28, 2014, as amended at 88 FR 4708, Jan. 24, 2023]