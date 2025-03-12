##### § 80.767 Propagation curve. #####

The propagation graph, § 80.767 Graph 1, must be used in computing the service area contour. The graph provides data for field strengths in dBu for an effective radiated power of 1 kW, over sea water, fresh water or land (smooth earth); transmitting antena heights of 4,800, 3,200, 1,600, 800, 400, 200, and 100 feet; based on a receiving antenna height of 9 meters (30 feet), for the 156-162 MHz band. The use of this is described in this section.

(a) Calculate the effective radiated power of the coast station, Ps in dB referred to 1 kW (dBk), as follows:

![](/graphics/ec02ap91.005.gif)where,Pt = Transmitter output power in dB referred to 1 kW: Transmitter output power in watts is converted to dBk by Pt = 10 [log10 (Power in watts)]−30. Also see § 80.761 Graph 1 for a conversion graph.G = Antenna gain in dB referred to a standard half-wave dipole, in the direction of each plotted radial, andL = Line losses between the transmitter and the antenna, in dB.Notes:

1. To determine field strengths where the distance is known, for effective radiated powers other than 1kW (0 dBk): Enter the graph from the “statute miles” scale at the known distance, read up to intersection with the curve for the antenna height, read left to the “dBu for 1 kW radiated” scale and note the referenced field strength (Fe). The value of the actual field strength (F) in dBu will be F = Fe + Ps where Ps is the effective radiated power calculated above.

2. To determine distance, where the actual field strength is specified, for effective radiated powers other than 0 dBk: The value of the field referenced strength will be Fe = F−Ps in dBu. Enter the graph, from the “dBu for 1 kW radiated” scale at the corrected value of Fe, read right to intersection with the antenna height, read down to “statute miles” scale.

(b) Determine the antenna height. For antenna heights between the heights for which this graph is drawn, use linear interpolation; assume linear height-gain for antennas higher than 4,800 feet.

(c) For receiver antenna heights lower than 9 meters (30 feet), assume that the field strength is the same as at 9 meters (30 feet).

(d) Assume that propagation over fresh water or over land is the same as that over sea water.

![](/graphics/ec02ap91.006.gif)