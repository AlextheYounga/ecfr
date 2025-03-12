##### § 1065.610 Duty cycle generation. #####

This section describes how to generate duty cycles that are specific to your engine, based on the normalized duty cycles in the standard-setting part. During an emission test, use a duty cycle that is specific to your engine to command engine speed, torque, and power, as applicable, using an engine dynamometer and an engine operator demand. Paragraphs (a) and (b) of this section describe how to “normalize” your engine's map to determine the maximum test speed or torque for your engine. The rest of this section describes how to use these values to “denormalize” the duty cycles in the standard-setting parts, which are all published on a normalized basis. Thus, the term “normalized” in paragraphs (a) and (b) of this section refers to different values than it does in the rest of the section.

(a) *Maximum test speed, ƒ*ntest. For variable-speed engines, determine ƒntest from the torque and power maps, generated according to § 1065.510, as follows:

(1) Determine a measured value for ƒntest as follows:

(i) Determine maximum power, *P*max, from the engine map generated according to § 1065.510 and calculate the value for power equal to 98% of *P*max.

(ii) Determine the lowest and highest engine speeds corresponding to 98% of *P*max, using linear interpolation, and no extrapolation, as appropriate.

(iii) Determine the engine speed corresponding to maximum power, *f*nPmax, by calculating the average of the two speed values from paragraph (a)(1)(ii) of this section. If there is only one speed where power is equal to 98% of *P*max, take *f*nPmax as the speed at which *P*max occurs.

(iv) Transform the map into a normalized power-versus-speed map by dividing power terms by *P*max and dividing speed terms by *f*nPmax. Use the following equation to calculate a quantity representing the sum of squares from the normalized map:

![](/graphics/er29jn21.209.gif)Where:*i* = an indexing variable that represents one recorded value of an engine map.*f*nnormi = an engine speed normalized by dividing it by *f*nPmax.*P*normi = an engine power normalized by dividing it by *P*max.

(v) Determine the maximum value for the sum of the squares from the map and multiply that value by 0.98.

(vi) Determine the lowest and highest engine speeds corresponding to the value calculated in paragraph (a)(1)(v) of this section, using linear interpolation as appropriate. Calculate *f*ntest as the average of these two speed values. If there is only one speed corresponding to the value calculated in paragraph (a)(1)(v) of this section, take *f*ntest as the speed where the maximum of the sum of the squares occurs.

(vii) The following example illustrates a calculation of *f*ntest:

*P*max = 230.0

(*f*n1 = 2360, *P*1 = 222.5, *f*nnorm1 = 1.002, *P*norm1 = 0.9675)(*f*n2 = 2364, *P*2 = 226.8, *f*nnorm2 = 1.004, *P*norm2 = 0.9859)(*f*n3 = 2369, *P*3 = 228.6, *f*nnorm3 = 1.006, *P*norm3 = 0.9940)(*f*n4 = 2374, *P*4 = 218.7, *f*nnorm4 = 1.008, *P*norm4 = 0.9508)Sum of squares = (1.0022 + 0.96752) = 1.94Sum of squares = (1.0042 + 0.98592) = 1.98Sum of squares = (1.0062 + 0.99402) = 2.00Sum of squares = (1.0082 + 0.95082) = 1.92![](/graphics/er19fe15.022.gif)

(2) For engines with a high-speed governor that will be subject to a reference duty cycle that specifies normalized speeds greater than 100%, calculate an alternate maximum test speed, *f*ntest,alt, as specified in this paragraph (a)(2). If *f*ntest,alt is less than the measured maximum test speed, *f*ntest, determined in paragraph (a)(1) of this section, replace *f*ntest with *f*ntest,alt. In this case, *f*ntest,alt becomes the “maximum test speed” for that engine for all duty cycles. Note that § 1065.510 allows you to apply an optional declared maximum test speed to the final measured maximum test speed determined as an outcome of the comparison between *f*ntest, and *f*ntest,alt in this paragraph (a)(2). Determine *f*ntest,alt as follows:

![](/graphics/er25oc16.160.gif)Where:*f*ntest,alt = alternate maximum test speed*f*nhi,idle = warm high-idle speed*f*nidle = warm idle speed*% speed*max = maximum normalized speed from duty cycleExample:*f*nhi,idle = 2200 r/min*f*nidle = 800 r/min![](/graphics/er25oc16.161.gif)*f*ntest,alt = 2133 r/min

(3) Transform normalized speeds to reference speeds according to paragraph (c) of this section by using the measured maximum test speed determined according to paragraphs (a)(1) and (2) of this section—or use your declared maximum test speed, as allowed in § 1065.510.

(b) *Maximum test torque,**T*test. For constant-speed engines, determine *T*test from the torque and power-versus-speed maps, generated according to § 1065.510, as follows:

(1) For constant speed engines mapped using the methods in § 1065.510(d)(5)(i) or (ii), determine a measured value for *T*test as follows:

(i) Determine maximum power, *P*max, from the engine map generated according to § 1065.510 and calculate the value for power equal to 98% of *P*max.

(ii) Determine the lowest and highest engine speeds corresponding to 98% of *P*max, using linear interpolation, and no extrapolation, as appropriate.

(iii) Determine the engine speed corresponding to maximum power, *f*nPmax, by calculating the average of the two speed values from paragraph (a)(1)(ii) of this section. If there is only one speed where power is equal to 98% of *P*max, take *f*nPmax as the speed at which *P*max occurs.

(iv) Transform the map into a normalized power-versus-speed map by dividing power terms by *P*max and dividing speed terms by *f*nPmax. Use Eq. 1065.610-1 to calculate a quantity representing the sum of squares from the normalized map.

(v) Determine the maximum value for the sum of the squares from the map and multiply that value by 0.98.

(vi) Determine the lowest and highest engine speeds corresponding to the value calculated in paragraph (a)(1)(v) of this section, using linear interpolation as appropriate. Calculate *f*ntest as the average of these two speed values. If there is only one speed corresponding to the value calculated in paragraph (a)(1)(v) of this section, take *f*ntest as the speed where the maximum of the sum of the squares occurs.

(vii) The measured *T*test is the mapped torque at *f*ntest.

(2) For constant speed engines using the two-point mapping method in § 1065.510(d)(5)(iii), you may follow paragraph (a)(1) of this section to determine the measured *T*test, or you may use the measured torque of the second point as the measured *T*test directly.

(3) Transform normalized torques to reference torques according to paragraph (d) of this section by using the measured maximum test torque determined according to paragraph (b)(1) or (2) of this section—or use your declared maximum test torque, as allowed in § 1065.510.

(c) *Generating reference speed values from normalized duty cycle speeds.* Transform normalized speed values to reference values as follows:

(1) *% speed.* If your normalized duty cycle specifies % speed values, use your warm idle speed and your maximum test speed to transform the duty cycle, as follows:

![](/graphics/er25oc16.162.gif)Example:*% speed* = 85% = 0.85*f*ntest = 2364 r/min*f*nidle = 650 r/min*f*nref = 0.85 • (2364−650) + 650*f*nref = 2107 r/min

(2) *A, B, C, and D speeds.* If your normalized duty cycle specifies speeds as A, B, C, or D values, use your power-versus-speed curve to determine the lowest speed below maximum power at which 50% of maximum power occurs. Denote this value as *n*lo. Take *n*lo to be warm idle speed if all power points at speeds below the maximum power speed are higher than 50% of maximum power. Also determine the highest speed above maximum power at which 70% of maximum power occurs. Denote this value as *n*hi. If all power points at speeds above the maximum power speed are higher than 70% of maximum power, take *n*hi to be the declared maximum safe engine speed or the declared maximum representative engine speed, whichever is lower. Use *n*hi and *n*lo to calculate reference values for A, B, C, or D speeds as follows:

![](/graphics/er24ja23.106.gif)Example:*n*lo = 1005 r/min*n*hi = 2385 r/minƒnrefA = 0.25 · (2385 − 1005) + 1005ƒnrefB = 0.50 · (2385 − 1005) + 1005ƒnrefC = 0.75 · (2385 − 1005) + 1005ƒnrefD = 0.15 · (2385 − 1005) + 1005ƒnrefA = 1350 r/minƒnrefB = 1695 r/minƒnrefC = 2040 r/minƒnrefD = 1212 r/min

(3) *Intermediate speed.* Based on the map, determine maximum torque, *T*max, and the corresponding speed, *f*nTmax, calculated as the average of the lowest and highest speeds at which torque is equal to 98% of *T*max. Use linear interpolation between points to determine the speeds where torque is equal to 98% of *T*max. Identify your reference intermediate speed as one of the following values:

(i) *f*nTmax if it is between (60 and 75) % of maximum test speed.

(ii) 60% of maximum test speed if *f*nTmax is less than 60% of maximum test speed.

(iii) 75% of maximum test speed if *f*nTmax is greater than 75% of maximum test speed.

(d) *Generating reference torques from normalized duty-cycle torques.* Transform normalized torques to reference torques using your map of maximum torque versus speed.

(1) *Reference torque for variable-speed engines.* For a given speed point, multiply the corresponding % torque by the maximum torque at that speed, according to your map. If your engine is subject to a reference duty cycle that specifies negative torque values (*i.e.*, engine motoring), use negative torque for those motoring points (*i.e.*, the motoring torque). If you map negative torque as allowed under § 1065.510 (c)(2) and the low-speed governor activates, resulting in positive torques, you may replace those positive motoring mapped torques with negative values between zero and the largest negative motoring torque. For both maximum and motoring torque maps, linearly interpolate mapped torque values to determine torque between mapped speeds. If the reference speed is below the minimum mapped speed (*i.e.*, 95% of idle speed or 95% of lowest required speed, whichever is higher), use the mapped torque at the minimum mapped speed as the reference torque. The result is the reference torque for each speed point.

(2) *Reference torque for constant-speed engines.* Multiply a % torque value by your maximum test torque. The result is the reference torque for each point.

(3) *Required deviations.* We require the following deviations for variable-speed engines intended primarily for propulsion of a vehicle with an automatic or manual transmission where that engine is subject to a transient duty cycle that specifies points with normalized reference speed of 0% and normalized reference torque of 0% (*i.e.,* idle points). These deviations are intended to produce a more representative transient duty cycle for these applications. For steady-state duty cycles or transient duty cycles with no idle operation, the requirements in this paragraph (d)(3) do not apply. Idle points for steady-state duty cycles of such engines are to be run at conditions simulating neutral or park on the transmission. For manual transmissions, set CITT to zero, which results in warm-idle-in-drive speed and torque values being the same as warm-idle-in-neutral values. For the case of a manual transmission where the optional declared idle torque in § 1065.510(f)(5)(iii) and the optional declared power in § 1065.510(f)(6) are not declared (*i.e.,* idle torque is zero), the required deviations in this paragraph (d)(3) have no impact and may be skipped.

(i) Determine the warm-idle-in-drive speed and torque values with the transmission in drive from the data collected during the engine mapping procedure in § 1065.510. The warm-idle-in-drive torque is the sum of CITT and the torques representing loads from vehicle accessories. For example, the sum of the required declared CITT in § 1065.510(f)(4), any optional declared torque in § 1065.510(f)(5)(iii), and the torque on the primary output shaft from any optional declared power in § 1065.510(f)(6).

(ii) Determine the warm-idle-in-neutral speed and torque values with the transmission in neutral from the data collected during the engine mapping procedure in § 1065.510. The warm-idle-in-neutral torque is the sum of any optional declared torque in § 1065.510(f)(5)(iii) and the torque on the primary output shaft from any optional declared power in § 1065.510(f)(6) (*i.e.,* the sum of the torques representing loads from vehicle accessories).

(iii) Zero-percent speed for denormalization of non-idle points is the warm-idle-in-drive speed.

(iv) For motoring points, make no changes.

(v) If the cycle begins with an idle segment (*i.e.,* a set of one or more contiguous idle points), set the reference speed and torque values to the warm-idle-in-neutral values for this initial segment. This is to represent idle operation with the transmission in neutral or park at the start of the transient duty cycle, after the engine is started. If the initial idle segment is longer than 24 seconds, change the reference speed and torque values for the remaining idle points in the initial idle segment to the warm-idle-in-drive values (*i.e.,* change idle points corresponding to 25 seconds to the end of the initial idle segment to warm-idle-in-drive). This is to represent manually shifting the transmission to drive.

(vi) For all other idle segments, set the reference speed and torque values to the warm-idle-in-drive values. This is to represent the transmission operating in drive.

(vii) If the engine is intended primarily for automatic transmissions with a Neutral-When-Stationary feature that automatically shifts the transmission to neutral after the vehicle is stopped for a designated time and automatically shifts back to drive when the operator increases demand (*i.e.,* pushes the accelerator pedal), reprocess all idle segments. Change reference speed and torque values from the warm-idle-in-drive values to the warm-idle-in-neutral values for idle points in drive after the designated time.

(viii) For all nonidle nonmotoring points with normalized speed at or below zero percent and reference torque from zero to the warm-idle-in-drive torque value, set the reference torque to the warm-idle-in-drive torque value. This is to represent the transmission operating in drive.

(ix) For consecutive nonidle nonmotoring points that immediately follow and precede idle segments, with reference torque values from zero to the warm-idle-in-drive torque value, change their reference torques to the warm-idle-in-drive torque value. This is to represent the transmission operating in drive.

(x) For consecutive nonidle nonmotoring points that immediately follow and precede any point(s) that were modified in paragraph (d)(3)(viii) of this section, with reference torque values from zero to the warm-idle-in-drive torque value, change their reference torques to the warm-idle-in-drive torque value. This is to provide smooth torque transition around these points.

(4) *Permissible deviations for any engine.* If your engine does not operate below a certain minimum torque under normal in-use conditions, you may use a declared minimum torque as the reference value instead of any value denormalized to be less than the declared value. For example, if your engine is connected to a hydrostatic transmission and it has a minimum torque even when all the driven hydraulic actuators and motors are stationary and the engine is at idle, then you may use this declared minimum torque as a reference torque value instead of any reference torque value generated under paragraph (d)(1) or (2) of this section that is between zero and this declared minimum torque.

(e) *Generating reference power values from normalized duty cycle powers.* Transform normalized power values to reference speed and power values using your map of maximum power versus speed.

(1) First transform normalized speed values into reference speed values. For a given speed point, multiply the corresponding % power by the mapped power at maximum test speed, *f*ntest, unless specified otherwise by the standard-setting part. The result is the reference power for each speed point, *P*ref. Convert these reference powers to corresponding torques for operator demand and dynamometer control and for duty cycle validation per 1065.514. Use the reference speed associated with each reference power point for this conversion. As with cycles specified with % torque, linearly interpolate between these reference torque values generated from cycles with % power.

(2) Permissible deviations for any engine. If your engine does not operate below a certain power under normal in-use conditions, you may use a declared minimum power as the reference value instead of any value denormalized to be less than the declared value. For example, if your engine is directly connected to a propeller, it may have a minimum power called idle power. In this case, you may use this declared minimum power as a reference power value instead of any reference power value generated per paragraph (e)(1) of this section that is from zero to this declared minimum power.

[73 FR 37324, June 30, 2008, as amended at 73 FR 59330, Oct. 8, 2008; 75 FR 23045, Apr. 30, 2010; 76 FR 57453, Sept. 15, 2011; 78 FR 36398, June 17, 2013; 79 FR 23783, Apr. 28, 2014; 80 FR 9118, Feb. 19, 2015; 81 FR 74170, Oct. 25, 2016; 86 FR 34555, June 29, 2021; 88 FR 4679, Jan. 24, 2023; 89 FR 29807, Apr. 22, 2024]