##### § 86.519-90 Constant volume sampler calibration. #####

(a) The CVS (Constant Volume Sampler) is calibrated using an accurate flowmeter and restrictor valve. Measurements of various parameters are made and related to flow through the unit. Procedures used by EPA for both PDP (Positive Displacement Pump) and CFV (Critical Flow Venturi) are outlined below. Other procedures yielding equivalent results may be used if approved in advance by the Administrator. After the calibration curve has been obtained, verification of the entire system can be performed by injecting a known mass of gas into the system and comparing the mass indicated by the system to the true mass injected. An indicated error does not necessarily mean that the calibration is wrong, since other factors can influence the accuracy of the system, e.g., analyzer calibration. A verification procedure is found in paragraph (d) of this section.

(b) *PDP calibration.* (1) The following calibration procedures outlines the equipment, the test configuration, and the various parameters which must be measured to establish the flow rate of the constant volume sampler pump. All the parameters related to the pump are simultaneously measured with the parameters related to a flowmeter which is connected in series with the pump. The calculated flow rate (at pump inlet absolute pressure and temperature) can then be plotted versus a correlation function which is the value of a specific combination of pump parameters. The linear equation which relates the pump flow and the correlation function is then determined. In the event that a CVS has a multiple speed drive, a calibration for each range must be performed.

(2) This calibration procedure is based on the measurement of the absolute values of the pump and flowmeter parameters that relate the flow rate at each point. Three conditions must be maintained to assure the accuracy and integrity of the calibration curve. First, the pump pressures should be measured at taps on the pump rather than at the external piping on the pump inlet and outlet. Pressure taps that are mounted at the top center and bottom center of the pump drive headplate are exposed to the actual pump cavity pressures, and therefore reflect the absolute pressure differentials. Secondly, temperature stability must be maintained during the calibration. The laminar flowmeter is sensitive to inlet temperature oscillations which cause the data points to be scattered. Gradual changes (±1 °C (±1.8 °F)) in temperature are acceptable as long as they occur over a period of several minutes. Finally, all connections between the flowmeter and the CVS pump must be absolutely void of any leakage.

(3) During an exhaust emission test the measurement of these same pump parameters enables the user to calculate the flow rate from the calibration equation.

(4) Connect a system as shown in Figure F78-5. Although particular types of equipment are shown, other configurations that yield equivalent results may be used if approved in advance by the Administrator. For the system indicated, the following data with given accuracy are required:

|                   Parameter                   |   Symbol    |          Units          |              Tolerances               |
|-----------------------------------------------|-------------|-------------------------|---------------------------------------|
|         Barometric pressure corrected         |P<sub>B</sub>|      kPa (in. Hg)       |       ±0.03 kPa (±0.01 in. Hg)        |
|              Ambient temperature              |T<sub>A</sub>|         °C (°F)         |          ±0.3 °C (±0.54 °F)           |
|           Air Temperature into LFE            |     ETI     |         °C (°F)         |          ±0.15 °C (±0.27 °F)          |
|      Pressure depression upstream of LFE      |     EPI     |kPa (in. H<sub>2</sub> O)| ±0.01 kPa (±0.05 in. H<sub>2</sub> O) |
|      Pressure drop across the LFE matrix      |     EDP     |kPa (in. H<sub>2</sub> O)|±0.001 kPa (±0.005 in. H<sub>2</sub> O)|
|       Air temperature at CVS pump inlet       |     PTI     |         °C (°F)         |          ±0.25 °C (±0.45 °F)          |
|     Pressure depression at CVS pump inlet     |     PPI     |     kPa (in. Fluid)     |     ±0.021 kPa (±0.046 in. Fluid)     |
|Specific gravity of manometer fluid (1.75 oil).|    Sp Gr    |                         |                                       |
|       Pressure head at CVS pump outlet        |     PPO     |     kPa (in. Fluid)     |     ±0.21 kPa (±0.046 in. Fluid)      |
| Air temperature at CVS pump outlet (optional) |     PTO     |         °C (°F)         |          ±0.25 °C (±0.45 °F)          |
|      Pump revolutions during test period      |      N      |          Revs           |                ±l Rev.                |
|         Elapsed time for test period          |      t      |          sec.           |              ±0.05 sec.               |

(5) After the system has been connected as shown in Figure F78-6, set the variable restrictor in the wide open position and run the CVS pump for twenty minutes. Record the calibration data.

(6) Reset the restrictor valve to a more restricted condition in an increment of pump inlet depression (about 1.0 kPa (4 in. H2O)) that will yield a minimum of six data points for the total calibration. Allow the system to stabilize for 3 minutes and repeat the data acquisition.

(7) Data analysis:

(i) The air flow rate, Qs, at each test point is calculated from the flowmeter data using the manufacturers' prescribed method.

(ii) The air flow rate is then converted to pump flow, Vo in m3 per revolution at absolute pump inlet temperature and pressure.

Vo = (Qs/n) × (Tp/293) × (101.3/Pp)Where:

(A) Vo = Pump flow, m3/rev (ft3/rev) at Tp, Pp.

(B) Qs = Meter air flow rate in standard cubic meters per minute; standard conditions are 20 °C, 101.3 kPa (68 °F, 29.92 in. Hg).

(C) n = Pump speed in revolutions per minute.

(D)(*1*) Tp = Pump inlet temperature, (°K) = PTI + 273.

(*2*) *For English units,* Tp = PTI + 460.

(E)(*1*) Pp = Absolute pump inlet pressure, kPa (in. Hg) = PB − PPI.

(*2*) *For English units,* Pp = PB − PPI(SP.GR./13.57).

Where:

(F) PB = barometric pressure, kPa (in. Hg.).

(G) PPI = Pump inlet depression, kPa (in. fluid).

(H) SP.GR. = Specific gravity of manometer fluid relative to water.

(iii) The correlation function at each test point is then calculated from the calibration data:

![](/graphics/er06oc93.105.gif)Where:

(A) Xo = correlation function.

(B) Δ Pp = The pressure differential from pump inlet to pump outlet, kPa (in. Hg) = Pe − Pp.

(C)(*1*) Pe = Absolute pump outlet pressure, kPa (in. Hg) = PB + PPO.

(*2*) *For English units,* Pe = PB + PPO(SP.GR./13.57).

Where:

(D) PPO = Pressure head at pump outlet, kPa (in. fluid).

(iv) A linear least squares fit is performed to generate the calibration equations which have the forms:

Vo = Do − M(Xo)

n = A − B(Δ Pp)

D0′ M, A, and B are the slope-intercept constants, describing the lines.

(8) A CVS system that has multiple speeds shall be calibrated on each speed used. The calibration curves generated for the ranges will be approximately parallel and the intercept values, D0′ will increase as the pump flow range decreases.

(9) If the calibration has been performed carefully, the calculated values from the equation will be within ±0.50 percent of the measured value of Vo. Values of M will vary from one pump to another, but values of Do for pumps of the same make, model, and range should agree within ±3 percent of each other. Particulate influx from use will cause the pump slip to decrease as reflected by lower values for M. Calibrations should be performed at pump startup and after major maintenance to assure the stability of the pump slip rate. Analysis of mass injection data will also reflect pump slip stability.

(c) *CFV calibration.* (1) Calibration of the Critical Flow Venturi (CFV) is based upon the flow equation for a critical venturi. Gas flow is a function of inlet pressure and temperature:

![](/graphics/er06oc93.106.gif)Where:

(i) Qs = Flow.

(ii) Kv = Calibration coefficient.

(iii) P = Absolute pressure.

(iv) T = Absolute temperature.

The calibration procedure described below establishes the value of the calibration coefficient at the measured values of pressure, temperature and air flow.

(2) The manufacturer's recommended procedure shall be followed for calibrating electronic portions of the CFV.

(3) Measurements necessary for flow calibration are as follows:

|                  Parameter                   |   Symbol    |                Units                 |              Tolerances               |
|----------------------------------------------|-------------|--------------------------------------|---------------------------------------|
|       Barometric pressure (corrected)        |P<sub>B</sub>|             kPa (in. Hg)             |       ±0.03 kPa (±0.01 in. Hg)        |
|          Air temperature, flowmeter          |     ETI     |               °C (°F)                |          ±0.15 °C (±0.27 °F)          |
|     Pressure depression upstream of LFE      |     EPI     |      kPa (in. H<sub>2</sub> O)       | ±0.01kPa (±0.05 in. H<sub>2</sub> O)  |
|       Pressure drop across LFE matrix        |     EDP     |      kPa (in. H<sub>2</sub> O)       |±0.001 kPa (±0.005 in. H<sub>2</sub> O)|
|                   Air flow                   |Q<sub>s</sub>|m<sup>3</sup>/min (ft<sup>3</sup>/min)|                 ±0.5%                 |
|             CFV inlet depression             |     PPI     |           kPa (in. fluid)            |      ±0.02 kPa (±0.05 in. fluid)      |
|         Temperature at venturi inlet         |T<sub>v</sub>|               °C (°F)                |          ±0.25 °C (±0.45 °F)          |
|Specific gravity of manometer fluid (1.75 oil)|    Sp Gr    |                . . .                 |                 . . .                 |

(4) Set up equipment as shown in Figure F78-6 and check for leaks. Any leaks between the flow measuring device and the critical flow venturi will seriously affect the accuracy of the calibration.

(5) Set the variable flow restrictor to the open position, start the blower and allow the system to stabilize. Record data from all instruments.

(6) Vary the flow restrictor and make at least 8 readings across the critical flow range of the venturi.

(7) *Data analysis.* The data recorded during the calibration are to be used in the following calculations:

(i) The air flow rate, Qs, at each test point is calculated from the flowmeter data using the manufacturer's prescribed method.

(ii) Calculate values of the calibration coefficient for each test point:

![](/graphics/er06oc93.107.gif)Where:

(A) Qs = Flow rate in m3/minute, standard conditions are 20 °C, 101.3 kPa (68 °F, 29.92 in. Hg)

(B) Tv = Temperature at venturi inlet, °K(°R).

(C)(*1*) Pv = Pressure at venturi inlet, kPa (mm Hg) = PB-PPI.

(*2*) *For English units,* Pv = PB − PPI (SP.GR./13.57).

Where:

(D) PPI = Venturi inlet pressure depression, kPa (in. fluid).

(E) SP.GR. = Specific gravity of manometer fluid, relative to water.

(iii) Plot Kv as a function of venturi inlet depression. For sonic flow, Kv will have a relatively constant value. As pressure decreases (vacuum increases), the venturi becomes unchoked and Kv decreases (is no longer constant). See Figure F78-7.

(iv) For a minimum of 8 points in the critical region, calculate an average Kv and the standard deviation.

(v) If the standard deviation exceeds 0.3 percent of the average Kv, take corrective action.

(d) *CVS system verification.* The following “gravimetric” technique can be used to verify that the CVS and analytical instruments can accurately measure a mass of gas that has been injected into the system. If the CVS and analytical system will be used only in the testing of gasoline-fueled vehicles, the system verification may be performed using either propane or carbon monoxide. If the CVS and analytical system will be used with methanol-fueled vehicles as well as gasoline-fueled vehicles, system verification performance check must include a methanol check in addition to either the propane or carbon monoxide check. (Verification can also be accomplished by constant flow metering using critical flow orifice devices.)

(1) Obtain a small cylinder that has been charged with pure propane or carbon monoxide gas (CAUTION—carbon monoxide is poisonous).

(2) Determine a reference cylinder weight to the nearest 0.01 grams.

(3) Operate the CVS in the normal manner and release a quantity of pure propane or carbon monoxide into the system during the sampling period (approximately 5 minutes).

(4) Following completion of step (3) above (if methanol injection is required), continue to operate the CVS in the normal manner and release a known quantity of pure methanol (in gaseous form) into the system during the sampling period (approximately 5 minutes). This step does not need to be performed with each verification, provided that it is performed at least twice annually.

(5) The calculations of § 86.544 are performed in the normal way except in the case of propane. The density of propane (0.6109 kg/m3/carbon atom (17.30 g/ft3/carbon atom)) is used in place of the density of exhaust hydrocarbons. In the case of carbon monoxide, the density of 1.164 kg/m3 (32.97 g/ft3) is used. In the case of methanol, the density of 1.332 kg/m3 (37.71 g/ft3) is used.

(6) The gravimetric mass is subtracted from the CVS measured mass and then divided by the gravimetric mass to determine the percent accuracy of the system.

(7) The cause for any discrepancy greater than ±2 percent must be found and corrected. The Administrator, upon request, may waive the requirement to comply with ±2 percent methanol recovery tolerance, and instead require compliance with a higher tolerance (not to exceed ±6 percent), provided that:

(i) The Administrator determines that compliance with the specified tolerance is not practically feasible; and

(ii) The manufacturer makes information available to the Administrator which indicates that the calibration tests and their results are consistent with good laboratory practice, and that the results are consistent with the results of calibration testing conducted by the Administrator.

[54 FR 14546, Apr. 11, 1989, as amended at 60 FR 34355, June 30, 1995]