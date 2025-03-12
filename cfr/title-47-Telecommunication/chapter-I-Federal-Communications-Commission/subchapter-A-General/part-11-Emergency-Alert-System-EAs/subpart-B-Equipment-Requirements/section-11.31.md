##### § 11.31 EAS protocol. #####

(a) The EAS uses a four part message for an emergency activation of the EAS. The four parts are: Preamble and EAS Header Codes; audio Attention Signal; message; and, Preamble and EAS End Of Message (EOM) Codes.

(1) The Preamble and EAS Codes must use Audio Frequency Shift Keying at a rate of 520.83 bits per second to transmit the codes. Mark frequency is 2083.3 Hz and space frequency is 1562.5 Hz. Mark and space time must be 1.92 milliseconds. Characters are ASCII seven bit characters as defined in ANSI X3.4-1977 ending with an eighth null bit (either 0 or 1) to constitute a full eight-bit byte.

(2) The Attention Signal must be made up of the fundamental frequencies of 853 and 960 Hz. The two tones must be transmitted simultaneously. The Attention Signal must be transmitted after the EAS header codes.

(3) The message may be audio, video or text.

(b) The ASCII dash and plus symbols are required and may not be used for any other purpose. Unused characters must be ASCII space characters. FM or TV call signs must use a slash ASCII character number 47 (/) in lieu of a dash.

(c) The EAS protocol, including any codes, must not be amended, extended or abridged without FCC authorization. The EAS protocol and message format are specified in the following representation.

Examples are provided in FCC Public Notices.

[PREAMBLE]ZCZC-ORG-EEE-PSSCCC + TTTT-JJJHHMM-LLLLLLLL-(one second pause)[PREAMBLE]ZCZC-ORG-EEE-PSSCCC + TTTTpJJJHHMM-LLLLLLLL-(one second pause)[PREAMBLE]ZCZC-ORG-EEE-PSSCCC + TTTT-JJJHHMM-LLLLLLLL-(at least a one second pause)(transmission of 8 to 25 seconds of Attention Signal)(transmission of audio, video or text messages)(at least a one second pause)[PREAMBLE]NNNN (one second pause)[PREAMBLE]NNNN (one second pause)[PREAMBLE]NNNN (at least one second pause)[PREAMBLE] This is a consecutive string of bits (sixteen bytes of AB hexadecimal [8 bit byte 10101011]) sent to clear the system, set AGC and set asynchronous decoder clocking cycles. The preamble must be transmitted before each header and End of Message code.ZCZC—This is the identifier, sent as ASCII characters ZCZC to indicate the start of ASCII code.ORG—This is the Originator code and indicates who originally initiated the activation of the EAS. These codes are specified in paragraph (d) of this section.EEE—This is the Event code and indicates the nature of the EAS activation. The codes are specified in paragraph (e) of this section. The Event codes must be compatible with the codes used by the NWS Weather Radio Specific Area Message Encoder (WRSAME).PSSCCC—This is the Location code and indicates the geographic area affected by the EAS alert. There may be 31 Location codes in an EAS alert. The Location code uses the codes described in the American National Standards Institute (ANSI) standard, ANSI INCITS 31-2009 (“Information technology—Codes for the Identification of Counties and Equivalent Areas of the United States, Puerto Rico, and the Insular Areas”). Each state is assigned an SS number as specified in paragraph (f) of this section. Each county and some cities are assigned a CCC number. A CCC number of 000 refers to an entire State or Territory. P defines county subdivisions as follows: 0 = all or an unspecified portion of a county, 1 = Northwest, 2 = North, 3 = Northeast, 4 = West, 5 = Central, 6 = East, 7 = Southwest, 8 = South, 9 = Southeast. Other numbers may be designated later for special applications. The use of county subdivisions will probably be rare and generally for oddly shaped or unusually large counties. Any subdivisions must be defined and agreed to by the local officials prior to use. + TTTT—This indicates the valid time period of a message in 15 minute segments up to one hour and then in 30 minute segments beyond one hour; *i.e.*, + 0015, + 0030, + 0045, + 0100, + 0430 and + 0600.JJJHHMM—This is the day in Julian Calendar days (JJJ) of the year and the time in hours and minutes (HHMM) when the message was initially released by the originator using 24 hour Universal Coordinated Time (UTC).LLLLLLLL—This is the identification of the EAS Participant, NWS office, etc., transmitting or retransmitting the message. These codes will be automatically affixed to all outgoing messages by the EAS encoder.NNNN—This is the End of Message (EOM) code sent as a string of four ASCII N characters.

(d)(1) The only originator codes are:

|       Originator       |ORG code|
|------------------------|--------|
|    EAS Participant     |  EAS   |
|   Civil authorities    |  CIV   |
|National Weather Service|  WXR   |
|United States Government|  PEP   |

(2) Use of the previously authorized NIC originator code (National Information Center) must be discontinued by no later than December 12, 2023.

(e) The following Event (EEE) codes are presently authorized:

|            Nature of activation             |Event codes|
|---------------------------------------------|-----------|
|         National codes (required):          |           |
|         National Emergency Message          |    EAN    |
|Nationwide Test of the Emergency Alert System|    NPT    |
|            Required Monthly Test            |    RMT    |
|            Required Weekly Test             |    RWT    |
|      State and Local Codes (Optional):      |           |
|           Administrative Message            |   ADR.    |
|              Avalanche Warning              |   AVW.    |
|               Avalanche Watch               |   AVA.    |
|              Blizzard Warning               |   BZW.    |
|                 Blue Alert                  |   BLU.    |
|          Child Abduction Emergency          |   CAE.    |
|            Civil Danger Warning             |   CDW.    |
|           Civil Emergency Message           |   CEM.    |
|            Coastal Flood Warning            |   CFW.    |
|             Coastal Flood Watch             |   CFA.    |
|             Dust Storm Warning              |   DSW.    |
|             Earthquake Warning              |   EQW.    |
|            Evacuation Immediate             |   EVI.    |
|            Extreme Wind Warning             |   EWW.    |
|                Fire Warning                 |   FRW.    |
|             Flash Flood Warning             |   FFW.    |
|              Flash Flood Watch              |   FFA.    |
|            Flash Flood Statement            |   FFS.    |
|                Flood Warning                |   FLW.    |
|                 Flood Watch                 |   FLA.    |
|               Flood Statement               |   FLS.    |
|         Hazardous Materials Warning         |   HMW.    |
|              High Wind Warning              |   HWW.    |
|               High Wind Watch               |   HWA.    |
|              Hurricane Warning              |   HUW.    |
|               Hurricane Watch               |   HUA.    |
|             Hurricane Statement             |   HLS.    |
|           Law Enforcement Warning           |   LEW.    |
|            Local Area Emergency             |   LAE.    |
|        Network Message Notification         |   NMN.    |
|       911 Telephone Outage Emergency        |   TOE.    |
|         Nuclear Power Plant Warning         |   NUW.    |
|            Practice/Demo Warning            |   DMO.    |
|         Radiological Hazard Warning         |   RHW.    |
|         Severe Thunderstorm Warning         |   SVR.    |
|          Severe Thunderstorm Watch          |   SVA.    |
|          Severe Weather Statement           |   SVS.    |
|          Shelter in Place Warning           |    SPW    |
|           Special Marine Warning            |   SMW.    |
|          Special Weather Statement          |   SPS.    |
|              Storm Surge Watch              |   SSA.    |
|             Storm Surge Warning             |   SSW.    |
|               Tornado Warning               |   TOR.    |
|                Tornado Watch                |   TOA.    |
|           Tropical Storm Warning            |   TRW.    |
|            Tropical Storm Watch             |   TRA.    |
|               Tsunami Warning               |   TSW.    |
|                Tsunami Watch                |   TSA.    |
|               Volcano Warning               |   VOW.    |
|            Winter Storm Warning             |   WSW.    |
|             Winter Storm Watch              |   WSA.    |

(f) The All U.S., State, Territory and Offshore (Marine Area) ANSI number codes (SS) are as follows. County ANSI numbers (CCC) are contained in the State EAS Mapbook.

|                                                                                                                                                                                                               |ANSI No.|
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
|                                                                                                    All U.S                                                                                                    |   00   |
|                                                                                                    State:                                                                                                     |        |
|                                                                                                      AL                                                                                                       |   01   |
|                                                                                                      AK                                                                                                       |   02   |
|                                                                                                      AZ                                                                                                       |   04   |
|                                                                                                      AR                                                                                                       |   05   |
|                                                                                                      CA                                                                                                       |   06   |
|                                                                                                      CO                                                                                                       |   08   |
|                                                                                                      CT                                                                                                       |   09   |
|                                                                                                      DE                                                                                                       |   10   |
|                                                                                                      DC                                                                                                       |   11   |
|                                                                                                      FL                                                                                                       |   12   |
|                                                                                                      GA                                                                                                       |   13   |
|                                                                                                      HI                                                                                                       |   15   |
|                                                                                                      ID                                                                                                       |   16   |
|                                                                                                      IL                                                                                                       |   17   |
|                                                                                                      IN                                                                                                       |   18   |
|                                                                                                      IA                                                                                                       |   19   |
|                                                                                                      KS                                                                                                       |   20   |
|                                                                                                      KY                                                                                                       |   21   |
|                                                                                                      LA                                                                                                       |   22   |
|                                                                                                      ME                                                                                                       |   23   |
|                                                                                                      MD                                                                                                       |   24   |
|                                                                                                      MA                                                                                                       |   25   |
|                                                                                                      MI                                                                                                       |   26   |
|                                                                                                      MN                                                                                                       |   27   |
|                                                                                                      MS                                                                                                       |   28   |
|                                                                                                      MO                                                                                                       |   29   |
|                                                                                                      MT                                                                                                       |   30   |
|                                                                                                      NE                                                                                                       |   31   |
|                                                                                                      NV                                                                                                       |   32   |
|                                                                                                      NH                                                                                                       |   33   |
|                                                                                                      NJ                                                                                                       |   34   |
|                                                                                                      NM                                                                                                       |   35   |
|                                                                                                      NY                                                                                                       |   36   |
|                                                                                                      NC                                                                                                       |   37   |
|                                                                                                      ND                                                                                                       |   38   |
|                                                                                                      OH                                                                                                       |   39   |
|                                                                                                      OK                                                                                                       |   40   |
|                                                                                                      OR                                                                                                       |   41   |
|                                                                                                      PA                                                                                                       |   42   |
|                                                                                                      RI                                                                                                       |   44   |
|                                                                                                      SC                                                                                                       |   45   |
|                                                                                                      SD                                                                                                       |   46   |
|                                                                                                      TN                                                                                                       |   47   |
|                                                                                                      TX                                                                                                       |   48   |
|                                                                                                      UT                                                                                                       |   49   |
|                                                                                                      VT                                                                                                       |   50   |
|                                                                                                      VA                                                                                                       |   51   |
|                                                                                                      WA                                                                                                       |   53   |
|                                                                                                      WV                                                                                                       |   54   |
|                                                                                                      WI                                                                                                       |   55   |
|                                                                                                      WY                                                                                                       |   56   |
|                                                                                                    Terr.:                                                                                                     |        |
|                                                                                                      AS                                                                                                       |   60   |
|                                                                                                      FM                                                                                                       |   64   |
|                                                                                                      GU                                                                                                       |   66   |
|                                                                                                      MH                                                                                                       |   68   |
|                                                                                                      PR                                                                                                       |   72   |
|                                                                                                      PW                                                                                                       |   70   |
|                                                                                                      UM                                                                                                       |   74   |
|                                                                                                      VI                                                                                                       |   78   |
|                                                                                     Offshore (Marine Areas) <sup>1</sup>                                                                                      |        |
|                                                         Eastern North Pacific Ocean, and along U.S. West Coast from Canadian border to Mexican border                                                         |   57   |
|                                                 North Pacific Ocean near Alaska, and along Alaska coastline, including the Bering Sea and the Gulf of Alaska                                                  |   58   |
|                                                                               Central Pacific Ocean, including Hawaiian waters                                                                                |   59   |
|                                                                         South Central Pacific Ocean, including American Samoa waters                                                                          |   61   |
|                                                                            Western Pacific Ocean, including Mariana Island waters                                                                             |   65   |
|                                               Western North Atlantic Ocean, and along U.S. East Coast, from Canadian border south to Currituck Beach Light, N.C                                               |   73   |
|                        Western North Atlantic Ocean, and along U.S. East Coast, south of Currituck Beach Light, NC, following the coastline to Ocean Reef, FL, including the Caribbean                        |   75   |
|                                                            Gulf of Mexico, and along the U.S. Gulf Coast from the Mexican border to Ocean Reef, FL                                                            |   77   |
|                                                                                                 Lake Superior                                                                                                 |   91   |
|                                                                                                 Lake Michigan                                                                                                 |   92   |
|                                                                                                  Lake Huron                                                                                                   |   93   |
|                                                                                                Lake St. Clair                                                                                                 |   94   |
|                                                                                                   Lake Erie                                                                                                   |   96   |
|                                                                                                 Lake Ontario                                                                                                  |   97   |
|                                                                                      St. Lawrence River above St. Regis                                                                                       |   98   |
|<sup>1</sup> The numbers assigned to the offshore marine areas listed in this table are not described under the ANSI standard, but rather are numeric codes that were assigned by the National Weather Service.|        |

[59 FR 67092, Dec. 28, 1994, as amended at 60 FR 55999, Nov. 6, 1995; 61 FR 54952, Oct. 23, 1996; 63 FR 29663, June 1, 1998; 67 FR 18508, Apr. 16, 2002; 67 FR 77174, Dec. 17, 2002; 69 FR 72031, Dec. 10, 2004; 70 FR 71033, Nov. 25, 2005; 77 FR 16701, Mar. 22, 2012; 80 FR 37174, June 30, 2015; 81 FR 53043, Aug. 11, 2016; 83 FR 2563, Jan. 18, 2018; 87 FR 67823, Nov. 10, 2022]