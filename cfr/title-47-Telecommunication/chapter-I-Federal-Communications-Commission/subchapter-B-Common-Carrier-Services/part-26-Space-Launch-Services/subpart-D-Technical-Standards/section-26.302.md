##### § 26.302 Emission masks. #####

Link to an amendment published at 90 FR 11493, Mar. 7, 2025.

(a) *2025-2110 MHz.* For frequencies offset from the assigned frequency less than the 50 percent of the necessary bandwidth, no attenuation is required. At a frequency offset equal to 50 percent of the necessary bandwidth, an attenuation of at least 8 dB is required. Frequencies offset more than 50 percent of the necessary bandwidth shall be attenuated by the following mask:

Equation 1 to Paragraph (a)![](/graphics/er05au24.006.gif)Where:fd is the frequency displaced from the center of the emission bandwidth.Bn is the necessary bandwidth, which is determined in accordance with Annex J of the NTIA Manual of Regulations and Procedures for Federal Radio Frequency Management (NTIA Manual) (incorporated by reference, see § 26.305).dBsd is dB attenuation in a 4 kHz bandwidth, relative to the maximum power in any 4 kHz bandwidth within the necessary bandwidth (0 dBsd), where attenuation in this sense refers to the reduction in level relative to the reference, 0 dBsd, unless otherwise specified.

The unwanted emission mask rolls off at 40 dB per decade to a maximum attenuation of 60 dBsd, at which point it continues on both sides of the carrier for all frequencies beyond this point; see Annex M of the NTIA Manual regarding measurement requirements (incorporated by reference, see § 26.305); for any narrowband or single frequency unwanted emission which is not spread by the modulation process, the required attenuation shall be at least 60 dBc, where dBc is attenuation below the mean transmit power, rather than the dBsd value determined in equation 1 to this paragraph (a).

(b) *2200-2290 MHz.* (1) During the first stage of a launch, all spectral components larger than −[55 + 10xlog(P)] dBc (*i.e.,* larger than −25 dBm) at the transmitter output must be within the spectral mask calculated using the following equation:

Equation 2 to Paragraph (b)(1)M(f) = K + 90 log(R)−100 log |f-fc|; |f-fc| ≥ R/mWhere:M(f) = power (dBc) at frequency f (MHz).K = −20 for analog signals.K = −28 for binary signals.K = −61 for FQPSK-B, FQPSK-JR, SOQPSK-TG.K = −73 for ARTM CPM.fc = transmitter center frequency (MHz).R = bit rate (Mbps) for digital signals or (Δf +fmax)(MHz) for analog FM signals.M = number of states in modulating signal (m = 2 for binary signals, m = 4 for quaternary signals and analog signals).f = peak deviation.fmax = maximum modulation frequency.

(2) After the first stage of a launch, the emission mask set forth in paragraph (a) of this section shall apply.