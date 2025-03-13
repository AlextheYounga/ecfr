##### § 170.24 CMMC Scoring Methodology. #####

(a) *General.* This scoring methodology is designed to provide a measurement of an OSA's implementation status of the NIST SP 800-171 R2 security requirements (incorporated by reference elsewhere in this part, see § 170.2) and the selected NIST SP 800-172 Feb2021 security requirements (incorporated by reference elsewhere in this part, see § 170.2). The CMMC Scoring Methodology is designed to credit partial implementation only in limited cases (*e.g.,* multi-factor authentication IA.L2-3.5.3).

(b) *Assessment findings.* Each security requirement assessed under the CMMC Scoring Methodology must result in one of three possible assessment findings, as follows:

(1) *Met.* All applicable objectives for the security requirement are satisfied based on evidence. All evidence must be in final form and not draft. Unacceptable forms of evidence include but are not limited to working papers, drafts, and unofficial or unapproved policies.

(i) Enduring exceptions when described, along with any mitigations, in the system security plan shall be assessed as MET.

(ii) Temporary deficiencies that are appropriately addressed in operational plans of action (*i.e.,* include deficiency reviews and show progress towards the implementation of corrections to reduce or eliminate identified vulnerabilities) shall be assessed as MET.

(2) *Not Met.* One or more applicable objectives for the security requirement is not satisfied. During an assessment, for each security requirement objective marked NOT MET, the assessor will document why the evidence does not conform.

(3) *Not Applicable (N/A).* A security requirement and/or objective does not apply at the time of the CMMC assessment. For example, Public-Access System Separation (SC.L2-3.13.5) might be N/A if there are no publicly accessible systems within the CMMC Assessment Scope. During an assessment, an assessment objective assessed as N/A is equivalent to the same assessment objective being assessed as MET.

(c) *Scoring.* At each CMMC Level, security requirements are scored as follows:

(1) *CMMC Level 1.* All CMMC Level 1 security requirements must be fully implemented to be considered MET. No POA&M is permitted for CMMC Level 1, and self-assessment results are scored as MET or NOT MET in their entirety.

(2) *CMMC Level 2 Scoring Methodology.* The maximum score achievable for a Level 2 self-assessment or Level 2 certification assessment is equal to the total number of CMMC Level 2 security requirements. If all CMMC Level 2 security requirements are MET, OSAs are awarded the maximum score. For each requirement NOT MET, the associated value of the security requirement is subtracted from the maximum score, which may result in a negative score.

(i) *Procedures.* (A) Scoring methodology for Level 2 self-assessment and Level 2 certification assessment is based on all CMMC Level 2 security requirement objectives, including those NOT MET.

(B) In the CMMC Level 2 Scoring Methodology, each security requirement has a value (*e.g.,* 1, 3 or 5), which is related to the designation by NIST as basic or derived security requirements. Per NIST SP 800-171 R2, the basic security requirements are obtained from FIPS PUB 200 Mar2006, which provides the high-level and fundamental security requirements for Federal information and systems. The derived security requirements, which supplement the basic security requirements, are taken from the security controls in NIST SP 800-53 R5.

(*1*) For NIST SP 800-171 R2 basic and derived security requirements that, if not implemented, could lead to significant exploitation of the network, or exfiltration of CUI, five (5) points are subtracted from the maximum score. The basic and derived security requirements with a value of five (5) points include:

(*i*) *Basic security requirements.* AC.L2-3.1.1, AC.L2-3.1.2, AT.L2-3.2.1, AT.L2-3.2.2, AU.L2-3.3.1, CM.L2-3.4.1, CM.L2-3.4.2, IA-L2-3.5.1, IA-L2-3.5.2, IR.L2-3.6.1, IR.L2-3.6.2, MA.L2-3.7.2, MP.L2-3.8.3, PS.L2-3.9.2, PE.L2-3.10.1, PE.L2-3.10.2, CA.L2-3.12.1, CA.L2-3.12.3, SC.L2-3.13.1, SC.L2-3.13.2, SI.L2-3.14.1, SI.L2-3.14.2, and SI.L2-3.14.3.

(*ii*) *Derived security requirements.* AC.L2-3.1.12, AC.L2-3.1.13, AC.L2-3.1.16, AC.L2-3.1.17, AC.L2-3.1.18, AU.L2-3.3.5, CM.L2-3.4.5, CM.L2-3.4.6, CM.L2-3.4.7, CM.L2-3.4.8, IA.L2-3.5.10, MA.L2-3.7.5, MP.L2-3.8.7, RA.L2-3.11.2, SC.L2-3.13.5, SC.L2-3.13.6, SC.L2-3.13.15, SI.L2-3.14.4, and SI.L2-3.14.6.

(*2*) For basic and derived security requirements that, if not implemented, have a specific and confined effect on the security of the network and its data, three (3) points are subtracted from the maximum score. The basic and derived security requirements with a value of three (3) points include:

(*i*) *Basic security requirements.* AU.L2-3.3.2, MA.L2-3.7.1, MP.L2-3.8.1, MP.L2-3.8.2, PS.L2-3.9.1, RA.L2-3.11.1, and CA.L2-3.12.2.

(*ii*) *Derived security requirements.* AC.L2-3.1.5, AC.L2- 3.1.19, MA.L2-3.7.4, MP.L2-3.8.8, SC.L2-3.13.8, SI.L2-3.14.5, and SI.L2-3.14.7.

(*3*) All remaining derived security requirements, other than the exceptions noted, if not implemented, have a limited or indirect effect on the security of the network and its data. For these, 1 point is subtracted from the maximum score.

(*4*) Two derived security requirements, IA.L2-3.5.3 and SC.L2-3.13.11, can be partially effective even if not completely or properly implemented, and the points deducted may be adjusted depending on how the security requirement is implemented.

(*i*) Multi-factor authentication (MFA) (CMMC Level 2 security requirement IA.L2-3.5.3) is typically implemented first for remote and privileged users (since these users are both limited in number and more critical) and then for the general user, so three (3) points are subtracted from the maximum score if MFA is implemented only for remote and privileged users. Five (5) points are subtracted from the maximum score if MFA is not implemented for any users.

(*ii*) FIPS-validated encryption (CMMC Level 2 security requirement SC.L2-3.13.11) is required to protect the confidentiality of CUI. If encryption is employed, but is not FIPS-validated, three (3) points are subtracted from the maximum score; if encryption is not employed; five (5) points are subtracted from the maximum score.

(*5*) OSAs must have a System Security Plan (SSP) (CMMC security requirement CA.L2-3.12.4) in place at the time of assessment to describe each information system within the CMMC Assessment Scope. The absence of an up to date SSP at the time of the assessment would result in a finding that '*an assessment could not be completed due to incomplete information and noncompliance with 48 CFR 252.204-7012.*'

(*6*) For each NOT MET security requirement the OSA must have a POA&M in place. A POA&M addressing NOT MET security requirements is not a substitute for a completed requirement. Security requirements not implemented, whether described in a POA&M or not, is assessed as 'NOT MET.'

(*7*) Specialized Assets must be evaluated for their asset category per the CMMC scoping guidance for the level in question and handled accordingly as set forth in § 170.19.

(*8*) If an OSC previously received a favorable adjudication from the DoD CIO indicating that a security requirement is not applicable or that an alternative security measure is equally effective (in accordance with 48 CFR 252.204-7008 or 48 CFR 252.204-7012), the DoD CIO adjudication must be included in the system security plan to receive consideration during an assessment. A security requirement for which implemented security measures have been adjudicated by the DoD CIO as equally effective is assessed as MET if there have been no changes in the environment.

(ii) *CMMC Level 2 Scoring Table.* CMMC Level 2 scoring has been assigned based on the methodology set forth in table 1 to this paragraph (c)(2)(ii).

|                                                         CMMC Level 2 requirement categories                                                         |Point value  <br/>subtracted from  <br/>maximum score|
|-----------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|
|                                                            Basic Security Requirements:                                                             |                                                     |
|                          If not implemented, could lead to significant exploitation of the network, or exfiltration of CUI                          |                          5                          |
|                          If not implemented, has specific and confined effect on the security of the network and its data                           |                          3                          |
|                                                           Derived Security Requirements:                                                            |                                                     |
|                          If not implemented, could lead to significant exploitation of the network, or exfiltration of CUI                          |                          5                          |
|If not completely or properly implemented, could be partially effective and points adjusted depending on how the security requirement is implemented:|                       3 or 5                        |
|                                                    —Partially effective implementation—3 points.                                                    |                                                     |
|                                                  —Non-effective (not implemented at all)—5 points.                                                  |                                                     |
|                          If not implemented, has specific and confined effect on the security of the network and its data                           |                          3                          |
|                          If not implemented, has a limited or indirect effect on the security of the network and its data                           |                          1                          |

(3) *CMMC Level 3 assessment scoring methodology.* CMMC Level 3 scoring does not utilize varying values like the scoring for CMMC Level 2. All CMMC Level 3 security requirements use a value of one (1) point for each security requirement. As a result, the maximum score achievable for a Level 3 certification assessment is equivalent to the total number of the selected subset of NIST SP 800-172 Feb2021 security requirements for CMMC Level 3, see § 170.14(c)(4). The maximum score is reduced by one (1) point for each security requirement NOT MET. The CMMC Level 3 scoring methodology reflects the fact that all CMMC Level 2 security requirements must already be MET (for the Level 3 CMMC Assessment Scope). A maximum score on the Level 2 certification assessment is required to be eligible to initiate a Level 3 certification assessment. The Level 3 certification assessment score is equal to the number of CMMC Level 3 security requirements that are assessed as MET.