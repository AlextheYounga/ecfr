##### § 86.119-90 CVS calibration. #####

The CVS is calibrated using an accurate flowmeter and restrictor valve. Measurements of various parameters are made and related to flow through the unit. Procedures used by EPA for both PDP and CFV are outlined below. Other procedures yielding equivalent results may be used if approved in advance by the Administrator. After the calibration curve has been obtained, verification of the entire system can be performed by injecting a known mass of gas into the system and comparing the mass indicated by the system to the true mass injected. An indicated error does not necessarily mean that the calibration is wrong, since other factors can influence the accuracy of the system, e.g., analyzer calibration. A verification procedure is found in paragraph (c) of this section.

(a) *PDP calibrations.* (1) The following calibration procedure outlines the equipment, the test configuration, and the various parameters which must be measured to establish the flow rate of the CVS pump. All the parameters related to the pump are simultaneously measured with the parameters related to a flowmeter which is connected in series with the pump. The calculated flow rate ft3/min (at pump inlet absolute pressure and temperature) can then be plotted versus a correlation function which is the value on a specific combination of pump parameters. The linear equation which relates the pump flow and the correlation function is then determined. In the event that a CVS has a multiple speed drive, a calibration for each range used must be performed.

(2) This calibration procedure is based on the measurement of the absolute values of the pump and flowmeter parameters that relate the flow rate at each point. Three conditions must be maintained to assure the accuracy and integrity of the calibration curve. First, the pump pressures should be measured at taps on the pump rather than at the external piping on the pump inlet and outlet. Pressure taps that are mounted at the top center and bottom center of the pump drive headplate are exposed to the actual pump cavity pressures, and therefore reflect the absolute pressure differentials. Secondly, temperature stability must be maintained during the calibration. The laminar flowmeter is sensitive to inlet temperature oscillations which cause the data points to be scattered. Gradual changes (±2 °F (1.1 °C)) in temperature are acceptable as long as they occur over a period of several minutes. Finally, all connections between the flowmeter and the CVS pump must be absolutely void of any leakage.

(3) During an exhaust emission test the measurement of these same pump parameters enables the user to calculate the flow rate from the calibration equation.

(4) Connect a system as shown in Figure B90-8. Although particular types of equipment are shown, other configurations that yield equivalent results may be used if approved in advance by the Administrator. For the system indicated, the following data with given accuracy are required:

|                  Parameter                   |   Symbol    |          Units          |              Tolerances               |
|----------------------------------------------|-------------|-------------------------|---------------------------------------|
|       Barometric pressure (corrected)        |P<sub>B</sub>|      in. Hg (kPa)       |       ±0.01 in. Hg (±0.034 kPa)       |
|             Ambient temperature              |T<sub>A</sub>|         °F(°C)          |          ±0.5 °F (±0.28 °C)           |
|           Air temperature into LFE           |     ETI     |         °F(°C)          |          ±0.25 °F (±0.14 °C)          |
|     Pressure depression upstream of LFE      |     EPI     |in. H<sub>2</sub> O (kPa)| ±0.05 in. H<sub>20</sub> (±0.012 kPa) |
|     Pressure drop across the LFE matrix      |     EDP     |in. H<sub>2</sub> O (kPa)|±0.005 in. H<sub>2</sub> O (±0.001 kPa)|
|      Air temperature at CVS pump inlet       |     PTI     |         °F(°C)          |           ±0.5 °F (±0.3 °C)           |
|    Pressure depression at CVS pump inlet     |     PPI     |     in. fluid (kPa)     |     ±0.05 in. fluid (±0.022 kPa)      |
|Specific gravity of manometer fluid (1.75 oil)|   Sp. Gr.   |                         |                                       |
|       Pressure head at CVS pump outlet       |     PPO     |     in. fluid (kPa)     |     ±0.05 in. fluid (±0.022 kPa)      |
|Air temperature at CVS pump outlet (optional) |     PTO     |         °F(°C)          |          ±0.5 °F (±0.28 °C)           |
|     Pump revolutions during test period      |      N      |          Revs           |                ±1 Rev.                |
|         Elapsed time for test period         |      t      |           sec           |              ±0.05 sec.               |

![](/graphics/er06oc93.157.gif)

(5) After the system has been connected as shown in Figure B90-8, set the variable restrictor in the wide open position and run the CVS pump for 20 minutes. Record the calibration data.

(6) Reset the restrictor valve to a more restricted condition in an increment of pump inlet depression (about 4 in. H2O (1.0 kPa) that will yield a minimum of six data points for the total calibration. Allow the system to stabilize for 3 minutes and repeat the data acquisition.

(7) Data analysis:

(i) The air flow rate, Qs, at each test point is calculated in standard cubic feet per minute from the flowmeter data using the manufacturer's prescribed method.

(ii) The air flow rate is then converted to pump flow, Vo, in cubic feet per revolution at absolute pump inlet temperature and pressure:

Vo = (Qs/n) × (Tp/528) × (29.92/Pp)Where:(A) Vo = Pump flow ft3/rev (m3/rev) at Tp, Pp.(B) Qs = Meter air flow rate in standard cubic feet per minute, standard conditions are 68 °F, 29.92 in. Hg (20 °C, 101.3 kPa).(C) n = Pump speed in revolutions per minute.(D)(*1*) Tp = Pump inlet temperature, °R(°K) = PTI + 460.(*2*) *For SI units,* Tp = PTI + 273.(E)(*l*) Pp = Absolute pump inlet pressure, in. Hg. (kPa) = PB − PPI (SP.GR./13.57).(*2*) *For SI units,* Pp = PB − PPI.Where:(F) PB = barometric pressure, in. Hg. (kPa).(G) PPI = Pump inlet depression, in. fluid (kPa).(H) SP.GR. = Specific gravity of manometer fluid relative to water.

(iii) The correlation function at each test point is then calculated from the calibration data:

![](/graphics/er06oc93.021.gif)Where:(A) Xo = correlation function.(B) Δ Pp = the pressure differential from pump inlet to pump outlet, in. Hg (kPa) = Pe − Pp.(C)(*1*) Pe = Absolute pump outlet pressure, in Hg, (kPa) = PB + PPO (SP.GR./13.57).(*2*) *For SI units,* Pe = PB + PPO.Where:(D) PPO = Pressure head at pump outlet, in. fluid (kPa).(iv) A linear least squares fit is performed to generate the calibration equations which have the forms:Vo = Do − M(Xo)n = A − B(Δ Pp)Do, M, A, and B are the slope-intercept constants describing lines.

(8) A CVS system that has multiple speeds should be calibrated on each speed used. The calibration curves generated for the ranges will be approximately parallel and the intercept values, Do, will increase as the pump flow range decreases.

(9) If the calibration has been performed carefully, the calculated values from the equation will be within ±0.50 percent of the measured value of Vo. Values of M will vary from one pump to another, but values of Do for pumps of the same make, model, and range should agree within ±3 percent of each other. Particulate influx from use will cause the pump slip to decrease as reflected by lower values for M. Calibrations should be performed at pump start-up and after major maintenance to assure the stability of the pump slip rate. Analysis of mass injection data will also reflect pump slip stability.

(b) *CFV calibration.* (1) Calibration of the CFV is based upon the flow equation for a critical venturi. Gas flow is a function of inlet pressure and temperature:

![](/graphics/er06oc93.022.gif)Where:(i) Qs = Flow.(ii) Kv = Calibration coefficient.(iii) P = Absolute pressure.(iv) T = Absolute temperature.The calibration procedure described below establishes the value of the calibration coefficient at measured values of pressure, temperature and air flow.

(2) The manufacturer's recommended procedure shall be followed for calibrating electronic portions of the CFV.

(3) Measurements necessary for flow calibration are as follows:

|                   Parameter                    |   Symbol    |                 Units                  |             Tolerances              |
|------------------------------------------------|-------------|----------------------------------------|-------------------------------------|
|        Barometric pressure (corrected)         |P<sub>b</sub>|            Inches Hg (kPa)             |       ±.01 in Hg (±.034 kPa)        |
|           Air temperature, flowmeter           |     ETI     |                °F (°C)                 |           ±25 °F (±14 °C)           |
|      Pressure depression upstream of LFE       |     EPI     |      Inches H<sub>2</sub> O (kPa)      | ±.05 in H<sub>2</sub> O (±.012 kPa) |
|        Pressure drop across LFE matrix         |     EDP     |      Inches H<sub>2</sub> O (kPa)      |±.005 in H<sub>2</sub> O (±.001 kPa) |
|                    Air flow                    |Q<sub>s</sub>|Ft<sup>3</sup>/min. (m<sup>3</sup>/min,)|               ±.5 pct               |
|              CFV inlet depression              |     PPI     |           Inches fluid (kPa)           |      ±.13 in fluid (±.055 kPa)      |
|              CFV outlet pressure               |     PPO     |            Inches Hg (kPa)             |±0.05 in. Hg (±0.17 kPa) <sup>1</sup>|
|          Temperature at venturi inlet          |T<sub>v</sub>|                °F (°C)                 |         ±0.5 °F (±0.28 °C)          |
| Specific gravity of manometer fluid (1.75 oil) |   Sp. Gr    |                                        |                                     |
|<sup>1</sup> Requirement begins August 20, 2001.|             |                                        |                                     |

(4) Set up equipment as shown in Figure B90-9 and check for leaks. Any leaks between the flow measuring device and the critical flow venturi will seriously affect the accuracy of the calibration.

![](/graphics/er06oc93.199.gif)

(5) Set the variable flow restrictor to the open position, start the blower, and allow the system to stabilize. Record data from all instruments.

(6) Vary the flow restrictor and make at least 8 readings across the critical flow range of the venturi.

(7) *Data analysis:* The data recorded during the calibration are to be used in the following calculations:

(i) The air flow rate, Qs, at each test point is calculated in standard cubic feet per minute from the flow meter data using the manufacturer's prescribed method.

(ii) Calculate values of the calibration coefficient for each test point:

![](/graphics/er06oc93.023.gif)Where:(A) Qs = Flow rate in standard cubic feet per minute, standard conditions are 68 °F 29.92 in. Hg (20 °C, 101.3 kPa).(B) Tv = Temperature at venturi inlet, °R(°K).(C)(*1*) Pv = Pressure at venturi inlet, mm Hg (kPa) = PB − PPI (SP.GR./13.57).(*2*) *For SI units,* Pv = PB − PPI.Where:(D) PPI = Venturi inlet pressure depression, in. fluid (kPa).(E) SP.GR. = Specific gravity of manometer fluid, relative to water.

(iii) Plot Kv as a function of venturi inlet pressure. For sonic flow Kv will have a relatively constant value. As pressure decreases (vacuum increases), the venturi becomes unchoked and Kv decreases. See Figure B90-10.

![](/graphics/er06oc93.200.gif)

(iv) For a minimum of 8 points in the critical region calculate an average Kv and the standard deviation.

(v) If the standard deviation exceeds 0.3 percent of the average Kv take corrective action.

(8) Calculation of a parameter for monitoring sonic flow in the CFV during exhaust emissions tests:

(i) *Option 1.* (A) CFV pressure ratio. Based upon the calibration data selected to meet the criteria for paragraphs (d)(7) (iv) and (v) of this section, in which Kv is constant, select the data values associated with the calibration point with the lowest absolute venturi inlet pressure. With this set of calibration data, calculated the following CFV pressure ratio limit, Prratio-lim:

![](/graphics/er18fe00.022.gif)Where: Pin-cal = Venturi inlet pressure (PPI in absolute pressure units), andPout-cal = Venturi outlet pressure (PPO in absolute pressure units), measured at the exit of the venturi diffuser outlet.

(B) The venturi pressure ratio (Prratio-i) during all emissions tests must be less than, or equal to, the calibration pressure ratio limit (Prratio-lim) derived from the CFV calibration data, such that:

![](/graphics/er18fe00.023.gif)Where: Pin-i and Pout-i are the venturi inlet and outlet pressures, in absolute pressure units, at each i-th interval during the emissions test.

(ii) *Option 2.* Other methods: With prior Administrator approval, any other method may be used that assure that the venturi operates at sonic conditions during emissions tests, provided the method is based upon sound engineering principles.

(c) *CVS System Verification.* The following “gravimetric” technique can be used to verify that the CVS and analytical instruments can accurately measure a mass of gas that has been injected into the system. If the CVS and analytical system will be used only in the testing of petroleum-fueled engines, the system verification may be performed using either propane or carbon monoxide. If the CVS and analytical system will be used with methanol-fueled vehicles as well as petroleum-fueled vehicles, system verification performance check must include a methanol check in addition to either the propane or carbon monoxide check. (Verification can also be accomplished by constant flow metering using critical flow orifice devices.)

(1) Obtain a small cylinder that has been charged with pure propane or carbon monoxide gas (CAUTION—carbon monoxide is poisonous).

(2) Determine a reference cylinder weight to the nearest 0.01 grams.

(3) Operate the CVS in the normal manner and release a quantity of pure propane or carbon monoxide into the system during the sampling period (approximately 5 minutes).

(4) Following completion of step (3) in this paragraph (c) (if methanol injection is required), continue to operate the CVS in the normal manner and release a known quantity of pure methanol (in gaseous form) into the system during the sampling period (approximately five minutes). This step does not need to be performed with each verification, provided that it is performed at least twice annually.

(5) The calculations of § 86.144 are performed in the normal way, except in the case of propane. The density of propane (17.30 g/ft3/carbon atom (0.6109 kg/m3/carbon atom)) is used in place of the density of exhaust hydrocarbons. In the case of carbon monoxide, the density of 32.97 g/ft3 (1.164 kg/m3) is used. In the case of methanol, the density of 37.71 g/ft3 (1.332 kg/m3) is used.

(6) The gravimetric mass is subtracted from the CVS measured mass and then divided by the gravimetric mass to determine the percent accuracy of the system.

(7) The cause for any discrepancy greater than ±2 percent must be found and corrected. (For 1991-1995 calendar years, discrepancies greater than ±2 percent are allowed for the methanol test, provided that they do not exceed ±8 percent for 1991 testing or ±6 percent for 1992-1995 testing.)

[54 FR 14518, Apr. 11, 1989, as amended at 60 FR 34344, June 30, 1995; 62 FR 47121, Sept. 5, 1997; 63 FR 24448, May 4, 1998; 65 FR 8278, Feb. 18, 2000]