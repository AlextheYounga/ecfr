##### § 1065.672 Drift correction. #####

(a) *Scope and frequency.* Perform the calculations in this section to determine if gas analyzer drift invalidates the results of a test interval. If drift does not invalidate the results of a test interval, correct that test interval's gas analyzer responses for drift according to this section. Use the drift-corrected gas analyzer responses in all subsequent emission calculations. Note that the acceptable threshold for gas analyzer drift over a test interval is specified in § 1065.550 for both laboratory testing and field testing.

(b) *Correction principles.* The calculations in this section utilize a gas analyzer's responses to reference zero and span concentrations of analytical gases, as determined sometime before and after a test interval. The calculations correct the gas analyzer's responses that were recorded during a test interval. The correction is based on an analyzer's mean responses to reference zero and span gases, and it is based on the reference concentrations of the zero and span gases themselves. Validate and correct for drift as follows:

(c) *Drift validation.* After applying all the other corrections—except drift correction—to all the gas analyzer signals, calculate emissions according to § 1065.650. Then correct all gas analyzer signals for drift according to this section. Recalculate emissions using all of the drift-corrected gas analyzer signals. Validate and report the emission results before and after drift correction according to § 1065.550.

(d) *Drift correction.* Correct all gas analyzer signals as follows:

(1) Correct each recorded concentration, *x*i, for continuous sampling or for batch sampling, *x*.

(2) Correct for drift using the following equation:

![](/graphics/er24fe09.005.gif)Where:*x*idriftcorrected = concentration corrected for drift.*x*refzero = reference concentration of the zero gas, which is usually zero unless known to be otherwise.*x*refspan = reference concentration of the span gas.*x*prespan = pre-test interval gas analyzer response to the span gas concentration.*x*postspan = post-test interval gas analyzer response to the span gas concentration.*x*i or *x* = concentration recorded during test, before drift correction.*x*prezero = pre-test interval gas analyzer response to the zero gas concentration.xpostzero = post-test interval gas analyzer response to the zero gas concentration.Example:*x*refzero = 0 µmol/mol *x*refspan = 1800.0 µmol/mol *x*prespan = 1800.5 µmol/mol *x*postspan = 1695.8 µmol/mol *x*i or *x* = 435.5 µmol/mol *x*prezero = 0.6 µmol/mol *x*postzero = −5.2 µmol/mol ![](/graphics/er24fe09.006.gif)*x*idriftcorrected = 450.2 µmol/mol

(3) For any pre-test interval concentrations, use the last concentration determined before the test interval. For some test intervals, the last pre-zero or pre-span might have occurred before one or more earlier test intervals.

(4) For any post-test interval concentrations, use the first concentration determined after the test interval. For some test intervals, the first post-zero or post-span might occur after one or more later test intervals.

(5) If you do not record any pre-test interval analyzer response to the span gas concentration, *x*prespan, set *x*prespan equal to the reference concentration of the span gas:

*x*prespan = *x*refspan.

(6) If you do not record any pre-test interval analyzer response to the zero gas concentration, *x*prezero, set *x*prezero equal to the reference concentration of the zero gas:

*x*prezero = *x*refzero.

(7) Usually the reference concentration of the zero gas, *x*refzero, is zero: *x*refzero = 0 µmol/mol. However, in some cases you might know that *x*refzero has a non-zero concentration. For example, if you zero a CO2 analyzer using ambient air, you may use the default ambient air concentration of CO2, which is 375 µmol/mol. In this case, *x*refzero = 375 µmol/mol. Note that when you zero an analyzer using a non-zero *x*refzero, you must set the analyzer to output the actual *x*refzero concentration. For example, if *x*refzero = 375 µmol/mol, set the analyzer to output a value of 375 µmol/mol when the zero gas is flowing to the analyzer.

[70 FR 40516, July 13, 2005, as amended at 74 FR 8427, Feb. 24, 2009; 75 FR 23056, Apr. 30, 2010; 88 FR 4686, Jan. 24, 2023; 89 FR 29823, Apr. 22, 2024]