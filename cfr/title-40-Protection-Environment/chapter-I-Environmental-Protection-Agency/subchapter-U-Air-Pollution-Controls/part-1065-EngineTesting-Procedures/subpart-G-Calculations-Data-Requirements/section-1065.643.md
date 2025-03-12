##### § 1065.643 Carbon balance error verification calculations. #####

This section describes how to calculate quantities used in the carbon balance error verification described in § 1065.543. Paragraphs (a) through (c) of this section describe how to calculate the mass of carbon for a test interval from carbon-carrying fluid streams, intake air into the system, and exhaust emissions, respectively. Paragraph (d) of this section describes how to use these carbon masses to calculate four different quantities for evaluating carbon balance error. Use rectangular or trapezoidal integration methods to calculate masses and amounts over a test interval from continuously measured or calculated mass and molar flow rates.

(a) *Fuel and other fluids.* Determine the mass of fuel, DEF, and other carbon-carrying fluid streams, other than intake air, flowing into the system, *m*fluidj, for each test interval. Note that § 1065.543 allows you to omit all flows other than fuel. You may determine the mass of DEF based on ECM signals for DEF flow rate. You may determine fuel mass during field testing based on ECM signals for fuel flow rate. Calculate the mass of carbon from the combined carbon-carrying fluid streams flowing into the system as follows:

![](/graphics/er29jn21.221.gif)Where:*j* = an indexing variable that represents one carbon-carrying fluid stream.*N* = total number of carbon-carrying fluid streams into the system over the test interval.*w*C = carbon mass fraction of the carbon-carrying fluid stream as determined in § 1065.655(d).*m*fluid = the mass of the carbon-carrying fluid stream determined over the test interval.Example:*N* = 2*w*Cfuel = 0.869*w*CDEF = 0.065*m*fuel = 1119.6 g*m*DEF = 36.8 g*m*Cfluid = 0.869·1119.6 + 0.065·36.8 = 975.3 g

(b) *Intake air.* Calculate the mass of carbon in the intake air, *m*Cair, for each test interval using one of the methods in this paragraph (b). The methods are listed in order of preference. Use the first method where all the inputs are available for your test configuration. For methods that calculate *m*Cair based on the amount of CO2 per mole of intake air, we recommend measuring intake air concentration, but you may calculate *x*CO2int using Eq. 1065.655-10 and letting *x*CO2intdry = 375 µmol/mol.

(1) Calculate *m*Cair, using the following equation if you measure intake air flow:

![](/graphics/er29jn21.222.gif)Where:*M*C = molar mass of carbon.*n*int = measured amount of intake air over the test interval.*x*CO2int = amount of intake air CO2 per mole of intake air.Example:*M*C = 12.0107 g/mol*n*int = 62862 mol*x*CO2int = 369 µmol/mol = 0.000369 mol/mol*m*Cair = 12.0107·62862·0.000369 = 278.6 g

(2) Calculate *m*Cair, using the following equation if you measure or calculate raw exhaust flow and you calculate chemical balance terms:

![](/graphics/er29jn21.223.gif)Where:*M*C = molar mass of carbon.*n*exh = calculated or measured amount of raw exhaust over the test interval.*x*H2Oexh = amount of H2O in exhaust per mole of exhaust.*x*CO2int = amount of intake air CO2 per mole of intake air.*x*dil/exhdry = amount of excess air per mole of dry exhaust. Note that excess air and intake air have the same composition, so *x*CO2dil = *x*CO2int and *x*H2Odil = *x*H2Oint for the chemical balance calculation for raw exhaust.*x*int/exhdry = amount of intake air required to produce actual combustion products per mole of dry exhaust.Example:*M*C = 12.0107 g/mol*n*exh = 62862 mol*x*H2Oexh = 0.034 mol/mol*x*CO2int = 369 µmol/mol = 0.000369 mol/mol*x*dil/exhdry = 0.570 mol/mol*x*int/exhdry = 0.465 mol/mol*m*Cair = 12.0107·62862·(1 − 0.034)·0.000369·(0.570 + 0.465) = 278.6 g

(3) Calculate *m*Cair, using the following equation if you measure raw exhaust flow:

![](/graphics/er29jn21.224.gif)Where:*M*C = molar mass of carbon.*n*exh = measured amount of raw exhaust over the test interval.*x*CO2int = amount of intake air CO2 per mole of intake air.Example:*M*C = 12.0107 g/mol*n*exh = 62862 mol*x*CO2int = 369 µmol/mol = 0.000369 mol/mol*m*Cair = 12.0107·62862·0.000369 = 278.6 g

(4) Calculate *m*Cair, using the following equation if you measure diluted exhaust flow and dilution air flow:

![](/graphics/er29jn21.225.gif)Where:*M*C = molar mass of carbon.*n*dexh = measured amount of diluted exhaust over the test interval as determined in § 1065.642.*n*dil = measured amount of dilution air over the test interval as determined in § 1065.667(b).*x*CO2int = amount of intake air CO2 per mole of intake air.Example:*M*C = 12.0107 g/mol*n*dexh = 942930 mol*n*dil = 880068 mol*x*CO2int = 369 µmol/mol = 0.000369 mol/mol*m*Cair = 12.0107·(942930 − 880068)·0.000369 = 278.6 g

(5) Determined *m*Cair based on ECM signals for intake air flow as described in paragraph (b)(1) of this section.

(6) If you measure diluted exhaust, determine *m*Cair as described in paragraph (b)(4) of this section using a calculated amount of dilution air over the test interval as determined in § 1065.667(d) instead of the measured amount of dilution air.

(c) *Exhaust emissions.* Calculate the mass of carbon in exhaust emissions, *m*Cexh, for each test interval as follows:

![](/graphics/er29jn21.226.gif)Where:*M*C = molar mass of carbon.*m*CO2 = mass of CO2 over the test interval as determined in § 1065.650(c).*M*CO2 = molar mass of carbon dioxide.*m*CO = mass of CO over the test interval as determined in § 1065.650(c).*M*CO = molar mass of carbon monoxide.*m*THC = mass of THC over the test interval as determined in § 1065.650(c).*M*THC = effective C1 molar mass of total hydrocarbon as defined in § 1065.1005(f)(2).Example:*M*C = 12.0107 g/mol*m*CO2 = 4567 g*M*CO2 = 44.0095 g/mol*m*CO = 0.803 g*M*CO = 28.0101 g/mol*m*THC = 0.537 g*M*THC = 13.875389 g/mol![](/graphics/er29jn21.227.gif)

(d) *Carbon balance error quantities.* Calculate carbon balance error quantities as follows:

(1) Calculate carbon mass absolute error, *ε*aC, for a test interval as follows:

![](/graphics/er24ja23.107.gif)Where:*m*Cexh = mass of carbon in exhaust emissions over the test interval as determined in paragraph (d) of this section.*m*Cfluid = mass of carbon in all the carbon-carrying fluid streams flowing into the system over the test interval as determined in paragraph (a) of this section.*m*Cair = mass of carbon in the intake air flowing into the system over the test interval as determined in paragraph (b) of this section.Example:*m*Cexh = 1247.2 g*m*Cfluid = 975.3 g*m*Cair = 278.6 g*ε*aC = 1247.2 − 975.3 − 278.6*ε*aC = −6.7 g

(2) Calculate carbon mass rate absolute error, *ε*aCrate, for a test interval as follows:

![](/graphics/er24ja23.108.gif)Where:*t* = duration of the test interval.Example:*ε*aC = −6.7 g

*t* = 1202.2 s = 0.3339 hr

![](/graphics/er24ja23.109.gif)*ε*aCrate = −20.065 g/hr

(3) Calculate carbon mass relative error, *ε*rC, for a test interval as follows:

![](/graphics/er24ja23.110.gif)Example:*ε*aC = −6.7 g*m*Cfluid = 975.3 g*m*Cair = 278.6 g![](/graphics/er24ja23.111.gif)*ε*rC = −0.0053

(4) Calculate composite carbon mass relative error, *ε*rCcomp, for a duty cycle with multiple test intervals as follows:

(i) Calculate *ε*rCcomp using the following equation:

![](/graphics/er24ja23.112.gif)Where:*i* = an indexing variable that represents one test interval.*N* = number of test intervals.*WF* = weighting factor for the test interval as defined in the standard-setting part.*m*Cexh = mass of carbon in exhaust emissions over the test interval as determined in paragraph (c) of this section.*m*Cfluid = mass of carbon in all the carbon-carrying fluid streams that flowed into the system over the test interval as determined in paragraph (a) of this section.*m*Cair = mass of carbon in the intake air that flowed into the system over the test interval as determined in paragraph (b) of this section.*t* = duration of the test interval. For duty cycles with multiple test intervals of a prescribed duration, such as cold-start and hot-start transient cycles, set *t* = 1 for all test intervals. For discrete-mode steady-state duty cycles with multiple test intervals of varying duration, set t equal to the actual duration of each test interval.

(ii) The following example illustrates calculation of *ε*rCcomp, for cold-start and hot-start transient cycles:

*N* = 2*WF*1 = 1/7*WF*2 = 6/7*m*Cexh1 = 1255.3 g*m*Cexh2 = 1247.2 g*m*Cfluid1 = 977.8 g*m*Cfluid2 = 975.3 g*m*Cair1 = 280.2 g*m*Cair2 = 278.6 g![](/graphics/er24ja23.113.gif)*ε*rCcomp = −0.0049

(iii) The following example illustrates calculation of *ε*rCcomp for multiple test intervals with varying duration, such as discrete-mode steady-state duty cycles:

*N* = 2*WF*1 = 0.85*WF*2 = 0.15*m*Cexh1 = 2.873 g*m*Cexh2 = 0.125 g*m*Cfluid1 = 2.864 g*m*Cfluid2 = 0.095 g*m*Cair1 = 0.023 g*m*Cair2 = 0.024 g*t*1 = 123 s*t*2 = 306 s![](/graphics/er24ja23.114.gif)*ε*rCcomp = −0.0047 [86 FR 34557, June 29, 2021, as amended at 87 FR 64865, Oct. 26, 2022; 88 FR 4680, Jan. 24, 2023]