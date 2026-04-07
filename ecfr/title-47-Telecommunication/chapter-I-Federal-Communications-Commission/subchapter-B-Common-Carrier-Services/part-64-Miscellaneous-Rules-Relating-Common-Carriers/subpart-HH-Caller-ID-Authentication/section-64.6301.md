##### § 64.6301 Caller ID authentication.

(a) *STIR/SHAKEN implementation by voice service providers.* Except as provided in §§ 64.6304 and 64.6306, not later than June 30, 2021, a voice service provider shall fully implement the STIR/SHAKEN authentication framework in its internet Protocol networks. To fulfill this obligation, a voice service provider shall:

(1) Obtain an SPC token from the Secure Telephone Identity Policy Administrator and use that token to obtain a Secure Telephone Identity certificate from a Secure Telephone Identity Certificate Authority;

(2) Using the certificate obtained pursuant to paragraph (a)(1) of this section:

(i) Authenticate and verify caller identification information for all SIP calls that exclusively transit its own network;

(ii) Authenticate caller identification information for all SIP calls it originates and that it will exchange with another voice service provider or intermediate provider and, to the extent technically feasible, transmit that call with authenticated caller identification information to the next voice service provider or intermediate provider in the call path; and

(3) Verify caller identification information for all SIP calls it receives from another voice service provider or intermediate provider which it will terminate and for which the caller identification information has been authenticated.

(b) A voice service provider may fulfill its obligations to authenticate caller identification information under paragraph (a)(2) of this section by entering into an agreement with a third-party authentication service, provided that the voice service provider.

(1) Requires the third party to sign all calls using the certificate obtained by the voice service provider in accordance with paragraph (a)(1);

(2) Makes all attestation-level decisions regarding the caller identification information of each SIP call it originates;

(3) Memorializes the agreement between it and the third party for the authentication service in writing, which:

(i) Specifies the specific tasks that the third-party authenticator will perform on the voice service provider's behalf, and

(ii) Confirms that the voice service provider shall make all attestation-level decisions for calls signed pursuant to the agreement, and that all calls shall be signed using the voice service provider's Secure Telephone Identity certificate;

(4) Maintains any agreement entered into pursuant to paragraph (b) of this section for as long as any third-party authentication arrangement exists; and

(5) Retains a copy of any agreement entered into pursuant to paragraph (b) of this section for a period of two (2) years from the end or termination of the agreement.

\[85 FR 22043, Apr. 21, 2020, as amended at 85 FR 73394, Nov. 17, 2020; 90 FR 40255, Aug. 19, 2025\]