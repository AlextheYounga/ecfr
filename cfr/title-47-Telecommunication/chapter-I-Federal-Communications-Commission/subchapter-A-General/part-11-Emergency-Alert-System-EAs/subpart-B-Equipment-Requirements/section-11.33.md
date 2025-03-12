##### § 11.33 EAS Decoder. #####

Link to an amendment published at 83 FR 39620, August 10, 2018.

(a) An EAS Decoder must at a minimum be capable of providing the EAS monitoring functions described in § 11.52, decoding EAS messages formatted in accordance with the EAS Protocol described in § 11.31, and converting Common Alerting Protocol (CAP)-formatted EAS messages into EAS alert messages that comply with the EAS Protocol, in accordance with § 11.56(a)(2), with the exception that the CAP-related monitoring and conversion requirements set forth in §§ 11.52(d)(2) and 11.56(a)(2) can be satisfied via an Intermediary Device, as specified in § 11.56(b), provided that all other requirements set forth in this part are met. An EAS Decoder also must be capable of the following minimum specifications:

(1) *Inputs.* Decoders must have the capability to receive at least two audio inputs from EAS monitoring assignments, and at least one data input. The data input(s) may be used to monitor other communications modes such as Radio Broadcast Data System (RBDS), NWR, satellite, public switched telephone network, or any other source that uses the EAS protocol.

(2) *Valid codes.* There must be a means to determine if valid EAS header codes are received and to determine if preselected header codes are received.

(3) *Storage.* Decoders must provide the means to:

(i) Record and store, either internally or externally, at least two minutes of audio or text messages. A decoder manufactured without an internal means to record and store audio or text must be equipped with a means (such as an audio or digital jack connection) to couple to an external recording and storing device.

(ii) Store at least ten preselected event and originator header codes, in addition to the seven mandatory event/originator codes for tests and national activations, and store any preselected location codes for comparison with incoming header codes. A non-preselected header code that is manually transmitted must be stored for comparison with later incoming header codes. The header codes of the last ten received valid messages which still have valid time periods must be stored for comparison with the incoming valid header codes for later messages. These last received header codes will be deleted from storage as their valid time periods expire.

(4) *Display and logging.* For received alert messages formatted in both the EAS Protocol and Common Alerting Protocol, a visual message shall be developed from any valid header codes for tests and national activations and any preselected header codes received. The message shall at a minimum include the Originator, Event, Location, the valid time period of the message and the local time the message was transmitted. The message shall be in the primary language of the EAS Participant and be fully displayed on the decoder and readable in normal light and darkness. The visual message developed from received alert messages formatted in the Common Alerting Protocol must conform to the requirements in §§ 11.51(d), (g)(3), (h)(3), and (j)(2) of this part. All existing and new models of EAS decoders manufactured after August 1, 2003 must provide a means to permit the selective display and logging of EAS messages containing header codes for state and local EAS events. Effective May 16, 2002, analog radio and television broadcast stations, analog cable systems and wireless cable systems may upgrade their decoders on an optional basis to include a selective display and logging capability for EAS messages containing header codes for state and local events. EAS Participants that install or replace their decoders after February 1, 2004 must install decoders that provide a means to permit the selective display and logging of EAS messages containing header codes for state and local EAS events.

(5) *Indicators.* EAS decoders must have a distinct and separate aural or visible means to indicate when any of the following conditions occurs:

(i) Any valid EAS header codes are received as specified in § 11.33(a)(10).

(ii) Preprogrammed header codes, such as those selected in accordance with § 11.52(d)(2) are received.

(iii) A signal is present at each audio input that is specified in § 11.33(a)(1).

(6) *Program Data Retention.* The program data must be retained even with power removed.

(7) *Outputs.* Decoders shall have at least one data port where received valid EAS header codes and received preselected header codes are available, at least one audio port that is capable of monitoring each decoder audio input, and an internal speaker to enable personnel to hear audio from each input.

(8) *Decoder Programming.* Access to decoder programming shall be protected by a lock or other security measures and be configured so that authorized personnel can readily select and program the EAS Decoder with preselected Originator, Event and Location codes for either manual or automatic operation.

(9) *Reset.* There shall be a method to automatically or manually reset the decoder to the normal monitoring condition. Operators shall be able to select a time interval, not less than two minutes, in which the decoder would automatically reset if it received an EAS header code but not an end-of-message (EOM) code. Messages received with the EAN Event codes shall disable the reset function so that lengthy audio messages can be handled. The last message received with valid header codes shall be displayed as required by paragraph (a)(4) of this section before the decoder is reset.

(10) *Message Validity.* An EAS Decoder must provide error detection and validation of the header codes of each message to ascertain if the message is valid. Header code comparisons may be accomplished through the use of a bit-by-bit compare or any other error detection and validation protocol. A header code must only be considered valid when two of the three headers match exactly. Duplicate messages must not be relayed automatically.

(11) A header code with the EAN Event code specified in § 11.31(c) that is received through any of the audio or data inputs must override all other messages.

(b) Decoders shall be capable of operation within the tolerances specified in this section as well as those in § 11.32 (b), (c) and (d).

[59 FR 67092, Dec. 28, 1994, as amended at 60 FR 55999, Nov. 6, 1995; 67 FR 18510, Apr. 16, 2002; 70 FR 71033, Nov. 25, 2005; 77 FR 16703, Mar. 22, 2012]