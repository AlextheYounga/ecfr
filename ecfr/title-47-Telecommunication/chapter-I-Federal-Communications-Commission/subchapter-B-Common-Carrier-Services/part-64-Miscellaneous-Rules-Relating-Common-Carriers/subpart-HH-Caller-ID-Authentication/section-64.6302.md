##### § 64.6302 Caller ID authentication by intermediate providers.

Not later than June 30, 2021, each intermediate provider shall fully implement the STIR/SHAKEN authentication framework in its internet Protocol networks. To fulfill this obligation, an intermediate provider shall:

(a) Obtain an SPC token from the Secure Telephone Identity Policy Administrator and use that token to obtain a Secure Telephone Identity certificate from a Secure Telephone Identity Certificate Authority;

(b) Pass unaltered to the subsequent intermediate provider or voice service provider in the call path any authenticated caller identification information it receives with a SIP call, subject to the following exceptions under which it may remove the authenticated caller identification information:

(1) Where necessary for technical reasons to complete the call; or

(2) Where the intermediate provider reasonably believes the caller identification authentication information presents an imminent threat to its network security; and

(c) Authenticate caller identification information for all calls it receives for which the caller identification information has not been authenticated and which it will exchange with another provider as a SIP call using the Secure Telephone Identity certificate it received from the Secure Telephone Identity Certificate Authority pursuant to paragraph (a) of this section, except that the intermediate provider is excused from such duty to authenticate if it:

(1) Cooperatively participates with the industry traceback consortium; and

(2) Responds fully and in a timely manner to all traceback requests it receives from the Commission, law enforcement, and the industry traceback consortium regarding calls for which it acts as an intermediate provider.

(d) Notwithstanding paragraph (c) of this section, a gateway provider must authenticate caller identification information using the Secure Telephone Identity certificate it received pursuant to paragraph (a) of this section for all calls it receives that use North American Numbering Plan resources that pertain to the United States in the caller ID field and for which the caller identification information has not been authenticated and which it will exchange with another provider as a SIP call, unless that gateway provider is subject to an applicable extension in § 64.6304.

(e) Notwithstanding paragraph (c) of this section, a non-gateway intermediate provider must authenticate caller identification information using the Secure Telephone Identity certificate it received pursuant to paragraph (a) of this section for all calls it receives directly from an originating provider and for which the caller identification information has not been authenticated and which it will exchange with another provider as a SIP call, unless that non-gateway intermediate provider is subject to an applicable extension in § 64.6304.

(f) An intermediate provider may fulfill its obligations to authenticate caller ID information under paragraphs (d) and (e) of this section by entering into an agreement with a third-party authentication service, provided that the intermediate provider:

(1) Requires the third party to sign all calls using the certificate obtained by the intermediate provider in accordance with paragraph (a) of this section;

(2) Makes all attestation-level decisions regarding the caller identification information of each SIP call it originates;

(3) Memorializes the agreement between it and the third party for the authentication service in writing, which:

(i) Specifies the specific tasks that the third-party authenticator will perform on the intermediate provider's behalf, and

(ii) Confirms that the intermediate provider shall make all attestation-level decisions for calls signed pursuant to the agreement, and that all calls shall be signed using the voice service provider's Secure Telephone Identity certificate;

(4) Maintains any agreement entered into pursuant to paragraph (f) of this section for as long as any third-party authentication arrangement exists; and

(5) Retains a copy of any agreement entered into pursuant to paragraph (f) of this section for a period of two (2) years from the end or termination of the agreement.

\[85 FR 73395, Nov. 17, 2020, as amended at 87 FR 42946, July 18, 2022; 88 FR 40118, June 21, 2023; 90 FR 40255, Aug. 19, 2025\]