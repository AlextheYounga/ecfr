##### § 85.2222 Onboard diagnostic test procedures. #####

The test sequence for the OBD inspection shall consist of the following steps:

(a) The OBD inspection shall be conducted with the key-on/engine running, with the exception of inspecting for MIL illumination as required in paragraph (d)(4) of this section, during which the inspection shall be conducted with the key-on/engine off.

(b) The inspector shall locate the vehicle connector and plug the test system into the connector.

(c) The test system shall send a Mode $01, PID $01 request in accordance with 40 CFR 86.1806 to determine the OBD evaluation status. The test system shall determine what monitors are supported by the OBD system, and perform the readiness evaluation for applicable monitors in accordance with the requirements and specifications in 40 CFR 86.1806.

(1) Coincident with the beginning of mandatory testing, repair, and retesting based upon the OBD test, if the readiness evaluation indicates that any onboard tests are not complete, the customer shall be instructed to return after the vehicle has been run under conditions that allow completion of all applicable onboard tests. If the readiness evaluation again indicates that any onboard test is not complete, the vehicle shall be failed.

(2) An exception to paragraph (c)(1) of this section is allowed for MY 1996 to MY 2000 vehicles, inclusive, with two or fewer unset readiness monitors, and for MY 2001 and newer vehicles with no more than one unset readiness monitor. Vehicles from those model years which would otherwise pass the OBD inspection, but for the unset readiness code in question, may be issued a passing certificate without being required to operate the vehicle in such a way as to activate those particular monitors. Vehicles from those model years with an unset readiness code that also have a DTC stored resulting in an illuminated MIL must be failed, though setting the unset readiness flag in question shall not be a prerequisite for passing the retest.

(d) The test system shall evaluate the MIL status bit and record status information in the vehicle test record.

(1) If the MIL status bit indicates that the MIL has been commanded to be illuminated, the test system shall send a Mode $03 request in accordance with 40 CFR 86.1806 to determine the stored DTCs. The system shall repeat this cycle until the number of codes reported equals the number expected based on the Mode $01 response. All DTCs resulting in MIL illumination shall be recorded in the vehicle test record and the vehicle shall fail the OBD inspection.

(2) If the MIL bit is not commanded to be illuminated the vehicle shall pass the OBD inspection, even if DTCs are present.

(3) If the MIL bit is commanded to be illuminated, the inspector shall visually inspect the MIL to determine if it is illuminated. If the MIL is commanded to be illuminated but is not, the vehicle shall fail the OBD inspection.

(4) If the MIL does not illuminate at all when the vehicle is in the key-on/engine-off condition, the vehicle shall fail the OBD inspection, even if no DTCs are present and the MIL has not been commanded on.