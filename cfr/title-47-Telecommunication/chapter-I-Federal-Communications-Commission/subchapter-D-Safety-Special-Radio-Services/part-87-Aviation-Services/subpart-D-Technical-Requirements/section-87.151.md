##### § 87.151 Special requirements for differential GPS receivers. #####

(a) The receiver shall achieve a message failure rate less than or equal to one failed message per 1000 full-length (222 bytes) application data messages, while operating over a range from −87 dBm to −1 dBm, provided that the variation in the average received signal power between successive bursts in a given time slot shall not exceed 40 dB. Failed messages include those lost by the VHF data receiver system or which do not pass the cyclic redundancy check (CRC) after application of the forward error correction (FEC).

(b) The aircraft receiving antenna can be horizontally or vertically polarized. Due to the difference in the signal strength of horizontally and vertically polarized components of the broadcast signal, the total aircraft implementation loss is limited to 15 dB for horizontally polarized receiving antennas and 11 dB for vertically polarized receiving antennas.

(c) *Desensitization.* The receiver shall meet the requirements specified in paragraph (a) of this section in the presence of VHF-FM broadcast signals in accord with following tables.

(1) Maximum levels of undesired signals.

|                                          Frequency <sup>1</sup>                                           |Maximum level of undesired signal at the receiver input (dBm)|
|-----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
|                                            50 kHz up to 88 MHz                                            |                             −13                             |
|                                            88 MHz-107.900 MHz                                             |                   [see paragraph (c)(2)]                    |
|                                          108.000 MHz-117.975 MHz                                          |                          excluded                           |
|                                                  118MHz                                                   |                             −44                             |
|                                                118.025 MHz                                                |                             −41                             |
|                                       118.050 MHz up to 1660.5 MHz                                        |                             −13                             |
|<sup>1</sup> The relationship is linear between single adjacent points designated by the above frequencies.|                                                             |

(2) Desensitization frequency and power requirements for the frequencies 108.025 MHz to 111.975 MHz.

|                                          Frequency <sup>1</sup>                                           |Maximum level of undesired signal at the receiver input (dBm)|
|-----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
|                                            88 MHz ≤f ≤102 MHz                                             |                             15                              |
|                                                  104 MHz                                                  |                             10                              |
|                                                  106 MHz                                                  |                              5                              |
|                                                 107.9 MHz                                                 |                             −10                             |
|<sup>1</sup> The relationship is linear between single adjacent points designated by the above frequencies.|                                                             |

(3) Desensitization frequency and power requirements for the frequencies 112.00 MHz to 117.975 MHz.

|                                          Frequency <sup>1</sup>                                           |Maximum level of undesired signal at the receiver input (dBm)|
|-----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
|                                            88 MHz ≤f ≤104 MHz                                             |                             15                              |
|                                                  106 MHz                                                  |                             10                              |
|                                                  107 MHz                                                  |                              5                              |
|                                                 107.9 MHz                                                 |                              0                              |
|<sup>1</sup> The relationship is linear between single adjacent points designated by the above frequencies.|                                                             |

(d) *Intermodulation immunity.* The receiver shall meet the requirements specified in paragraph (a) of this section in the presence of interference from two-signal, third order intermodulation products of two VHF-FM broadcast signals having levels in accordance with the following:

(1) 2N1 + N2 + 72 ≤0 for VHF-FM sound broadcasting signals in the range 107.7-108 MHz; and

(2) 2N1 + N2 + 3 (24 −20log delta *f*/0.4) ≤0 for VHF-FM sound broadcasting signals below 107.7 MHz, where the frequencies of the two VHF-FM sound broadcasting signals produce, within the receiver, a two signal, third-order intermodulation product on the desired VDB frequency.

(3) In the formulas in paragraphs (d)(1) and (d)(2) of this section, N1 and N2 are the levels (dBm) of the two VHF FM sound broadcasting signals at the VHF data broadcast (VDB) receiver input. Neither level shall exceed the desensitization criteria set forth in paragraph (c) of this section. Delta *f* = 108.1 − *f*1, where *f*1 is the frequency of N1, the VHF FM sound broadcasting signal closer to 108.1 MHz.

[69 FR 32881, June 14, 2004]