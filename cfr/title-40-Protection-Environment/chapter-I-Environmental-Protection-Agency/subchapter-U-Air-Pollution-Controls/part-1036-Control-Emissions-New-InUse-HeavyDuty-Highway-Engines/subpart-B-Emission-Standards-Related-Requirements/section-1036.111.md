##### § 1036.111 Inducements related to SCR. #####

Engines using SCR to control emissions depend on a constant supply of diesel exhaust fluid (DEF). This section describes how manufacturers must design their engines to derate power output to induce operators to take appropriate actions to ensure the SCR system is working properly. The requirements of this section apply equally for engines installed in heavy-duty vehicles at or below 14,000 lbs GVWR. The requirements of this section apply starting in model year 2027, though you may comply with the requirements of this section in earlier model years.

(a) *General provisions.* The following terms and general provisions apply under this section:

(1) As described in § 1036.110, this section relies on terms and requirements specified for OBD systems by California ARB in 13 CCR 1968.2 and 1971.1 (incorporated by reference, see § 1036.810).

(2) The provisions of this section apply differently based on an individual vehicle's speed history. A vehicle's speed category is based on the OBD system's recorded value for average speed for the preceding 30 hours of non-idle engine operation. The vehicle speed category applies at the point that the engine first detects an inducement triggering condition identified under paragraph (b) of this section and continues to apply until the inducement triggering condition is fully resolved as specified in paragraph (e) of this section. Non-idle engine operation includes all operating conditions except those that qualify as idle based on OBD system controls as specified in 13 CCR 1971.1(h)(5.4.10). Apply speed derates based on the following categories:

|                                            Vehicle category <sup>a</sup>                                             |Average speed  <br/>(mi/hr)|
|----------------------------------------------------------------------------------------------------------------------|---------------------------|
|                                                      Low-speed                                                       |        speed \<15.        |
|                                                     Medium-speed                                                     |     15 ≤ speed \<25.      |
|                                                      High-speed                                                      |        speed ≥25.         |
|<sup>a</sup> A vehicle is presumed to be a high-speed vehicle if it has not yet logged 30 hours of non-idle operation.|                           |

(3) Where engines derate power output as specified in this section, the derate must decrease vehicle speed by 1 mi/hr for every five minutes of engine operation until reaching the specified derate speed. This paragraph (a)(3) applies at the onset of an inducement, at any transition to a different step of inducement, and for any derate that recurs under paragraph (e)(3) of this section.

(b) *Inducement triggering conditions.* Create derate strategies that monitor for and trigger an inducement based on the following conditions:

(1) DEF supply falling to 2.5 percent of DEF tank capacity or a level corresponding to three hours of engine operation, based on available information on DEF consumption rates.

(2) DEF quality failing to meet your concentration specifications.

(3) Any signal indicating that a catalyst is missing.

(4) Open circuit faults related to the following: DEF tank level sensor, DEF pump, DEF quality sensor, SCR wiring harness, NOX sensors, DEF dosing valve, DEF tank heater, DEF tank temperature sensor, and aftertreatment control module.

(c) [Reserved]

(d) *Derate schedule.* Engines must follow the derate schedule described in this paragraph (d) if the engine detects an inducement triggering condition identified in paragraph (b) of this section. The derate takes the form of a maximum drive speed for the vehicle. This maximum drive speed decreases over time based on hours of non-idle engine operation without regard to engine starting.

(1) Apply speed-limiting derates according to the following schedule:

|                                                                                                                      High-speed vehicles                                                                                                                       |   Medium-speed vehicles   |              Low-speed vehicles              |                           |                                              |                           |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------|----------------------------------------------|---------------------------|----------------------------------------------|---------------------------|
|                                                                                                         Hours of  <br/>non-idle engine  <br/>operation                                                                                                         |Maximum speed  <br/>(mi/hr)|Hours of  <br/>non-idle engine  <br/>operation|Maximum speed  <br/>(mi/hr)|Hours of  <br/>non-idle engine  <br/>operation|Maximum speed  <br/>(mi/hr)|
|                                                                                                                               0                                                                                                                                |            65             |                      0                       |            55             |                      0                       |            45             |
|                                                                                                                               6                                                                                                                                |            60             |                      6                       |            50             |                      5                       |            40             |
|                                                                                                                               12                                                                                                                               |            55             |                      12                      |            45             |                      10                      |            35             |
|                                                                                                                               20                                                                                                                               |            50             |                      45                      |            40             |                      30                      |            25             |
|                                                                                                                               86                                                                                                                               |            45             |                      70                      |            35             |                                              |                           |
|                                                                                                                              119                                                                                                                               |            40             |                      90                      |            25             |                                              |                           |
|                                                                                                                              144                                                                                                                               |            35             |                                              |                           |                                              |                           |
|                                                                                                                              164                                                                                                                               |            25             |                                              |                           |                                              |                           |
|<sup>a</sup> Hours start counting when the engine detects an inducement triggering condition specified in paragraph (b) of this section. For DEF supply, you may program the engine to reset the timer to three hours when the engine detects an empty DEF tank.|                           |                                              |                           |                                              |                           |

(2) You may design and produce engines that will be installed in motorcoaches with an alternative derate schedule that starts with a 65 mi/hr derate when an inducement triggering condition is first detected, steps down to 50 mi/hr after 80 hours, and concludes with a final derate speed of 25 mi/hr after 180 hours of non-idle operation.

(e) *Deactivating derates.* Program the engine to deactivate derates as follows:

(1) Evaluate whether the detected inducement triggering condition continues to apply. Deactivate derates if the engine confirms that the detected inducement triggering condition is resolved.

(2) Allow a generic scan tool to deactivate inducement triggering codes while the vehicle is not in motion.

(3) Treat any detected inducement triggering condition that recurs within 40 hours of engine operation as the same detected inducement triggering condition, which would restart the derate at the same point in the derate schedule that the system last deactivated the derate.

[88 FR 4487, Jan. 24, 2023, as amended at 89 FR 29739, Apr. 22, 2024]