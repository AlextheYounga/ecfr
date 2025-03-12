##### § 86.1370 Not-To-Exceed test procedures. #####

(a) *General.* The purpose of this test procedure is to measure in-use emissions of heavy-duty diesel engines while operating within a broad range of speed and load points (the Not-To-Exceed Control Area) and under conditions which can reasonably be expected to be encountered in normal vehicle operation and use. Emission results from this test procedure are to be compared to the Not-To-Exceed Limits specified in § 86.007-11(a)(4), or to later Not-To-Exceed Limits. The Not-To-Exceed Limits do not apply for engine-starting conditions. Tests conducted using the procedures specified in this subpart are considered valid Not-To-Exceed tests (Note: duty cycles and limits on ambient conditions do not apply for Not-To-Exceed tests).

(b) *Not-to-exceed control area for diesel heavy-duty engines.* The Not-To-Exceed Control Area for diesel heavy-duty engines consists of the following engine speed and load points:

(1) All operating speeds greater than the speed calculated using the following formula, where nhi and nlo are determined according to the provisions in § 86.1360(c):

nlo + 0.15 × (nhi-nlo)

(2) All engine load points greater than or equal to 30% or more of the maximum torque value produced by the engine.

(3) Notwithstanding the provisions of paragraphs (b)(1) and (2) of this section, all operating speed and load points with brake specific fuel consumption (BSFC) values within 5% of the minimum BSFC value of the engine. For the purposes of this requirement, BFSC must be calculated under the general test cell conditions specified in 40 CFR part 1065. The manufacturer may petition the Administrator at certification to exclude such points if the manufacturer can demonstrate that the engine is not expected to operate at such points in normal vehicle operation and use. Engines equipped with drivelines with multi-speed manual transmissions or automatic transmissions with a finite number of gears are not subject to the requirements of this paragraph (b)(3).

(4) Notwithstanding the provisions of paragraphs (b)(1) through (b)(3) of this section, speed and load points below 30% of the maximum power value produced by the engine shall be excluded from the Not-To-Exceed Control Area for all emissions.

(5) [Reserved]

(6)(i) For petroleum-fueled diesel cycle engines, the manufacturer may identify particular engine-vehicle combinations and may petition the Administrator at certification to exclude operating points from the Not-to-Exceed Control Area defined in paragraphs (b)(1) through (5) of this section if the manufacturer can demonstrate that the engine is not capable of operating at such points when used in the specified engine-vehicle combination(s).

(ii) For diesel cycle engines that are not petroleum-fueled, the manufacturer may petition the Administrator at certification to exclude operating points from the Not-to-Exceed Control Area defined in paragraphs (b)(1) through (5) of this section if the manufacturer can demonstrate that the engine is not expected to operate at such points in normal vehicle operation and use.

(7) Manufacturers may petition the Administrator to limit NTE testing in a single defined region of speeds and loads. Such a defined region must generally be of elliptical or rectangular shape, and must share some portion of its boundary with the outside limits of the NTE zone. Under this provision testing would not be allowed with sampling periods in which operation within that region constitutes more than 5.0 percent of the time-weighted operation within the sampling period. Approval of this limit by the Administrator is contingent on the manufacturer satisfactorily demonstrating that operation at the speeds and loads within that region accounts for less than 5.0 percent of all in-use operation (weighted by vehicle-miles-traveled or other EPA-approved weightings) for the in-use engines of that configuration (or sufficiently similar engines). At a minimum, this demonstration must include operational data from representative in-use vehicles.

(c) [Reserved]

(d) *Not-to-exceed control area limits.* (1) When operated within the Not-To-Exceed Control Area defined in paragraph (b) of this section, diesel engine emissions shall not exceed the applicable Not-To-Exceed Limits specified in § 86.007-11(a)(4) when averaged over any time period greater than or equal to 30 seconds, except where a longer minimum averaging period is required by paragraph (d)(2) of this section.

(2) For engines equipped with emission controls that include discrete regeneration events and that send a recordable electronic signal indicating the start and end of the regeneration event, determine the minimum averaging period for each NTE event that includes regeneration active operation as described in paragraph (d)(2)(i) of this section. This minimum averaging period is used to determine whether the individual NTE event is a valid NTE event. For engines equipped with emission controls that include multiple discrete regeneration events (*e.g.,* de-soot, de-NOX, de-SOX, etc.) and associated electronic signals, if an NTE event includes regeneration active operation on multiple regeneration signals, determine the minimum averaging period for each regeneration signal according to paragraph (d)(2)(i) of this section and use the longest period. This minimum averaging period applies if it is longer than 30 seconds. The electronic signal from the engine's ECU must indicate non-regeneration and regeneration operation. Regeneration operation may be further divided into regeneration pending and regeneration active operation. These are referred to as states 0, 1, and 2 for non-regeneration, regeneration pending, and regeneration active operation, respectively. No further subdivision of these states are allowed for use in this paragraph (d)(2). Where the electronic signal does not differentiate between regeneration pending and active operation, take the regeneration signal to mean regeneration active operation (state 2). A complete non-regeneration event is a time period that occurs during the course of the shift-day that is bracketed by regeneration operation, which is either regeneration active operation (state 2) or regeneration pending operation (state 1). A complete regeneration event is a time period that occurs during the course of the shift-day that is bracketed before and after by non-regeneration operation (state 0); a complete regeneration event includes any time in the event where regeneration is pending (state 1). The following figure provides an example of regeneration events during a shift-day:

![](/graphics/er08no10.021.gif)

(i) Calculate the minimum averaging period, *t*NTE,min, for each candidate NTE event as follows:

![](/graphics/er08no10.023.gif)Where:*i* = an indexing variable that represents periods of time within the candidate NTE event where the electronic signal indicates regeneration active operation (state 2).*N* = the number of periods of time within the candidate NTE event where the electronic signal indicates regeneration active operation (state 2).*t*2,NTE,i = the duration of the i-th time period within the candidate NTE event where the electronic signal indicates regeneration active operation (state 2), in seconds.*RF* = regeneration fraction over the course of the shift-day, as determined in paragraph (d)(2)(ii) of this section.

(ii) Calculate the regeneration fraction, *RF,* over the course of a shift-day as follows:

![](/graphics/er08no10.024.gif)Where:i = an indexing variable that represents complete regeneration events within the shift-day.j = an indexing variable that represents periods of time within the i-th complete regeneration event where the electronic signal indicates regeneration active operation (state 2).k = an indexing variable that represents complete non-regeneration events within the shift-day.*N*0 = the number of complete non-regeneration events within the shift-day.*N*12 = the number of complete regeneration events within the shift-day.*N*2,i = the number of periods of within the i-th complete regeneration event where the electronic signal indicates regeneration active operation (state 2).*t*0,k = the duration of the k-th complete non-regeneration event within the shift-day, in seconds.*t*12,i = the duration of the i-th complete regeneration event within the shift-day, in seconds, including time in those events where regeneration is pending (state 1).*t*2,i,j = the duration of the j-th time period within the i-th complete regeneration event where the electronic signal indicates regeneration active operation (state 2), in seconds. Note that this excludes time in each complete regeneration event where regeneration is pending (state 1).

(iii) If either N0 or N12 are zero, then RF cannot be calculated and all candidate NTE events that include regeneration active operation are void.

(iv) Compare the minimum averaging period for the candidate NTE event, *t*NTE,min, to the actual NTE duration, *t*NTE. If *t*NTE \<*t*NTE,min the candidate NTE event is void. If *t*NTE ≥*t*NTE,min the candidate NTE event is valid. It can also therefore be included in the overall determination of vehicle-pass ratio according to § 86.1912.

(v) You may choose to not void emission results for a candidate NTE event even though we allow you to void the NTE event under paragraph (d)(2)(iii) or (iv) of this section. If you choose this option, you must include the results for all regulated pollutants that were measured and validated during the NTE event for a given NTE monitoring system.

(vi)(A) The following is an example of calculating the minimum averaging period, *t*NTE,min, for a candidate NTE event. See Figure 1 of this section for an illustration of the terms to calculate the regeneration fraction, *RF.* For this example there are three complete non-regeneration events and two complete regeneration events in the shift-day.

*N*0 = 3*N*12 = 2

(B) The duration of the three complete non-regeneration events within the shift-day are:

*t*0,1 = 5424 s*t*0,2 = 6676 s*t*0,3 = 3079 s

(C) The sums of all the regeneration active periods in the two complete regeneration events are:

![](/graphics/er08no10.025.gif)

(D) The duration of each of the two complete regeneration events within the shift-day are:

*t*12,1 = 8440 s*t*12,2 = 3920 s

(E) The *RF* for this shift-day is:

![](/graphics/er08no10.026.gif)

(F) For this example, consider a candidate NTE event where there are two periods of regeneration active operation (state 2).

*t*2,NTE,1 = 37 s*t*2,NTE,2 = 40 s

(G) The minimum averaging period for this candidate NTE event is:

![](/graphics/er08no10.027.gif)tNTE,min = 320.0 s

(e) *Ambient corrections.* The measured data shall be corrected based on the ambient conditions under which it was taken, as specified in this section.

(1) For engines operating within the ambient conditions specified in § 86.007-11(a)(4)(ii)(a):

(i) NOX emissions shall be corrected for ambient air humidity to a standard humidity level of 50 grains (7.14 g/kg) if the humidity of the intake air was below 50 grains, or to 75 grains (10.71 g/kg) if above 75 grains.

(ii) NOX and PM emissions shall be corrected for ambient air temperature to a temperature of 55 degrees F (12.8 degrees C) for ambient air temperatures below 55 degrees F or to 95 degrees F (35.0 degrees C) if the ambient air temperature is above 95 degrees F.

(iii) No ambient air temperature or humidity correction factors shall be used within the ranges of 50-75 grains or 55-95 degrees F.

(iv) Where test conditions require such correction factors, the manufacturer must use good engineering judgement and generally accepted engineering practice to determine the appropriate correction factors, subject to EPA review.

(2) For engines operating within the ambient conditions specified in § 86.007-11(a)(4)(ii)(b):

(i) NOX emissions shall be corrected for ambient air humidity to a standard humidity level of 50 grains (7.14 g/kg) if the humidity of the intake air was below 50 grains, or to 75 grains (10.71 g/kg) if above 75 grains.

(ii) NOX and PM emissions shall be corrected for ambient air temperature to a temperature of 55 degrees F (12.8 degrees C) for ambient air temperatures below 55 degrees F.

(iii) No ambient air temperature or humidity correction factors shall be used within the ranges of 50-75 grains or for temperatures greater than or equal to 55 degrees F.

(iv) Where test conditions require such correction factors, the manufacturer must use good engineering judgement and generally accepted engineering practice to determine the appropriate correction factors, subject to EPA review.

(f) *NTE cold temperature operating exclusion.* Engines equipped with exhaust gas recirculation (EGR) whose operation within the NTE control area specified in paragraph (b) of this section when operating during cold temperature conditions as specified in paragraph (f)(1) of this section are not subject to the NTE emission limits during the specified cold temperature conditions.

(1) Cold temperature operation is defined as engine operating conditions meeting either of the following two criteria:

(i) Intake manifold temperature (IMT) less than or equal to the temperature defined by the following relationship between IMT and absolute intake manifold pressure (IMP) for the corresponding IMP:

![](/graphics/er06oc00.009.gif)Where: P = absolute intake manifold pressure in bars. IMT = intake manifold temperature in degrees Fahrenheit.

(ii) Engine coolant temperature (ECT) less than or equal to the temperature defined by the following relationship between ECT and absolute intake manifold pressure (IMP) for the corresponding IMP:

![](/graphics/er06oc00.010.gif)Where: P = absolute intake manifold pressure in bars. ECT = engine coolant temperature in degrees Fahrenheit.

(2) [Reserved]

(g) You may exclude emission data based on catalytic aftertreatment temperatures as follows:

(1) For an engine equipped with a catalytic NOX aftertreatment system, exclude NOX emission data that is collected when the exhaust temperature at any time during the NTE event is less than 250 °C.

(2) For an engine equipped with an oxidizing catalytic aftertreatment system, exclude NMHC and CO emission data that is collected if the exhaust temperature is less than 250 °C at any time during the NTE event.

(3) Using good engineering judgment, measure exhaust temperature within 30 cm downstream of the last applicable catalytic aftertreatment device. Where there are parallel paths, use good engineering judgment to measure the temperature within 30 cm downstream of the last applicable catalytic aftertreatment device in the path with the greatest exhaust flow.

(h) Any emission measurements corresponding to engine operating conditions that do not qualify as a valid NTE sampling event may be excluded from the determination of the vehicle-pass ratio specified in § 86.1912 for the specific pollutant.

(i) Start emission sampling at the beginning of each valid NTE sampling event, except as needed to allow for zeroing or conditioning the PEMS. For gaseous emissions, PEMS preparation must be complete for all analyzers before starting emission sampling.

(j) Emergency vehicle AECDs. If your engine family includes engines with one or more approved AECDs for emergency vehicle applications under paragraph (4) of the definition of “defeat device” in § 86.1803, the NTE emission limits do not apply when any of these AECDs are active. apply when any of these AECDs are active.

[65 FR 59961, Oct. 6, 2000, as amended at 66 FR 5188, Jan. 18, 2001; 70 FR 40441, July 13, 2005; 75 FR 68457, Nov. 8, 2010; 77 FR 34146, June 8, 2012. Redesignated and amended at 79 FR 23705, Apr. 28, 2014; 81 FR 73982, Oct. 25, 2016]