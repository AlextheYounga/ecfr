##### § 1065.645 Amount of water in an ideal gas. #####

This section describes how to determine the amount of water in an ideal gas, which you need for various performance verifications and emission calculations. Use the equation for the vapor pressure of water in paragraph (a) of this section or another appropriate equation and, depending on whether you measure dewpoint or relative humidity, perform one of the calculations in paragraph (b) or (c) of this section. Paragraph (d) of this section provides an equation for determining dewpoint from relative humidity and dry bulb temperature measurements. The equations for the vapor pressure of water as presented in this section are derived from equations in “Saturation Pressure of Water on the New Kelvin Temperature Scale” (Goff, J.A., Transactions American Society of Heating and Air-Conditioning Engineers, Vol. 63, No. 1607, pages 347-354). Note that the equations were originally published to derive vapor pressure in units of atmospheres and have been modified to derive results in units of kPa by converting the last term in each equation.

(a) *Vapor pressure of water.* Calculate the vapor pressure of water for a given saturation temperature condition, *T*sat, as follows, or use good engineering judgment to use a different relationship of the vapor pressure of water to a given saturation temperature condition:

(1) For humidity measurements made at ambient temperatures from (0 to 100) °C, or for humidity measurements made over super-cooled water at ambient temperatures from (−50 to 0) °C, use the following equation:

![](/graphics/er28ap14.039.gif)

(2) For humidity measurements over ice at ambient temperatures from (-100 to 0) °C, use the following equation:

![](/graphics/er28ap14.040.gif)

(b) *Dewpoint.* If you measure humidity as a dewpoint, determine the amount of water in an ideal gas, *x*H20, as follows:

![](/graphics/er30ap10.034.gif)Where:*x*H20 = amount of water in an ideal gas.*p*H20 = water vapor pressure at the measured dewpoint, *T*sat = *T*dew.*p*abs = wet static absolute pressure at the location of your dewpoint measurement.Example: :*p*abs = 99.980 kPa*T*sat = *T*dew = 9.5 °CUsing Eq. 1065.645-1,*p*H20 = 1.186581 kPa*x*H2O = 1.186581/99.980*x*H2O = 0.011868 mol/mol

(c) *Relative humidity.* If you measure humidity as a relative humidity, *RH,* determine the amount of water in an ideal gas, *x*H2O, as follows:

![](/graphics/er25oc16.195.gif)Where:*x*H2O = amount of water in an ideal gas.*RH* = relative humidity.*p*H2O = water vapor pressure at 100% relative humidity at the location of your relative humidity measurement, *T*sat = *T*amb.*p*abs = wet static absolute pressure at the location of your relative humidity measurement.Example:*RH* = 50.77% = 0.5077*p*abs = 99.980 kPa*T*sat = *T*amb = 20 °CUsing Eq. 1065.645-1,*p*H2O = 2.3371 kPa*x*H2O = (0.5077 · 2.3371)/99.980*x*H2O = 0.011868 mol/mol

(d) *Dewpoint determination from relative humidity and dry bulb temperature.* This paragraph (d) describes how to calculate dewpoint temperature from relative humidity, *RH.* This is based on “ITS-90 Formulations for Vapor Pressure, Frostpoint Temperature, Dewpoint Temperature, and Enhancement Factors in the Range −100 to + 100 °C” (Hardy, B., The Proceedings of the Third International Symposium on Humidity & Moisture, Teddington, London, England, April 1998). Calculate *p*H20sat as described in paragraph (a) of this section based on setting *T*sat equal to *T*amb. Calculate *p*H20scaled by multiplying *p*H20sat by *RH.* Calculate the dewpoint, *T*dew, from *p*H20 using the following equation:

![](/graphics/er25oc16.196.gif)Where:ln(*p*H2O) = the natural log of *p*H2Oscaled, which is the water vapor pressure scaled to the relative humidity at the location of the relative humidity measurement, *T*sat = *T*ambExample:*RH* = 39.61% = 0.3961*T*sat = Tamb = 20.00 °C = 293.15KUsing Eq. 1065.645-1,*p*H2Osat = 2.3371 kPa*p*H2Oscaled = (0.3961 · 2.3371) = 0.925717 kPa = 925.717 Pa![](/graphics/er25oc16.197.gif)[73 FR 37327, June 30, 2008, as amended at 73 FR 59331, Oct. 8, 2008; 75 FR 23048, Apr. 30, 2010; 76 FR 57456, Sept. 15, 2011;79 FR 23796, Apr. 28, 2014; 81 FR 74179, Oct. 25, 2016]