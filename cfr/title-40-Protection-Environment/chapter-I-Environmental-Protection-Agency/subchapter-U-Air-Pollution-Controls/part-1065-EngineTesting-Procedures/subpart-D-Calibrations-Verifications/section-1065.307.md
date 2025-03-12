##### § 1065.307 Linearity verification. #####

(a) *Scope and frequency.* Perform linearity verification on each measurement system listed in Table 1 of this section at least as frequently as indicated in Table 1 of § 1065.303, consistent with measurement system manufacturer's recommendations and good engineering judgment. The intent of linearity verification is to determine that a measurement system responds accurately and proportionally over the measurement range of interest. Linearity verification generally consists of introducing a series of at least 10 reference values to a measurement system. The measurement system quantifies each reference value. The measured values are then collectively compared to the reference values by using a least-squares linear regression and the linearity criteria specified in Table 1 of this section.

(b) *Performance requirements.* If a measurement system does not meet the applicable linearity criteria referenced in Table 1 of this section, correct the deficiency by re-calibrating, servicing, or replacing components as needed. Repeat the linearity verification after correcting the deficiency to ensure that the measurement system meets the linearity criteria. Before you may use a measurement system that does not meet linearity criteria, you must demonstrate to us that the deficiency does not adversely affect your ability to demonstrate compliance with the applicable standards in this chapter.

(c) *Procedure.* Use the following linearity verification protocol, or use good engineering judgment to develop a different protocol that satisfies the intent of this section, as described in paragraph (a) of this section:

(1) In this paragraph (c), the letter “y” denotes a generic measured quantity, the superscript over-bar denotes an arithmetic mean (such as *y*), and the subscript “ref” denotes the known or reference quantity being measured.

(2) Use good engineering judgment to operate a measurement system at normal operating conditions. This may include any specified adjustment or periodic calibration of the measurement system.

(3) If applicable, zero the instrument as you would before an emission test by introducing a zero signal. Depending on the instrument, this may be a zero-concentration gas, a reference signal, a set of reference thermodynamic conditions, or some combination of these. For gas analyzers, use a zero gas that meets the specifications of § 1065.750 and introduce it directly at the analyzer port.

(4) If applicable, span the instrument as you would before an emission test by introducing a span signal. Depending on the instrument, this may be a span-concentration gas, a reference signal, a set of reference thermodynamic conditions, or some combination of these. For gas analyzers, use a span gas that meets the specifications of § 1065.750 and introduce it directly at the analyzer port.

(5) If applicable, after spanning the instrument, check zero with the same signal you used in paragraph (c)(3) of this section. Based on the zero reading, use good engineering judgment to determine whether or not to rezero and or re-span the instrument before continuing.

(6) For all measured quantities, use the instrument manufacturer's recommendations and good engineering judgment to select reference values, *y*refi, that cover a range of values that you expect would prevent extrapolation beyond these values during emission testing. We recommend selecting a zero reference signal as one of the reference values for the linearity verification. For pressure, temperature, dewpoint, power, current, voltage, photoacoustic analyzers, and GC-ECD linearity verifications, we recommend at least three reference values. For all other linearity verifications select at least ten reference values.

(7) Use the instrument manufacturer's recommendations and good engineering judgment to select the order in which you will introduce the series of reference values. For example, you may select the reference values randomly to avoid correlation with previous measurements and to avoid hysteresis; you may select reference values in ascending or descending order to avoid long settling times of reference signals; or you may select values to ascend and then descend to incorporate the effects of any instrument hysteresis into the linearity verification.

(8) Generate reference quantities as described in paragraph (d) of this section. For gas analyzers, use gas concentrations known to be within the specifications of § 1065.750 and introduce them directly at the analyzer port.

(9) Introduce a reference signal to the measurement instrument.

(10) Allow time for the instrument to stabilize while it measures the value at the reference condition. Stabilization time may include time to purge an instrument and time to account for its response.

(11) At a recording frequency of at least *f* Hz, specified in Table 1 of § 1065.205, measure the value at the reference condition for 30 seconds (you may select a longer sampling period if the recording update frequency is less than 0.5 Hz) and record the arithmetic mean of the recorded values, *y*i. Refer to § 1065.602 for an example of calculating an arithmetic mean.

(12) Repeat the steps in paragraphs (c)(9) though (11) of this section until measurements are complete at each of the reference conditions.

(13) Use the arithmetic means, *y*i, and reference values, *y*refi, to calculate least-squares linear regression parameters and statistical values to compare to the minimum performance criteria specified in Table 1 of this section. Use the calculations for a floating intercept described in § 1065.602. Using good engineering judgment, you may weight the results of individual data pairs (*i.e.,* (*y*refi, *y*i)), in the linear regression calculations.

(d) *Reference signals.* This paragraph (d) describes recommended methods for generating reference values for the linearity-verification protocol in paragraph (c) of this section. Use reference values that simulate actual values, or introduce an actual value and measure it with a reference-measurement system. In the latter case, the reference value is the value reported by the reference-measurement system. Reference values and reference-measurement systems must be NIST-traceable. We recommend using calibration reference quantities that are NIST-traceable within ±0.5% uncertainty, if not specified elsewhere in this part 1065. Use the following recommended methods to generate reference values or use good engineering judgment to select a different reference:

(1) *Speed.* Run the engine or dynamometer at a series of steady-state speeds and use a strobe, photo tachometer, or laser tachometer to record reference speeds.

(2) *Torque.* Use a series of calibration weights and a calibration lever arm to simulate engine torque. You may instead use the engine or dynamometer itself to generate a nominal torque that is measured by a reference load cell or proving ring in series with the torque-measurement system. In this case, use the reference load cell measurement as the reference value. Refer to § 1065.310 for a torque-calibration procedure similar to the linearity verification in this section.

(3) *Electrical power, current, and voltage.* You must perform linearity verification for either electrical power meters, or for current and voltage meters. Perform linearity verifications using a reference meter and controlled sources of current and voltage. We recommend using a complete calibration system that is suitable for the electrical power distribution industry.

(4) *Fuel and DEF mass flow rate*. Use a gravimetric reference measurement (such as a scale, balance, or mass comparator) and a container. Use a stopwatch or timer to measure the time intervals over which reference masses of fluid pass through the mass flow rate meter. Use good engineering judgment to correct the reference mass flowing through the mass flow rate meter for buoyancy effects from any tubes, temperature probes, or objects submerged in the fluid in the container that are not attached to the container. If the container has any tubes or wires connected to the container, recalibrate the gravimetric reference measurement device with them connected and at normal operating pressure using calibration weights that meet the requirements in § 1065.790. The corrected reference mass that flowed through the mass flow rate meter during a time interval divided by the duration of the time interval is the average reference mass flow rate. For meters that report a different quantity (such as actual volume, standard volume, or moles), convert the reported quantity to mass. For meters that report a cumulative quantity calculate the average measured mass flow rate as the difference in the reported cumulative mass during the time interval divided by the duration of the time interval. For measuring flow rate of gaseous fuel prevent condensation on the fuel container and any attached tubes, fittings, or regulators.

(5) *Flow rates—inlet air, dilution air, diluted exhaust, raw exhaust, or sample flow.* Use a reference flow meter with a blower or pump to simulate flow rates. Use a restrictor, diverter valve, a variable-speed blower or a variable-speed pump to control the range of flow rates. Use the reference meter's response as the reference values.

(i) *Reference flow meters.* Because the flow range requirements for these various flows are large, we allow a variety of reference meters. For example, for diluted exhaust flow for a full-flow dilution system, we recommend a reference subsonic venturi flow meter with a restrictor valve and a blower to simulate flow rates. For inlet air, dilution air, diluted exhaust for partial-flow dilution, raw exhaust, or sample flow, we allow reference meters such as critical flow orifices, critical flow venturis, laminar flow elements, master mass flow standards, or Roots meters. Make sure the reference meter is calibrated and its calibration is NIST-traceable. If you use the difference of two flow measurements to determine a net flow rate, you may use one of the measurements as a reference for the other.

(ii) *Reference flow values.* Because the reference flow is not absolutely constant, sample and record values of *n*refi for 30 seconds and use the arithmetic mean of the values, *n*ref, as the reference value. Refer to § 1065.602 for an example of calculating arithmetic mean.

(6) *Gas division.* Use one of the two reference signals:

(i) At the outlet of the gas-division system, connect a gas analyzer that meets the linearity verification described in this section and has not been linearized with the gas divider being verified. For example, verify the linearity of an analyzer using a series of reference analytical gases directly from compressed gas cylinders that meet the specifications of § 1065.750. We recommend using a FID analyzer or a PMD or MPD O2 analyzer because of their inherent linearity. Operate this analyzer consistent with how you would operate it during an emission test. Connect a span gas containing only a single constituent of interest with balance of purified air or purified N2 to the gas-divider inlet. Use the gas-division system to divide the span gas with purified air or nitrogen. Select gas divisions that you typically use. Use a selected gas division as the measured value. Use the analyzer response divided by the span gas concentration as the reference gas-division value. Because the instrument response is not absolutely constant, sample and record values of *x*refi for 30 seconds and use the arithmetic mean of the values, *x*ref, as the reference value. Refer to § 1065.602 for an example of calculating arithmetic mean.

(ii) Using good engineering judgment and the gas divider manufacturer's recommendations, use one or more reference flow meters to measure the flow rates of the gas divider and verify the gas-division value.

(7) *Continuous constituent concentration.* For reference values, use a series of gas cylinders of known gas concentration containing only a single constituent of interest with balance of purified air or purified N2 or use a gas-division system that is known to be linear with a span gas. Gas cylinders, gas-division systems, and span gases that you use for reference values must meet the specifications of § 1065.750.

(8) *Temperature.* You may perform the linearity verification for temperature measurement systems with thermocouples, RTDs, and thermistors by removing the sensor from the system and using a simulator in its place. Use a NIST-traceable simulator that is independently calibrated and, as appropriate, cold-junction-compensated. The simulator uncertainty scaled to absolute temperature must be less than 0.5% of *T*max. If you use this option, you must use sensors that the supplier states are accurate to better than 0.5% of *T*max compared with their standard calibration curve.

(9) *Mass*. For linearity verification for gravimetric PM balances, fuel mass scales, and DEF mass scales, use external calibration weights that meet the requirements in § 1065.790. Perform the linearity verification for fuel mass scales and DEF mass scales with the in-use container, installing all objects that interface with the container. For example, this includes all tubes, temperature probes, and objects submerged in the fluid in the container; it also includes tubes, fittings, regulators, and wires, and any other objects attached to the container. We recommend that you develop and apply appropriate buoyancy corrections for the configuration of your mass scale during normal testing, consistent with good engineering judgment. Account for the scale weighing a calibration weight instead of fluid if you calculate buoyancy corrections. You may also correct for the effect of natural convection currents from temperature differences between the container and ambient air. Prepare for linearity verification by taking the following steps for vented and unvented containers:

(i) If the container is vented to ambient, fill the container and tubes with fluid above the minimum level used to trigger a fill operation; drain the fluid down to the minimum level; tare the scale; and perform the linearity verification.

(ii) If the container is rigid and not vented, drain the fluid down to the minimum level; fill all tubes attached to the container to normal operating pressure; tare the scale; and perform the linearity verification.

(e) *Measurement systems that require linearity verification.* Table 1 of this section indicates measurement systems that require linearity verification, subject to the following provisions:

(1) Perform linearity verification more frequently based on the instrument manufacturer's recommendation or good engineering judgment.

(2) The expression “*x*min” refers to the reference value used during linearity verification that is closest to zero. This is the value used to calculate the first tolerance in Table 1 of this section using the intercept, *a*0. Note that this value may be zero, positive, or negative depending on the reference values. For example, if the reference values chosen to validate a pressure transducer vary from −10 to −1 kPa, *x*min is −1 kPa. If the reference values used to validate a temperature device vary from 290 to 390 K, *x*min is 290 K.

(3) The expression “max” generally refers to the absolute value of the reference value used during linearity verification that is furthest from zero. This is the value used to scale the first and third tolerances in Table 1 of this section using *a*0 and *SEE*. For example, if the reference values chosen to validate a pressure transducer vary from −10 to −1 kPa, then *p*max is +10 kPa. If the reference values used to validate a temperature device vary from 290 to 390 K, then *T*max is 390 K. For gas dividers where “max” is expressed as, *x*max/*x*span; *x*max is the maximum gas concentration used during the verification, *x*span is the undivided, undiluted, span gas concentration, and the resulting ratio is the maximum divider point reference value used during the verification (typically 1). The following are special cases where “max” refers to a different value:

(i) For linearity verification of a PM balance, *m*max is the typical mass of a PM filter.

(ii) For linearity verification of a torque measurement system used with the engine's primary output shaft, *T*max is the manufacturer's specified peak torque of the lowest torque engine expected during testing.

(iii) For linearity verification of a fuel mass scale, *m*max is determined based on the range of engines and test interval durations expected during testing. It is the minimum, over all engines expected during testing, of the fuel consumption expected over the minimum test interval duration at the engine's maximum fuel rate. If the minimum test interval duration used during testing does not change with engine power or if the minimum test interval duration used during testing increases with engine power, *m*max is given by Eq. 1065.307-1. Calculate *m*max using the following equation:

![](/graphics/er29jn21.172.gif)Where:*m*max,fuel = the manufacturer's specified maximum fuel rate on the lowest-power engine expected during testing.*t*min = the minimum test interval duration expected during testing. If the minimum test interval duration decreases with engine power, evaluate Eq. 1065.307-1 for the range of engines expected during testing and use the minimum calculated value of *m*max,fuel scale.

(iv) For linearity verification of a DEF mass scale, *m*max is 10% of the value determined for a fuel mass scale in paragraph (e)(3)(iii) of this section. You may determine *m*max for a DEF mass scale by evaluating *m*max for a fuel mass scale based only on the DEF-using engines expected during testing.

(v) For linearity verification of a fuel flow rate meter, *m*max is the manufacturer's specified maximum fuel rate of the lowest-power engine expected during testing.

(vi) For linearity verification of a DEF flow rate meter, *m*max is 10% of the manufacturer's specified maximum fuel rate of the lowest-power DEF-using engine expected during testing.

(vii) For linearity verification of an intake-air flow rate meter, *n*max is the manufacturer's specified maximum intake-air flow rate (converted to molar flow rate) of the lowest-power engine expected during testing.

(viii) For linearity verification of a raw exhaust flow rate meter, *n*max is the manufacturer's specified maximum exhaust flow rate (converted to molar flow rate) of the lowest-power engine expected during testing.

(ix) For linearity verification of an electrical-power measurement system used to determine the engine's primary output shaft torque, *P*max is the manufacturer's specified maximum power of the lowest-power engine expected during testing.

(x) For linearity verification of an electrical-current measurement system used to determine the engine's primary output shaft torque, *I*max is the maximum current expected on the lowest-power engine expected during testing.

(xi) For linearity verification of an electrical-voltage measurement system used to determine the engine's primary output shaft torque, *V*max is the minimum peak voltage expected on the range of engines expected during testing.

(4) The specified ranges are inclusive. For example, a specified range of 0.98-1.02 for *a*1 means 0.98≤*a*1≤1.02.

(5) Table 2 of this section describes optional verification procedures you may perform instead of linearity verification for certain systems. The following provisions apply for the alternative verification procedures:

(i) Perform the propane check verification described in § 1065.341 at the frequency specified in Table 1 of § 1065.303.

(ii) Perform the carbon balance error verification described in § 1065.543 on all test sequences that use the corresponding system. It must also meet the restrictions listed in Table 2 of this section. You may evaluate the carbon balance error verification multiple ways with different inputs to validate multiple flow-measurement systems.

(6) You must meet the *a*1 criteria for these quantities only if the absolute value of the quantity is required, as opposed to a signal that is only linearly proportional to the actual value.

(7) Linearity verification is required for the following temperature measurements:

(i) The following temperature measurements always require linearity verification:

(A) Air intake.

(B) Aftertreatment bed(s), for engines tested with aftertreatment devices subject to cold-start testing.

(C) Dilution air for gaseous and PM sampling, including CVS, double-dilution, and partial-flow systems.

(D) PM sample.

(E) Chiller sample, for gaseous sampling systems that use thermal chillers to dry samples and use chiller temperature to calculate the dewpoint at the outlet of the chiller. For your testing, if you choose to use a high alarm temperature setpoint for the chiller temperature as a constant value in determining the amount of water removed from the emission sample, you may use good engineering judgment to verify the accuracy of the high alarm temperature setpoint instead of linearity verification on the chiller temperature. To verify that the alarm trip point value is no less than 2.0 °C below the reference value at the trip point, we recommend that you input a reference simulated temperature signal below the alarm trip point and increase this signal until the high alarm trips.

(F) Transmission oil.

(G) Axle gear oil.

(ii) Linearity verification is required for the following temperature measurements if these temperature measurements are specified by the engine manufacturer:

(A) Fuel inlet.

(B) Air outlet to the test cell's charge air cooler air outlet, for engines tested with a laboratory heat exchanger that simulates an installed charge air cooler.

(C) Coolant inlet to the test cell's charge air cooler, for engines tested with a laboratory heat exchanger that simulates an installed charge air cooler.

(D) Oil in the sump/pan.

(E) Coolant before the thermostat, for liquid-cooled engines.

(8) Linearity verification is required for the following pressure measurements:

(i) The following pressure measurements always require linearity verification:

(A) Air intake restriction.

(B) Exhaust back pressure as required in § 1065.130(h).

(C) Barometer.

(D) CVS inlet gage pressure where the raw exhaust enters the tunnel.

(E) Sample dryer, for gaseous sampling systems that use either osmotic-membrane or thermal chillers to dry samples. For your testing, if you choose to use a low alarm pressure setpoint for the sample dryer pressure as a constant value in determining the amount of water removed from the emission sample, you may use good engineering judgment to verify the accuracy of the low alarm pressure setpoint instead of linearity verification on the sample dryer pressure. To verify that the trip point value is no more than 4.0 kPa above the reference value at the trip point, we recommend that you input a reference pressure signal above the alarm trip point and decrease this signal until the low alarm trips.

(ii) Linearity verification is required for the following pressure measurements if these pressure measurements are specified by the engine manufacturer:

(A) The test cell's charge air cooler and interconnecting pipe pressure drop, for turbo-charged engines tested with a laboratory heat exchanger that simulates an installed charge air cooler.

(B) Fuel outlet.

(f) *Performance criteria for measurement systems.* Table 1 follows:

|                                                                                        Measurement system                                                                                        |     Quantity     |           Linearity criteria           |              |                                      |      |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------|----------------------------------------|--------------|--------------------------------------|------|
|                                                                        |x<sub>min</sub> (a<sub>1</sub>-1)+a<sub>0</sub>|                                                                         |  a<sub>1</sub>   |                  SEE                   |r <sup>2</sup>|                                      |      |
|                                                                                              Speed                                                                                               |  f<sub>n</sub>   |        ≤0.05% ·f<sub>nmax</sub>        |  0.98-1.02   |        ≤2% ·f<sub>nmax</sub>         |≥0.990|
|                                                                                              Torque                                                                                              |        T         |         ≤1% · T<sub>max</sub>          |  0.98-1.02   |        ≤2% · T<sub>max</sub>         |≥0.990|
|                                                                                         Electrical power                                                                                         |        P         |         ≤1% · P<sub>max</sub>          |  0.98-1.02   |        ≤2% · P<sub>max</sub>         |≥0.990|
|                                                                                             Current                                                                                              |        I         |         ≤1% · I<sub>max</sub>          |  0.98-1.02   |        ≤2% · I<sub>max</sub>         |≥0.990|
|                                                                                             Voltage                                                                                              |        U         |         ≤1% · U<sub>max</sub>          |  0.98-1.02   |        ≤2% · U<sub>max</sub>         |≥0.990|
|                                                                                          Fuel flow rate                                                                                          |        m         |         ≤1% · m<sub>max</sub>          |  0.98-1.02   |        ≤2% · m<sub>max</sub>         |≥0.990|
|                                                                                         Fuel mass scale                                                                                          |        m         |        ≤0.3% · m<sub>max</sub>         | 0.996-1.004  |       ≤0.4% · m<sub>max</sub>        |≥0.999|
|                                                                                          DEF flow rate                                                                                           |        m         |         ≤1% · m<sub>max</sub>          |  0.98-1.02   |        ≤2% · m<sub>max</sub>         |≥0.990|
|                                                                                          DEF mass scale                                                                                          |        m         |        ≤0.3% · m<sub>max</sub>         | 0.996-1.004  |       ≤0.4% · m<sub>max</sub>        |≥0.999|
|                                                                                Intake-air flow rate <sup>a</sup>                                                                                 |        n         |         ≤1% · n<sub>max</sub>          |  0.98-1.02   |        ≤2% · n<sub>max</sub>         |≥0.990|
|                                                                               Dilution air flow rate <sup>a</sup>                                                                                |        n         |         ≤1% · n<sub>max</sub>          |  0.98-1.02   |        ≤2% · n<sub>max</sub>         |≥0.990|
|                                                                              Diluted exhaust flow rate <sup>a</sup>                                                                              |        n         |         ≤1% · n<sub>max</sub>          |  0.98-1.02   |        ≤2% · n<sub>max</sub>         |≥0.990|
|                                                                                Raw exhaust flow rate <sup>a</sup>                                                                                |        n         |         ≤1% · n<sub>max</sub>          |  0.98-1.02   |         ≤2% ·n<sub>max</sub>         |≥0.990|
|                                                                              Batch sampler flow rates <sup>a</sup>                                                                               |        n         |         ≤1% · n<sub>max</sub>          |  0.98-1.02   |         ≤2% ·n<sub>max</sub>         |≥0.990|
|                                                                                           Gas dividers                                                                                           |x/x<sub>span</sub>|≤0.5% · x<sub>max/x</sub><sub>span</sub>|  0.98-1.02   |≤2% · x<sub>max/x</sub><sub>span</sub>|≥0.990|
|                                                                               Gas analyzers for laboratory testing                                                                               |        x         |        ≤0.5% · x<sub>max</sub>         |  0.99-1.01   |        ≤1% · x<sub>max</sub>         |≥0.998|
|                                                                                 Gas analyzers for field testing                                                                                  |        x         |         ≤1% · x<sub>max</sub>          |  0.99-1.01   |        ≤1% · x<sub>max</sub>         |≥0.998|
|                                                                          Electrical aerosol analyzer for field testing                                                                           |        x         |         ≤5% · x<sub>max</sub>          |  0.85-1.15   |        ≤10% · x<sub>max</sub>        |≥0.950|
|                                                                             Photoacoustic analyzer for field testing                                                                             |        x         |         ≤5% · x<sub>max</sub>          |  0.90-1.10   |        ≤10% · x<sub>max</sub>        |≥0.980|
|                                                                                            PM balance                                                                                            |        m         |         ≤1% · m<sub>max</sub>          |  0.99-1.01   |        ≤1% · m<sub>max</sub>         |≥0.998|
|                                                                                            Pressures                                                                                             |        p         |         ≤1% · p<sub>max</sub>          |  0.99-1.01   |        ≤1% · p<sub>max</sub>         |≥0.998|
|                                                                Dewpoint for intake air, PM-stabilization and balance environments                                                                | T<sub>dew</sub>  |       ≤0.5% · T<sub>dewmax</sub>       |  0.99-1.01   |      ≤0.5% ·T<sub>dewmax</sub>       |≥0.998|
|                                                                                   Other dewpoint measurements                                                                                    | T<sub>dew</sub>  |        ≤1% · T<sub>dewmax</sub>        |  0.99-1.01   |       ≤1% · T<sub>dewmax</sub>       |≥0.998|
|                                                                       Analog-to-digital conversion of temperature signals                                                                        |        T         |         ≤1% · T<sub>max</sub>          |  0.99-1.01   |        ≤1% · T<sub>max</sub>         |≥0.998|
|<sup>a</sup> For flow meters that determine volumetric flow rate, V<sub>std</sub>, you may substitute V<sub>std</sub> for n as the quantity and substitute V<sub>stdmax</sub> for n<sub>max</sub>.|                  |                                        |              |                                      |      |

(g) *Alternative verification procedures.* Table 2 follows:

|                                                     Measurement system                                                      |§ 1065.341|§ 1065.543|                                                                                                                             Restrictions for § 1065.543                                                                                                                              |
|-----------------------------------------------------------------------------------------------------------------------------|----------|----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                    Intake-air flow rate                                                     |   Yes    |   Yes    |Determine raw exhaust flow rate using the intake-air flow rate signal as an input into Eq. 1065.655-24 and determine mass of CO<sub>2</sub> over each test interval input into Eq. 1065.643-6 using samples taken from the raw exhaust (continuous or bag, and with or without a PFD).|
|                                               Dilution air flow rate for CVS                                                |   Yes    |    No    |                                                                                                                                     Not allowed.                                                                                                                                     |
|                                              Diluted exhaust flow rate for CVS                                              |   Yes    |   Yes    |                                                         Determine mass of CO<sub>2</sub> over each test interval input into Eq. 1065.643-6 using samples taken from the CVS (continuous or bag, and with or without a PFD).                                                          |
|                                           Raw exhaust flow rate for exhaust stack                                           |   Yes    |   Yes    |                                                     Determine mass of CO<sub>2</sub> over each test interval input into Eq. 1065.643-6 using samples taken from the raw exhaust (continuous or bag, and with or without a PFD).                                                      |
|Flow measurements in a PFD (usually dilution air and diluted exhaust streams) used to determine the dilution ratio in the PFD|   Yes    |   Yes    |                                                                       Determine mass of CO<sub>2</sub> over each test interval input into Eq. 1065.643-6 using samples taken from the PFD (continuous or bag).                                                                       |
|                                                  Batch sampler flow rates                                                   |   Yes    |    No    |                                                                                                                                     Not allowed.                                                                                                                                     |
|                                                     Fuel mass flow rate                                                     |    No    |   Yes    |                                                                              Determine mass of a carbon-carrying fluid stream used as an input into Eq. 1065.643-1 using the fuel mass flow rate meter.                                                                              |
|                                                       Fuel mass scale                                                       |    No    |   Yes    |                                                                                   Determine mass of a carbon-carrying fluid stream used as an input into Eq. 1065.643-1 using the fuel mass scale.                                                                                   |

[79 FR 23763, Apr. 28, 2014, as amended at 86 FR 34538, June 29, 2021; 87 FR 64865, Oct. 26, 2022; 88 FR 4673, Jan. 24, 2023]