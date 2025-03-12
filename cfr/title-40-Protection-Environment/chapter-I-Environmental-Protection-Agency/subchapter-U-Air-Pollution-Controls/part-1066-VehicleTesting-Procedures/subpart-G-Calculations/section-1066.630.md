##### § 1066.630 PDP, SSV, and CFV flow rate calculations. #####

This section describes the equations for calculating flow rates from various flow meters. After you calibrate a flow meter according to § 1066.625, use the calculations described in this section to calculate flow during an emission test. Calculate flow according to 40 CFR 1065.642 instead if you calculate emissions based on molar flow rates.

(a) *PDP.* (1) Based on the speed at which you operate the PDP for a test interval, select the corresponding slope, *a*1, and intercept, *a*0, as determined in § 1066.625(a), to calculate PDP flow rate, *v*, as follows:

![](/graphics/er25oc16.292.gif)Where:*f*nPDP = pump speed.*V*rev = PDP volume pumped per revolution, as determined in paragraph (a)(2) of this section.*T*std = standard temperature = 293.15 K.*p*in = static absolute pressure at the PDP inlet.*T*in = absolute temperature at the PDP inlet.*p*std = standard pressure = 101.325 kPa.

(2) Calculate *V*rev using the following equation:

![](/graphics/er18ap24.073.gif)Eq. 1066.630-2Where:*p*out = static absolute pressure at the PDP outlet.Example:*a*1 = 0.8405 m3/s*f*nPDP = 12.58 r/s*p*out = 99.950 kPa*p*in = 98.575 kPa*a*0 = 0.056 m3/r*T*in = 323.5 K![](/graphics/er18ap24.074.gif)

(b) *SSV.* Calculate SSV flow rate, *v*, as follows:

![](/graphics/er25oc16.296.gif)Where:*C*d = discharge coefficient, as determined based on the *C*d versus *Re*# equation in § 1066.625(b)(2)(viii).*C*f = flow coefficient, as determined in § 1066.625(b)(2)(ii).*A*t = venturi throat cross-sectional area.*R* = molar gas constant.*p*in = static absolute pressure at the venturi inlet.*T*std = standard temperature.*p*std = standard pressure.*Z* = compressibility factor.*M*mix = molar mass of gas mixture.*T*in = absolute temperature at the venturi inlet.Example:*C*d = 0.890*C*f = 0.472*A*t = 0.01824 m2*R* = 8.314472 J/(mol·K) = 8.314472 (m2·kg)/(s2·mol·K)*p*in = 98.496 kPa*T*std = 293.15 K*p*std = 101.325 kPa*Z* = 1*M*mix = 28.7789 g/mol = 0.0287789 kg/mol*T*in = 296.85 K![](/graphics/er25oc16.297.gif)*V* = 2.155 m3/s

(c) *CFV.* If you use multiple venturis and you calibrated each venturi independently to determine a separate calibration coefficient, *K*v, for each venturi, calculate the individual volume flow rates through each venturi and sum all their flow rates to determine CFV flow rate, *V*. If you use multiple venturis and you calibrated venturis in combination, calculate *V* using the *K*v that was determined for that combination of venturis.

(1) To calculate *V* through one venturi or a combination of venturis, use the mean *K*v you determined in § 1066.625(c) and calculate *V* as follows:

![](/graphics/er25oc16.298.gif)Where:*K*v = flow meter calibration coefficient.*T*in = temperature at the venturi inlet.*p*in = absolute static pressure at the venturi inlet.Example:*K*v = 0.074954 m3·K0.5/(kPa·s)*p*in = 99.654 kPa*T*in = 353.15 K![](/graphics/er25oc16.299.gif)*V*= 0.39748 m3/s

(2) [Reserved]

[81 FR 74211, Oct. 25, 2016, as amended at 89 FR 28212, Apr. 18, 2024]