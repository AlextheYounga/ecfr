##### § 1065.656 Hydrogen-based chemical balances of fuel, DEF, intake air, and exhaust. #####

(a) *General.* Chemical balances of fuel, DEF, intake air, and exhaust may be used to calculate flows, the amount of water in their flows, and the wet concentration of constituents in their flows. See § 1065.520(f) for information about when to use this hydrogen-based chemical balance procedure. With one flow rate of either fuel, intake air, or exhaust, you may use chemical balances to determine the flows of the other two. For example, you may use chemical balances along with either intake air or fuel flow to determine raw exhaust flow. Note that chemical balance calculations allow measured values for the flow rate of diesel exhaust fluid for engines with urea-based selective catalytic reduction.

(b) *Procedures that require chemical balances.* We require chemical balances when you determine the following:

(1) A value proportional to total work, when you choose to determine brake-specific emissions as described in § 1065.650(f).

(2) Raw exhaust molar flow rate either from measured intake air molar flow rate or from fuel mass flow rate as described in paragraph (f) of this section.

(3) Raw exhaust molar flow rate from measured intake air molar flow rate and dilute exhaust molar flow rate as described in paragraph (g) of this section.

(4) The amount of water in a raw or diluted exhaust flow, *x*H2Oexh, when you do not measure the amount of water to correct for the amount of water removed by a sampling system. Correct for removed water according to § 1065.659.

(5) The calculated total dilution air flow when you do not measure dilution air flow to correct for background emissions as described in § 1065.667(c) and (d).

(c) *Chemical balance procedure.* The calculations for a chemical balance involve a system of equations that require iteration. We recommend using a computer to solve this system of equations. You must guess the initial values of two of the following quantities: the amount of hydrogen in the measured flow, *x*H2exhdry, the fraction of dilution air in diluted exhaust, *x*dil/exhdry, and the amount of intake air required to produce actual combustion products per mole of dry exhaust, *x*int/exhdry. You may use time-weighted mean values of intake air humidity and dilution air humidity in the chemical balance; as long as your intake air and dilution air humidities remain within tolerances of ±0.0025 mol/mol of their respective mean values over the test interval. For each emission concentration, *x,* and amount of water, *x*H2Oexh, you must determine their completely dry concentrations, *x*dry and *x*H2Oexhdry. You must also use your fuel mixture's carbon mass fraction, *w*C, hydrogen mass fraction, *w*H, oxygen mass fraction, *w*O, sulfur mass fraction, *w*S, and nitrogen mass fraction, *w*N; you may optionally account for diesel exhaust fluid (or other fluids injected into the exhaust), if applicable. Calculate *w*C, wH, *w*O, wS, and *w*N as described in paragraphs (d) and (e) of this section. You may alternatively use any combination of default values and measured values as described in paragraphs (d) and (e) of this section. Use the following steps to complete a chemical balance:

(1) Convert your measured concentrations such as *x*H2meas, xNH3meas, *x*CO2meas, *x*COmeas, *x*THCmeas, *x*O2meas, *x*H2meas, *x*NOmeas, *x*NO2meas, and *x*H2Oint, to dry concentrations by dividing them by one minus the amount of water present during their respective measurements; for example: *x*H2Omeas, *x*H2OxO2meas, *x*H2OxNOmeas, and *x*H2Oint. If the amount of water present during a “wet” measurement is the same as an unknown amount of water in the exhaust flow, *x*H2Oexh, iteratively solve for that value in the system of equations. If you measure only total NOX and not NO and NO2 separately, use good engineering judgment to estimate a split in your total NOX concentration between NO and NO2 for the chemical balances. For example, if you measure emissions from a stoichiometric combustion engine, you may assume all NOX is NO. For a lean-burn combustion engine, you may assume that your molar concentration of NOX, *x*NOx, is 75% NO and 25% NO2. For NO2 storage aftertreatment systems, you may assume *x*NOx is 25% NO and 75% NO2. Note that for calculating the mass of NOX emissions, you must use the molar mass of NO2 for the effective molar mass of all NOX species, regardless of the actual NO2 fraction of NOX.

(2) Enter the equations in paragraph (c)(5) of this section into a computer program to iteratively solve for *x*H2exhdry, *x*dil/exhdry, and *x*int/exhdry. Use good engineering judgment to guess initial values for *x*H2exhdry, *x*dil/exhdry, and *x*int/exhdry. We recommend guessing an initial amount of hydrogen of 0 mol/mol. We recommend guessing an initial *x*int/exhdry of 1 mol/mol. We also recommend guessing an initial *x*dil/exhdry of 0.8 mol/mol. Iterate values in the system of equations until the most recently updated guesses are all within ±1% or ±1 µmol/mol, whichever is larger, of their respective most recently calculated values.

(3) Use the following symbols and subscripts in the equations for performing the chemical balance calculations in this paragraph (c):

| x<sub>[emission]meas</sub>  |                                                                        Amount of measured emission in the sample at the respective gas analyzer.                                                                        |
|-----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  x<sub>[emission]exh</sub>  |                                                                                       Amount of emission per dry mole of exhaust.                                                                                       |
|x<sub>[emission]exhdry</sub> |                                                                                     Amount of emission per dry mole of dry exhaust.                                                                                     |
|x<sub>H2O[emission]meas</sub>|                                           Amount of H<sub>2</sub> O in sample at emission-detection location; measure or estimate these values according to § 1065.145(e)(2).                                           |
|    x<sub>Ccombdry</sub>     |                                                               Amount of carbon from fuel and any injected fluids in the exhaust per mole of dry exhaust.                                                                |
|    x<sub>Hcombdry</sub>     |                                                              Amount of hydrogen from fuel and any injected fluids in the exhaust per mole of dry exhaust.                                                               |
|     x<sub>dil/exh</sub>     |                                                                                Amount of dilution gas or excess air per mole of exhaust.                                                                                |
|   x<sub>dil/exhdry</sub>    |                                                                            amount of dilution gas and/or excess air per mole of dry exhaust.                                                                            |
|    x<sub>Hcombdry</sub>     |                                                              Amount of hydrogen from fuel and any injected fluids in the exhaust per mole of dry exhaust.                                                               |
|   x<sub>int/exhdry</sub>    |                                                      Amount of intake air required to produce actual combustion products per mole of dry (raw or diluted) exhaust.                                                      |
|   x<sub>raw/exhdry</sub>    |                                                               Amount of undiluted exhaust, without excess air, per mole of dry (raw or diluted) exhaust.                                                                |
|     x<sub>CO2int</sub>      |                                                                               Amount of intake air CO<sub>2</sub> per mole of intake air.                                                                               |
|    x<sub>CO2intdry</sub>    |                amount of intake air CO<sub>2</sub> per mole of dry intake air; you may use x<sub>CO2intdry</sub> = 375 µmol/mol, but we recommend measuring the actual concentration in the intake air.                 |
|     x<sub>H2Oint</sub>      |                                                               Amount of H<sub>2</sub> O in the intake air, based on a humidity measurement of intake air.                                                               |
|    x<sub>H2Ointdry</sub>    |                                                                            Amount of intake air H<sub>2</sub> O per mole of dry intake air.                                                                             |
|      x<sub>O2int</sub>      |                                                                               Amount of intake air O<sub>2</sub> per mole of intake air.                                                                                |
|     x<sub>CO2dil</sub>      |                                                                             Amount of dilution gas CO<sub>2</sub> per mole of dilution gas.                                                                             |
|    x<sub>CO2dildry</sub>    |Amount of dilution gas CO<sub>2</sub> per mole of dry dilution gas; if you use air as diluent, you may use x<sub>CO2dildry</sub> = 375 µmol/mol, but we recommend measuring the actual concentration in the dilution gas.|
|     x<sub>H2Odil</sub>      |                                                                            Amount of dilution gas H<sub>2</sub> O per mole of dilution gas.                                                                             |
|    x<sub>H2Odildry</sub>    |                                                                          Amount of dilution gas H<sub>2</sub> O per mole of dry dilution gas.                                                                           |
|              τ              |                                                                              Effective carbon content of the fuel and any injected fluids.                                                                              |
|              χ              |                                                                             Effective hydrogen content of the fuel and any injected fluids.                                                                             |
|              ϕ              |                                                                              Effective oxygen content of the fuel and any injected fluids.                                                                              |
|              ξ              |                                                                              Effective sulfur content of the fuel and any injected fluids.                                                                              |
|              ω              |                                                                             Effective nitrogen content of the fuel and any injected fluids.                                                                             |
|        w<sub>C</sub>        |                                                                  Carbon mass fraction of the fuel (or mixture of test fuels) and any injected fluids.                                                                   |
|        w<sub>H</sub>        |                                                                 Hydrogen mass fraction of the fuel (or mixture of test fuels) and any injected fluids.                                                                  |
|        w<sub>O</sub>        |                                                                  Oxygen mass fraction of the fuel (or mixture of test fuels) and any injected fluids.                                                                   |
|        w<sub>S</sub>        |                                                                  Sulfur mass fraction of the fuel (or mixture of test fuels) and any injected fluids.                                                                   |
|        w<sub>N</sub>        |                                                                 Nitrogen mass fraction of the fuel (or mixture of test fuels) and any injected fluids.                                                                  |

(4) Use the equations specified in this section to iteratively solve for *x*int/exhdry, *x*dil/exhdry, and *x*H2exhdry. The following exceptions apply:

(i) For *x*H2exhdry multiple equations are provided, see table 2 to paragraph (c)(6) of this section to determine for which cases the equations apply.

(ii) The calculation of *x*O2exhdry is only required when *x*O2meas is measured.

(iii) The calculation of *x*NH3exhdry is only required for engines that use ammonia as fuel and engines that are subject to NH3 measurement under the standard setting part, for all other engines *x*NH3exhdry may be set to zero.

(iv) The calculation of *x*CO2exhdry is only required for engines that use carbon-containing fuels or fluids, either as single fuel or as part of the fuel mixture, and for engines that are subject to CO2 measurement under the standard setting part, for all other engines *x*CO2exhdry may be set to a value that yields for *x*Ccombdry a value of zero. (v) The calculation of *x*COexhdry and *x*THCexhdry is only required for engines that use carbon-containing fuels and for engines that are subject to CO and THC measurement under the standard setting part, for all other engines *x*COexhdry and *x*THCexhdry may be set to zero. (vi) The calculation of *x*N2Oexhdry is only required for engines that are subject to N2O measurement under the standard setting part, for all other engines *x*N2Oexhdry may be set to zero.

(5) The chemical balance equations are as follows:

xCcombdry = *x*co2exhdry + *x*coexhdry + *x*THCexhdry − *x*co2dil · *x*dil/exhdry − *x*co2int · *x*int/exhdryEq. 1065.656-1![](/graphics/er22ap24.236.gif)Eq. 1065.656-2![](/graphics/er22ap24.237.gif)Eq. 1065.656-3![](/graphics/er22ap24.238.gif)Eq. 1065.656-4![](/graphics/er22ap24.239.gif)Eq. 1065.656-5![](/graphics/er22ap24.240.gif)Eq. 1065.656-6 (see table 2 of this section)![](/graphics/er22ap24.241.gif)Eq. 1065.656-7 (see table 2 of this section)![](/graphics/er22ap24.242.gif)Eq. 1065.656-8![](/graphics/er22ap24.243.gif)Eq. 1065.656-9![](/graphics/er22ap24.244.gif)Eq. 1065.656-10![](/graphics/er22ap24.245.gif)Eq. 1065.656-11![](/graphics/er22ap24.246.gif)Eq. 1065.656-12![](/graphics/er22ap24.247.gif)Eq. 1065.656-13![](/graphics/er22ap24.248.gif)Eq. 1065.656-14![](/graphics/er22ap24.249.gif)Eq. 1065.656-15![](/graphics/er22ap24.250.gif)Eq. 1065.656-16 (see table 2 of this section)![](/graphics/er22ap24.251.gif)Eq. 1065.656-17![](/graphics/er22ap24.252.gif)Eq. 1065.656-18![](/graphics/er22ap24.253.gif)Eq. 1065.656-19![](/graphics/er22ap24.254.gif)Eq. 1065.656-20![](/graphics/er22ap24.255.gif)Eq. 1065.656-21![](/graphics/er22ap24.256.gif)Eq. 1065.656-22![](/graphics/er22ap24.257.gif)Eq. 1065.656-23

(6) Depending on your measurements, use the equations and guess the quantities specified in the following table:

|    When measuring     |                   Guess . . .                   |                Calculate . . .                |
|-----------------------|-------------------------------------------------|-----------------------------------------------|
|(i) x<sub>O2meas</sub> | x<sub>int/exhdry</sub> and x<sub>H2exhdry</sub> |(A) x<sub>H2exhdry</sub> using Eq. 1065.656-7. |
|                       |                                                 |(B) x<sub>O2exhdry</sub> using Eq. 1065.656-16.|
|(ii) x<sub>H2meas</sub>|x<sub>int/exhdry</sub> and x<sub>dil/exhdry</sub>|(A) x<sub>H2exhdry</sub> using Eq. 1065.656-6. |
|                       |                                                 |                (B) [Reserved]                 |

(7) The following example is a solution for xint/exhdry,xdil/exhdry, and xHOexhdry using the equations in paragraph (c)(5) of this section:

![](/graphics/er22ap24.259.gif)![](/graphics/er22ap24.260.gif)

(d) *Mass fractions of fuel.* (1) For fuels other than carbon-containing fuels determine the mass fractions of fuel *W*C, *W*H, *W*O, *W*S, and *W*N, based on the fuel properties as determined in paragraph (e) of this section. Calculate *W*C, *W*H, *W*O, *W*S, and *W*N using the following equations:

![](/graphics/er22ap24.261.gif)Eq. 1065.656-24![](/graphics/er22ap24.262.gif)Eq. 1065.656-25![](/graphics/er22ap24.263.gif)Eq. 1065.656-26![](/graphics/er22ap24.264.gif)Eq. 1065.656-27![](/graphics/er22ap24.265.gif)Eq. 1065.656-28Where:*w*C = carbon mass fraction of the fuel and any injected fluids.*w*H = hydrogen mass fraction of the fuel and any injected fluids.*w*O = oxygen mass fraction of the fuel and any injected fluids.*w*S = sulfur mass fraction of the fuel and any injected fluids.*w*N = nitrogen mass fraction of the fuel and any injected fluids.*τ* = effective carbon content of the fuel and any injected fluids.*M*C = molar mass of carbon.*χ* = effective hydrogen content of the fuel and any injected fluids.*M*H = molar mass of hydrogen.*ϕ* = effective oxygen content of the fuel and any injected fluids.*M*O = molar mass of oxygen.*ξ* = effective sulfur content of the fuel and any injected fluids.*M*S = molar mass of nitrogen.*ω* = effective nitrogen content of the fuel and any injected fluids.*M*N = molar mass of nitrogen.

*Example for NH*3*fuel:*

*τ* = 0*χ* = 3*ϕ* = 0*ξ* = 0*ω* = 1*M*C = 12.0107 g/mol*M*H = 1.00794 g/mol*M*O = 15.9994 g/mol*M*S = 32.065 g/mol*M*N = 14.0067 g/mol![](/graphics/er22ap24.266.gif)*w*C = 0 g/g*w*H = 0.1775530 g/g*w*O = 0 g/g*w*S = 0 g/g*w*N = 0.8224470 g/g

(2) For carbon-containing fuels and diesel exhaust fluid determine the mass fractions of fuel, *W*C, *W*H, *W*O, *W*S, and *W*N, based on properties determined according to § 1065.655(d). Calculate *W*C, *W*H, *W*O, *W*S, and *W*N using the following equations:

![](/graphics/er22ap24.267.gif)Eq. 1065.656-29![](/graphics/er22ap24.268.gif)Eq. 1065.656-30![](/graphics/er22ap24.269.gif)Eq. 1065.656-31![](/graphics/er22ap24.270.gif)Eq. 1065.656-32![](/graphics/er22ap24.271.gif)Eq. 1065.656-33Where:*w*C = carbon mass fraction of the fuel and any injected fluids.*w*H = hydrogen mass fraction of the fuel and any injected fluids.*w*O = oxygen mass fraction of the fuel and any injected fluids.*w*S = sulfur mass fraction of the fuel and any injected fluids.*w*N = nitrogen mass fraction of the fuel and any injected fluids.*M*C = molar mass of carbon.*α* = atomic hydrogen-to-carbon ratio of the fuel and any injected fluids.*M*H = molar mass of hydrogen.*β* = atomic oxygen-to-carbon ratio of the fuel and any injected fluids.*M*O = molar mass of oxygen.*γ* = atomic sulfur-to-carbon ratio of the fuel and any injected fluids.*M*S = molar mass of sulfur.*δ* = atomic nitrogen-to-carbon ratio of the fuel and any injected fluids.*M*N = molar mass of nitrogen.

*Example:*

*α* = 1.8*β* = 0.05*γ* = 0.0003*δ* = 0.0001*M*C = 12.0107*M*H = 1.00794*M*O = 15.9994*M*S = 32.065*M*N = 14.0067![](/graphics/er22ap24.272.gif)

(3) For nonconstant fuel mixtures, you must account for the varying proportions of the different fuels. This paragraph (d)(3) generally applies for dual-fuel and flexible-fuel engines, but optionally it may also be applied if diesel exhaust fluid or other fluids injected into the exhaust are injected in a way that is not strictly proportional to fuel flow. Account for these varying concentrations either with a batch measurement that provides averaged values to represent the test interval, or by analyzing data from continuous mass rate measurements. Application of average values from a batch measurement generally applies to situations where one fluid is a minor component of the total fuel mixture; consistent with good engineering judgment. Calculate *W*C, *W*H, *W*O, *W*S, and *W*N of the fuel mixture using the following equations:

![](/graphics/er22ap24.273.gif)Eq. 1065.656-34![](/graphics/er22ap24.274.gif)Eq. 1065.656-35![](/graphics/er22ap24.275.gif)Eq. 1065.656-36![](/graphics/er22ap24.276.gif)Eq. 1065.656-37![](/graphics/er22ap24.277.gif)Eq. 1065.656-38*Where:**w*C = carbon mass fraction of the mixture of test fuels and any injected fluids.*w*H = hydrogen mass fraction of the mixture of test fuels and any injected fluids.*w*O = oxygen mass fraction of the mixture of test fuels and any injected fluids.*w*S = sulfur mass fraction of the mixture of test fuels and any injected fluids.*w*N = nitrogen mass fraction of the mixture of test fuels and any injected fluids.*N* = total number of fuels and injected fluids over the duty cycle.*j* = an indexing variable that represents one fuel or injected fluid, starting with *j* = 1.*m*j = the mass flow rate of the fuel or any injected fluid *j.* For batch measurements, divide the total mass of fuel over the test interval duration to determine a mass rate.*w*Cmeasj = carbon mass fraction of fuel or any injected fluid *j.**w*Hmeasj = hydrogen mass fraction of fuel or any injected fluid *j.**w*Omeasj = oxygen mass fraction of fuel or any injected fluid *j.**w*Smeasj = sulfur mass fraction of fuel or any injected fluid *j.**w*Nmeasj = nitrogen mass fraction of fuel or any injected fluid *j.*

*Example for a mixture of diesel and NH*3*fuel where diesel represents 15% of energy:*

*N* = 2*m*1= 0.5352 g/s*m*2= 7.024 g/s*w*Cmeas1 = 0.820628 g/g*w*Hmeas1 = 0.123961 g/g*w*Omeas1 = 0.0546578 g/g*w*Smeas1 = 0.00065725 g/g*w*Nmeas1 = 0.0000957004 g/g*w*Cmeas2 = 0 g/g*w*Hmeas2 = 0.177553 g/g*w*Omeas2 = 0 g/g*w*Smeas2 = 0 g/g*w*Nmeas2 = 0.822447 g/g![](/graphics/er22ap24.278.gif)![](/graphics/er22ap24.279.gif)

*w*C = 0.0581014 g/g

*w*H = 0.1737586 g/g

*w*O = 0.00386983 g/g

*w*S = 0.0000465341 g/g

*w*N = 0.76422359 g/g

(e) *Fuel and diesel exhaust fluid composition.* (1) For carbon-containing fuels and diesel exhaust fluid determine the composition represented by *α, β,**γ,* and *δ,* as described in § 1065.655(e).

(2) For fuels other than carbon-containing fuels use the default values for *τ, χ,**ϕ, ξ,* and *ω* in table 3 to this section, or use good engineering judgment to determine those values based on measurement. If you determine compositions based on measured values and the default value listed in table 3 to this section is zero, you may set *τ, ϕ,**ξ,* and *ω* to zero; otherwise determine *τ, ϕ,**ξ,* and *ω* (along with *χ*) based on measured values.

(3) If your fuel mixture contains carbon-containing fuels and your testing requires fuel composition values referencing carbon, calculate *α, β,**γ,* and *δ* for the fuel mixture as described in § 1065.655(e)(4).

|  Fuel  |Atomic carbon, oxygen, and nitrogen-to-hydrogen ratios Ct,Hx,Oq,Sj,Nv |
|--------|----------------------------------------------------------------------|
|Hydrogen|C<sub>0</sub> H<sub>2</sub> O<sub>o</sub> S<sub>o</sub> N<sub>o</sub>.|
|Ammonia |C<sub>0</sub> H<sub>3</sub> O<sub>o</sub> S<sub>o</sub> N<sub>1</sub>.|

(f) *Calculated raw exhaust molar flow rate from measured intake air molar flow rate or fuel mass flow rate.* You may calculate the raw exhaust molar flow rate from which you sampled emissions, , based on the measured intake air molar flow rate, , or the measured fuel mass flow rate, , and the values calculated using the chemical balance in paragraph (c) of this section. The chemical balance must be based on raw exhaust gas concentrations. Solve for the chemical balance in paragraph (c) of this section at the same frequency that you update and record or . For laboratory tests, calculating raw exhaust molar flow rate using measured fuel mass flow rate is valid only for steady-state testing. See § 1065.915(d)(5)(iv) for application to field testing.

(1) *Crankcase flow rate.* If engines are not subject to crankcase controls under the standard-setting part, you may calculate raw exhaust flow based on or using one of the following:

(i) You may measure flow rate through the crankcase vent and subtract it from the calculated exhaust flow.

(ii) You may estimate flow rate through the crankcase vent by engineering analysis as long as the uncertainty in your calculation does not adversely affect your ability to show that your engines comply with applicable emission standards.

(iii) You may assume your crankcase vent flow rate is zero.

(2) *Intake air molar flow rate calculation.* Calculate *n* based on using the following equation:

![](/graphics/er22ap24.281.gif)Eq. 1065.656-39Where:*n*exh = raw exhaust molar flow rate from which you measured emissions.*n*int = intake air molar flow rate including humidity in intake air.

Example:

*n*int = 3.780 mol/s*x*int/exhdry = 0.69021 mol/mol*x*raw/exhdry = 1.10764 mol/mol*x*H20exhdry = 107.64 mmol/mol = 0.10764 mol/mol![](/graphics/er22ap24.282.gif)

(3) *Fluid mass flow rate calculation.* This calculation may be used only for steady-state laboratory testing. See § 1065.915(d)(5)(iv) for application to field testing. Calculate based on using the following equation:

![](/graphics/er22ap24.283.gif)Eq. 1065.656-40Where:*n*exh = raw exhaust molar flow rate from which you measured emissions.*j* = an indexing variable that represents one fuel or injected fluid, starting with *j* = 1.*N* = total number of fuels and injected fluids over the duty cycle.*m*j = the mass flow rate of the fuel or any injected fluid *j.**w*Cj = carbon mass fraction of the fuel (or mixture of test fuels) and any injected fluid *j.**w*Hj = hydrogen mass fraction of the fuel (or mixture of test fuels) and any injected fluid *j.*

Example:

*x*H20exhdry1 = 312.013 mmol/mol = 0.10764 mol/mol*M*C = 12.0107 g/mol*M*H = 1.00794 g/mol*x*Ccombdry1 = 6.45541 mmol/mol = 0.00645541 mol/mol*x*Hcombdry1 = 641.384 mmol/mol = 0.641384 mol/mol*m*1 = 0.167974 g/s*m*2 = 7.39103 g/s*w*C1 = 0.820628 g/g*w*C2 = 0 g/g*w*H1 = 0.123961 g/g*w*H2 = 0.177553 g/g*N* = 2![](/graphics/er22ap24.284.gif)

(g) *Calculated raw exhaust molar flow rate from measured intake air molar flow rate, dilute exhaust molar flow rate, and dilute chemical balance.* You may calculate the raw exhaust molar flow rate, *n*exh, based on the measured intake air molar flow rate, *n*int, the measured dilute exhaust molar flow rate, *n*dexh, and the values calculated using the chemical balance in paragraph (c) of this section. Note that the chemical balance must be based on dilute exhaust gas concentrations. For continuous-flow calculations, solve for the chemical balance in paragraph (c) of this section at the same frequency that you update and record *n*int and *n*dexh. This calculated *n*dexh may be used for the PM dilution ratio verification in § 1065.546; the calculation of dilution air molar flow rate in the background correction in § 1065.667; and the calculation of mass of emissions in § 1065.650(c) for species that are measured in the raw exhaust.

(1) *Crankcase flow rate.* If engines are not subject to crankcase controls under the standard-setting part, calculate raw exhaust flow as described in paragraph (f)(1) of this section.

(2) Dilute exhaust and intake air molar flow rate calculation. Calculate as follows:

*n*exh = (*x*raw/exhdry − *x*int/exhdry) · (1 − *x*H20exh) · *n*dexh + *n*intEq. 1065.656-41

*Example:*

*n*int = 7.930 mol/s*x*raw/exhdry = 0.1544 mol/mol*x*int/exhdry = 0.1451 mol/mol*x*H20exhdry = 32.46 mmol/mol = 0.03246 mol/mol*n*dexh = 49.02 mol/s*n*exh = (0.1544 − 0.1451) · (1 − 0.03246) · 49.02 + 7.930 = 0.4411 + 7.930 = 8.371 mol/s [89 FR 29810, Apr. 22, 2024, as amended at 89 FR 51238, June 17, 2024]