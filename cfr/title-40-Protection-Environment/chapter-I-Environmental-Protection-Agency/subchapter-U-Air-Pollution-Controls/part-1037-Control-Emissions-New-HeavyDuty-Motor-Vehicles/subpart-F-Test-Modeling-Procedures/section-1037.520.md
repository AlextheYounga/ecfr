##### § 1037.520 Modeling CO2 emissions to show that vehicles comply with standards. #####

This section describes how to use the Greenhouse gas Emissions Model (GEM) to show compliance with the CO2 standards of §§ 1037.105 and 1037.106. Use GEM version 2.0.1 to demonstrate compliance with Phase 1 standards; use GEM Phase 2, Version 4.0 to demonstrate compliance with Phase 2 and Phase 3 standards (both incorporated by reference, see § 1037.810). Use good engineering judgment when demonstrating compliance using GEM.

(a) *General modeling provisions.* To run GEM, enter all applicable inputs as specified by the model.

(1) GEM inputs apply for Phase 1 standards as follows:

(i) Model year and regulatory subcategory (see § 1037.230).

(ii) Coefficient of aerodynamic drag or drag area, as described in paragraph (b) of this section (tractors only).

(iii) Steer and drive tire rolling resistance, as described in paragraph (c) of this section.

(iv) Vehicle speed limit, as described in paragraph (d) of this section (tractors only).

(v) Vehicle weight reduction, as described in paragraph (e) of this section (tractors only for Phase 1).

(vi) Automatic engine shutdown systems, as described in § 1037.660 (only for Class 8 sleeper cabs). Enter a GEM input value of 5.0 g/ton-mile, or an adjusted value as specified in § 1037.660.

(2) For Phase 2 and later vehicles, the GEM inputs described in paragraphs (a)(1)(i) through (v) of this section continue to apply. Note that the provisions in this part related to vehicle speed limiters and automatic engine shutdown systems are available for Phase 2 and later vocational vehicles. The rest of this section describes additional GEM inputs for demonstrating compliance with Phase 2 and later standards. Simplified versions of GEM apply for limited circumstances as follows:

(i) You may use default engine fuel maps for glider kits as described in § 1037.635.

(ii) If you certify vehicles to the custom-chassis standards specified in § 1037.105(h), run GEM by identifying the vehicle type and entering “NA” instead of what would otherwise apply for, tire revolutions per mile, engine information, transmission information, drive axle ratio, axle efficiency, and aerodynamic improvement as specified in paragraphs (c)(1), (f), (g)(1) and (3), (i), and (m) of this section, respectively. Incorporate other GEM inputs as specified in this section.

(b) *Coefficient of aerodynamic drag and drag area for tractors.* Determine the appropriate drag area, *C*d*A*, for tractors as described in this paragraph (b). Use the recommended method or an alternate method to establish a value for *C*d*A*, expressed in m2 to one decimal place, as specified in § 1037.525. Where we allow you to group multiple configurations together, measure *C*d*A* of the worst-case configuration.

(1) Except as specified in paragraph (b)(2) of this section, determine the Phase 1 bin level for your vehicle based on measured *C*d*A* values as shown in the following tables:

|     Tractor type     |Bin level|If your  <br/>measured  <br/>C<sub>D</sub>A (M<sup>2</sup>) is . .|Then your C<sub>D</sub> input is . . .|
|----------------------|---------|------------------------------------------------------------------|--------------------------------------|
|  High-Roof Day Cabs  |  Bin I  |                               ≥8.0                               |                 0.79                 |
|                      | Bin II  |                             7.1-7.9                              |                 0.72                 |
|                      | Bin III |                             6.2-7.0                              |                 0.63                 |
|                      | Bin IV  |                             5.6-6.1                              |                 0.56                 |
|                      |  Bin V  |                               ≤5.5                               |                 0.51                 |
|High-Roof Sleeper Cabs|  Bin I  |                               ≥7.6                               |                 0.75                 |
|                      | Bin II  |                             6.8-7.5                              |                 0.68                 |
|                      | Bin III |                             6.3-6.7                              |                 0.60                 |
|                      | Bin IV  |                             5.6-6.2                              |                 0.52                 |
|                      |  Bin V  |                               ≤5.5                               |                 0.47                 |

|        Tractor type         |    Bin level     |If your  <br/>measured  <br/>C<sub>D</sub>A (M<sup>2</sup>) is . .|Then your C<sub>D</sub> input is . . .|
|-----------------------------|------------------|------------------------------------------------------------------|--------------------------------------|
|Low-Roof Day and Sleeper Cabs|Bin I  <br/>Bin II|                         ≥5.1  <br/>≤5.0                          |           0.77  <br/>0.71            |
|Mid-Roof Day and Sleeper Cabs|      Bin I       |                               ≥5.6                               |                 0.87                 |
|                             |      Bin II      |                               ≤5.5                               |                 0.82                 |

(2) For Phase 1 low- and mid-roof tractors, you may instead determine your drag area bin based on the drag area bin of an equivalent high-roof tractor. If the high-roof tractor is in Bin I or Bin II, then you may assume your equivalent low- and mid-roof tractors are in Bin I. If the high-roof tractor is in Bin III, Bin IV, or Bin V, then you may assume your equivalent low- and mid-roof tractors are in Bin II.

(3) For Phase 2 and later tractors other than heavy-haul tractors, determine bin levels and *C*d*A* inputs as follows:

(i) Determine bin levels for high-roof tractors based on aerodynamic test results as specified in § 1037.525 and summarized in the following table:

|Tractor type|Bin I|Bin II |Bin III|Bin IV | Bin V |Bin VI |Bin VII|
|------------|-----|-------|-------|-------|-------|-------|-------|
|  Day Cabs  |≥7.2 |6.6-7.1|6.0-6.5|5.5-5.9|5.0-5.4|4.5-4.9| ≤4.4  |
|Sleeper Cabs|≥6.9 |6.3-6.8|5.7-6.2|5.2-5.6|4.7-5.1|4.2-4.6| ≤4.1  |

(ii) For low- and mid-roof tractors, you may either use the same bin level that applies for an equivalent high-roof tractor as shown in table 3 to paragraph (b)(3)(i) of this section, or you may determine your bin level based on aerodynamic test results as described in table 4 to this paragraph (b)(3)(ii).

|Tractor type |Bin I|Bin II |Bin III|Bin IV | Bin V |Bin VI |Bin VII|
|-------------|-----|-------|-------|-------|-------|-------|-------|
|Low-Roof Cabs|≥5.4 |4.9-5.3|4.5-4.8|4.1-4.4|3.8-4.0|3.5-3.7| ≤3.4  |
|Mid-Roof Cabs|≥5.9 |5.5-5.8|5.1-5.4|4.7-5.0|4.4-4.6|4.1-4.3| ≤4.0  |

(iii) Determine the *C*d*A* input according to the tractor's bin level as described in the following table:

|     Tractor type     |Bin I|Bin II|Bin III|Bin IV|Bin V|Bin VI|Bin VII|
|----------------------|-----|------|-------|------|-----|------|-------|
|  High-Roof Day Cabs  |7.45 | 6.85 | 6.25  | 5.70 |5.20 | 4.70 | 4.20  |
|High-Roof Sleeper Cabs|7.15 | 6.55 | 5.95  | 5.40 |4.90 | 4.40 | 3.90  |
|    Low-Roof Cabs     |6.00 | 5.60 | 5.15  | 4.75 |4.40 | 4.10 | 3.80  |
|    Mid-Roof Cabs     |7.00 | 6.65 | 6.25  | 5.85 |5.50 | 5.20 | 4.90  |

(4) Note that, starting in model year 2027, GEM internally reduces *C*d*A* for high-roof tractors by 0.3 m2 to simulate adding a rear fairing to the standard trailer.

(c) *Tire revolutions per mile and rolling resistance.* You must have a tire revolutions per mile (TRPM) and a tire rolling resistance level (TRRL) for each tire configuration. For purposes of this section, you may consider tires with the same SKU number to be the same configuration. Determine TRRL input values separately for drive and steer tires; determine TRPM only for drive tires.

(1) Use good engineering judgment to determine a tire's revolutions per mile to the nearest whole number as specified in SAE J1025 (incorporated by reference, see § 1037.810). Note that for tire sizes that you do not test, we will treat your analytically derived revolutions per mile the same as test results, and we may perform our own testing to verify your values. We may require you to test a sample of additional tire sizes that we select.

(2) Measure tire rolling resistance in newton per kilonewton as specified in ISO 28580 (incorporated by reference, see § 1037.810), except as specified in this paragraph (c). Use good engineering judgment to ensure that your test results are not biased low. You may ask us to identify a reference test laboratory to which you may correlate your test results. Prior to beginning the test procedure in Section 7 of ISO 28580 for a new bias-ply tire, perform a break-in procedure by running the tire at the specified test speed, load, and pressure for (60±2) minutes.

(3) For each tire design tested, measure rolling resistance of at least three different tires of that specific design and size. Perform the test at least once for each tire. Calculate the arithmetic mean of these results to the nearest 0.1 N/kN and use this value or any higher value as your GEM input for TRRL. You must test at least one tire size for each tire model, and may use engineering analysis to determine the rolling resistance of other tire sizes of that model. Note that for tire sizes that you do not test, we will treat your analytically derived rolling resistances the same as test results, and we may perform our own testing to verify your values. We may require you to test a small sub-sample of untested tire sizes that we select.

(4) If you obtain your test results from the tire manufacturer or another third party, you must obtain a signed statement from the party supplying those test results to verify that tests were conducted according to the requirements of this part. Such statements are deemed to be submissions to EPA.

(5) For tires marketed as light truck tires that have load ranges C, D, or E, use as the GEM input TRRL multiplied by 0.87.

(6) For vehicles with at least three drive axles or for vehicles with more than three axles total, use good engineering judgment to combine tire rolling resistance into three values (steer, drive 1, and drive 2) for use in GEM. This may require performing a weighted average of tire rolling resistance from multiple axles based on the typical load on each axle. For liftable axles, calculate load- and time-weighted values to represent the load and the amount of time these tires are in contact with the ground during typical in-use operation.

(7) For vehicles with a single rear axle, enter “NA” as the TRRL value for drive axle 2.

(d) *Vehicle speed limit.* If the vehicles will be equipped with a vehicle speed limiter, input the maximum vehicle speed to which the vehicle will be limited (in miles per hour rounded to the nearest 0.1 mile per hour) as specified in § 1037.640. Use good engineering judgment to ensure the limiter is tamper resistant. We may require you to obtain preliminary approval for your designs.

(e) *Vehicle weight reduction.* Develop a weight-reduction as a GEM input as described in this paragraph (e). Enter the sum of weight reductions as described in this paragraph (e), or enter zero if there is no weight reduction. For purposes of this paragraph (e), high-strength steel is steel with tensile strength at or above 350 MPa.

(1) Vehicle weight reduction inputs for wheels are specified relative to dual-wide tires with conventional steel wheels. For purposes of this paragraph (e)(1), an aluminum alloy qualifies as light-weight if a dual-wide drive wheel made from this material weighs at least 21 pounds less than a comparable conventional steel wheel. The inputs are listed in table 6 to this paragraph (e)(1). For example, a tractor or vocational vehicle with aluminum steer wheels and eight (4×2) dual-wide aluminum drive wheels would have an input of 210 pounds (2×21 + 8×21).

|                                                     Tire type                                                     |            Material             |Weight  <br/>reduction—  <br/>Phase 1   <br/>(pounds  <br/>per wheel)|Weight  <br/>reduction—  <br/>Phase 2 and later  <br/>(pounds  <br/>per wheel)|
|-------------------------------------------------------------------------------------------------------------------|---------------------------------|---------------------------------------------------------------------|------------------------------------------------------------------------------|
|                                Wide-Base Single Drive Tire with . . .<sup>a</sup>                                 |           Steel Wheel           |                                 84                                  |                                      84                                      |
|                                                                                                                   |         Aluminum Wheel          |                                 139                                 |                                     147                                      |
|                                                                                                                   |Light-Weight Aluminum Alloy Wheel|                                 147                                 |                                     147                                      |
|                                   Steer Tire or Dual-wide Drive Tire with . . .                                   |    High-Strength Steel Wheel    |                                  8                                  |                                      8                                       |
|                                                                                                                   |         Aluminum Wheel          |                                 21                                  |                                      25                                      |
|                                                                                                                   |Light-Weight Aluminum Alloy Wheel|                                 30                                  |                                      25                                      |
|<sup>a</sup> The weight reduction for wide-base tires accounts for reduced tire weight relative to dual-wide tires.|                                 |                                                                     |                                                                              |

(2) Weight reduction inputs for tractor components other than wheels are specified in the following table:

|    Weight reduction technologies    |Aluminum|High-strength  <br/>steel|Thermoplastic|
|-------------------------------------|--------|-------------------------|-------------|
|                Door                 |   20   |            6            |             |
|                Roof                 |   60   |           18            |             |
|            Cab rear wall            |   49   |           16            |             |
|              Cab floor              |   56   |           18            |             |
|    Hood Support Structure System    |   15   |            3            |             |
|        Hood and Front Fender        |        |                         |     65      |
|        Day Cab Roof Fairing         |        |                         |     18      |
|      Sleeper Cab Roof Fairing       |   75   |           20            |     40      |
|      Aerodynamic Side Extender      |        |                         |     10      |
|  Fairing Support Structure System   |   35   |            6            |             |
| Instrument Panel Support Structure  |   5    |            1            |             |
|    Brake Drums—Drive (set of 4)     |  140   |           74            |             |
|  Brake Drums—Non Drive (set of 2)   |   60   |           42            |             |
|             Frame Rails             |  440   |           87            |             |
|           Crossmember—Cab           |   15   |            5            |             |
|       Crossmember—Suspension        |   25   |            6            |             |
|Crossmember—Non Suspension (set of 3)|   15   |            5            |             |
|             Fifth Wheel             |  100   |           25            |             |
|          Radiator Support           |   20   |            6            |             |
|     Fuel Tank Support Structure     |   40   |           12            |             |
|                Steps                |   35   |            6            |             |
|               Bumper                |   33   |           10            |             |
|              Shackles               |   10   |            3            |             |
|             Front Axle              |   60   |           15            |             |
|    Suspension Brackets, Hangers     |  100   |           30            |             |
|          Transmission Case          |   50   |           12            |             |
|           Clutch Housing            |   40   |           10            |             |
|  Fairing Support Structure System   |   35   |            6            |             |
|     Drive Axle Hubs (set of 4)      |   80   |           20            |             |
|         Non Drive Hubs (2)          |   40   |            5            |             |
|        Two-piece driveshaft         |   20   |            5            |             |
|  Transmission/Clutch Shift Levers   |   20   |            4            |             |

(3) Weight-reduction inputs for vocational-vehicle components other than wheels are specified in the following table:

|                                          Component                                           |       Material        |Vehicle type|   |   |
|----------------------------------------------------------------------------------------------|-----------------------|------------|---|---|
|                                          Light HDV                                           |Medium HDV <sup>b</sup>| Heavy HDV  |   |   |
|                                     Axle Hubs—Non-Drive                                      |       Aluminum        |     40     |40 |   |
|                                     Axle Hubs—Non-Drive                                      |  High Strength Steel  |     5      | 5 |   |
|                                        Axle—Non-Drive                                        |       Aluminum        |     60     |60 |   |
|                                        Axle—Non-Drive                                        |  High Strength Steel  |     15     |15 |   |
|                                    Brake Drums—Non-Drive                                     |       Aluminum        |     60     |60 |   |
|                                    Brake Drums—Non-Drive                                     |  High Strength Steel  |     42     |42 |   |
|                                       Axle Hubs—Drive                                        |       Aluminum        |     40     |80 |   |
|                                       Axle Hubs—Drive                                        |  High Strength Steel  |     10     |20 |   |
|                                      Brake Drums—Drive                                       |       Aluminum        |     70     |140|   |
|                                      Brake Drums—Drive                                       |  High Strength Steel  |     37     |74 |   |
|                                 Suspension Brackets, Hangers                                 |       Aluminum        |     67     |100|   |
|                                 Suspension Brackets, Hangers                                 |  High Strength Steel  |     20     |30 |   |
|                                       Crossmember—Cab                                        |       Aluminum        |     10     |15 |15 |
|                                       Crossmember—Cab                                        |  High Strength Steel  |     2      | 5 | 5 |
|                                  Crossmember—Non-Suspension                                  |       Aluminum        |     15     |15 |15 |
|                                  Crossmember—Non-Suspension                                  |  High Strength Steel  |     5      | 5 | 5 |
|                                    Crossmember—Suspension                                    |       Aluminum        |     15     |25 |25 |
|                                    Crossmember—Suspension                                    |  High Strength Steel  |     6      | 6 | 6 |
|                                          Driveshaft                                          |       Aluminum        |     12     |40 |50 |
|                                          Driveshaft                                          |  High Strength Steel  |     5      |10 |12 |
|                                         Frame Rails                                          |       Aluminum        |    120     |300|440|
|                                         Frame Rails                                          |  High Strength Steel  |     40     |40 |87 |
|        <sup>a</sup> Weight-reduction values apply per vehicle unless otherwise noted.        |                       |            |   |   |
|<sup>b</sup> For Medium HDV with 6×4 or 6×2 axle configurations, use the values for Heavy HDV.|                       |            |   |   |

(4) GEM inputs associated with powertrain testing include powertrain family, transmission calibration identifier, test data from 40 CFR 1036.545, and the powertrain test configuration (dynamometer connected to transmission output or wheel hub). You do not need to identify or provide inputs for transmission gear ratios, fuel map data, or engine torque curves, which would otherwise be required under paragraph (f) of this section.

(5) You may ask to apply the off-cycle technology provisions of § 1037.610 for weight reductions not covered by this paragraph (e).

(f) *Engine characteristics.* Enter information from the engine manufacturer to describe the installed engine and its operating parameters as described in 40 CFR 1036.505. Note that you do not need fuel consumption at idle for tractors.

(g) *Vehicle characteristics.* Enter the following information to describe the vehicle and its operating parameters:

(1) Transmission make, model, and type. Also identify the gear ratio for every available forward gear to two decimal places, the input torque limit for each of the forward gears, and, if applicable, the lowest gear involving a locked torque converter. Count forward gears as being available only if the vehicle has the hardware and software to allow operation in those gears. For vehicles with a manual transmission, GEM applies a 2% emission increase relative to automated manual transmissions. If your vehicle has a dual-clutch transmission, use good engineering judgment to determine if it can be accurately represented in GEM as an automated manual transmission. We may require you to perform a powertrain test with dual-clutch transmissions to show that they can be properly simulated as an automated manual transmission.

(2) Drive axle make, model, and configuration. Select a drive axle configuration to represent your vehicle for modeling.

(i) 4x2: One drive axle and one non-drive axle. This includes vehicles with two drive axles where one of the drive axles is disconnectable and that disconnectable drive axle is designed to be connected only when the vehicle is driven off-road or in slippery conditions if at least one of the following is true:

(A) The input and output of the disconnectable axle is mechanically disconnected from the drive shaft and the wheels when the axle is in 4x2 configuration.

(B) You provide power loss data generated according to § 1037.560 for the combination of both drive axles, where the disconnectable drive axle is in the disconnected configuration.

(ii) 6x2: One drive axle and two non-drive axles.

(iii) 6x4: Two or more drive axles, or more than three total axles. Note that this includes, for example, a vehicle with two drive axles out of four total axles (otherwise known as an 8x4 configuration).

(iv) 6x4D: One non-drive axle and two drive axles where one of the two drive axles is automatically disconnectable such that the axle can switch between 6x2 and 6x4 configurations. You may select this configuration only if at least one of the following is true:

(A) The input and output of the disconnectable axle is mechanically disconnected from the drive shaft and the wheels when the axle is in the 6x2 configuration.

(B) You provide power loss data generated according to § 1037.560 for the combination of both drive axles, where the disconnectable drive axle is in the disconnected configuration.

(3) Drive axle ratio, *k*a. If a vehicle is designed with two or more user-selectable axle ratios, use the drive axle ratio that is expected to be engaged for the greatest driving distance. If the vehicle does not have a drive axle, such as a hybrid vehicle with direct electric drive, let *k*a = 1.

(4) GEM inputs associated with powertrain testing include powertrain family, transmission calibration identifier, test data from 40 CFR 1036.545, and the powertrain test configuration (dynamometer connected to transmission output or wheel hub). You do not need to identify or provide inputs for transmission gear ratios, fuel map data, or engine torque curves, which would otherwise be required under paragraph (f) of this section.

(h) *Idle speed and idle-reduction technologies.* The following provisions apply for engine idling:

(1) For engines with no adjustable warm idle speed, input vehicle idle speed as the manufacturer's declared warm idle speed. For engines with adjustable warm idle speed, input your vehicle idle speed as follows:

|                                                                                                            If your vehicle is a                                                                                                            |         And your engine is subject to          |Your default vehicle idle speed is <sup>a</sup>|
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------|-----------------------------------------------|
|                                                                                                               (i) Heavy HDV                                                                                                                |compression-ignition or spark-ignition standards|                  600 r/min.                   |
|                                                                                                          (ii) Medium HDV tractor                                                                                                           |         compression-ignition standards         |                  700 r/min.                   |
|                                                                                              (iii) Light HDV or Medium HDV vocational vehicle                                                                                              |         compression-ignition standards         |                  750 r/min.                   |
|                                                                                                        (iv) Light HDV or Medium HDV                                                                                                        |            spark-ignition standards            |                  600 r/min.                   |
|<sup>a</sup> If the default idle speed is above or below the engine manufacturer's whole range of declared warm idle speeds, use the manufacturer's maximum or minimum declared warm idle speed, respectively, instead of the default value.|                                                |                                               |

(2) Identify whether your vehicle has qualifying idle-reduction technologies, subject to the qualifying criteria in § 1037.660, as follows:

(i) Stop-start technology and automatic engine shutdown systems apply for vocational vehicles. See paragraph (j) of this section for automatic engine shutdown systems for tractors.

(ii) Neutral idle applies for tractors and vocational vehicles.

(i) *Axle, transmission, and torque converter characterization.* You may characterize the axle, transmission, and torque converter using axle efficiency maps as described in § 1037.560, transmission efficiency maps as described in § 1037.565, and torque converter capacity factors and torque ratios as described in § 1037.570 to replace the default values in GEM. If you obtain your test results from the axle manufacturer, transmission manufacturer, torque converter manufacturer or another third party, you must obtain a signed statement from the party supplying those test results to verify that tests were conducted according to the requirements of this part. Such statements are deemed to be submissions to EPA.

(j) *Additional reduction technologies.* Enter input values in GEM as follows to characterize the percentage CO2 emission reduction corresponding to certain technologies and vehicle configurations, or enter 0:

(1) *Intelligent controls.* Enter 2 for tractors with predictive cruise control. This includes any cruise control system that incorporates satellite-based global-positioning data for controlling operator demand. For tractors without predictive cruise control and for all vocational vehicles, enter 1.5 if they have neutral coasting or the installed engine deactivates all cylinders closing all intake and exhaust valves when operator demand is zero while the vehicle is in motion, unless good engineering judgment indicates that a lower percentage should apply.

(2) *Accessory load.* Enter the following values related to accessory loads; if more than one item applies, enter the sum of those values:

(i) If vocational vehicles have electrically powered pumps for steering, enter 0.5 for vocational vehicles certified with the Regional duty cycle, and enter 1 for other vocational vehicles.

(ii) If tractors have electrically powered pumps for both steering and engine cooling, enter 1.

(iii) If vehicles have a high-efficiency air conditioning compressor, enter 0.5 for tractors, 0.5 for vocational Heavy HDV, and 1 for other vocational vehicles. This includes all electrically powered compressors. It also include mechanically powered compressors if the coefficient of performance improves by 10 percent or greater over the baseline design, consistent with the provisions for improved evaporators and condensers in 40 CFR 86.1868-12(h)(5).

(3) *Tire-pressure systems.* Enter 1.2 for vehicles with automatic tire inflation systems on all axles (1.1 for Multi-Purpose and Urban vocational vehicles). Enter 1.0 for vehicles with tire pressure monitoring systems on all axles (0.9 for Multi-Purpose and Urban vocational vehicles). If vehicles use a mix of the two systems, treat them as having only tire pressure monitoring systems.

(4) *Extended-idle reduction.* Enter values as shown in the following table for sleeper cabs equipped with idle-reduction technology meeting the requirements of § 1037.660 that are designed to automatically shut off the main engine after 300 seconds or less:

|          Technology           |   GEM input values    |   |
|-------------------------------|-----------------------|---|
|          Adjustable           |Tamper-  <br/>resistant|   |
|      Standard AES system      |           1           | 4 |
|        With diesel APU        |           3           | 4 |
|       With battery APU        |           5           | 6 |
|   With automatic stop-start   |           3           | 3 |
|With fuel-operated heater (FOH)|           2           | 3 |
|    With diesel APU and FOH    |           4           | 5 |
|   With battery APU and FOH    |           5           | 6 |
|    With stop-start and FOH    |           4           | 5 |

(5) *Other.* Additional GEM inputs may apply as follows:

(i) Enter 0.9 and 1.7, respectively, for school buses and coach buses that have at least seven available forward gears.

(ii) If we approve off-cycle technology under § 1037.610 in the form of an improvement factor, enter the improvement factor expressed as a percentage reduction in CO2 emissions. (*Note:* In the case of approved off-cycle technologies whose benefit is quantified as a g/ton-mile credit, apply the credit to the GEM result, not as a GEM input value.)

(k) *Vehicles with hybrid power take-off.* For vocational vehicles, determine the delta PTO emission result of your engine and hybrid power take-off system as described in § 1037.540.

(l) [Reserved]

(m) *Aerodynamic improvements for vocational vehicles.* For vocational vehicles certified using the Regional duty cycle, enter Δ*C*d*A* values to account for using aerodynamic devices as follows:

(1) Enter 0.2 for vocational vehicles with an installed rear fairing if the vehicle is at least 7 m long with a minimum frontal area of 8 m2.

(2) For vehicles at least 11 m long with a minimum frontal area of 9 m2, enter 0.5 if the vehicle has both skirts and a front fairing, and enter 0.3 if it has only one of those devices.

(3) You may determine input values for these or other technologies based on aerodynamic measurements as described in § 1037.527.

(n) *Alternate fuels.* For fuels other than those identified in GEM, perform the simulation by identifying the vehicle as being diesel-fueled if the engine is subject to the compression-ignition standard, or as being gasoline-fueled if the engine is subject to the spark-ignition standards. Correct the engine or powertrain fuel map for mass-specific net energy content as described in 40 CFR 1036.535(b).

[86 FR 34467, June 29, 2021, as amended at 87 FR 45265, July 28, 2022; 88 FR 4642, Jan. 24, 2023; 89 FR 29780, Apr. 22, 2024]