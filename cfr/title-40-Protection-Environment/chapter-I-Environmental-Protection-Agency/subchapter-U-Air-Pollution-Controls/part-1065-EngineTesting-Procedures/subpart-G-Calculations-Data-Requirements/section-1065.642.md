##### § 1065.642 PDP, SSV, and CFV molar flow rate calculations. #####

This section describes the equations for calculating molar flow rates from various flow meters. After you calibrate a flow meter according to § 1065.640, use the calculations described in this section to calculate flow during an emission test.

(a) *PDP molar flow rate.* (1) Based on the speed at which you operate the PDP for a test interval, select the corresponding slope, *a*1, and intercept, *a*0, as calculated in § 1065.640, to calculate PDP molar flow rate,, as follows:

![](/graphics/er25oc16.185.gif)Where:*f*nPDP = pump speed.*V*rev = PDP volume pumped per revolution, as determined in paragraph (a)(2) of this section.*p*in = static absolute pressure at the PDP inlet.*R* = molar gas constant.*T*in = absolute temperature at the PDP inlet.

(2) Calculate *V*rev using the following equation:

![](/graphics/er25oc16.186.gif)*p*out = static absolute pressure at the PDP outlet.Example:*a*1 = 0.8405 (m3/s)*f*nPDP = 12.58 r/s*P*out = 99.950 kPa*P*in = 98.575 kPa = 98575 Pa = 98575 kg/(m·s2)*a*0 = 0.056 (m3/r)*R* = 8.314472 J/(mol·K) = 8.314472 (m2·kg)/(s2·mol·K)*T*in = 323.5 K![](/graphics/er25oc16.187.gif)![](/graphics/er25oc16.188.gif)*n* = 29.428 mol/s

(b) *SSV molar flow rate.* Calculate SSV molar flow rate, *n*, as follows:

![](/graphics/er29jn21.217.gif)Where:*C*d = discharge coefficient, as determined based on the *C*d versus *Re*# equation in § 1065.640(d)(2).*C*f = flow coefficient, as determined in § 1065.640(c)(3)(ii).*A*t = venturi throat cross-sectional area.*p*in = static absolute pressure at the venturi inlet.*Z* = compressibility factor.*M*mix = molar mass of gas mixture.*R* = molar gas constant.*T*in = absolute temperature at the venturi inlet.Example:*A*t = 0.01824 m2*p*in = 99.132 kPa = 99132 Pa = 99132 kg/(m·s2)*Z* = 1*M*mix = 28.7805 g/mol = 0.0287805 kg/mol*R* = 8.314472 J/(mol·K) = 8.314472 (m2·kg)/(s2·mol·K)*T*in = 298.15 K*Re*# = 7.232·105γ = 1.399β = 0.8Δp = 2.312 kPa

Using Eq. 1065.640-7:

*r*ssv = 0.997

Using Eq. 1065.640-6:

*C*f = 0.274

Using Eq. 1065.640-5:

*C*d = 0.990![](/graphics/er29jn21.218.gif)*n* = 58.173 mol/s

(c) *CFV molar flow rate.* If you use multiple venturis and you calibrate each venturi independently to determine a separate discharge coefficient, *C*d (or calibration coefficient, *K*v), for each venturi, calculate the individual molar flow rates through each venturi and sum all their flow rates to determine CFV flow rate, *n*. If you use multiple venturis and you calibrated venturis in combination, calculate *n* using the sum of the active venturi throat areas as *A*t, the square root of the sum of the squares of the active venturi throat diameters as *d*t, and the ratio of the venturi throat to inlet diameters as the ratio of the square root of the sum of the active venturi throat diameters (*d*t) to the diameter of the common entrance to all the venturis (*D*).

(1) To calculate *n* through one venturi or one combination of venturis, use its respective mean Cd and other constants you determined according to § 1065.640 and calculate *n* as follows:

![](/graphics/er29jn21.219.gif)Where:*C*f = flow coefficient, as determined in § 1065.640(c)(3).Example:*C*d = 0.985*C*f = 0.7219*A*t = 0.00456 m2*p*in = 98.836 kPa = 98836 Pa = 98836 kg/(m·s2)*Z* = 1*M*mix = 28.7805 g/mol = 0.0287805 kg/mol*R* = 8.314472 J/(mol·K) = 8.314472 (m2·kg)/(s2·mol·K)*T*in = 378.15 K![](/graphics/er29jn21.220.gif)*n* = 33.690 mol/s

(2) To calculate the molar flow rate through one venturi or a combination of venturis, you may use its respective mean, *K*v, and other constants you determined according to § 1065.640 and calculate its molar flow rate *n* during an emission test. Note that if you follow the permissible ranges of dilution air dewpoint versus calibration air dewpoint in Table 3 of § 1065.640, you may set *M*mix-cal and *M*mix equal to 1. Calculate *n* as follows:

![](/graphics/er25oc16.192.gif)Where:![](/graphics/er25oc16.193.gif)*V*stdref = volume flow rate of the standard at reference conditions of 293.15 K and 101.325 kPa.*T*in-cal = venturi inlet temperature during calibration.*P*in-cal = venturi inlet pressure during calibration.*M*mix-cal = molar mass of gas mixture used during calibration.*M*mix = molar mass of gas mixture during the emission test calculated using Eq. 1065.640-9.Example:*V*stdref = 0.4895 m3*T*in-cal = 302.52 K*P*in-cal = 99.654 kPa = 99654 Pa = 99654 kg/(m·s2)*p*in = 98.836 kPa = 98836 Pa = 98836 kg/(m·s2)*p*std = 101.325 kPa = 101325 Pa = 101325 kg/(m·s2)*M*mix-cal = 28.9656 g/mol = 0.0289656 kg/mol*M*mix = 28.7805 g/mol = 0.0287805 kg/mol*T*in = 353.15 K*T*std = 293.15 K*R* = 8.314472 J/(mol·K) = 8.314472 (m2·kg)/(s2·mol·K)![](/graphics/er25oc16.194.gif)*n* = 16.457 mol/s[81 FR 74177, Oct. 25, 2016, as amended at 86 FR 34557, June 29, 2021]