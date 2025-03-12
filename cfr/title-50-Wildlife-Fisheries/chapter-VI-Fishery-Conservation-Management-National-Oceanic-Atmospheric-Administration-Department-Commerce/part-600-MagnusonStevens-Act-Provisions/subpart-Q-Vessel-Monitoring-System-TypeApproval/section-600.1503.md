##### § 600.1503 Position report data formats and transmission. #####

Unless otherwise specified, this subsection applies to all VMS units, MCSs and bundles. Units that can operate as both an EMTU and EMTU-C must meet the requirements for both an EMTU and an EMTU-C in order to gain type-approval as both. To be type-approved in any given fishery, a VMS unit must also meet any additional positioning information as required by the applicable VMS regulations and requirements in effect for each fishery or region for which the type-approval applies. The VMS unit must meet the following requirements:

(a) Transmit all automatically-generated position reports, for vessels managed individually or grouped by fleet, that meet the latency requirement under § 600.1504.

(b) When powered up, must automatically re-establish its position reporting function without manual intervention.

(c) Position reports must contain all of the following:

(1) Unique identification of an EMTU/EMTU-C and clear indication if the unit is an EMTU-C.

(2) Date (year/month/day with century in the year) and time stamp (GMT) of the position fix.

(3) Date (year/month/day with century in the year) and time stamp (GMT) that the EMTU-C position report was sent from the EMTU-C.

(4) Position fixed latitude and longitude, including the hemisphere of each, which comply with the following requirements:

(i) The position fix precision must be to the decimal minute hundredths.

(ii) Accuracy of the reported position must be within 100 meters (328.1 ft).

(d) An EMTU/EMTU-C must have the ability to: (1) Store 1,000 position fixes in local, non-volatile memory.

(2) Allow for defining variable reporting intervals between 5 minutes and 24 hours.

(3) Allow for changes in reporting intervals remotely and only by authorized users.

(e) An EMTU/EMTU-C must generate specially identified position reports upon:

(1) Antenna disconnection.

(2) Loss of positioning reference signals.

(3) Security events, power-up, power down, and other status data.

(4) A request for EMTU/EMTU-C status information such as configuration of programming and reporting intervals.

(5) The EMTUs loss of the mobile communications signals.

(6) An EMTU must generate a specially identified position report upon the vessel crossing of a pre-defined geographic boundary.