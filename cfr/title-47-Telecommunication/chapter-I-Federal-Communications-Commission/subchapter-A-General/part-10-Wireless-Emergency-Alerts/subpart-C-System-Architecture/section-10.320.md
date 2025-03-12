##### § 10.320 Provider alert gateway requirements. #####

Link to an amendment published at 81 FR 75725, Nov. 1, 2016.

This section specifies the functions that each Participating Commercial Mobile Service provider is required to support and perform at its CMS provider gateways.

(a) *General.* The CMS provider gateway must provide secure, redundant, and reliable connections to receive Alert Messages from the Federal alert gateway. Each CMS provider gateway must be identified by a unique IP address or domain name.

(b) *Authentication and validation.* The CMS provider gateway must authenticate interactions with the Federal alert gateway, and validate Alert Message integrity and parameters. The CMS provider gateway must provide an error message immediately to the Federal alert gateway if a validation fails.

(c) *Security.* The CMS provider gateway must support standardized IP-based security mechanisms such as a firewall, and support the defined WEA “C” interface and associated protocols between the Federal alert gateway and the CMS provider gateway.

(d) *Geographic targeting.* The CMS provider gateway must determine whether the provider has elected to transmit an Alert Message within a specified alert area and, if so, map the Alert Message to an associated set of transmission sites.

(e) *Message management* - (1) *Formatting.* The CMS provider gateway is not required to perform any formatting, reformatting, or translation of an Alert Message, except for transcoding a text, audio, video, or multimedia file into the format supported by mobile devices.

(2) Reception. The CMS provider gateway must support a mechanism to stop and start Alert Message deliveries from the Federal alert gateway to the CMS provider gateway.

(3) Prioritization. The CMS provider gateway must process an Alert Message on a first in-first out basis except for Presidential Alerts, which must be processed before all non-Presidential alerts.

(4) Distribution. A Participating CMS provider must deploy one or more CMS provider gateways to support distribution of Alert Messages and to manage Alert Message traffic.

(5) Retransmission. The CMS provider gateway must manage and execute Alert Message retransmission, and support a mechanism to manage congestion within the CMS provider's infrastructure.

(f) *CMS provider profile.* The CMS provider gateway will provide profile information on the CMS provider for the Federal alert gateway to maintain at the Federal alert gateway. This profile information must be provided by an authorized CMS provider representative to the Federal alert gateway administrator. The profile information must include the data listed in Table 10.320(f) and must comply with the following procedures:

(1) The information must be provided 30 days in advance of the date when the CMS provider begins to transmit WEA alerts.

(2) Updates of any CMS provider profiles must be provided in writing at least 30 days in advance of the effective change date.

Table 10.320(f) - CMSP Profile on Federal Alert Gateway

|  Profile parameter   |   Parameter election    |                                                                 Description                                                                  |
|----------------------|-------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
|      CMSP Name       |                         |                                                        Unique identification of CMSP.                                                        |
| CMSP gateway Address |IP address or Domain Name|                                                                                                                                              |
|                      |  Alternate IP address   |                                                   Optional and subject to implementation.                                                    |
|Geo-Location Filtering|       \<yes/no\>        |If “yes” the only CMAM issued in the listed states will be sent to the CMSP gateway.  <br/>If “no”, all CMAM will be sent to the CMSP gateway.|
|If yes, list of states| CMAC Geocode for state  |                                              List can be state name or abbreviated state name.                                               |

[73 FR 43117, July 24, 2008, as amended at 78 FR 16808, Mar. 19, 2013]