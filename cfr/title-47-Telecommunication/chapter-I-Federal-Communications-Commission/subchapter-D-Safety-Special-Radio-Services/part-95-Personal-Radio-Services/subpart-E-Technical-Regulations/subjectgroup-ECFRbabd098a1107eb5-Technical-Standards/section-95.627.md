##### § 95.627 MedRadio transmitters in the 401-406 MHz band. #####

The following provisions apply only to MedRadio transmitters operating in the 401-406 MHz band.

(a) *Frequency monitoring.* Except as provided in (b) of this section, all MedRadio programmer/control transmitters operating in the 401-406 MHz band must operate under the control of a monitoring system that incorporates a mechanism for monitoring the channel or channels that the MedRadio system devices intend to occupy. The monitoring system antenna shall be the antenna normally used by the programmer/control transmitter for a communications session. Before the monitoring system of a MedRadio programmer/control transmitter initiates a MedRadio communications session, the following access criteria must be met:

(1) The monitoring system bandwidth measured at its 20 dB down points must be equal to or greater than the emission bandwidth of the intended transmission.

(2) Within 5 seconds prior to initiating a communications session, circuitry associated with a MedRadio programmer/control transmitter must monitor the channel or channels the system devices intend to occupy for a minimum of 10 milliseconds per channel.

(3) Based on use of an isotropic monitoring system antenna, the monitoring threshold power level must not be more than 10logB(Hz) −150 (dBm/Hz) + G(dBi), where B is the emission bandwidth of the MedRadio communications session transmitter having the widest emission and G is the MedRadio programmer/control transmitter monitoring system antenna gain relative to an isotropic antenna. For purposes of showing compliance with the above provision, the above calculated threshold power level must be increased or decreased by an amount equal to the monitoring system antenna gain above or below the gain of an isotropic antenna, respectively.

(4) If no signal in a MedRadio channel above the monitoring threshold power level is detected, the MedRadio programmer/control transmitter may initiate a MedRadio-communications session involving transmissions to and from a medical implant or medical body-worn device on that channel. The MedRadio communications session may continue as long as any silent period between consecutive data transmission bursts does not exceed 5 seconds. If a channel meeting the criteria in paragraph (a)(3) of this section is unavailable, MedRadio transmitters that are capable of operating on multiple channels may transmit on the alternate channel accessible by the device with the lowest monitored ambient power level. Except as provided in paragraph (b) of this section, MedRadio transmitters that operate on a single channel and thus do not have the capability of operating on alternate channels may not transmit unless no signal on the single channel of operation exceeds the monitoring threshold power level.

(5) When a channel is selected prior to a MedRadio communications session, it is permissible to select an alternate channel for use if communications are interrupted, provided that the alternate channel selected is the next best choice using the above criteria. The alternate channel may be accessed in the event a communications session is interrupted by interference. The following criteria must be met:

(i) Before transmitting on the alternate channel, the channel must be monitored for a period of at least 10 milliseconds.

(ii) The detected power level during this 10 millisecond or greater monitoring period must be no higher than 6dB above the power level detected when the channel was chosen as the alternate channel.

(iii) In the event that this alternate channel provision is not used by the MedRadio system or if the criteria in paragraphs (a)(5)(i) and (ii) are not met, a channel must be selected using the access criteria specified in paragraphs (a)(1) through (a)(4) of this section.

(6) As used in this section, the following definitions apply:

(i) *Emission bandwidth* - Measured as the width of the signal between the points on either side of carrier center frequency that are 20 dB down relative to the maximum level of the modulated carrier. Compliance will be determined using instrumentation employing a peak detector function and a resolution bandwidth approximately equal to 1% of the emission bandwidth of the device under test.

(ii) *MedRadio channel* - Any continuous segment of spectrum in the MedRadio band that is equal to the emission bandwidth of the device with the largest bandwidth that is to participate in a MedRadio communications session.

Note to paragraph (a)(6)(ii):

The rules do not specify a channeling scheme for use by MedRadio systems.

(iii) *MedRadio communications session* - A collection of transmissions, that may or may not be continuous, between MedRadio system devices.

(b) *Exceptions to frequency monitoring criteria.* MedRadio devices or communications sessions that meet any one of the following criteria are not required to use the access criteria set forth in paragraph (a) of this section:

(1) MedRadio communications sessions initiated by a medical implant event.

(2) MedRadio devices operating in either the 401-401.85 MHz or 405-406 MHz bands, provided that the transmit power is not greater than 250 nanowatts EIRP and the duty cycle for such transmissions does not exceed 0.1%, based on the total transmission time during a one-hour interval, and a maximum of 100 transmissions per hour.

(3) MedRadio devices operating in the 401.85-402 MHz band, provided that the transmit power is not greater than 25 microwatts EIRP and the duty cycle for such transmissions does not exceed 0.1%, based on the total transmission time during a one hour interval, and a maximum of 100 transmissions per hour.

(4) MedRadio devices operating with a total emission bandwidth not exceeding 300 kHz centered at 403.65 MHz, provided that the transmit power is not greater than 100 nanowatts EIRP and the duty cycle for such transmissions does not exceed 0.01%, based on the total transmission time during a one-hour interval, and a maximum of 10 transmissions per hour.

(c) *Operating frequency.* MedRadio stations authorized under this part may operate on frequencies in the 401-406 MHz band as follows provided that the out-of-band emissions are attenuated in accordance with § 95.635:

(1) MedRadio stations associated with medical implant devices, which incorporate a frequency monitoring system as set forth in paragraph (a) of this section, may operate on any of the frequencies in the 401-406 MHz band.

(2) MedRadio stations associated with medical implant devices, which do not incorporate a frequency monitoring system as set forth in paragraph (a) of this section, may operate on any frequency in 401-402 MHz or 405-406 MHz bands, or at 403.65 MHz in the 402-405 MHz band.

(3) MedRadio stations associated with medical body-worn devices, regardless of whether a frequency monitoring system as set forth in paragraph (a) of this section is employed, may operate on any of the frequencies in the 401-402 MHz or 405-406 MHz bands.

(4) MedRadio stations that are used externally to evaluate the efficacy of a more permanent medical implant device, regardless of whether a frequency monitoring system as set forth in paragraph (a) of this section is employed, may operate on any of the frequencies in the 402-405 MHz band, provided that:

(i) Such external body-worn operation is limited solely to evaluating with a patient the efficacy of a fully implanted permanent medical device that is intended to replace the temporary body-worn device;

(ii) RF transmissions from the external device must cease following the patient evaluation period, which may not exceed 30 days, except where a health care practitioner determines that additional time is necessary due to unforeseen circumstances;

(iii) The maximum output power of the temporary body-worn device shall not exceed 200 nW EIRP; and

(iv) The temporary body-worn device must comply fully with all other MedRadio rules applicable to medical implant device operation in the 402-405 MHz band.

(d) *Authorized bandwidth.* The authorized bandwidth of the emission from a MedRadio station operating between 402-405 MHz shall not exceed 300 kHz, and no communications session involving MedRadio stations shall use more than a total of 300 kHz of bandwidth during such a session. The authorized bandwidth of the emission from a MedRadio station operating between 401-401.85 MHz or 405-406 MHz shall not exceed 100 kHz, and no communications session involving MedRadio stations shall use more than a total of 100 kHz of bandwidth during such a session. The authorized bandwidth of the emission from a MedRadio station operating between 401.85-402 MHz shall not exceed 150 kHz, and no communications session involving MedRadio stations shall use more than a total of 150 kHz of bandwidth during such a session.

Note to paragraph (d):

This provision does not preclude full duplex or half duplex communications provided that the total amount of bandwidth utilized by all of the MedRadio channels employed in such a MedRadio communications session does not exceed 300 kHz in the 402-405 MHz band, or 100 kHz in the 401-402 MHz and 405-406 MHz bands.

(e) *Frequency stability.* Each transmitter in the MedRadio service must maintain a frequency stability of ±100 ppm of the operating frequency over the range:

(1) 25 °C to 45 °C in the case of medical implant transmitters; and

(2) 0 °C to 55 °C in the case of MedRadio programmer/control transmitters and MedRadio body-worn transmitters.

(f) *Shared access.* The provisions of this section shall not be used to extend the range of spectrum occupied over space or time for the purpose of denying fair access to spectrum for other MedRadio systems.

(g) *Measurement procedures.* (1) MedRadio transmitters shall be tested for frequency stability, radiated emissions and EIRP limit compliance in accordance with paragraphs (g)(2) and (g)(3) of this section.

(3) Radiated emissions and EIRP measurements may be determined by measuring the radiated field from the equipment under test at 3 meters and calculating the EIRP. The equivalent radiated field strength at 3 meters for 25 microwatts, 250 nanowatts, and 100 nanowatts EIRP is 18.2, 1.8, or 1.2 mV/meter, respectively, when measured on an open area test site; or 9.1, 0.9, or 0.6 mV/meter, respectively, when measured on a test site equivalent to free space such as a fully anechoic test chamber. Compliance with the maximum transmitter power requirements set forth in § 95.639(f) shall be based on measurements using a peak detector function and measured over an interval of time when transmission is continuous and at its maximum power level. In lieu of using a peak detector function, measurement procedures that have been found to be acceptable to the Commission in accordance with § 2.947 of this chapter may be used to demonstrate compliance.

(2) Frequency stability testing shall be performed over the temperature range set forth in (e) of this section.

(3) Radiated emissions and EIRP measurements may be determined by measuring the radiated field from the equipment under test at 3 meters and calculating the EIRP. The equivalent radiated field strength at 3 meters for 25 microwatts, 250 nanowatts, and 100 nanowatts EIRP is 18.2, 1.8, or 1.2 mV/meter, respectively, when measured on an open area test site; or 9.1, 0.9, or 0.6 mV/meter, respectively, when measured on a test site equivalent to free space such as a fully anechoic test chamber. Compliance with the maximum transmitter power requirements set forth in § 95.639(f) shall be based on measurements using a peak detector function and measured over an interval of time when transmission is continuous and at its maximum power level. In lieu of using a peak detector function, measurement procedures that have been found to be acceptable to the Commission in accordance with § 2.947 of this chapter may be used to demonstrate compliance.

(i) For a transmitter intended to be implanted in a human body, radiated emissions and EIRP measurements for transmissions by stations authorized under this section may be made in accordance with a Commission-approved human body simulator and test technique. A formula for a suitable tissue substitute material is defined in OET Bulletin 65 Supplement C (01-01).

[74 FR 22705, May 14, 2009, as amended at 75 FR 52477, Aug. 26, 2010. Redesignated and amended at 77 FR 4268, Jan. 27, 2012]