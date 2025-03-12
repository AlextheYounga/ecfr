##### § 1036.540 Determining cycle-average engine fuel maps. #####

(a) *Overview.* This section describes how to determine an engine's cycle-average fuel maps for model year 2021 and later vehicles. Vehicle manufacturers may need cycle-average fuel maps for transient duty cycles, highway cruise cycles, or both to demonstrate compliance with emission standards under 40 CFR part 1037. Generate cycle-average engine fuel maps as follows:

(1) Determine the engine's torque maps as described in § 1036.505(c).

(2) Determine the engine's steady-state fuel map and fuel consumption at idle as described in § 1036.535. If you are applying cycle-average fuel mapping for highway cruise cycles, you may instead use GEM's default fuel map instead of generating the steady-state fuel map in § 1036.535(b).

(3) Simulate several different vehicle configurations using GEM (see 40 CFR 1037.520) to create new engine duty cycles as described in paragraph (c) of this section. The transient vehicle duty cycles for this simulation are in 40 CFR part 1037, appendix A; the highway cruise cycles with grade are in 40 CFR part 1037, appendix D. Note that GEM simulation relies on vehicle service classes as described in 40 CFR 1037.140.

(4) Test the engines using the new duty cycles to determine fuel consumption, cycle work, and average vehicle speed as described in paragraph (d) of this section and establish GEM inputs for those parameters for further vehicle simulations as described in paragraph (e) of this section.

(b) *General test provisions.* The following provisions apply for testing under this section:

(1) Measure NOX emissions for each specified sampling period in grams. You may perform these measurements using a NOX emission-measurement system that meets the requirements of 40 CFR part 1065, subpart J. Include these measured NOX values any time you report to us your fuel-consumption values from testing under this section. If a system malfunction prevents you from measuring NOX emissions during a test under this section but the test otherwise gives valid results, you may consider this a valid test and omit the NOX emission measurements; however, we may require you to repeat the test if we determine that you inappropriately voided the test with respect to NOX emission measurement.

(2) The provisions related to carbon balance error verification in § 1036.543 apply for all testing in this section. These procedures are optional, but we will perform carbon balance error verification for all testing under this section.

(3) Correct fuel mass to a mass-specific net energy content of a reference fuel as described in paragraph (d)(13) of this section.

(4) This section uses engine parameters and variables that are consistent with 40 CFR part 1065.

(c) *Create engine duty cycles.* Use GEM to simulate your engine operation with several different vehicle configurations to create transient and highway cruise engine duty cycles corresponding to each vehicle configuration as follows:

(1) Set up GEM to simulate your engine's operation based on your engine's torque maps, steady-state fuel maps, warm-idle speed as defined in 40 CFR 1037.520(h)(1), and fuel consumption at idle as described in paragraphs (a)(1) and (2) of this section.

(2) Set up GEM with transmission parameters for different vehicle service classes and vehicle duty cycles. Specify the transmission's torque limit for each gear as the engine's maximum torque as determined in 40 CFR 1065.510. Specify the transmission type as Automatic Transmission for all engines and for all engine and vehicle duty cycles, except that the transmission type is Automated Manual Transmission for Heavy HDE operating over the highway cruise cycles or the SET duty cycle. For automatic transmissions set neutral idle to “Y” in the vehicle file. Select gear ratios for each gear as shown in the following table:

| Gear No.  |Spark-ignition HDE, light HDE, and medium HDE—  <br/>all duty cycles|Heavy HDE—  <br/>transient and ftp duty cycles|Heavy HDE—  <br/>cruise and set duty cycles|
|-----------|--------------------------------------------------------------------|----------------------------------------------|-------------------------------------------|
|     1     |                                3.10                                |                     3.51                     |                   12.8                    |
|     2     |                                1.81                                |                     1.91                     |                   9.25                    |
|     3     |                                1.41                                |                     1.43                     |                   6.76                    |
|     4     |                                1.00                                |                     1.00                     |                   4.90                    |
|     5     |                                0.71                                |                     0.74                     |                   3.58                    |
|     6     |                                0.61                                |                     0.64                     |                   2.61                    |
|     7     |                                 —                                  |                      —                       |                   1.89                    |
|     8     |                                 —                                  |                      —                       |                   1.38                    |
|     9     |                                 —                                  |                      —                       |                   1.00                    |
|    10     |                                 —                                  |                      —                       |                   0.73                    |
|Lockup Gear|                                 3                                  |                      3                       |                     —                     |

(3) Run GEM for each simulated vehicle configuration and use the GEM outputs of instantaneous engine speed and engine flywheel torque for each vehicle configuration to generate a 10 Hz transient duty cycle corresponding to each vehicle configuration operating over each vehicle duty cycle. Run GEM for the specified number of vehicle configurations. You may run additional vehicle configurations to represent a wider range of in-use vehicles. Run GEM as follows:

(i) *Determining axle ratio and tire size.* Set the axle ratio, *k*a, and tire size,

![](/graphics/er24ja23.060.gif)

for each vehicle configuration based on the corresponding designated engine speed (*f*nrefA, *f*nrefB, *f*nrefC, *f*nrefD, or *f*ntest as defined in 40 CFR 1065.610(c)(2)) at 65 mi/hr for the transient duty cycle and for the 65 mi/hr highway cruise cycle. Similarly, set these parameters based on the corresponding designated engine speed at 55 mi/hr for the 55 mi/hr highway cruise cycle. Use one of the following equations to determine

![](/graphics/er24ja23.061.gif)and *k*a at each of the defined engine speeds:![](/graphics/er24ja23.062.gif)Where:*f*n[speed] = engine's angular speed as determined in paragraph (c)(3)(ii) or (iii) of this section.*k*topgear = transmission gear ratio in the highest available gear from Table 1 of this section.*v*ref = reference speed. Use 65 mi/hr for the transient cycle and the 65 mi/hr highway cruise cycle and use 55 mi/hr for the 55 mi/hr highway cruise cycle.![](/graphics/er24ja23.063.gif)Example for a vocational Light HDV or vocational Medium HDV with a 6-speed automatic transmission at B speed (Test 3 or 4 in Table 3 of this section):*f*nrefB = 1870 r/min = 31.17 r/s*k*aB = 4.0*k*topgear = 0.61*v*ref = 65 mi/hr = 29.06 m/s![](/graphics/er24ja23.064.gif)

(ii) *Vehicle configurations for Spark-ignition HDE, Light HDE, and Medium HDE.* Test at least eight different vehicle configurations for engines that will be installed in vocational Light HDV or vocational Medium HDV using vehicles in the following table:

![](/graphics/er24ja23.065.gif)

(iii) *Vehicle configurations for Heavy HDE.* Test at least nine different vehicle configurations for engines that will be installed in vocational Heavy HDV and for tractors that are not heavy-haul tractors. Test six different vehicle configurations for engines that will be installed in heavy-haul tractors. Use the settings specific to each vehicle configuration as shown in Table 3 or Table 4 in this section, as appropriate. Engines subject to testing under both Table 3 and Table 4 in this section need not repeat overlapping vehicle configurations, so complete fuel mapping requires testing 12 (not 15) vehicle configurations for those engines. However, the preceding sentence does not apply if you choose to create two separate maps from the vehicle configurations defined in Table 3 and Table 4 in this section. Tables 3 and 4 follow:

![](/graphics/er24ja23.066.gif)

(iv) *Vehicle configurations for mixed-use engines.* If the engine will be installed in a combination of vehicles defined in paragraphs (c)(3)(ii) and (iii) of this section, use good engineering judgment to select at least nine vehicle configurations from Table 2 and Table 3 in this section that best represent the range of vehicles your engine will be sold in. This may require you to define additional representative vehicle configurations. For example, if your engines will be installed in vocational Medium HDV and vocational Heavy HDV, you might select Tests 2, 4, 6 and 8 of Table 2 in this section to represent vocational Medium HDV and Tests 3, 6, and 9 of Table 3 in this section to represent vocational Heavy HDV and add two more vehicle configurations that you define.

(v) *Defining GEM inputs.* Use the defined values in Tables 1 through 4 in this section to set up GEM with the correct regulatory subcategory and vehicle weight reduction.

(d) *Test the engine with GEM cycles.* Test the engine over each of the engine duty cycles generated in paragraph (c) of this section as follows:

(1) Operate the engine over a sequence of required and optional engine duty cycles as follows:

(i) Sort the list of engine duty cycles into three separate groups by vehicle duty cycle: transient vehicle cycle, 55 mi/hr highway cruise cycle, and 65 mi/hr highway cruise cycle.

(ii) Within each group of engine duty cycles derived from the same vehicle duty cycle, first run the engine duty cycle with the highest reference cycle work, followed by the cycle with the lowest cycle work; followed by the cycle with second-highest cycle work, followed by the cycle with the second-lowest cycle work; continuing through all the cycles for that vehicle duty cycle. The series of engine duty cycles to represent a single vehicle duty cycle is a single fuel-mapping sequence. Each engine duty cycle represents a different interval. Repeat the fuel-mapping sequence for the engine duty cycles derived from the other vehicle duty cycles until testing is complete.

(iii) Operate the engine over two full engine duty cycles to precondition before each interval in the fuel-mapping sequence. Precondition the engine before the first and second engine duty cycle in each fuel-mapping sequence by repeating operation with the engine duty cycle with the highest reference cycle work over the relevant vehicle duty cycle. The preconditioning for the remaining cycles in the fuel-mapping sequence consists of operation over the preceding two engine duty cycles in the fuel-mapping sequence (with or without measurement). For transient vehicle duty cycles, start each engine duty cycle within 10 seconds after finishing the preceding engine duty cycle (with or without measurement). For highway cruise cycles, start each engine duty cycle and interval after linearly ramping to the speed and torque setpoints over 5 seconds and stabilizing for 15 seconds.

(2) If the engine has an adjustable warm idle speed setpoint, set it to the value defined in 40 CFR 1037.520(h)(1).

(3) Control speed and torque to meet the cycle validation criteria in 40 CFR 1065.514 for each interval, except that the standard error of the estimate in 40 CFR 1065.514(f)(3) is the only speed criterion that applies if the range of reference speeds is less than 10 percent of the mean reference speed. For spark-ignition gaseous-fueled engines with fuel delivery at a single point in the intake manifold, you may apply the alternative cycle-validation criteria in table 5 to this paragraph (c)(3) for transient testing. Note that 40 CFR part 1065 does not allow reducing cycle precision to a lower frequency than the 10 Hz reference cycle generated by GEM.

|                                               Parameter                                                |Speed|           Torque            |            Power            |
|--------------------------------------------------------------------------------------------------------|-----|-----------------------------|-----------------------------|
|                                          Slope, a<sub>1</sub>                                          |     |                             |                             |
|                              Absolute value of intercept, |a<sub>0</sub>|                              |     |≤3% of maximum mapped torque |                             |
|                                  Standard error of the estimate, SEE                                   |     |≤15% of maximum mapped torque|≤15% of maximum mapped power.|
|                              Coefficient of determination, r<sup>2</sup>                               |     |           ≥0.700            |           ≥0.750.           |
|<sup>a</sup> Cycle-validation criteria apply as specified in 40 CFR 1065.514 unless otherwise specified.|     |                             |                             |

(4) Record measurements using direct and/or indirect measurement of fuel flow as follows:

(i) *Direct fuel-flow measurement.* Record speed and torque and measure fuel consumption with a fuel flow meter for the interval defined by the engine duty cycle. Determine the corresponding mean values for the interval. Use of redundant direct fuel-flow measurements requires our advance approval.

(ii) *Indirect fuel-flow measurement.* Record speed and torque and measure emissions and other inputs needed to run the chemical balance in 40 CFR 1065.655(c) for the interval defined by the engine duty cycle. Determine the corresponding mean values for the interval. Use of redundant indirect fuel-flow measurements requires our advance approval. Measure background concentration as described in 40 CFR 1065.140, except that you may use one of the following methods to apply a single background reading to multiple intervals:

(A) If you use batch sampling to measure background emissions, you may sample periodically into the bag over the course of multiple intervals. If you use this provision, you must apply the same background readings to correct emissions from each of the applicable intervals.

(B) You may determine background emissions by sampling from the dilution air over multiple engine duty cycles. If you use this provision, you must allow sufficient time for stabilization of the background measurement; followed by an averaging period of at least 30 seconds. Use the average of the two background readings to correct the measurement from each engine duty cycle. The first background reading must be taken no greater than 30 minutes before the start of the first applicable engine duty cycle and the second background reading must be taken no later than 30 minutes after the end of the last applicable engine duty cycle. Background readings may not span more than a full fuel-mapping sequence for a vehicle duty cycle.

(5) Warm up the engine as described in 40 CFR 1065.510(b)(2). Within 60 seconds after concluding the warm-up, start the linear ramp of speed and torque over 20 seconds to the first speed and torque setpoint of the preconditioning cycle.

(6) Precondition the engine before the start of testing as described in paragraph (d)(1)(iii) of this section.

(7) Operate the engine over the first engine duty cycle. Record measurements during the interval. Measure and report NOX emissions over each interval as described in paragraph (b)(2) of this section.

(8) Continue testing engine duty cycles that are derived from the other vehicle duty cycles until testing is complete.

(9) You may interrupt the fuel-mapping sequence after completing any interval. You may calibrate analyzers, read and evacuate background bag samples, or sample dilution air for measuring background concentration before restarting. Shut down the engine during any interruption. If you restart the sequence within 30 minutes or less, restart the sequence at paragraph (d)(6) of this section and then restart testing at the next interval in the fuel-mapping sequence. If you restart the sequence after more than 30 minutes, restart the sequence at paragraph (d)(5) of this section and then restart testing at the next interval in the fuel-mapping sequence.

(10) The following provisions apply for infrequent regeneration events, other interruptions during intervals, and otherwise voided intervals:

(i) Stop testing if an infrequent regeneration event occurs during an interval or an interval is interrupted for any other reason. Void the interrupted interval and any additional intervals for which you are not able to meet requirements for measuring background concentration. If the infrequent regeneration event occurs between intervals, void completed intervals only if you are not able to meet requirements for measuring background concentration for those intervals.

(ii) If an infrequent regeneration event occurs, allow the regeneration event to finish with the engine operating at a speed and load that allows effective regeneration.

(iii) If you interrupt testing during an interval, if you restart the sequence within 30 minutes or less, restart the sequence at paragraph (d)(6) of this section and then restart testing at the next interval in the fuel-mapping sequence. If you restart the sequence after more than 30 minutes, restart the sequence at paragraph (d)(5) of this section and then restart testing at the next interval in the fuel-mapping sequence.

(iv) If you void one or more intervals, you must perform additional testing to get results for all intervals. You may rerun a complete fuel-mapping sequence or any contiguous part of the fuel-mapping sequence. If you get a second valid measurement for any interval, use only the result from the last valid interval. If you restart the sequence within 30 minutes or less, restart the sequence at paragraph (d)(6) of this section and then restart testing at the first selected interval in the fuel-mapping sequence. If you restart the sequence after more than 30 minutes, restart the sequence at paragraph (d)(5) of this section and then restart testing at the first selected interval in the fuel-mapping sequence. Continue testing until you have valid results for all intervals. The following examples illustrate possible scenarios for a partial run through a fuel-mapping sequence:

(A) If you voided only the interval associated with the fourth engine duty cycle in the sequence, you may restart the sequence using the second and third engine duty cycles as the preconditioning cycles and stop after completing the interval associated with the fourth engine duty cycle.

(B) If you voided the intervals associated with the fourth and sixth engine duty cycles, you may restart the sequence using the second and third engine duty cycles for preconditioning and stop after completing the interval associated with the sixth engine duty cycle.

(11) You may send signals to the engine controller during the test, such as current transmission gear and vehicle speed, if that allows engine operation to better represent in-use operation.

(12) Calculate the fuel mass, *m*fuel, for each duty cycle using one of the following equations:

(i) Determine fuel-consumption using emission measurements from the raw or diluted exhaust. Calculate the mass of fuel for each duty cycle, *m*fuel[cycle], as follows:

(A) For calculations that use continuous measurement of emissions and continuous CO2 from urea, calculate *m*fuel[cycle] using the following equation:

![](/graphics/er22ap24.186.gif)Eq. 1036.540-3Where:*M*C = molar mass of carbon.*w*Cmeas = carbon mass fraction of fuel (or mixture of fuels) as determined in 40 CFR 1065.655(d), except that you may not use the default properties in 40 CFR 1065.655(e)(5) to determine *α, β,* and *w*C. You may not account for the contribution to *α, β,**γ,* and *δ* of diesel exhaust fluid or other non-fuel fluids injected into the exhaust.*i* = an indexing variable that represents one recorded emission value.*N* = total number of measurements over the duty cycle.*n*1 = exhaust molar flow rate from which you measured emissions according to 40 CFR 1065.655.*x*Ccombdryi = amount of carbon from fuel and any injected fluids in the exhaust per mole of dry exhaust as determined in 40 CFR 1065.655(c).*x*H2Oexhdryi = amount of H2O in exhaust per mole of exhaust as determined in 40 CFR 1065.655(c).Δ*t* = 1/*f*record*M*CO2 = molar mass of carbon dioxide.*m*CO2DEFi = mass emission rate of CO2 resulting from diesel exhaust fluid decomposition over the duty cycle as determined from § 1036.535(b)(9). If your engine does not utilize diesel exhaust fluid for emission control, or if you choose not to perform this correction, set *m*CO2DEFi equal to 0.

*Example:*

*M*C = 12.0107 g/mol*w*Cmeas = 0.867*N* = 6680*n*1 = 2.876 mol/s*n*2 = 2.224 mol/s*x*Ccombdryi1 = 2.61·10−3 mol/mol*x*Ccombdryi2 = 1.91·10−3 mol/mol*x*H2Oexh1 = 3.53·10−2 mol/mol*x*H2Oexh2 = 3.13·10−2 mol/mol*f*record = 10 HzΔ*t* = 1/10 = 0.1 s*M*CO2 = 44.0095 g/mol*m*CO2DEF1 = 0.0726 g/s*m*CO2DEF2= 0.0751 g/s![](/graphics/er22ap24.187.gif)

(B) If you measure batch emissions and continuous CO2 from urea, calculate *m*fuel[cycle] using the following equation:

![](/graphics/er24ja23.069.gif)

(C) If you measure continuous emissions and batch CO2 from urea, calculate *m*fuel[cycle] using the following equation:

![](/graphics/er24ja23.070.gif)

(D) If you measure batch emissions and batch CO2 from urea, calculate *m*fuel[cycle] using the following equation:

![](/graphics/er24ja23.071.gif)

(ii) Manufacturers may choose to measure fuel mass flow rate. Calculate the mass of fuel for each duty cycle, *m*fuel[cycle], as follows:

![](/graphics/er24ja23.072.gif)Where:*i* = an indexing variable that represents one recorded value.*N* = total number of measurements over the duty cycle. For batch fuel mass measurements, set *N* = 1.*m*fueli = the fuel mass flow rate, for each point, *i*, starting from *i* = 1.Δ*t* = 1/*ƒ*record*ƒ*record = the data recording frequency.Example:*N* = 6680*m*fuel1 = 1.856 g/s*m*fuel2 = 1.962 g/s*ƒ*record = 10 HzΔ*t* = 1/10 = 0.1 s*m*fueltransient = (1.856 + 1.962+ . . . +*m*fuel6680) · 0.1*m*fueltransient = 111.95 g

(13) Correct the measured or calculated fuel mass, *m*fuel, for each result to a mass-specific net energy content of a reference fuel as described in § 1036.535(e), replacing *m*fuel with *m*fuel in Eq. 1036.535-4.

(e) *Determine GEM inputs.* Use the results of engine testing in paragraph (d) of this section to determine the GEM inputs for the transient duty cycle and optionally for each of the highway cruise cycles corresponding to each simulated vehicle configuration as follows:

(1) Using the calculated fuel mass consumption values, *m*fuel[cycle], described in paragraph (d) of this section, declare values using the methods described in § 1036.535(g)(2) and (3).

(2) We will determine *m*fuel[cycle] values using the method described in § 1036.535(g)(3).

(3) For the transient cycle, calculate engine output speed per unit vehicle speed,

![](/graphics/er24ja23.073.gif)

by taking the average engine speed measured during the engine test while the vehicle is moving and dividing it by the average vehicle speed provided by GEM. Note that the engine cycle created by GEM has a flag to indicate when the vehicle is moving.

(4) Determine engine idle speed and torque, by taking the average engine speed and torque measured during the engine test while the vehicle is not moving. Note that the engine cycle created by GEM has a flag to indicate when the vehicle is moving.

(5) For the cruise cycles, calculate the average engine output speed, *f*nengine, and the average engine output torque (positive torque only), *T*engine, while the vehicle is moving. Note that the engine cycle created by GEM has a flag to indicate when the vehicle is moving.

(6) Determine positive work according to 40 CFR part 1065, *W*[cycle], by using the engine speed and engine torque measured during the engine test while the vehicle is moving. Note that the engine cycle created by GEM has a flag to indicate when the vehicle is moving.

(7) The following tables illustrate the GEM data inputs corresponding to the different vehicle configurations for a given duty cycle:

(i) For the transient cycle:

![](/graphics/er24ja23.074.gif)

(ii) For the cruise cycles:

|                         Parameter                         |Configuration|   |   |     |   |   |
|-----------------------------------------------------------|-------------|---|---|-----|---|---|
|                             1                             |      2      | 3 | 4 |. . .| n |   |
| m<sub>fuel</sub><sub>[</sub><sub>cycle</sub><sub>]</sub>  |             |   |   |     |   |   |
|f<sub>nengine</sub><sub>[</sub><sub>cycle</sub><sub>]</sub>|             |   |   |     |   |   |
|                 T<sub>engine[cycle]</sub>                 |             |   |   |     |   |   |
|         W<sub>[</sub><sub>cycle</sub><sub>]</sub>         |             |   |   |     |   |   |

[88 FR 4487, Jan. 24, 2023, as amended at 89 FR 29751, Apr. 22, 2024]