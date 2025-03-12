##### § 95.2559 MedRadio channel access requirements. #####

To reduce interference and make the most effective use of the MedRadio frequency bands, MedRadio transmitter types must be designed to operate in accordance with the rules in this section.

(a) *Frequency monitoring in the 401-406 MHz band.* Except as provided in paragraph (b) of this section, all MedRadio programmer/control transmitters operating in the 401-406 MHz band must operate under the control of a monitoring system that incorporates a mechanism for monitoring the channel or channels that the MedRadio system devices intend to occupy. The monitoring system antenna shall be the antenna normally used by the programmer/control transmitter for a MedRadio communications session. Before the monitoring system of a programmer/control transmitter initiates a MedRadio communications session, the following access criteria must be met:

(1) The monitoring system bandwidth, measured at its 20 dB down points, must be equal to or greater than the MedRadio emission bandwidth of the intended transmission.

(2) Within 5 seconds prior to initiating a MedRadio communications session, circuitry associated with a MedRadio programmer/control transmitter must monitor the channel or channels the system devices intend to occupy for a minimum of 10 milliseconds per channel.

(3) The monitoring threshold power level, PMT, in dBm, is calculated using the following formula.

PMT = 10 log B−150 (dBm/Hz) + GWhere:

(i) B is the MedRadio emission bandwidth in Hertz of the MedRadio communications session transmitter having the widest emission; and,

(ii) G is the MedRadio programmer/control transmitter monitoring system antenna gain, in decibels, relative to the gain of an isotropic antenna (dBi).

(4) For the purposes of showing compliance with the above provisions, the above calculated threshold power level must be increased or decreased by an amount equal to the monitoring system antenna gain above or below the gain of an isotropic antenna, respectively.

(5) If no signal above the monitoring threshold power level is detected in a MedRadio channel, the MedRadio programmer/control transmitter may initiate on that channel a MedRadio communications session involving transmissions to and from a medical implant or medical body-worn device. The MedRadio communications session may continue as long as any silent period between consecutive data transmission bursts does not exceed 5 seconds. If no channel meeting the requirements in paragraphs (a)(3) and (4) of this section is available, MedRadio transmitters that are capable of operating on multiple channels may transmit on the alternate channel accessible by the device with the lowest monitored ambient power level.

(6) When a channel is selected prior to a MedRadio communications session, it is permissible to select an alternate authorized channel for use if communications are interrupted, provided that the alternate channel selected is the next best choice using the above criteria. The alternate channel may be accessed in the event a communications session is interrupted by interference. The following criteria must be met:

(i) Before transmitting on the alternate channel, the channel must be monitored for a period of at least 10 milliseconds.

(ii) The detected power level during this 10 millisecond or greater monitoring period must be no higher than 6 dB above the power level detected when the channel was chosen as the alternate channel.

(iii) In the event that this alternate channel provision is not used by the MedRadio system, or if the criteria in paragraphs (a)(6)(i) and (ii) of this section are not met, any alternate authorized channel must be selected using the access criteria specified in paragraphs (a)(1) through (5) of this section.

(7) Except as provided in paragraph (b) of this section, MedRadio transmitters that operate on a single channel and thus do not have the capability of operating on alternate channels may not transmit unless no signal on the single channel of operation exceeds the monitoring threshold power level.

(b) *Exceptions to frequency monitoring in the 401-406 MHz band.* MedRadio devices or communications sessions that meet any one of the following criteria are not required to be operated in accordance with the access rules set forth in paragraph (a) of this section:

(1) MedRadio communications sessions that are initiated by a medical implant event.

(2) MedRadio devices operating in either the 401-401.85 MHz or 405-406 MHz bands, provided that the transmit power is not greater than 250 nanowatts EIRP and the duty cycle for such transmissions does not exceed 0.1%, based on the total transmission time during a one-hour interval, and a maximum of 100 transmissions per hour.

(3) MedRadio devices operating in the 401.85-402 MHz band, provided that the transmit power is not greater than 25 microwatts EIRP and the duty cycle for such transmissions does not exceed 0.1%, based on the total transmission time during a one-hour interval, and a maximum of 100 transmissions per hour.

(4) MedRadio devices operating with a total emission bandwidth not exceeding 300 kHz, centered at 403.65 MHz, provided that the transmit power is not greater than 100 nanowatts EIRP and the duty cycle for such transmissions does not exceed 0.01%, based on the total transmission time during a one-hour interval and a maximum of 10 transmissions per hour.

(c) *Shared access.* The provisions of this section shall not be used to extend the range of spectrum occupied over space or time for the purpose of denying fair access to spectrum for other MedRadio systems.

(d) *Frequency monitoring in the 413-419 MHz, 426-432 MHz, 438-444 MHz, and 451-457 MHz bands.* MedRadio programmer/control transmitters must incorporate a mechanism for monitoring the authorized bandwidth of the frequency band that the MedRadio transmitters intend to occupy. The monitoring system antenna shall be the same antenna used by the programmer/control transmitter for a communications session.

(1) The MedRadio programmer/control transmitter shall be capable of monitoring any occupied frequency band at least once every second and monitoring alternate frequency bands within two seconds prior to executing a change to an alternate frequency band.

(2) The MedRadio programmer/control transmitter shall move to another authorized frequency band within one second of detecting a persistent (*i.e.,* lasting more than 50 milliseconds) signal level greater than −60 dBm as received by a 0 dBi gain antenna in any 12.5 kHz bandwidth within the authorized bandwidth.

(3) The MedRadio programmer/control transmitter shall be capable of monitoring the authorized bandwidth of the occupied frequency band to determine whether either direction of the communications link is becoming degraded to the extent that communications is likely to be lost for more than 45 milliseconds. Upon making such a determination the MedRadio programmer/control transmitter shall move to another authorized frequency band.

(e) *System shutdown.* MedRadio transmitters shall incorporate a programmable means to implement a system shutdown process in the event of communication failure, on command from the MedRadio programmer/control transmitter, or when no authorized alternate frequency band is available. The shutdown process shall commence within 45 milliseconds after loss of the communication link or receipt of the shutdown command from the MedRadio programmer/control transmitter. This requirement does not apply to MedRadio operations in the 401-406 MHz band.

(f) *Requirements for MBAN Networks.* A MedRadio programmer/control transmitter and its associated medical body-worn transmitters shall not commence operating in, and shall automatically cease operating in, the 2360-2390 MHz band if the programmer/control transmitter does not receive, in accordance with the protocols specified by the manufacturer, a control message permitting such operation. Medical body-worn transmitters shall cease operating in 2360-2390 MHz if they lose communication with their associated programmer/control transmitter. Additionally, a MedRadio programmer/control transmitter and its associated medical body-worn transmitters operating in the 2360-2390 MHz band shall comply with a control message that notifies the devices to limit transmissions to segments of the 2360-2390 MHz band or to cease operation in the band.