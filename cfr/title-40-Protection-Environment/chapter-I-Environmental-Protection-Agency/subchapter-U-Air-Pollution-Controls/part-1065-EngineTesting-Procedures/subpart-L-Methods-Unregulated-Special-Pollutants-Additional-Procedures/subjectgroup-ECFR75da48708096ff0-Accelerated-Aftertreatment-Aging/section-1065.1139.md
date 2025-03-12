##### § 1065.1139 Aging cycle generation. #####

Generation of the accelerated aging cycle for a given application involves analysis of the field data to determine a set of aging modes that will represent that field operation. There are two methods of cycle generation, each of which is described separately below. Method 1 involves the direct application of field data and is used when the recorded data includes sufficient exhaust flow and temperature data to allow for determination of aging conditions directly from the field data set and must be available for all of the key components. Method 2 is meant to be used when insufficient flow and temperature data is available from the field data. In Method 2, the field data is used to weight a set of modes derived from the laboratory certification cycles for a given application. These weighted modes are then combined with laboratory recorded flow and temperatures on the certification cycles to derive aging modes. There are two different cases to consider for aging cycle generation, depending on whether or not a given aftertreatment system incorporates the use of a periodic regeneration event. For the purposes of this section, a “regeneration” is any event where the operating temperature of some part of the aftertreatment system is raised beyond levels that are observed during normal (non-regeneration) operation. The analysis of regeneration data is considered separately from normal operating data.

(a) *Cycle generation process overview.* The process of cycle generation begins with the determination of the number of bench aging hours. The input into this calculation is the number of real or field hours that represent the useful life for the target application. This could be given as a number of hours or miles, and for miles, the manufacturer must use field data and good engineering judgment to translate this to an equivalent number of operating hours for the target application. The target for the accelerated aging protocol is a 10-time acceleration of the aging process, therefore the total number of aging hours is always set at useful life hours divided by 10. For example, if an on-highway heavy duty engine has a full useful life of 750,000 miles and this is determined to be represented by 24,150 field hours, the target duration for the DAAAC protocol for this application would be 2,415 bench-aging hours. The 2,415 hours will then be divided among different operating modes that will be arranged to result in repetitive temperature cycling over that period. For systems that incorporate periodic regeneration, the total duration will be split between regeneration and normal (non-regeneration) operation. The analysis of normal operation data is given in paragraph (b) of this section. The analysis of regeneration data is given in paragraph (c) of this section.

(b) *Analysis of normal (non-regeneration) operating data.* This analysis develops a reduced set of aging modes that represent normal operation. As noted earlier, there are two methods for conducting this analysis, based on the data available.

(1) *Method 1—Direct clustering.* Use Method 1 when sufficient exhaust flow and temperature data are available directly from the field data. The data requirements for Method 1 are described in § 1065.1133(b)(1). The method involves three steps: clustering analysis, mode consolidation, and cycle building.

(i) The primary method for determining modes from a field data set involves the use of k-means clustering. K-means clustering is a method where a series of observations is partitioned into set of clusters of “similar” data points, where every observation is a member of a cluster with the nearest mean, which is referred to as the centroid of that cluster. The number of clusters is a parameter of the analysis, and the k-means algorithm generally seeks an optimal number of clusters to minimize the least-squares distance of all points to their respective centroids. There are a number of different commercially available software programs to perform k-means clustering, as well as freely available algorithm codes. K-means clustering can arrive at many different solutions, and we are providing the following guidance to help select the optimal solution for use in accelerated aging cycle generation. The process involves analyzing the data multiple time using an increasing number of clusters for each analysis. Use at least 5 clusters, and we recommend developing solutions for the range between 5 and 8 clusters, although you may use more if desired. Each cluster is a potential aging mode with a temperature and flow rate defined by the centroid. More clusters result in more aging modes, although this number may be reduced later via model consolidation.

(ii) The cubic clustering criteria (CCC) is a metric calculated for each solution having a different number of clusters. The computation of CCC is complex and described in more detail in the following reference. The CCC computation is normally available as one of the metrics in commercially available software packages that can be used for k-means clustering. The optimal solution is typically the one with the number of clusters corresponding to the highest CCC.

(iii) Check each solution, starting with the one with the highest CCC to determine if it satisfies the following requirements:

(A) No more than one cluster contains fewer than 3% of the data points.

(B) The temperature ratio between the centroid with the maximum temperature and the centroid with the minimum temperature is at least 1.6 for clusters containing more than 3% of the data points.

(C) If that solution does not satisfy these requirements move to the solution with the next highest CCC.

(iv) The process described in paragraph (c)(1)(iii) of this section generally works well for most data sets, but if you have difficulty with the CCC metric in a particular data set, use good engineering judgment to leverage additional criteria to help the down-selection process. Examples of alternate clustering metrics include a Davies-Bouldin Index (optimizing on the minimum value) or a Calinski-Harabasz Index (optimize on the maximum value).

(v) The initial candidate mode conditions are temperature and flow rate combinations that are the centroids for each cluster from the analysis in paragraph (c)(1)(iii) of this section. As part of the analysis, you must also determine the 10th percentile and 90th percentile temperatures for each cluster. These additional values may be needed later for the cycle heat load tuning process described in § 1065.1143.

(vi) The mode weight factor for a given cluster is the fraction data points contained within that cluster.

(2) *Method 2—Cluster-based weighting of certification cycle modes.* Use Method 2 if there is insufficient exhaust flow and temperature data from the field at the time the cycle is being developed. The data requirements for Method 2 are described in § 1065.1133(b)(2). You also need laboratory data recorded in the form of 1 Hz data sets for the regulatory duty cycles you are certifying to for your application as described in the standard setting part. Include exhaust flow rate and the inlet temperature for each key catalyst component in the laboratory data sets, as described in paragraph (e) of this section. The laboratory data sets must also include parameters that match the field data as described in § 1065.1133(b)(2), which will be used to facilitate the clustering analysis.

(i) Perform k-means clustering is described in § 1065.1133(b)(1) but using data sets containing the two parameters recorded in the field data sets. For example, you might use speed and torque, as recorded both in the field and the laboratory for Method 2 clustering.

(ii) Determine the fraction of points from each of the regulatory laboratory duty-cycles that are within each cluster, in addition to the overall fraction of points from the entire data set.

(iii) For each cycle, calculate a square sum error, *SSE,* as follows:

![](/graphics/er24ja23.149.gif)Where:*i* = an indexing variable that represents one cluster.*N* = total number of clusters.*Cycle*prob = the fraction of points in a given cluster, *i,* for the regulatory duty-cycle of interest.*RefData*prob = the fraction of points in a given cluster, *i,* for the full data set.

(iv) For each cycle, calculate a dissimilarity index as follows:

![](/graphics/er24ja23.150.gif)Where:*SSE* = sum square error from Eq. 1065.1139-2.*N* = total number of clusters.

(v) If you have more than one regulatory duty cycle, weight the regulatory cycles.

(A) Determine the weighting factors for a given regulatory cycle, *w*i, by solving a system of equations:

![](/graphics/er24ja23.151.gif)Where:*d*i = dissimilarity for a given regulatory cycle, *i.**d*j = dissimilarity for a given regulatory cycle, *j.*

(B) For example, for three duty cycles, calculate *w*1 as follows:

![](/graphics/er24ja23.152.gif)

(C) Calculate subsequent wi values after calculating w1 as follows:

![](/graphics/er24ja23.153.gif)

(D) Calculate the sum of the weighting factors to verify that they are equal to one.

![](/graphics/er24ja23.154.gif)Where:*n* = number of regulatory cycles for the application.

(vi) For each regulatory cycle determine the average exhaust flow and the average inlet temperature for each key catalyst. Determine the 25th and 90th percentile inlet temperatures for the primary catalyst and the respective associated exhaust flow rate for each data point.

(vii) Use the cycle weights from paragraph (b)(2)(v) of this section and the mode conditions from paragraph (b)(2)(vi) of this section to generate a set of candidate aging modes by multiplying the cycle weight factor, *w*[cycle] by 0.25 for the 25th percentile temperature mode, 0.65 for the 50th percentile temperature mode, and by 0.10 for the 90th percentile temperature mode. This will generate a weighted set of mode numbers three times the number of regulatory cycles for the target application. Each mode will have a target temperature and exhaust flow rate.

(viii) If you have only one regulatory cycle for your application, use the cycle modes and weighting factors as they are given in the standard setting part.

(3) *Determination of mode total durations.* The output for either method will be a set of mode exhaust conditions, with an associated weighting factor for each mode. Multiply the mode weight factors by the total number of normal operating (non-regenerating) hours, to get a target mode duration for each mode. This will be used in the heat load calculations.

(c) *Mode consolidation.* Sometimes the clustering analysis process will generate multiple modes that are very similar to each other in temperature, such that although they are distinct modes they will not have a significantly different impact on aftertreatment aging. To reduce the complexity of the aging cycle, you may consolidate modes that are similar into a single mode as described below.

(1) Consolidate any two or more modes which have a target temperature within 10 °C into a single mode. If you choose to do this, the target temperature of the single consolidated mode is the temperature associated with the highest weight factor mode before consolidation. If the modes being consolidated all have weighting factors within 0.05 of each other, use the highest temperature among the modes.

(2) Use the highest exhaust flow target among the modes being combined as the target exhaust flow for new consolidate mode.

(3) Use the combined sum of the weighting factors for all modes being consolidate as the weighting factor for the new consolidated mode. Similarly, the total duration of the new consolidated mode is the sum of the durations of the modes being consolidated.

(d) *Analysis of regeneration data.* Regeneration data is treated separately from the normal operating mode data. Generally, the target for accelerated aging cycle operation is to run all of the regenerations that would be expected over the course of useful life. If multiple types of regeneration are conducted on different system components, each type of regeneration must be analyzed separately using the steps in this paragraph (d). The data requirements for input into this process are described in § 1065.1133(b)(3). The process described below is meant to determine a representative regeneration profile that will be used during aging. You may also ask us to allow the use of other engineering data or analysis to determine a representative regeneration profile.

(1) The total number of regenerations that will be run during the accelerated aging process will be the same as the total number of regenerations over useful life. Calculate this number by dividing the total number of useful life hours by the interval between regenerations as determined in § 1065.1133(b)(3).

(2) Use the 1 Hz regeneration data to determine an appropriate regeneration profile. The recorded regeneration event begins when the engine indicates it has started regeneration using the recorded regeneration indicator and ends when the aftertreatment has returned back to the normal operating temperature after the flag indicates the regeneration is complete.

(3) For each recorded regeneration, calculate the cumulative deactivation, *D*t, using the equations in paragraph (e) of this section.

(4) If you have a large number of recorded regenerations in your data set, select a regeneration event with a cumulative deactivation representing the 75th percentile of the distribution of heat loads in your recorded data set. If you have a smaller number of recorded regenerations, such that you cannot clearly identify the real distribution, select the recorded regeneration with the highest recorded cumulative deactivation.

(5) This regeneration event will be used as the regeneration profile for that type of event during aging. The profile should include the entire event, include the temperature ramp and cool-down period.

(6) The regeneration must be conducted in the same manner as it is run in the field. For instance, if the regeneration temperature is generated from an exothermic reaction by injecting fuel in front of a DOC, this methodology should also be used during bench aging.

(7) If part of the system is at a lower temperature during regeneration because it is upstream of the temperature generating component, the set the target temperature for the aftertreatment system inlet to be equivalent to the system inlet temperature used during the highest duration non-regeneration mode, or 350 °C, whichever is lower.

(e) *Heat load calculation and tuning for systems that have regeneration events.* Perform this procedure after the preliminary cycles are completed for both normal and regeneration operation. The target cumulative deactivation is determined from the input field data, and then a similar calculation is performed for the preliminary aging cycle. If the cumulative deactivation for the preliminary cycle does not match cumulative deactivation from the field data, then the cycle is tuned over a series of steps until the target is matched.

(1) The deactivation for a given catalyst is calculated for each time step as follows:

![](/graphics/er24ja23.155.gif)Where:*D*i = incremental deactivation for time step *i.**E*a = thermal reactivity coefficient for the catalyst as determined in § 1065.1137.*R* = molar gas constant in kJ/mol·K.*T*std = standard temperature = 293.15 K.*T* = catalyst temperature in K.

(2) Calculate the cumulative deactivation, *D*t, for a given catalyst over a series of time steps, *N*, using the following equation:

![](/graphics/er24ja23.156.gif)Where:*i* = an indexing variable that represents one time step.*N* = total number of cumulative deactivation time steps in the data set.*D*i = incremental deactivation for each time step.

(3) Calculate the cumulative deactivation, *D*t, for the input field data set. The time step for the calculations should be 1 second for 1-Hz input data.

(i) First calculate *D*t for the non-regeneration portion of the field data set. For Method 2 use the 1-Hz data from the regulatory cycles as the field data set.

(ii) Divide the calculate field *D*t by the number of hours represented in the field data set.

(iii) Multiply the hourly *D*t by the number of hours required to reach full useful life. This is the target *D*t,field-normi.

(iv) Multiply the total number of regenerations for full useful life by the cumulative deactivation *D*t for the target regeneration profile determined in paragraph (d)(4) of this section. This is the target *D*t,field-regen.

(v) The total target cumulative deactivation for the field data, *D*t,field, is the sum of *D*t,field-normi and *D*t,field-regen.

(4) Calculate the cumulative deactivation for the candidate aging cycle generated under paragraphs (c) and (d) of this section as follows:

(i) Using the modes and mode durations for normal operation generated in paragraph (c) of this section, calculate the cumulative deactivation, *D*t,cycle-norm, using the method given in paragraph (e)(2) of this section.

(ii) The total cumulative deactivation for the candidate aging cycle, *D*t, is the sum of *D*t,cycle-norm and *D*t,field-regen.

(5) If *D*t,cycle is within ±1% of *D*t,field, the candidate cycle is deemed representative and may be used for aging.

(6) If *D*t,cycle is not within ±1% of *D*t,field, the candidate cycle must be adjusted to meet this criterion using the following steps. It should be noted that if the *D*t,cycle is outside of the criteria it will usually be lower than the *D*t,field.

(i) Increase the duration of the stable portion of the regeneration profile, which is defined as the portion of the regeneration profile where the temperature has completed ramping and is being controlled to a stationary target temperature. Note that this will increase the number of hours of regeneration time. You must compensate for this by decreasing the total number of normal operation (non-regeneration) hours in the cycle. Recalculate the duration of all the normal operation modes. You may not increase the duration of the stable portion of the regeneration profile by more than a factor of 2. If you reach this limit and you still do not meet the criteria in paragraph (e)(5) of this section, proceed to the next step.

(ii) Increase the target temperature of the stable portion of the regeneration profile by the amount necessary to reach the target criteria. You may not increase this temperature higher than the temperature observed in the regeneration profile with the highest *D*t observed in the field. If you reach this limit and you still do not meet the criteria in paragraph (e)(5) of this section, proceed to the next step.

(iii) Increase the target temperature of the highest temperature normal operation mode. You may not increase this temperature above the 90th percentile determined in paragraph (b)(1)(v) of this section for Method 1, or above the maximum temperature for the regulatory cycle from which the mode was derived for Method 2. If you reach this limit and you still do not meet the criteria in paragraph (e)(5) of this section, you may repeat this step using the next highest temperature mode, until you reach the target, or all modes have been adjusted.

(iv) If you are unable to reach the target deactivation by following paragraphs (e)(6)(i) through (iii) of this section, use good engineering judgment to increase the number of regenerations to meet the criteria in paragraph (e)(5) of this section. Note that this will increase the total regeneration hours, therefore you must decrease the number of normal operation hours and re-calculate mode durations for the normal operation modes.

(v) If you are not able to achieve the target *D*t,field using the steps in paragraphs (e)(6)(i) through (iv) of this section without exceeding catalyst temperature limits, use good engineering judgement to reduce the acceleration factor from 10 to a lower number. If you reduce the acceleration factor you must re-calculate the number of hours determine in paragraph (a) of this section and re-run the process in this paragraph (e). Note that if you reduce the acceleration factor you must use the same lower acceleration factor in the chemical exposure calculations in paragraph (h) of this section, instead of 10.

(f) *Heat load calculation and tuning for systems that do not have regeneration events.* Follow the steps described for systems with regeneration events to calculate *D*t,field and *D*t,cycle, omitting the steps related to regeneration events. The *D*t,cycle will be well below the *D*t,field. Follow the steps given below to adjust the cycle until you meet the criteria in paragraph (e)(5) of this section.

(1) Increase the temperature of the highest temperature mode. Use good engineering judgment to ensure that this temperature does not exceed the limits of the catalyst in a way that might cause rapid deactivation or failure via a mechanism that is not considered normal degradation.

(2) Increase the duration of the highest temperature mode and decrease the duration of the other modes in proportion. You may not increase the duration highest temperature mode by more than a factor of 2.

(3) If you are not able to achieve the target *D*t,field using the steps in paragraphs (f)(1) and (2) of this section without exceeding catalyst temperature limits, use good engineering judgement to reduce the acceleration factor from 10 to a lower number. If you reduce the acceleration factor you must re-calculate the number of hours determine in paragraph (a) of this section and re-run the process in this paragraph (f). Note that if you reduce the acceleration factor you must use the same lower acceleration factor in the chemical exposure calculations in paragraph (h) of this section, instead of 10.

(g) *Final aging cycle assembly.* The final step of aging cycle development is the assembly of the actual cycle based on the mode data from either paragraph (e) of this section for systems with infrequent regeneration, or paragraph (f) of this section for systems that do not incorporate infrequent regeneration. This cycle will repeat a number of times until the total target aging duration has been reached.

(1) *Cycle assembly with infrequent regenerations.* For systems that use infrequent regenerations, the number of cycle repeats is equal to the number of regeneration events that happen over full useful life. The total cycle duration of the aging cycle is calculated as the total aging duration in hours divided by the number of infrequent regeneration events. In the case of systems with multiple types of infrequent regenerations, use the regeneration with the lowest frequency to calculate the cycle duration.

(i) If you have multiple types of infrequent regenerations, arrange the more frequent regenerations such that they are spaced evenly throughout the cycle.

(ii) Determine the length of the normal (non-regeneration) part of the cycle by subtracting the regeneration duration, including any regeneration extension determined as part of cycle tuning from paragraph (e) of this section, from the total cycle duration. If you have multiple types of regeneration, then the combined total duration of regeneration events performed in the cycle must be subtracted from the total. For example, if you have one type of regeneration that is performed for 30 minutes every 30 cycle hours, and a second type that is performed for 30 minutes every 10 cycle hours (such that 3 of these secondary events will happen during each cycle), then you would subtract a total of 2 hours of regeneration time from the total cycle duration considering all 4 of these events.

(iii) Divide the duration of the normal part of the cycle into modes based on the final weighting factors determined in paragraph (c) of this section following any mode consolidation.

(iv) Place the mode with the lowest temperature first, then move to the highest temperature mode, followed by the next lowest temperature mode, and then the next highest mode, continuing in this alternating pattern until all modes are included.

(v) Transition between normal modes within (60 to 300) seconds. The transition period is considered complete when you are within ±5 °C of the target temperature for the primary key component. Transitions may follow any pattern of flow and temperature to reach this target within the required 300 seconds.

(vi) For normal modes longer than 30 minutes, you may count the transition time as time in mode. Account for the transition time for modes shorter than 30 minutes by shortening the duration of the longest mode by an equivalent amount of time.

(vii) If the shortest normal operating mode is longer than 60 minutes, you must divide the normal cycle into shorter sub-cycles with the same pattern in paragraph (g)(1)(iii) of this section, but with shorter durations, so that the pattern repeats two or more times. You must divide the cycle into sub-cycles until the duration of the shortest mode in each sub-cycle is no longer than 30 minutes. No mode may have a duration shorter than 15 minutes, not including transition time.

(viii) If a regeneration event is scheduled to occur during a normal mode, shift the start of regeneration to the end of the nearest normal mode.

(2) *Cycle assembly without infrequent regenerations.* For systems that do not use infrequent regenerations, the cycle will be arranged to achieve as much thermal cycling as possible using the following steps.

(i) Assign a duration of 15 minutes to the mode with the lowest weight factor. Calculate the duration of the remaining modes in proportion to the final weight factors after mode durations have been adjusted during heat load tuning in paragraph (f) of this section.

(ii) Place the mode with the lowest temperature first, then move to the highest temperature mode, followed by the next lowest temperature mode, and then the next highest mode, continuing in this alternating pattern until all modes are included.

(iii) Transition between normal modes within (60 to 300) seconds. The transition period is considered complete when you are within ±5 °C of the target temperature for the primary key component. Transitions may follow any pattern of flow and temperature to reach this target within the required 300 seconds.

(iv) For normal modes longer than 30 minutes, you may count the transition time as time in mode. Account for the transition time for modes shorter than 30 minutes by shortening the duration of the longest mode by an equivalent amount of time.

(v) This cycle will be repeated the number of times necessary to reach the target aging duration.

(h) *Chemical exposure targets.* Determine targets for accelerated oil and fuel sulfur exposure as follows:

(1) *Oil exposure targets.* The target oil exposure rate during accelerated aging is 10 times the field average oil consumption rate determined in § 1065.1133(a)(2). You must achieve this target exposure rate on a cycle average basis during aging. Use good engineering judgment to determine the oil exposure rates for individual operating modes that will achieve this cycle average target. For engine-based aging stands you will likely have different oil consumption rates for different modes depending on the speed and load conditions you set. For burner-based aging stands, you may find that you have to limit oil exposure rates at low exhaust flow or low temperature modes to ensure good atomization of injected oil. On a cycle average basis, the portion of oil exposure from the volatile introduction pathway (*i.e.,* oil doped in the burner or engine fuel) must be between (10 to 30) % of the total. The remainder of oil exposure must be introduced through bulk pathway.

(2) *Fuel sulfur exposure targets.* The target sulfur exposure rate for fuel-related sulfur is determined by utilizing the field mean fuel rate data for the engine determined in § 1065.1133(a)(3). Calculate the total sulfur exposure mass using this mean fuel rate, the total number of non-accelerated hours to reach full useful life, and a fuel sulfur level of 10 ppmw.

(i) For an engine-based aging stand, if you perform accelerated sulfur exposure by additizing engine fuel to a higher sulfur level, determine the accelerated aging target additized fuel sulfur mass fraction, *w*S, as follows:

![](/graphics/er22ap24.332.gif)Eq. 1065.1139-9Where:*m*fuel,field = field mean fuel flow rate.*m*fuel,cycle = accelerated aging cylce mean fuel low rate.*m*Sfuel,ref = reference mass of sulfur per mass of fuel = 0.00001 kg/kg.*S*acc,rate = sulfur acceleration rate = 10.

*Example:*

*m*fuel,field= 54.3 kg/hr*m*fuel,cycle = 34.1 kg/hr*m*Sfuel,ref = 0.00001 kg/kg.*S*acc,rate = 10![](/graphics/er22ap24.333.gif)

(ii) If you use gaseous SO2 to perform accelerated sulfur exposure, such as on a burner-based stand, calculate the target SO2 concentration to be introduced, *x*SO2,target, as follows:

![](/graphics/er22ap24.334.gif)Eq. 1065.1139-10Where:*m*fuel,field = field mean fuel flow rate.*m*exhaust,cycle = mean exhaust flow rate during the burner aging cycle.*x*Sfuel,ref = reference mol fraction of sulfur in fuel = 10 µmol/mol.*S*acc,rate = sulfur acceleration rate = 10.*M*exh = molar mass of exhaust = molar mass of air.*M*S = molar mass of sulfur.

Example:

*m*fuel,field= 54.3 kg/hr*m*exhaust,cycle= 1000.8 kg/hr*x*Sfuel,ref = 10 µmol/mol*S*acc,rate = 10*M*exh = 28.96559 g/mol*M*S = 32.065 g/mol![](/graphics/er22ap24.335.gif)

(iii) You may choose to turn off gaseous sulfur injection during infrequent regeneration modes, but if you do you must increase the target SO2 concentration by the ratio of total aging time to total normal (non-regeneration) aging time.

[79 FR 23820, Apr. 28, 2014, as amended at 89 FR 29829, Apr. 22, 2024]