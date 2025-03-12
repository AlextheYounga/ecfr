##### § 64.1601 Delivery requirements and privacy restrictions. #####

Link to an amendment published at 82 FR 56917, December 1, 2017.

(a) *Delivery.* Except as provided in paragraphs (d) and (e) of this section:

(1) Telecommunications carriers and providers of interconnected Voice over Internet Protocol (VoIP) services, in originating interstate or intrastate traffic on the public switched telephone network (PSTN) or originating interstate or intrastate traffic that is destined for the PSTN (collectively “PSTN Traffic”), are required to transmit for all PSTN Traffic the telephone number received from or assigned to or otherwise associated with the calling party to the next provider in the path from the originating provider to the terminating provider. This provision applies regardless of the voice call signaling and transmission technology used by the carrier or VoIP provider. Entities subject to this provision that use Signaling System 7 (SS7) are required to transmit the calling party number (CPN) associated with all PSTN Traffic in the SS7 ISUP (ISDN User Part) CPN field to interconnecting providers, and are required to transmit the calling party's charge number (CN) in the SS7 ISUP CN field to interconnecting providers for any PSTN Traffic where CN differs from CPN. Entities subject to this provision who use multi-frequency (MF) signaling are required to transmit CPN, or CN if it differs from CPN, associated with all PSTN Traffic in the MF signaling automatic numbering information (ANI) field.

(2) Intermediate providers within an interstate or intrastate call path that originates and/or terminates on the PSTN must pass unaltered to subsequent providers in the call path signaling information identifying the telephone number, or billing number, if different, of the calling party that is received with a call. This requirement applies to SS7 information including but not limited to CPN and CN, and also applies to MF signaling information or other signaling information intermediate providers receive with a call. This requirement also applies to VoIP signaling messages, such as calling party and charge information identifiers contained in Session Initiation Protocol (SIP) header fields, and to equivalent identifying information as used in other VoIP signaling technologies, regardless of the voice call signaling and transmission technology used by the carrier or VoIP provider.

(b) *Privacy.* Except as provided in paragraph (d) of this section, originating carriers using Signaling System 7 and offering or subscribing to any service based on Signaling System 7 functionality will recognize \*67 dialed as the first three digits of a call (or 1167 for rotary or pulse dialing phones) as a caller's request that the CPN not be passed on an interstate call. Such carriers providing line blocking services will recognize \*82 as a caller's request that the CPN be passed on an interstate call. No common carrier subscribing to or offering any service that delivers CPN may override the privacy indicator associated with an interstate call. Carriers must arrange their CPN-based services, and billing practices, in such a manner that when a caller requests that the CPN not be passed, a carrier may not reveal that caller's number or name, nor may the carrier use the number or name to allow the called party to contact the calling party. The terminating carrier must act in accordance with the privacy indicator unless the call is made to a called party that subscribes to an ANI or charge number based service and the call is paid for by the called party.

(c) *Charges.* No common carrier subscribing to or offering any service that delivers calling party number may

(1) Impose on the calling party charges associated with per call blocking of the calling party's telephone number, or

(2) Impose charges upon connecting carriers for the delivery of the calling party number parameter or its associated privacy indicator.

(d) *Exemptions.* Section 64.1601(a) and (b) shall not apply when:

(1) A call originates from a payphone.

(2) A local exchange carrier with Signaling System 7 capability does not have the software to provide \*67 or \*82 functionalities. Such carriers are prohibited from passing CPN.

(3) A Private Branch Exchange or Centrex system does not pass end user CPN. Centrex systems that rely on \*6 or \*8 for a function other than CPN blocking or unblocking, respectively, are also exempt if they employ alternative means of blocking or unblocking.

(4) CPN delivery -

(i) Is used solely in connection with calls within the same limited system, including (but not limited to) a Centrex system, virtual private network, or Private Branch Exchange;

(ii) Is used on a public agency's emergency telephone line or in conjunction with 911 emergency services, or on any entity's emergency assistance poison control telephone line; or

(iii) Is provided in connection with legally authorized call tracing or trapping procedures specifically requested by a law enforcement agency.

(e) Any person or entity that engages in telemarketing, as defined in section 64.1200(f)(10) must transmit caller identification information.

(1) For purposes of this paragraph, caller identification information must include either CPN or ANI, and, when available by the telemarketer's carrier, the name of the telemarketer. It shall not be a violation of this paragraph to substitute (for the name and phone number used in, or billed for, making the call) the name of the seller on behalf of which the telemarketing call is placed and the seller's customer service telephone number. The telephone number so provided must permit any individual to make a do-not-call request during regular business hours.

(2) Any person or entity that engages in telemarketing is prohibited from blocking the transmission of caller identification information.

(3) Tax-exempt nonprofit organizations are not required to comply with this paragraph.

[60 FR 29490, June 5, 1995; 60 FR 54449, Oct. 24, 1995, as amended at 62 FR 34015, June 24, 1997; 68 FR 44179, July 25, 2003; 71 FR 75122, Dec. 14, 2006; 76 FR 73882, Nov. 29, 2011]