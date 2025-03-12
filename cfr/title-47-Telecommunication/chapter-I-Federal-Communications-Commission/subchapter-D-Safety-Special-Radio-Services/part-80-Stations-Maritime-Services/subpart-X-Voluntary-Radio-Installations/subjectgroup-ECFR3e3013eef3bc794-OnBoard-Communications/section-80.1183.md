##### § 80.1183 Remote control for maneuvering or navigation. #####

(a) An on-board station may be used for remote control of maneuvering or navigation control systems aboard the same ship or, where that ship is towing a second ship, aboard the towed ship.

(b) The remote control system transmissions must contain a synchronization signal and a message signal composed of a documentation number group, a company control group, an actuation instruction group, and a termination of transmission group.

(1) The synchronization signal must be the control character “SYN”, transmitted twice.

(2) The message signal is composed of the following groups:

(i) The documentation number group must be transmitted once and be the ship's U.S. Coast Guard documentation number or, if the ship is not documented, the call sign of the on-board station.

(ii) The company control group, composed of three letters taken from AAA through ZZZ, which must be transmitted one time.

(iiii) The actuation instruction group, composed of two letters taken from AA through ZZ, which must be transmitted one time.

(iv) The termination of transmission group, composed of the control character “EM”, which must be transmitted twice.

(c) The receiving system must:

(1) Reject any actuation instruction until it recognizes and accepts the company control group.

(2) Reject any company control group until it recognizes and accepts the documentation number group.

(d) The emission employed must be G2D. The provisions applicable to G3E emission are also applicable to G2D emission.

(e) The binary information must be applied to the carrier as frequency-shift keying (FSK) of the standard tones 1070 and 1270 Hz. “0” (low) must correspond to 1070 Hz and “1” (high) must correspond to 1270 Hz. The signalling rate must be 300 bits per second.

(f) The alphabet employed must be the United States of America Standard Code for Information Interchange (USASCII), contained in the United States of America Standards Institute publication USAS X3.4-1968.

(1) The bit sequence must be least significant bit first to most significant bit (bit 1 through 7), consecutively.

(2) The character structure must consist of 8 bits (seven bits plus one character parity bit) having equal time intervals.

(3) “Odd” parity is required.