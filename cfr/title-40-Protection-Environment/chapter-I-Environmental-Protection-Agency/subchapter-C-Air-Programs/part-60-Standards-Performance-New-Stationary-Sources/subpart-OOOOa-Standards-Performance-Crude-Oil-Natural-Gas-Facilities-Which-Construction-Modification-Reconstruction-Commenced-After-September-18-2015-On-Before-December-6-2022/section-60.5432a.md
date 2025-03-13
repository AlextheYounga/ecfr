##### § 60.5432a How do I determine whether a well is a low pressure well using the low pressure well equation? #####

(a) To determine that your well is a low pressure well subject to § 60.5375a(f), you must determine whether the characteristics of the well are such that the well meets the definition of low pressure well in § 60.5430a. To determine that the well meets the definition of low pressure well in § 60.5430a, you must use the low pressure well equation below:

![](/graphics/er03jn16.006.gif)Where:(1) *P*L is the pressure of flowback fluid immediately before it enters the flow line, expressed in pounds force per square inch (psia), and is to be calculated using the equation above;(2) *P*R is the pressure of the reservoir containing oil, gas, and water at the well site, expressed in psia;(3) *L*is the true vertical depth of the well, expressed in feet (ft);(4) *q*o is the flow rate of oil in the well, expressed in cubic feet/second (cu ft/sec);(5) *q*g is the flow rate of gas in the well, expressed in cu ft/sec;(6) *q*w is the flow rate of water in the well, expressed in cu ft/sec;(7) *ρ*o is the density of oil in the well, expressed in pounds mass per cubic feet (lbm/cu ft).

(b) You must determine the four values in paragraphs (a)(4) through (7) of this section, using the calculations in paragraphs (b)(1) through (b)(15) of this section.

(1) Determine the value of the bottom hole pressure, *P*BH (*psia*), based on available information at the well site, or by calculating it using the reservoir pressure, *P*R (*psia*), in the following equation:

![](/graphics/er03jn16.007.gif)

(2) Determine the value of the bottom hole temperature, *T*BH (*F*), based on available information at the well site, or by calculating it using the true vertical depth of the well, *L (ft)*, in the following equation:

*T*BH (*F*) = (0.014 × *L*) + 79.081

(3) Calculate the value of the applicable natural gas specific gravity that would result from a separator pressure of 100 psig, γgs, using the following equation with: Separator at standard conditions (pressure, *p* = 14.7 (*psia*), temperature, T = 60 (*F*)); the oil API gravity at the well site, γ0; and the gas specific gravity at the separator under standard conditions, γgp = 0.75:

![](/graphics/er03jn16.008.gif)

(4) Calculate the value of the applicable dissolved GOR, *Rs (scf/STBO)*, using the following equation with: The bottom hole pressure, *P*BH (*psia*), determined in (b)(1) of this section; the bottom hole temperature, *T*BH (*F*), determined in (b)(2) of this section; the gas gravity at separator pressure of 100 psig, γgs, calculated in (b)(3) of this section; the oil API gravity, γo, at the well site; and the constants, C1, C2, and C3, found in Table A:

![](/graphics/er03jn16.009.gif)

|Constant|γ<sub><em>API</em></sub> ≤ 30|γ<sub><em>API</em></sub> \> 30|
|--------|-----------------------------|------------------------------|
|   C1   |           0.0362            |            0.0178            |
|   C2   |           1.0937            |            1.1870            |
|   C3   |           25.7240           |            23.931            |

(5) Calculate the value of the oil formation volume factor, *Bo (bbl/STBO)*, using the following equation with: the bottom hole temperature, *T*BH (*F*), determined in paragraph (b)(2) of this section; the gas gravity at separator pressure of 100 psig, γgs, calculated in paragraph (b)(3) of this section; the dissolved GOR, Rs (scf/STBO), calculated in paragraph (b)(4) of this section; the oil API gravity, γ*o*, at the well site; and the constants, C1, C2, and C3, found in Table B:

![](/graphics/er03jn16.010.gif)

|Constant|γ<sub><em>API</em></sub> ≤ 30|γ<sub><em>API</em></sub> \> 30|
|--------|-----------------------------|------------------------------|
|   C1   |  4.677 × 10 <sup>−4</sup>   |   4.670 × 10 <sup>−4</sup>   |
|   C2   |  1.751 × 10 <sup>−5</sup>   |   1.100 × 10 <sup>−5</sup>   |
|   C3   |  −1.811 × 10 <sup>−8</sup>  |   1.337 × 10 <sup>−9</sup>   |

(6) Calculate the density of oil at the wellhead,

![](/graphics/er03jn16.300.gif)using the following equation with the value of the oil API gravity, γ*o*, at the well site:![](/graphics/er03jn16.301.gif)

(7) Calculate the density of oil at bottom hole conditions,

![](/graphics/er03jn16.302.gif)using the following equation with: the dissolved GOR, Rs (scf/STBO), calculated in paragraph (b)(4) of this section; the oil formation volume factor, Bo (bbl/STBO), calculated in paragraph (b)(5) of this section; the oil density at the wellhead,![](/graphics/er03jn16.303.gif)calculated in paragraph (b)(6) of this section; and the dissolved gas gravity, γgd = 0.77:![](/graphics/er03jn16.304.gif)

(8) Calculate the density of oil in the well,

![](/graphics/er03jn16.305.gif)using the following equation with the density of oil at the wellhead,![](/graphics/er03jn16.306.gif)calculated in paragraph (b)(6) of this section; and the density of oil at bottom hole conditions,![](/graphics/er03jn16.307.gif)calculated in paragraph (b)(7) of this section:![](/graphics/er03jn16.308.gif)

(9) Calculate the oil flow rate, *q*o (*cu ft/sec,*) using the following equation with: the oil formation volume factor, *Bo* (bbl/STBO), as calculated in paragraph (b)(5) of this section; and the estimated oil production rate at the well head, *Qo* (STBO/day):

![](/graphics/er03jn16.309.gif)

(10) Calculate the critical pressure, Pc (psia), and critical temperature, Tc (R), using the equations below with: Gas gravity at standard conditions (pressure, *P* = 14.7 (*psia*), temperature, T = 60 (*F*)), γ = 0.75; and where the mole fractions of nitrogen, carbon dioxide and hydrogen sulfide in the gas are *X*N2 = 0.168225, *X*CO2 = 0.013163, and *X*H2S = 0.013680, respectively:

*P*c(*psia*) = 678 − 50 · (γg − 0.5) − 206.7 · *X*N2 + 440 · *X*CO2 + 606.7 · *X*H2S*T*c(*R*) = 326 + 315.7 · (γg − 0.5) − 240 · *X*N2 − 88.3 · *X*CO2 + 133.3 · *X*H2S

(11) Calculate reduced pressure, Pr, and reduced temperature, Tr, using the following equations with: the bottom hole pressure, *P*BH, as determined in paragraph (b)(1) of this section; the bottom hole temperature, *T*BH (*F*), as determined in paragraph (b)(2) of this section in the following equations:

![](/graphics/er03jn16.310.gif)![](/graphics/er03jn16.311.gif)

(12)(i) Calculate the gas compressibility factor, *Z*, using the following equation with the reduced pressure, Pr, calculated in paragraph (b)(11) of this section:

![](/graphics/er03jn16.312.gif)

(ii) The values for A, B, C, D in the above equation, are calculated using the following equations with the reduced pressure, Pr, and reduced temperature, Tr, calculated in paragraph (b)(11) of this section:

![](/graphics/er03jn16.313.gif)

(13) Calculate the gas formation volume factor,

![](/graphics/er03jn16.314.gif)using the bottom hole pressure, *P*BH*(psia)*, as determined in paragraph (b)(1) of this section; and the bottom hole temperature, *T*BH*(F)*, as determined in paragraph (b)(2) of this section:![](/graphics/er03jn16.315.gif)

(14) Calculate the gas flow rate,

![](/graphics/er03jn16.316.gif)using the following equation with: the value of gas formation volume factor,![](/graphics/er03jn16.317.gif)calculated in paragraph (b)(13) of this section; the estimated gas production rate, Qg (scf/day); the estimated oil production rate, Qo (STBO/day); and the dissolved GOR, Rs (scf/STBO), as calculated in paragraph (b)(4) of this section:![](/graphics/er03jn16.318.gif)

(15) Calculate the flow rate of water in the well, *q*w (*cu ft/sec*), using the following equation with the water production rate Qw (bbl/day) at the well site:

![](/graphics/er03jn16.319.gif)