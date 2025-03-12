##### § 299.211 Communications and security requirements. #####

(a) All wireless communications between the office, wayside, and onboard components in a PTC system shall provide cryptographic message integrity and authentication.

(b) Cryptographic keys required under this section shall—

(1) Use an algorithm approved by the National Institute of Standards or a similarly recognized and FRA-approved standards body;

(2) Be distributed using manual or automated methods, or a combination of both; and

(3) Be revoked—

(i) If compromised by unauthorized disclosure of the cleartext key; or

(ii) When the key algorithm reaches its lifespan as defined by the standards body responsible for approval of the algorithm.

(c) The cleartext form of the cryptographic keys shall be protected from unauthorized disclosure, modification, or substitution, except during key entry when the cleartext keys and key components may be temporarily displayed to allow visual verification. When encrypted keys or key components are entered, the cryptographically protected cleartext key or key components shall not be displayed.

(d) Access to cleartext keys shall be protected by a tamper-resistant mechanism.

(e) If the railroad elects to also provide cryptographic message confidentiality, it shall:

(1) Comply with the same requirements for message integrity and authentication under this section; and

(2) Only use keys meeting or exceeding the security strength required to protect the data as defined in the railroad's PTCSP.

(f) The railroad, or its vendor or supplier, shall have a prioritized service restoration and mitigation plan for scheduled and unscheduled interruptions of service. This plan shall be made available to FRA upon request, without undue delay, for restoration of communication services that support PTC system services.