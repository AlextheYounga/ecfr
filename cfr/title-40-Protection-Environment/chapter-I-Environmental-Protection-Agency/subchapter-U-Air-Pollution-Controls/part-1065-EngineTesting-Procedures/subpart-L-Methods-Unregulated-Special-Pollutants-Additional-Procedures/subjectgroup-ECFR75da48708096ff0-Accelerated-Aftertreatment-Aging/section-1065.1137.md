##### § 1065.1137 Determination of thermal reactivity coefficient. #####

This section describes the method for determining the thermal reactivity coefficient(s) used for thermal heat load calculation in the accelerated aging protocol.

(a) The calculations for thermal degradation are based on the use of an Arrhenius rate law function to model cumulative thermal degradation due to heat exposure. Under this model, the thermal aging rate constant, *k,* is an exponential function of temperature which takes the form shown in the following equation:

![](/graphics/er22ap24.313.gif)Eq. 1065.1137-1Where:*A* = frequency factor or pre-exponential factor.*E*a = thermal reactivity coefficient.*R* = molar gas constant.*T* = catalyst temperature.

(b) The process of determining *E*a begins with determining what catalyst characteristic will be tracked as the basis for measuring thermal deactivation. This metric varies for each type of catalyst and may be determined from the experimental data using good engineering judgment. We recommend the following metrics; however, you may also use a different metric based on good engineering judgment:

(1) *Copper-based zeolite SCR.* Total ammonia (NH3) storage capacity is a key aging metric for copper-zeolite SCR catalysts, and they typically contain multiple types of storage sites. It is typical to model these catalysts using two different storage sites, one of which is more active for NOX reduction, as this has been shown to be an effective metric for tracking thermal aging. In this case, there are two recommended aging metrics:

(i) The ratio between the storage capacity of the two sites, with more active site being in the denominator.

(ii) Storage capacity of the more active site.

(2) *Iron-based zeolite SCR.* Total NH3 storage capacity is a key aging metric for iron-zeolite SCR catalysts. Using a single storage site is the recommended metric for tracking thermal aging.

(3) *Vanadium SCR.* Brunauer-Emmett-Teller (BET) theory for determination of surface area is a key aging metric for vanadium-based SCR catalysts. Total NH3 storage capacity may also be used as a surrogate to probe the surface area. If you use NH3 storage to probe surface area, using a single storage site is the recommended metric for tracking thermal aging. You may also use low temperature NOX conversion as a metric. If you choose this option, you may be limited in your choice of temperatures for the experiment described in paragraph (c)(1) of this section due to vanadium volatility. In that case, it is possible that you may need to run a longer experimental duration than the recommended 64 hours to reach reliably measurable changes in NOX conversion.

(4) *Zone-coated zeolite SCR.* This type of catalyst is zone coated with both copper- and iron-based zeolite. As noted in paragraphs (b)(1) and (2) of this section, total NH3 storage capacity is a key aging metric, and each zone must be evaluated separately.

(5) *Diesel oxidation catalysts.* The key aging metric for tracking thermal aging for DOCs which are used to optimize exhaust characteristics for a downstream SCR system is the conversion rate of NO to NO2. Select a conversion rate temperature less than or equal to 200 °C using good engineering judgement. The key aging metric for DOCs, which are part of a system that does not contain an SCR catalyst for NOX reduction, is the HC reduction efficiency (as measured using ethylene). Select a conversion rate temperature less than or equal to 200 °C using good engineering judgement. This same guidance applies to an oxidation catalyst coated onto the surface of a DPF, if there is no other DOC in the system.

(c)(1) Use good engineering judgment to select at least three different temperatures to complete the degradation experiments. We recommend selecting these temperatures to accelerate thermal deactivation such that measurable changes in the aging metric can be observed at multiple time points over the course of no more than 64 hours. Avoid temperatures that are too high to prevent rapid catalyst failure by a mechanism that does not represent normal aging. An example of temperatures to run the degradation experiment at for a small-pore copper zeolite SCR catalyst is 600 °C, 650 °C, and 725 °C.

(2) For each aging temperature selected, perform testing to assess the aging metric at different times. These time intervals do not need to be evenly spaced and it is typical to complete these experiments using increasing time intervals (*e.g.,* after 2, 4, 8, 16, and 32 hours). Use good engineering judgment to stop each temperature experiment after sufficient data has been generated to characterize the shape of the deactivation behavior at a given temperature.

(i) For SCR-based NH3 storage capacity testing, perform a Temperature Programmed Desorption (TPD) following NH3 saturation of the catalyst (*i.e.,* ramping gas temperature from 200 to 550 °C) to quantify total NH3 released during the TPD.

(ii) For DOC formulations, conduct an NO Reverse Light Off (RLO) to quantify oxidation conversion efficiency of NO to NO2 (*i.e.,* ramping gas temperature from 500 to 150 °C).

(d) Generate a fit of the deactivation data generated in paragraph (b) of this section at each temperature.

(1) *Copper-based zeolite SCR.* Process all NH3 TPD data from each aging condition using an algorithm to fit the NH3 desorption data.

(i) We recommend that you use the Temkin adsorption model to quantify the NH3 TPD at each site to determine the desorption peaks of individual storage sites. The adsorption model is adapted from “Adsorption of Nitrogen and the Mechanism of Ammonia Decomposition Over Iron Catalysts” (Brunauer, S. *et al,* Journal of the American Chemical Society, 1942, 64 (4), 751-758) and “On Kinetic Modeling of Change in Active Sites upon Hydrothermal Aging of Cu-SSZ-13” (Daya, R. *et al,* Applied Catalysis B: Environmental, 2020, 263, 118368-118380). It is generalized using the following equation (assuming a two-site model):

![](/graphics/er22ap24.314.gif)Eq. 1065.1137-2Where:*k* = *e*−*E*a(1−αθ)/RT*E*a = thermal reactivity coefficient of ammonia desorption.*α* = Temkin constant.*θ* = fraction of adsorption sites currently occupied (initial θ is assumed to be 1).*R* = molar gas constant.*T* = aging temperature.

(A) Use Eq. 1065.1137-2 to express the NH3 storage site desorption peaks as follows:

![](/graphics/er22ap24.315.gif)Eq. 1065.1137-3Where:*N*1 = moles of NH3 desorbed from Site 1.*A*1 = pre-exponential factor associated with Site 1.*E*a,T1 = thermal reactivity coefficient of ammonia desorption for Site 1.*N*2 = moles of NH3 desorbed from Site 2.*A*2 = pre-exponential factor associated with Site 2.*E*a,T2 = thermal reactivity coefficient of ammonia desorption for Site 2.

(B) Optimize *E*a,T1, *α*1, *A*1, *E*a,T2, *α*2, and *A*2 to fit each NH3 TPD peak to give the best fit. The moles of NH3 (*N*1 and *N*2) may vary for each individual TPD data set.

(ii) Use one of the following modeling approaches to derive the thermal reactivity coefficient, *E*a,D. We recommend that you use both models to fit the data and check that the resulting *E*a,D values for the two methods are within 3% of each other.

(A) *General Power Law Expression (GPLE).* Generate a fit of the deactivation data from paragraph (d)(1)(i) of this section for each aging temperature using the following expression:

![](/graphics/er22ap24.316.gif)Eq. 1065.1137-4Where:*k*D = the thermal aging rate constant.![](/graphics/er22ap24.317.gif)Eq. 1065.1137-5*A* = pre-exponential factor.*E*a,D = thermal reactivity coefficient.*R* = molar gas constant.*T* = aging temperature.Ω = *N*2/*N*1 or = *N*2 (normalizing Ω to the degreened Ω value for each new catalyst component prior to aging is recommended (*i.e.,* Ω = 1 at *t* = 0 for each aging temperature).Ωeq = aging metric at equilibrium (set = 0 unless there is a known activity minimum).*m* = model order (assumed to be 2 for copper-based zeolite SCR).

(*1*) Solve Eq. 1065.1137-4 for Ω to yield the following expression:

![](/graphics/er22ap24.318.gif)Eq. 1065.1137-6Where:Ω0 = 1 (assumes that *N*2/*N*1 or = *N*2 values were normalized to the degreened value for each aging temperature).*A* = pre-exponential factor.*E*a,D = thermal reactivity coefficient.*R* = molar gas constant.*T* = aging temperature.*t* = aging time.

(*2*) Use a global fitting approach to solve for *E*a,D and *A*D by applying a generalized reduced gradient (GRG) nonlinear minimization algorithm, or equivalent. For the global fitting approach, optimize the model by minimizing the Global Sum of Square Errors (*SSE*Global) between the experimental Ω and model Ω while only allowing *E*a,D and *A*D to vary. Global SSE is defined as the summed total SSE for all aging temperatures evaluated.

![](/graphics/er22ap24.319.gif)Eq. 1065.1137-7Where:*n* = total number of aging temperatures.*i* = an indexing variable that represents one aging temperature.*SEE*T = sum of square errors (SSE) for a single aging temperature, *T*, (see Eq. 1065.1137-8).![](/graphics/er22ap24.320.gif)Eq. 1065.1137-8Where:*n* = total number of aging intervals for a single aging temperature.*i* = an indexing variable that represents one aging interval for a single aging temperature.*Ω*Exp = experimentally derived aging metric for aging temperature, *T*.*Ω*model = aging metric calculated from Eq. 1065.1137-6 for aging temperature, *T*.

(B) *Arrhenius approach.* In the Arrhenius approach, the deactivation rate constant, *k*D, of the aging metric, *Ω*, is calculated at each aging temperature.

(*1*) Generate a fit of the deactivation data in paragraph (d)(1)(i) of this section at each aging temperature using the following linear expression:

![](/graphics/er22ap24.321.gif)Eq. 1065.1137-9Where:Ω = N2/N1 or = N2 (*Ω* is to be normalized to the degreened *Ω* value for each new catalyst component prior to aging, *i.e., Ω* = 1 at *t* = 0 for each aging temperature).![](/graphics/er22ap24.322.gif)(Eq. 1065.1137-5)*A* = pre-exponential factor.*E*a,D = thermal reactivity coefficient.*R* = molar gas constant.*T* = aging temperature.

(*2*) Generate a plot of 1/*Ω* versus *t* for each aging temperature evaluated in paragraph (c)(1) in this section. The slope of each line is equal to the thermal aging rate, *k*D, at a given aging temperature. Using the data pairs of aging temperature and thermal aging rate constant, *k*D, determine the thermal reactivity coefficient, *E*a, by performing a regression analysis of the natural log of *k*D versus the inverse of temperature, *T*, in Kelvin. Determine *E*a,D from the slope of the resulting regression line, *m*deactivation, using the following equation:

*E*a,D = −*m*deactivation · *R*Eq. 1065.1137-10Where:*m*deactivation = the slope of the regression line of ln(*k*D) versus 1/*T*.*R* = molar gas constant.

(2) *Iron-based zeolite or vanadium SCR.* Process all NH3 TPD data from each aging condition using a GPLE to fit the NH3 desorption data (or BTE surface area data for vanadium SCR). Note that this expression is different from the one used in paragraph (d)(1)(ii)(A) of this section because the model order *m* is allowed to vary. This general expression takes the following form:

![](/graphics/er22ap24.323.gif)Eq. 1065.1137-11Where:*Ω* = total NH3 (or BET surface area) normalized to the degreened value for each new catalyst component prior to aging (*i.e.,* Ω = 1 at *t* = 0 for each aging temperature).![](/graphics/er22ap24.324.gif)(Eq. 1065.1137-5)*A* = pre-exponential factor.*E*a,D = thermal reactivity coefficient.*R* = molar gas constant.*T* = aging temperature.*t* = time.Ωeq = aging metric at equilibrium (set to 0 unless there is a known activity minimum).*m* = model order.

(i) Solve Eq. 1065.1137-10 for Ω to yield the following expression:

![](/graphics/er22ap24.325.gif)Eq. 1065.1137-12Where:Ω0 = 1 (assumes total NH3 storage, or BET surface area, was normalized to the degreened value for each aging temperature).*A =* pre-exponential factor.*E*a,D = thermal reactivity coefficient.*R* = molar gas constant.*T* = aging temperature.*t* = aging time.*m* = model order (to be varied from 1 to 8 using whole numbers).

(ii) Global fitting is to be used to solve for *E*a,D and *A*D by applying a GRG nonlinear minimization algorithm, as described in paragraph (d)(1)(ii)(A) of this section. Minimize the *SSE*Global for each model order, *m*, while only allowing *E*a,D and *A*D to vary. The optimal solution is determined by selecting the model order, *m*, that yields the lowest global fit SSE. If you have a range of model order solutions where the *SSE*Global does not vary substantially, use good engineering judgement to choose the lowest *m* for this range.

(3) *Zone-coated zeolite SCR.* Derive the thermal reactivity coefficient, *E*a,D, for each zone of the SCR, based on the guidance provided in paragraphs (d)(1) and (2) of this section. The zone that yields the lowest *E*a,D shall be used for calculating the target cumulative thermal load, as outlined in § 1065.1139.

(4) *Diesel oxidation catalyst.* (i) The catalyst monolith is modeled as a plug flow reactor with first order reaction rate:

![](/graphics/er22ap24.326.gif)Eq. 1065.1137-13Where:*v* = velocity.*X* = conversion (NO to NO2) in %/100.*V* = volume of reactor.![](/graphics/er22ap24.327.gif)Eq. 1065.1137-14*A*D = pre-exponential factor.*E*a,D = thermal reactivity coefficient.*R* = molar gas constant.*T* = aging temperature.

(ii) For a diesel oxidation catalyst, the preexponential term *A*D is proportional to the number of active sites and is the desired aging metric. Solving Eq. 1065.1137-13 for *k*D, substituting it for *k*D in Eq. 1065.1137-5, and then solving for *A*D yields Eq. 1065.1137-15:

![](/graphics/er22ap24.328.gif)Eq. 1065.1137-15Where:*SV* = space velocity used during RLO testing.*X*= conversion (NO to NO2).*E*a,D = thermal reactivity coefficient.*T* = temperature where *X* was measured.*R* = molar gas constant.

(iii) Process all NO to NO2 oxidation RLO data for each aging condition by determining the average oxidation conversion efficiency, *X,* at the temperature determined in paragraph (b)(5) of this section. We recommend maintaining the target oxidation conversion temperature to ±5 °C. For each aging condition (aging temperature, *T* and aging time, *t*), calculate the aging metric, Ω, by normalizing *A*D to the degreened *A*D value for each new catalyst component prior to aging (*i.e.,* Ω = 1 at *t* = 0 for each aging temperature).

(A) Use the GPLE to fit the NO to NO2 conversion data, *X,* at each aging temperature. The GPLE takes the following form:

![](/graphics/er22ap24.329.gif)Eq. 1065.1137-16Where:Ω = aging metric for diesel oxidation catalysts.![](/graphics/er22ap24.330.gif)(Eq. 1065.1137-14)*R* = molar gas constant.*T* = aging temperature.*t* = aging time.Ωeq = aging metric at equilibrium (set to 0 unless there is a known activity minimum).*m* = model order.

(B) Solve Eq. 1065.1137-12 for to yield the following expression:

![](/graphics/er22ap24.331.gif)Eq. 1065.1137-17Where:Ωeq = 1 (assumes the oxidation efficiency, *X,* was normalized to the degreened value for each aging temperature).*A =* pre-exponential factor.*E*a,D = thermal reactivity coefficient.*R* = molar gas constant.*T* = aging temperature.*t* = aging time.*m* = model order (to be varied from 1 to 8 using whole numbers)

(iv) Use global fitting to solve for *E*a,D and *A* by applying a GRG nonlinear minimization algorithm, as described in paragraph (d)(1)(ii)(A) of this section. Minimize the *SSE*Global for each model order, *m,* while only allowing *E*a,D and *A* to vary. The optimal solution is determined by selecting the model order, *m,* that yields the lowest global fit SSE. If you have a range of model order solutions where the *SSE*Global does not vary substantially, use good engineering judgement to choose the lowest *m* for this range.

[89 FR 29827, Apr. 22, 2024]