##### § 1065.602 Statistics. #####

(a) *Overview.* This section contains equations and example calculations for statistics that are specified in this part. In this section we use the letter “y” to denote a generic measured quantity, the superscript over-bar “-” to denote an arithmetic mean, and the subscript “ref” to denote the reference quantity being measured.

(b) *Arithmetic mean.* Calculate an arithmetic mean, *y*, as follows:

![](/graphics/er29jn21.176.gif)Example:*N* = 3*y*1 = 10.60*y*2 = 11.91*y*N = *y*3 = 11.09![](/graphics/er29jn21.177.gif)*y* = 11.20

(c) *Standard deviation.* Calculate the standard deviation for a non-biased (*e.g.,* N-1) sample, σ, as follows:

![](/graphics/er29jn21.178.gif)Example:*N* = 3*y*1 = 10.60*y*2 = 11.91*y*N = *y*3 = 11.09*y* = 11.20![](/graphics/er29jn21.179.gif)σy = 0.6619

(d) *Root mean square.* Calculate a root mean square, *rms*y, as follows:

![](/graphics/er29jn21.180.gif)Example:*N* = 3*y*1 = 10.60*y*2 = 11.91*y*N = *y*3 = 11.09![](/graphics/er29jn21.181.gif)*rms*y = 11.21

(e) *Accuracy.* Determine accuracy as described in this paragraph (e). Make multiple measurements of a standard quantity to create a set of observed values, *y*i, and compare each observed value to the known value of the standard quantity. The standard quantity may have a single known value, such as a gas standard, or a set of known values of negligible range, such as a known applied pressure produced by a calibration device during repeated applications. The known value of the standard quantity is represented by *y*refi. If you use a standard quantity with a single value, *y*refi would be constant. Calculate an accuracy value as follows:

![](/graphics/er29jn21.182.gif)Example:*y*ref = 1800.0*N* = 3*y*1 = 1806.4*y*2 = 1803.1*y*3 = 1798.9![](/graphics/er29jn21.183.gif)*accuracy* = 2.8

(f) *t-test.* Determine if your data passes a *t*-test by using the following equations and tables: (1) For an unpaired *t*-test, calculate the *t* statistic and its number of degrees of freedom, *v*, as follows:

![](/graphics/er29jn21.184.gif)![](/graphics/er29jn21.185.gif)Example:*Y*ref = 1205.3*Y* = 1123.8σref = 9.399σy = 10.583*N*ref = 11*N* = 7![](/graphics/er29jn21.186.gif)*t* = 16.63σref = 9.399σy = 10.583*N*ref = 11*N* = 7![](/graphics/er29jn21.187.gif)*v* = 11.76

(2) For a paired *t*-test, calculate the *t* statistic and its number of degrees of freedom, *v*, as follows, noting that the εi are the errors (*e.g.,* differences) between each pair of *y*refi and *y*i:

![](/graphics/er29jn21.188.gif)Example 1:*ε* = −0.12580*N* = 16σε = 0.04837![](/graphics/er29jn21.189.gif)*t* = 10.403*v* = *N*−1Example 2:*N* = 16*v* = 16−1*v* = 15

(3) Use Table 1 of this section to compare *t* to the *t*crit values tabulated versus the number of degrees of freedom. If *t* is less than *t*crit, then *t* passes the *t*-test. The Microsoft Excel software has a TINV function that returns results equivalent results and may be used in place of Table 1, which follows:

|                                    v                                    |Confidence|      |
|-------------------------------------------------------------------------|----------|------|
|                                   90%                                   |   95%    |      |
|                                    1                                    |  6.314   |12.706|
|                                    2                                    |  2.920   |4.303 |
|                                    3                                    |  2.353   |3.182 |
|                                    4                                    |  2.132   |2.776 |
|                                    5                                    |  2.015   |2.571 |
|                                    6                                    |  1.943   |2.447 |
|                                    7                                    |  1.895   |2.365 |
|                                    8                                    |  1.860   |2.306 |
|                                    9                                    |  1.833   |2.262 |
|                                   10                                    |  1.812   |2.228 |
|                                   11                                    |  1.796   |2.201 |
|                                   12                                    |  1.782   |2.179 |
|                                   13                                    |  1.771   |2.160 |
|                                   14                                    |  1.761   |2.145 |
|                                   15                                    |  1.753   |2.131 |
|                                   16                                    |  1.746   |2.120 |
|                                   18                                    |  1.734   |2.101 |
|                                   20                                    |  1.725   |2.086 |
|                                   22                                    |  1.717   |2.074 |
|                                   24                                    |  1.711   |2.064 |
|                                   26                                    |  1.706   |2.056 |
|                                   28                                    |  1.701   |2.048 |
|                                   30                                    |  1.697   |2.042 |
|                                   35                                    |  1.690   |2.030 |
|                                   40                                    |  1.684   |2.021 |
|                                   50                                    |  1.676   |2.009 |
|                                   70                                    |  1.667   |1.994 |
|                                   100                                   |  1.660   |1.984 |
|                                  1000+                                  |  1.645   |1.960 |
|<sup>a</sup> Use linear interpolation to establish values not shown here.|          |      |

(g) *F-test*. Calculate the *F* statistic as follows:

![](/graphics/er29jn21.190.gif)Example:![](/graphics/er29jn21.191.gif)*F* = 1.268

(1) For a 90% confidence *F*-test, use the following table to compare *F* to the *F*crit90 values tabulated versus (*N*−1) and (*N*ref−1). If *F* is less than *F*crit90, then *F* passes the *F*-test at 90% confidence.

![](/graphics/er29jn21.192.gif)

(2) For a 95% confidence *F*-test, use the following table to compare *F* to the *F*crit90 values tabulated versus (*N*−1) and (*N*ref−1). If *F* is less than *F*crit95, then *F* passes the *F*-test at 95% confidence.

![](/graphics/er29jn21.193.gif)

(h) *Slope.* Calculate a least-squares regression slope, *a*1y, using one of the following two methods:

(1) If the intercept floats, *i.e.,* is not forced through zero:

![](/graphics/er29jn21.194.gif)Example:*N* = 6000*y*1 = 2045.8*y* = 1050.1*y*ref1 = 2045.0*y*ref = 1055.3![](/graphics/er29jn21.195.gif)*a*1y = 1.0110

(2) If the intercept is forced through zero, such as for verifying proportional sampling:

![](/graphics/er29jn21.196.gif)Example:*N* = 6000*y*1 = 2045.8*y*ref1 = 2045.0![](/graphics/er29jn21.197.gif)*a*1y = 1.0110

(i) *Intercept*. For a floating intercept, calculate a least-squares regression intercept, a0y, as follows:

![](/graphics/er29jn21.198.gif)Example:*y* = 1050.1*a*1y = 1.0110*y*ref = 1055.3*a*0y = 1050.1 − (1.0110 · 1055.3)*a*0y = −16.8083

(j) *Standard error of the estimate*. Calculate a standard error of the estimate, *SEE*, using one of the following two methods:

(1) For a floating intercept:

![](/graphics/er29jn21.199.gif)Example:*N* = 6000*y*1 = 2045.8*a*0y = −16.8083*a*1y = 1.0110*y*ref1 = 2045.0![](/graphics/er29jn21.200.gif)*SEE*y = 5.348

(2) If the intercept is forced through zero, such as for verifying proportional sampling:

![](/graphics/er29jn21.201.gif)Example:*N* = 6000*y*1 = 2045.8*a*1y = 1.0110*y*ref1 = 2045.0![](/graphics/er29jn21.202.gif)*SEE*y = 5.347

(k) *Coefficient of determination.* Calculate a coefficient of determination, *r*y2, as follows:

![](/graphics/er29jn21.203.gif)Example:*N* = 6000*y*1 = 2045.8*a*0y = −16.8083*a*1y = 1.0110*y*ref1 = 2045.0*y* = 1480.5![](/graphics/er29jn21.204.gif)

(l) *Flow-weighted mean concentration.* In some sections of this part, you may need to calculate a flow-weighted mean concentration to determine the applicability of certain provisions. A flow-weighted mean is the mean of a quantity after it is weighted proportional to a corresponding flow rate. For example, if a gas concentration is measured continuously from the raw exhaust of an engine, its flow-weighted mean concentration is the sum of the products of each recorded concentration times its respective exhaust molar flow rate, divided by the sum of the recorded flow rate values. As another example, the bag concentration from a CVS system is the same as the flow-weighted mean concentration because the CVS system itself flow-weights the bag concentration. You might already expect a certain flow-weighted mean concentration of an emission at its standard based on previous testing with similar engines or testing with similar equipment and instruments. If you need to estimate your expected flow-weighted mean concentration of an emission at its standard, we recommend using the following examples as a guide for how to estimate the flow-weighted mean concentration expected at the standard. Note that these examples are not exact and that they contain assumptions that are not always valid. Use good engineering judgment to determine if you can use similar assumptions.

(1) To estimate the flow-weighted mean raw exhaust NOX concentration from a turbocharged heavy-duty compression-ignition engine at a NOX standard of 2.5 g/(kW·hr), you may do the following:

(i) Based on your engine design, approximate a map of maximum torque versus speed and use it with the applicable normalized duty cycle in the standard-setting part to generate a reference duty cycle as described in § 1065.610. Calculate the total reference work, *W*ref, as described in § 1065.650. Divide the reference work by the duty cycle's time interval, Δ*t*dutycycle, to determine mean reference power, *p*ref.

(ii) Based on your engine design, estimate maximum power, *P*max, the design speed at maximum power, ƒnmax, the design maximum intake manifold boost pressure, *P*inmax, and temperature, *T*inmax. Also, estimate a mean fraction of power that is lost due to friction and pumping, Pfrict. Use this information along with the engine displacement volume, *V*disp, an approximate volumetric efficiency, η V, and the number of engine strokes per power stroke (two-stroke or four-stroke), *N*stroke, to estimate the maximum raw exhaust molar flow rate, *n*exhmax.

(iii) Use your estimated values as described in the following example calculation:

![](/graphics/er29jn21.205.gif)Example:*e*NOX = 2.5 g/(kW·hr)*W*ref = 11.883 kW·hr*M*NOX = 46.0055 g/mol = 46.0055·10−6 g/µmolΔ*t*dutycycle = 20 min = 1200 s*P*ref = 35.65 kW*P*frict = 15%*P*max = 125 kW*p*max = 300 kPa = 300000 Pa*V*disp = 3.0 l = 0.0030 m3/r*f*nmax = 2800 r/min = 46.67 r/s*N*stroke = 4ηV = 0.9*R* = 8.314472 J/(mol·K)*T*max = 348.15 K![](/graphics/er29jn21.206.gif)

(2) To estimate the flow-weighted mean NMHC concentration in a CVS from a naturally aspirated nonroad spark-ignition engine at an NMHC standard of 0.5 g/(kW·hr), you may do the following:

(i) Based on your engine design, approximate a map of maximum torque versus speed and use it with the applicable normalized duty cycle in the standard-setting part to generate a reference duty cycle as described in § 1065.610. Calculate the total reference work, *W*ref, as described in § 1065.650.

(ii) Multiply your CVS total molar flow rate by the time interval of the duty cycle, Δ*t*dutycycle. The result is the total diluted exhaust flow of the *n*dexh.

(iii) Use your estimated values as described in the following example calculation:

![](/graphics/er29jn21.207.gif)Example:*e*NMHC = 1.5 g/(kW·hr)*W*ref = 5.389 kW·hr*M*NMHC = 13.875389 g/mol = 13.875389·10−6 g/µmol*n*dexh = 6.021 mol/sΔ*t*dutycycle = 30 min = 1800 s![](/graphics/er29jn21.208.gif)*X*NMHC = 53.8 µmol/mol

(m) *Median.* Determine median, *M*, as described in this paragraph (m). Arrange the data points in the data set in increasing order where the smallest value is ranked 1, the second-smallest value is ranked 2, etc.

(1) For even numbers of data points:

(i) Determine the rank of the data point whose value is used to determine the median as follows:

![](/graphics/er22ap24.222.gif)Eq. 1065.602-18Where:*i* = an indexing variable that represents the rank of the data point whose value is used to determine the median.*N* = the number of data points in the set.*Example:**N* = 4*y*1 = 41.515*y*2 = 41.780*y*3 = 41.861*y*4 = 41.902*i* = 2*i* = 2

(ii) Determine the median as the average of the data point *i* and the data point *i* + 1 as follows:

![](/graphics/er17jn24.006.gif)

*Example:*

![](/graphics/er17jn24.007.gif)Eq. 1065.602-19

(2) For odd numbers of data points, determine the rank of the data point whose value is the median and the corresponding median value as follows:

![](/graphics/er22ap24.225.gif)Eq. 1065.602-20Where:*i* = an indexing variable that represents the rank of the data point whose value is the median.*N* = the number of data points in the set.

*Example:*

*N* = 3*y*1 = 41.515*y*2 = 41.780*y*3 = 41.861![](/graphics/er22ap24.226.gif)[86 FR 34548, June 29, 2021; 87 FR 64865, Oct. 26, 2022; 89 FR 29807, Apr. 22, 2024]