##### § 91.227 Automatic Dependent Surveillance-Broadcast (ADS-B) Out equipment performance requirements. #####

(a) *Definitions.* For the purposes of this section:

*ADS-B Out* is a function of an aircraft's onboard avionics that periodically broadcasts the aircraft's state vector (3-dimensional position and 3-dimensional velocity) and other required information as described in this section.

*Navigation Accuracy Category for Position* (*NAC*P) specifies the accuracy of a reported aircraft's position.

*Navigation Accuracy Category for Velocity* (*NAC*V) specifies the accuracy of a reported aircraft's velocity.

*Navigation Integrity Category (NIC)* specifies an integrity containment radius around an aircraft's reported position.

*Position Source* refers to the equipment installed onboard an aircraft used to process and provide aircraft position (for example, latitude, longitude, and velocity) information.

*Source Integrity Level (SIL)* indicates the probability of the reported horizontal position exceeding the containment radius defined by the NIC on a per sample or per hour basis.

*System Design Assurance (SDA)* indicates the probability of an aircraft malfunction causing false or misleading information to be transmitted.

*Total latency* is the total time between when the position is measured and when the position is transmitted by the aircraft.

*Uncompensated latency* is the time for which the aircraft does not compensate for latency.

(b) *1090 MHz ES and UAT Broadcast Links and Power Requirements*—

(1) Aircraft operating in Class A airspace must have equipment installed that meets the antenna and power output requirements of Class A1S, A1, A2, A3, B1S, or B1 equipment as defined in TSO-C166b and Section 2 of RTCA DO-260B (as referenced in TSO-C166b), or TSO-C166c and Section 2 of RTCA DO-260C as modified by DO-260C—Change 1 (as referenced in TSO-C166c).

(2) Aircraft operating in airspace designated for ADS-B Out, but outside of Class A airspace, must have equipment installed that meets the antenna and output power requirements of either:

(i) Class A1S, A1, A2, A3, B1S, or B1 as defined in TSO-C166b and Section 2 of RTCA DO-260B (as referenced in TSO-C166b) or TSO-C166c and Section 2 of RTCA DO-260C as modified by DO-260C—Change 1 (as referenced in TSO-C166c); or

(ii) Class A1S, A1H, A2, A3, B1S, or B1 equipment as defined in TSO-C154c and Section 2 of RTCA DO-282B (as referenced in TSO-C154c), or TSO-C154d and Section 2 of RTCA DO-282C (as referenced in TSO-C154d).

(c) *ADS-B Out Performance Requirements for NAC*P,*NAC*V*, NIC, SDA*, *and SIL*—

(1) For aircraft broadcasting ADS-B Out as required under § 91.225 (a) and (b)—

(i) The aircraft's NACP must be less than 0.05 nautical miles;

(ii) The aircraft's NACV must be less than 10 meters per second;

(iii) The aircraft's NIC must be less than 0.2 nautical miles;

(iv) The aircraft's SDA must be less than or equal to 10−5 per flight hour; and

(v) The aircraft's SIL must be less than or equal to 10−7 per flight hour or per sample.

(2) Changes in NACP, NACV, SDA, and SIL must be broadcast within 10 seconds.

(3) Changes in NIC must be broadcast within 12 seconds.

(d) *Minimum Broadcast Message Element Set for ADS-B Out.* Each aircraft must broadcast the following information, as defined in TSO-C166b (including Section 2 of RTCA DO-260B, as referenced in TSO-C166b), TSO-C166c (including Section 2 of RTCA DO-260C as modified by DO-260C—Change 1, as referenced in TSO-C166c), TSO-C154c (including Section 2 of RTCA DO-282B, as referenced in TSO-C154c), or TSO-C154d (including Section 2 of RTCA DO-282C, as referenced in TSO-C154d). The pilot must enter information for message elements listed in paragraphs (d)(7) through (10) of this section during the appropriate phase of flight.

(1) The length and width of the aircraft;

(2) An indication of the aircraft's latitude and longitude;

(3) An indication of the aircraft's barometric pressure altitude;

(4) An indication of the aircraft's velocity;

(5) An indication if a collision avoidance system is installed and operating in a mode that can generate resolution advisory alerts;

(6) If an operable collision avoidance system is installed, an indication if a resolution advisory is in effect;

(7) An indication of the Mode A transponder code specified by ATC;

(8) An indication of the aircraft identification that is submitted on the flight plan or used for communicating with ATC, except when the pilot has not filed a flight plan, has not requested ATC services, and is using a TSO-C154c or TSO-C154d self-assigned temporary 24-bit address;

(9) An indication if the flightcrew has identified an emergency, radio communication failure, or unlawful interference;

(10) An indication of the aircraft's “IDENT” to ATC;

(11) An indication of the aircraft assigned ICAO 24-bit address, except when the pilot has not filed a flight plan, has not requested ATC services, and is using a TSO-C154c or TSO-C154d self-assigned temporary 24-bit address;

(12) An indication of the aircraft's emitter category;

(13) An indication of whether an ADS-B In capability is available;

(14) An indication of the aircraft's geometric altitude;

(15) An indication of the Navigation Accuracy Category for Position (NACP);

(16) An indication of the Navigation Accuracy Category for Velocity (NACV);

(17) An indication of the Navigation Integrity Category (NIC);

(18) An indication of the System Design Assurance (SDA); and

(19) An indication of the Source Integrity Level (SIL).

(e) *ADS-B Latency Requirements*—

(1) The aircraft must transmit its geometric position no later than 2.0 seconds from the time of measurement of the position to the time of transmission.

(2) Within the 2.0 total latency allocation, a maximum of 0.6 seconds can be uncompensated latency. The aircraft must compensate for any latency above 0.6 seconds up to the maximum 2.0 seconds total by extrapolating the geometric position to the time of message transmission.

(3) The aircraft must transmit its position and velocity at least once per second while airborne or while moving on the airport surface.

(4) The aircraft must transmit its position at least once every 5 seconds while stationary on the airport surface.

(f) *Equipment with an approved deviation.* Operators with equipment installed with an approved deviation under § 21.618 of this chapter also are in compliance with this section.

(g) *Incorporation by reference.* The standards required in this section are incorporated by reference with the approval of the Director of the Office of the Federal Register under 5 U.S.C. 552(a) and 1 CFR part 51. This incorporation by reference (IBR) material is available for inspection at the FAA and the National Archives and Records Administration (NARA). Contact the FAA at: Office of Rulemaking (ARM-1), 800 Independence Avenue SW, Washington, DC 20590 (telephone 202-267-9677). For information on the availability of this material at NARA, visit *www.archives.gov/federal-register/cfr/ibr-locations.html* or email *fr.inspection@nara.gov.* This material is also available from the following sources indicated in this paragraph (g).

(1) U.S. Department of Transportation, Subsequent Distribution Office, DOT Warehouse M30, Ardmore East Business Center, 3341 Q 75th Avenue, Landover, MD 20785; telephone (301) 322-5377; website: *www.faa.gov/aircraft/air\_cert/design\_approvals/tso/* (select the link “Search Technical Standard Orders”).

(i) TSO-C166b, Extended Squitter Automatic Dependent Surveillance-Broadcast (ADS-B) and Traffic Information Service-Broadcast (TIS-B) Equipment Operating on the Radio Frequency of 1090 Megahertz (MHz), December 2, 2009.

(ii) TSO-C166c, Extended Squitter Automatic Dependent Surveillance-Broadcast (ADS-B) and Traffic Information Service-Broadcast (TIS-B) Equipment Operating on the Radio Frequency of 1090 Megahertz (MHz), March 10, 2023.

(iii) TSO-C154c, Universal Access Transceiver (UAT) Automatic Dependent Surveillance-Broadcast (ADS-B) Equipment Operating on the Frequency of 978 MHz, December 2, 2009.

(iv) TSO-C154d, Universal Access Transceiver (UAT) Automatic Dependent Surveillance-Broadcast (ADS-B) Equipment Operating on the Radio Frequency of 978 Megahertz (MHz), March 10, 2023.

(2) RTCA, Inc., 1150 18th St. NW, Suite 910, Washington, DC 20036; telephone (202) 833-9339; website: *www.rtca.org/products.*

(i) RTCA DO-260B, Minimum Operational Performance Standards for 1090 MHz Extended Squitter Automatic Dependent Surveillance-Broadcast (ADS-B) and Traffic Information Services-Broadcast (TIS-B), Section 2, Equipment Performance Requirements and Test Procedures, December 2, 2009.

(ii) RTCA DO-260C, Minimum Operational Performance Standards for 1090 MHz Extended Squitter Automatic Dependent Surveillance-Broadcast (ADS-B) and Traffic Information Services-Broadcast (TIS-B), Section 2, Equipment Performance Requirements and Test Procedures, December 17, 2020.

(iii) RTCA DO-260C, Minimum Operational Performance Standards for 1090 MHz Extended Squitter Automatic Dependent Surveillance-Broadcast (ADS-B) and Traffic Information Services-Broadcast (TIS-B), Change 1, January 25, 2022.

(iv) RTCA DO-282B, Minimum Operational Performance Standards for Universal Access Transceiver (UAT) Automatic Dependent Surveillance-Broadcast (ADS-B), Section 2, Equipment Performance Requirements and Test Procedures, December 2, 2009.

(v) RTCA DO-282C, Minimum Operational Performance Standards (MOPS) for Universal Access Transceiver (UAT) Automatic Dependent Surveillance-Broadcast (ADS-B), Section 2, Equipment Performance Requirements and Test Procedures, June 23, 2022.

[Doc. No. FAA-2007-29305, 75 FR 30194, May 28, 2010; Amdt. 91-314-A, 75 FR 37712, June 30, 2010, as amended at Amdt. 91-316, 75 FR 37712, June 30, 2010; Docket No. FAA-2023-1836; Amdt. No. 91-371, 88 FR 71477, Oct. 17, 2023]