##### § 1066.230 Time verification procedure. #####

(a) *Overview.* This section describes how to verify the accuracy of the dynamometer's timing device.

(b) *Scope and frequency.* Perform this verification upon initial installation and after major maintenance.

(c) *Procedure.* Perform this verification using one of the following procedures:

(1) *WWV method.* You may use the time and frequency signal broadcast by NIST from radio station WWV as the time standard if the trigger for the dynamometer timing circuit has a frequency decoder circuit, as follows:

(i) Contact station WWV by telephone by dialing (303) 499-7111 and listen for the time announcement. Verify that the trigger started the dynamometer timer. Use good engineering judgment to minimize error in receiving the time and frequency signal.

(ii) After at least 1000 seconds, re-dial station WWV and listen for the time announcement. Verify that the trigger stopped the dynamometer timer.

(iii) Compare the measured elapsed time, *y*act, to the corresponding time standard, *y*ref, to determine the time error, *y*error, using the following equation:

![](/graphics/er28ap14.063.gif)

(2) *Ramping method.* You may use an operator-defined ramp function to serve as the time standard as follows:

(i) Set up a signal generator to output a marker voltage at the peak of each ramp to trigger the dynamometer timing circuit. Output the designated marker voltage to start the verification period.

(ii) After at least 1000 seconds, output the designated marker voltage to end the verification period.

(iii) Compare the measured elapsed time between marker signals, *y*act, to the corresponding time standard, *y*ref, to determine the time error, *y*error, using Eq. 1066.230-1.

(3) *Dynamometer coastdown method.* You may use a signal generator to output a known speed ramp signal to the dynamometer controller to serve as the time standard as follows:

(i) Generate upper and lower speed values to trigger the start and stop functions of the coastdown timer circuit. Use the signal generator to start the verification period.

(ii) After at least 1000 seconds, use the signal generator to end the verification period.

(iii) Compare the measured elapsed time between trigger signals, *y*act, to the corresponding time standard, *y*ref, to determine the time error, *y*error, using Eq. 1066.230-1.

(d) *Performance evaluation.* The time error determined in paragraph (c) of this section may not exceed ±0.001%.