##### § 1036.510 Supplemental Emission Test. #####

(a) Measure emissions using the steady-state SET duty cycle as described in this section. Note that the SET duty cycle is operated as a ramped-modal cycle rather than discrete steady-state test points.

(b) Procedures apply differently for testing certain kinds of engines and powertrains as follows:

(1) For testing nonhybrid engines, the SET duty cycle is based on normalized speed and torque values relative to certain maximum values. Denormalize speed as described in 40 CFR 1065.512. Denormalize torque as described in 40 CFR 1065.610(d). Note that idle points are to be run at conditions simulating neutral or park on the transmission.

(2) Test hybrid powertrains as described in § 1036.545, except as specified in this paragraph (b)(2). Do not compensate the duty cycle for the distance driven as described in § 1036.545(g)(4). For hybrid engines, select the transmission from § 1036.540(c)(2), substituting “engine” for “vehicle” and “highway cruise cycle” for “SET”. Disregard duty cycles in § 1036.545(j). For cycles that begin with idle, leave the transmission in neutral or park for the full initial idle segment. Place the transmission into drive no earlier than 5 seconds before the first nonzero vehicle speed setpoint. For SET testing only, place the transmission into park or neutral when the cycle reaches the final idle segment. Use the following vehicle parameters instead of those in § 1036.545 to define the vehicle model in § 1036.545(a)(3):

(i) Determine the vehicle test mass, *M,* as follows:

![](/graphics/er24ja23.016.gif)Where:*P*contrated = the continuous rated power of the hybrid system determined in sect; 1036.520.Example:*P*contrated = 350.1 kW*M* = 15.1·350.11.31*M* = 32499 kg

(ii) Determine the vehicle frontal area, *A*front, as follows:

(A) For *M* ≤ 18050 kg:

![](/graphics/er24ja23.017.gif)Example:*M* = 16499 kg*A*front = −1.69·10−8·164992+6.33·10−4·16499+1.67*A*front = 7.51 m2

(B) For *M* \> 18050 kg, *A*front = 7.59 m2

(iii) Determine the vehicle drag area, *C*d*A*, as follows:

![](/graphics/er24ja23.018.gif)Where:*g* = gravitational constant = 9.80665 m/s2.*ρ* = air density at reference conditions. Use *ρ* = 1.1845 kg/m3.Example:![](/graphics/er24ja23.019.gif)

*C*d*A* = 3.08 m2

(iv) Determine the coefficient of rolling resistance, *C*rr, as follows:

![](/graphics/er24ja23.020.gif)Example:![](/graphics/er24ja23.021.gif)*C*rr = 5.7 N/kN = 0.0057 N/N

(v) Determine the vehicle curb mass, *M*curb, as follows:

![](/graphics/er24ja23.022.gif)Example:*M*curb = −0.000007376537·324992 + 0.6038432·32499*M*curb = 11833 kg

(vi) Determine the linear equivalent mass of rotational moment of inertias, *M*rotating, as follows:

![](/graphics/er24ja23.023.gif)Example:*M*rotating = 0.07·11833*M*rotating = 828.3 kg

(vii) Select a combination of drive axle ratio, *k*a, and a tire radius, *r,* that represents the worst-case combination of top gear ratio, drive axle ratio, and tire size for CO2 expected for vehicles in which the hybrid engine or hybrid powertrain will be installed. This is typically the highest axle ratio and smallest tire radius. Disregard configurations or settings corresponding to a maximum vehicle speed below 60 mi/hr in selecting a drive axle ratio and tire radius, unless you can demonstrate that in-use vehicles will not exceed that speed. You may request preliminary approval for selected drive axle ratio and tire radius consistent with the provisions of § 1036.210. If the hybrid engine or hybrid powertrain is used exclusively in vehicles not capable of reaching 60 mi/hr, you may request that we approve an alternate test cycle and cycle-validation criteria as described in 40 CFR 1066.425(b)(5). Note that hybrid engines rely on a specified transmission that is different for each duty cycle; the transmission's top gear ratio therefore depends on the duty cycle, which will in turn change the selection of the drive axle ratio and tire size. For example, § 1036.520 prescribes a different top gear ratio than this paragraph (b)(2).

(viii) If you are certifying a hybrid engine, use a default transmission efficiency of 0.95 and create the vehicle model along with its default transmission shift strategy as described in § 1036.545(a)(3)(ii). Use the transmission parameters defined in § 1036.540(c)(2) to determine transmission type and gear ratio. For Light HDV and Medium HDV, use the Light HDV and Medium HDV parameters for FTP, LLC, and SET duty cycles. For Tractors and Heavy HDVs, use the Tractor and Heavy HDV transient cycle parameters for the FTP and LLC duty cycles and the Tractor and Heavy HDV highway cruise cycle parameters for the SET duty cycle.

(c) Measure emissions using the SET duty cycle shown in Table 1 of this section to determine whether engines meet the steady-state compression-ignition standards specified in subpart B of this part. Table 1 of this section specifies test settings, as follows:

(1) The duty cycle for testing nonhybrid engines involves a schedule of normalized engine speed and torque values. Note that nonhybrid powertrains are generally tested as engines, so this section does not describe separate procedures for that configuration.

(2) The duty cycle for testing hybrid powertrains involves a schedule of vehicle speeds and road grade as follows:

(i) Determine road grade at each point based on the continuous rated power of the hybrid powertrain, *P*contrated, in kW determined in § 1036.520, the vehicle speed (A, B, or C) in mi/hr for a given SET mode, *v*ref[speed], and the specified road-grade coefficients using the following equation:

![](/graphics/er24ja23.024.gif)Example for SET mode 3a in Table 1 of this section:*P*contrated = 345.2 kW*v*refB = 59.3 mi/hr*Road grade* = 8.296 · 10−9 · 345.23 + (−4.752 · 10−7) · 345.22 · 59.3 + 1.291 · 10−5 · 345.22 + 2.88 · 10−4 · 59.32 + 4.524 · 10−4 · 345.2 · 59.3 + (−1.802 · 10−2) · 345.2 + (−1.83 · 10−1) · 59.3 + 8.81*Road grade* = 0.53%

(ii) Use the vehicle C speed determined in § 1036.520. Determine vehicle A and B speeds as follows:

(A) Determine vehicle A speed using the following equation:

![](/graphics/er24ja23.025.gif)Example:*v*refC = 68.42 mi/hr![](/graphics/er24ja23.026.gif)*v*refA = 50.2 mi/hr

(B) Determine vehicle B speed using the following equation:

![](/graphics/er24ja23.027.gif)Example:![](/graphics/er24ja23.028.gif)*v*refB = 59.3 mi/hr

(3) Table 1 follows:

![](/graphics/er24ja23.029.gif)

(d) Determine criteria pollutant emissions for plug-in hybrid powertrains as follows:

(1) Carry out a charge-sustaining test as described in paragraph (b)(2) of this section.

(2) Carry out a charge-depleting test as described in paragraph (b)(2) of this section, except as follows:

(i) Fully charge the RESS after preconditioning.

(ii) Operate the engine or powertrain continuously over repeated SET duty cycles until you reach the end-of-test criterion defined in 40 CFR 1066.501(a)(3).

(iii) Calculate emission results for each SET duty cycle. Figure 1 to paragraph (d)(4) of this section provides an example of a charge-depleting test sequence where there are two test intervals that contain engine operation.

(3) Report the highest emission result for each criteria pollutant from all tests in paragraphs (d)(1) and (2) of this section, even if those individual results come from different test intervals.

(4) The following figure illustrates an example of an SET charge-depleting test sequence:

Figure 1 to Paragraph (d)(4) of § 1036.510—SET Charge-Depleting Criteria Pollutant Test Sequence.![](/graphics/er22ap24.165.gif)

(e) Determine greenhouse gas pollutant emissions for plug-in hybrid powertrains using the emissions results for all the SET test intervals for both charge-depleting and charge-sustaining operation from paragraph (d)(2) of this section. Calculate the utility factor-weighted composite mass of emissions from the charge-depleting and charge-sustaining test results, *e*UF[emission]comp, using the following equation:

![](/graphics/er22ap24.166.gif)Eq. 1036.510-10Where:*i* = an indexing variable that represents one test interval.*N* = total number of charge-depleting test intervals.*e*[emission][int]CDi = total mass of emissions in the charge-depleting portion of the test for each test interval, *i,* starting from *i* = 1, including the test interval(s) from the transition phase.*UF*DCDi = utility factor fraction at distance *D*CDi from Eq. 1036.510-11, as determined by interpolating the approved utility factor curve for each test interval, *i,* starting from *i* = 1. Let *UF*DCD0 = 0.*j* = an indexing variable that represents one test interval.*M* = total number of charge-sustaining test intervals.*e*[emission][int]CSj = total mass of emissions in the charge-sustaining portion of the test for each test interval, *j,* starting from *j* = 1.*UF*RCD = utility factor fraction at the full charge-depleting distance, *R*CD, as determined by interpolating the approved utility factor curve. *R*CD is the cumulative distance driven over *N* charge-depleting test intervals.![](/graphics/er22ap24.167.gif)Eq. 1036.510-11Where:*k* = an indexing variable that represents one recorded velocity value.*Q* = total number of measurements over the test interval.*v* = vehicle velocity at each time step, *k,* starting from *k* = 1. For tests completed under this section, *v* is the vehicle velocity from the vehicle model in § 1036.545. Note that this should include charge-depleting test intervals that start when the engine is not yet operating.Δ*t* = 1/*f*record*f*record = the record rate.

*Example using the charge-depletion test in figure 1 to paragraph (d)(4) of this section for the SET for CO*2*emission determination:*

*Q* = 24000v1 = 0 mi/hrv2 = 0.8 mi/hrv3 = 1.1 mi/hr*f*record = 10 HzΔ*t* = 1/10 Hz = 0.1 s![](/graphics/er22ap24.168.gif)*D*CD1 = 30.1 mi*D*CD2 = 30.0 mi*D*CD3 = 30.1 mi*D*CD4 = 30.2 mi*D*CD5 = 30.1 mi*N* = 5*UF*DCD1 = 0.11*UF*DCD2 = 0.23*UF*DCD3 = 0.34*UF*DCD4 = 0.45*UF*DCD5 = 0.53*e*CO2SETCD1 = 0 g/hp·hr*e*CO2SETCD2 = 0 g/hp·hr*e*CO2SETCD3 = 0 g/hp·hr*e*CO2SETCD4 = 0 g/hp·hr*e*CO2SETCD5 = 174.4 g/hp·hr*M* = 1*e*CO2SETCS = 428.1 g/hp·hr*UF*RCD = 0.53![](/graphics/er22ap24.169.gif)

(f) Calculate and evaluate cycle-validation criteria as specified in 40 CFR 1065.514 for nonhybrid engines and § 1036.545 for hybrid powertrains.

(g) Calculate the total emission mass of each constituent, *m,* over the test interval as described in 40 CFR 1065.650. Calculate the total work, *W,* over the test interval as described in 40 CFR 1065.650(d). For hybrid powertrains, calculate *W* using system power, *P*sys as described in § 1036.520(f).

[88 FR 4487, Jan. 24, 2023, as amended at 89 FR 29743, Apr. 22, 2024]