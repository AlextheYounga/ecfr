##### § 1037.540 Special procedures for testing vehicles with hybrid power take-off. #####

This section describes optional procedures for quantifying the reduction in greenhouse gas emissions for vehicles as a result of running power take-off (PTO) devices with a hybrid energy delivery system. See 40 CFR 1036.545 for powertrain testing requirements that apply for drivetrain hybrid systems. The procedures are written to test the PTO by ensuring that the engine produces all of the energy with no net change in stored energy (charge-sustaining), and for plug-in hybrid electric vehicles, also allowing for drawing down the stored energy (charge-depleting). The full charge-sustaining test for the hybrid vehicle is from a fully charged rechargeable energy storage system (RESS) to a depleted RESS and then back to a fully charged RESS. You must include all hardware for the PTO system. You may ask us to modify the provisions of this section to allow testing hybrid vehicles that use a technology other than batteries for storing energy, consistent with good engineering judgment. For plug-in hybrid electric vehicles, use a utility factor to properly weight charge-sustaining and charge-depleting operation as described in paragraph (f)(3) of this section.

(a) Select two vehicles for testing as follows:

(1) Select a vehicle with a hybrid energy delivery system to represent the range of PTO configurations that will be covered by the test data. If your test data will represent more than one PTO configuration, use good engineering judgment to select the configuration with the maximum number of PTO circuits that has the smallest potential reduction in greenhouse gas emissions.

(2) Select an equivalent conventional vehicle as specified in § 1037.615.

(b) Measure PTO emissions from the fully warmed-up conventional vehicle as follows:

(1) Without adding a restriction, instrument the vehicle with pressure transducers at the outlet of the hydraulic pump for each circuit. Perform pressure measurements with a frequency of at least 1 Hz.

(2) Operate the PTO system with no load for at least 15 seconds. Measure gauge pressure and record the average value over the last 10 seconds (*p*min). For hybrid PTO systems the measured pressure with no load is typically zero. Apply maximum operator demand to the PTO system until the pressure relief valve opens and pressure stabilizes; measure gauge pressure and record the average value over the last 10 seconds (*p*max).

(3) Denormalize the PTO duty cycle in appendix B of this part using the following equation:

![](/graphics/er24ja23.078.gif)Where:*p*refi = the reference pressure at each point *i* in the PTO cycle.*p*i = the normalized pressure at each point *i* in the PTO cycle (relative to pmax).pmax = the mean maximum pressure measured in paragraph (b)(2) of this section.pmin = the mean minimum pressure measured in paragraph (b)(2) of this section.

(4) If the PTO system has two circuits, repeat paragraph (b)(2) and (3) of this section for the second PTO circuit.

(5) Install a system to control pressures in the PTO system during the cycle.

(6) Start the engine.

(7) Depending on the number of circuits the PTO system has, operate the vehicle over one or concurrently over both of the denormalized PTO duty cycles in appendix B of this part. Measure emissions during operation over each duty cycle using the provisions of 40 CFR part 1066.

(8) Measured pressures must meet the cycle-validation specifications in the following table for each test run over the duty cycle:

|                                                                                        Parameter <sup>a</sup>                                                                                        |            Pressure             |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------|
|                                                                                         Slope, a<sub>1</sub>                                                                                         |  0.950 ≤a<sub>1</sub> ≤1.030.   |
|                                                                             Absolute value of intercept, |a<sub>0</sub>|                                                                             |≤2.0% of maximum mapped pressure.|
|                                                                                 Standard error of the estimate, SEE                                                                                  |≤10% of maximum mapped pressure. |
|                                                                             Coefficient of determination, r<sup>2</sup>                                                                              |             ≥0.970.             |
|<sup>a</sup> Determine values for specified parameters as described in 40 CFR 1065.514(e) by comparing measured values to denormalized pressure values from the duty cycle in appendix B of this part.|                                 |

(c) Measure PTO emissions from the fully warmed-up hybrid vehicle as follows:

(1) Perform the steps in paragraphs (b)(1) through (5) of this section.

(2) Prepare the vehicle for testing by operating it as needed to stabilize the RESS at a full state of charge (or equivalent for vehicles that use a technology other than batteries for storing energy).

(i) For plug-in hybrid electric vehicles, we recommend charging the battery with an external electrical source.

(ii) For other vehicles, we recommend running back-to-back PTO tests until engine operation is initiated to charge the RESS. The RESS should be fully charged once engine operation stops. The ignition should remain in the “on” position.

(3) Turn the vehicle and PTO system off while the sampling system is being prepared.

(4) Turn the vehicle and PTO system on such that the PTO system is functional, whether it draws power from the engine or a battery.

(5) Operate the vehicle over one or both of the denormalized PTO duty cycles without turning the vehicle off, until the engine starts and then shuts down. This may require running multiple repeats of the PTO duty cycles. For non-PHEV systems that are not plug-in hybrid systems, the test cycle is completed once the engine shuts down. For plug-in hybrid systems, continue running until the PTO hybrid is running in a charge-sustaining mode such that the “End of Test” requirements defined in 40 CFR 1066.501(a)(3) are met. Measure emissions as described in paragraph (b)(7) of this section. Use good engineering judgment to minimize the variability in testing between the two types of vehicles.

(6) For plug-in hybrid electric vehicles, follow 40 CFR 1066.501(a)(3) to divide the test into charge-depleting and charge-sustaining operation.

(7) Apply cycle-validation criteria as described in paragraph (b)(8) of this section to both charge-sustaining and charge-depleting operation.

(d) Calculate the equivalent distance driven based on operating time for each section of the PTO portion of the test as applicable by determining the time of the test and applying the conversion factor in paragraph (d)(4) of this section. For testing where fractions of a cycle were run (for example, where three cycles are completed and the halfway point of a fourth PTO cycle is reached before the engine starts and shuts down again), calculate the time of the test, *t*test, as follows:

(1) Add up the time run for all complete tests.

(2) For fractions of a test, use the following equation to calculate the time:

![](/graphics/er29jn21.129.gif)Where:*i* = an indexing variable that represents one recorded value.*N* = number of measurement intervals.*p*circuit-1,i = normalized pressure command from circuit 1 of the PTO cycle for each point, *i,* starting from *i* = 1.*p*circuit-2,i = normalized pressure command from circuit 2 of the PTO cycle for each point, *i,* starting from *i* = 1. Let *p*circuit-2 = 0 if there is only one circuit.pcircuit-1 = the mean normalized pressure command from circuit 1 over the entire PTO cycle.pcircuit-2 = the mean normalized pressure command from circuit 2 over the entire PTO cycle. Let pcircuit-2 = 0 if there is only one circuit.Δ*t* = the time interval between measurements. For example, at 100 Hz, Δ*t* = 0.0100 seconds.

(3) Sum the time from the complete cycles and from the partial cycle.

(4) Divide the total PTO operating time from paragraph (d)(3) of this section by a conversion factor of 0.0144 hr/mi for Phase 1 and 0.0217 hr/mi for Phase 2 and later to determine the equivalent distance driven. The conversion factors are based on estimates of average vehicle speed and PTO operating time as a percentage of total engine operating time; the Phase 2 and later conversion factor is calculated from an average speed of 27.1 mi/hr and PTO operation 37% of engine operating time, as follows:

![](/graphics/er22ap24.218.gif)Eq. 1037.540-2a

(e) For Phase 1, calculate combined cycle-weighted emissions of the four duty cycles for vocational vehicles, for both the conventional and hybrid PTO vehicle tests, as follows:

(1) Calculate the CO2 emission rates in grams per test without rounding for both the conventional vehicle and the charge-sustaining and charge-depleting portions of the test for the hybrid vehicle as applicable.

(2) Divide the CO2 mass from the PTO cycle by the distance determined in paragraph (d)(4) of this section and the standard payload as defined in § 1037.801 to get the CO2 emission rate in g/ton-mile. For plug-in hybrid electric vehicles follow paragraph (f)(3) of this section to calculate utility factor weighted CO2 emissions in g/ton-mile.

(3) Calculate the g/ton-mile emission rate for the driving portion of the test specified in § 1037.510 and add this to the CO2 g/ton-mile emission rate for the PTO portion of the test.

(4) Follow the provisions of § 1037.615 to calculate improvement factors and benefits for advanced technologies.

(f) For Phase 2 and later, calculate the delta PTO fuel results for input into GEM during vehicle certification as follows:

(1) Determine fuel consumption by calculating the mass of fuel for each test in grams, *m*fuelPTO, without rounding, as described in 40 CFR 1036.540(d)(12) for both the conventional vehicle and the charge-sustaining and charge-depleting portions of the test for the hybrid vehicle as applicable.

(2) Divide the fuel mass by the applicable distance determined in paragraph (d)(4) of this section and the appropriate standard payload as defined in § 1037.801 to determine the fuel-consumption rate in g/ton-mile.

(3) For plug-in hybrid electric vehicles calculate the utility factor weighted fuel-consumption rate in g/ton-mile, as follows:

(i) Determine the utility factor fraction for the PTO system from the table in appendix E of this part using interpolation based on the total time of the charge-depleting portion of the test as determined in paragraphs (c)(6) and (d)(3) of this section.

(ii) Weight the emissions from the charge-sustaining and charge-depleting portions of the test to determine the utility factor-weighted fuel mass, *m*fuelUF[cycle]plug-in, using the following equation:

![](/graphics/er22ap24.219.gif)Eq. 1037.540-3Where:*i* = an indexing variable that represents one test interval.*N* = total number of charge-depleting test intervals.*m*fuelPTOCD = total mass of fuel per ton-mile in the charge-depleting portion of the test for each test interval, *i,* starting from *i* = 1.*UF*DCDi = utility factor fraction at time *t*CDi as determined in paragraph (f)(3)(i) of this section for each test interval, *i,* starting from *i* = 1.*j* = an indexing variable that represents one test interval.*M* = total number of charge-sustaining test intervals.*m*fuelPTOCS = total mass of fuel per ton-mile in the charge-sustaining portion of the test for each test interval, *j,* starting from *j* = 1.*UF*RCD = utility factor fraction at the full charge-depleting time, *t*CD, as determined by interpolating the utility factor curve in appendix E to this part. *t*CD is the sum of the time over *N* charge-depleting test intervals.

(4) Calculate the difference between the conventional PTO emissions result and the hybrid PTO emissions result for input into GEM.

(g) If the PTO system has more than two circuits, apply the provisions of this section using good engineering judgment.

[81 FR 74048, Oct. 25, 2016, as amended at 86 FR 34477, June 29, 2021; 87 FR 64864, Oct. 26, 2022; 88 FR 4642, Jan. 24, 2023; 89 FR 29785, Apr. 22, 2024]