##### § 431.60 Beneficiary access to and exchange of data. #####

(a) *Application Programming Interface to support Medicaid beneficiaries.* A State must implement and maintain a standards-based Application Programming Interface (API) that permits third-party applications to retrieve, with the approval and at the direction of a current beneficiary or the beneficiary's personal representative, data specified in paragraph (b) of this section through the use of common technologies and without special effort from the beneficiary.

(b) *Accessible content.* A State must make the following information accessible to its current beneficiaries or the beneficiary's personal representative through the API described in paragraph (a) of this section:

(1) Data concerning adjudicated claims, including claims data for payment decisions that may be appealed, were appealed, or are in the process of appeal, and provider remittances and beneficiary cost-sharing pertaining to such claims, no later than one (1) business day after a claim is processed;

(2) Encounter data no later than one (1) business day after receiving the data from providers, other than MCOs, PIHPs, and PAHPs, compensated on the basis of capitation payments;

(3) All data classes and data elements included in a content standard in 45 CFR 170.213 that are maintained by the State no later than 1 business day after the State receives the data; and

(4) Information about covered outpatient drugs and updates to such information, including, where applicable, preferred drug list information, no later than one (1) business day after the effective date of any such information or updates to such information.

(5) Beginning January 1, 2027, the information in paragraph (b)(5)(i) of this section about prior authorizations for items and services (excluding drugs as defined in paragraph (b)(6) of this section), according to the timelines in paragraph (b)(5)(ii) of this section.

(i) The prior authorization request and decision, including all of the following, as applicable:

(A) The prior authorization status.

(B) The date the prior authorization was approved or denied.

(C) The date or circumstance under which the prior authorization ends.

(D) The items and services approved.

(E) If denied, a specific reason why the request was denied.

(F) Related structured administrative and clinical documentation submitted by a provider.

(ii) The information in paragraph (b)(5)(i) of this section must—

(A) Be accessible no later than 1 business day after the State receives a prior authorization request;

(B) Be updated no later than 1 business day after any status change; and

(C) Continue to be accessible for the duration that the authorization is active and at least 1 year after the prior authorization's last status change.

(6) Drugs are defined for the purposes of paragraph (b)(5) of this section as any and all drugs covered by the State.

(c) *Technical requirements.* A State implementing an API under paragraph (a) of this section:

(1) Must implement and maintain API technology conformant with 45 CFR 170.215(a)(1), (b)(1)(i), (c)(1), and (e)(1);

(2) Must conduct routine testing and monitoring, and update as appropriate, to ensure the API functions properly, including assessments to verify that the API is fully and successfully implementing privacy and security features such as, but not limited to, those required to comply with HIPAA privacy and security requirements in 45 CFR parts 160 and 164, 42 CFR parts 2 and 3, and other applicable law protecting the privacy and security of individually identifiable data;

(3) Must comply with the content and vocabulary standards requirements in paragraphs (c)(3)(i) and (ii) of this section, as applicable to the data type or data element, unless alternate standards are required by other applicable law:

(i) Content and vocabulary standards at 45 CFR 170.213 where such standards are applicable to the data type or element, as appropriate; and

(ii) Content and vocabulary standards at 45 CFR part 162 and § 423.160 of this chapter where required by law, or where such standards are applicable to the data type or element, as appropriate.

(4) May use an updated version of any standard or all standards required under paragraph (c)(1) or (3) of this section, where:

(i) Use of the updated version of the standard is required by other applicable law, or

(ii) Use of the updated version of the standard is not prohibited under other applicable law, provided that:

(A) For content and vocabulary standards other than those at 45 CFR 170.213, the Secretary has not prohibited use of the updated version of a standard for purposes of this section or 45 CFR part 170;

(B) For standards at 45 CFR 170.213 and 45 CFR 170.215, the National Coordinator has approved the updated version for use in the ONC Health IT Certification Program; and

(C) Using the updated version of the standard, implementation guide, or specification does not disrupt an end user's ability to access the data specified in paragraph (b) of this section or §§ 431.61, 431.70, and 431.80, through the required APIs.

(d) *Documentation requirements for APIs.* For each API implemented in accordance with paragraph (a) of this section, a State must make publicly accessible, by posting directly on its website or via publicly accessible hyperlink(s), complete accompanying documentation that contains, at a minimum the information listed in this paragraph. For the purposes of this section, “publicly accessible” means that any person using commonly available technology to browse the internet could access the information without any preconditions or additional steps, such as a fee for access to the documentation; a requirement to receive a copy of the material via email; a requirement to register or create an account to receive the documentation; or a requirement to read promotional material or agree to receive future communications from the organization making the documentation available;

(1) API syntax, function names, required and optional parameters supported and their data types, return variables and their types/structures, exceptions and exception handling methods and their returns;

(2) The software components and configurations an application must use in order to successfully interact with the API and process its response(s); and

(3) All applicable technical requirements and attributes necessary for an application to be registered with any authorization server(s) deployed in conjunction with the API.

(e) *Denial or discontinuation of access to the API.* A State may deny or discontinue any third-party application's connection to the API required under paragraph (a) of this section if the State:

(1) Reasonably determines, consistent with its security risk analysis under 45 CFR part 164 subpart C, that allowing an application to connect or remain connected to the API would present an unacceptable level of risk to the security of protected health information on the State's systems; and

(2) Makes this determination using objective, verifiable criteria that are applied fairly and consistently across all apps and developers through which parties seek to access electronic health information, as defined in 45 CFR 171.102, including but not limited to criteria that rely on automated monitoring and risk mitigation tools.

(f) *Reporting on Patient Access API usage.* Beginning in 2026, by March 31 of each year, a State must report to CMS the following metrics, in the form of aggregated, de-identified data, for the previous calendar year at the State level in the form and manner specified by the Secretary:

(1) The total number of unique beneficiaries whose data are transferred via the Patient Access API to a health app designated by the beneficiary; and

(2) The total number of unique beneficiaries whose data are transferred more than once via the Patient Access API to a health app designated by the beneficiary.

(g) *Data availability.* (1) The State must comply with the requirements in paragraph (a) through (f) of this section beginning January 1, 2021 with regard to data:

(i) With a date of service on or after January 1, 2016; and

(ii) That are maintained by the State.

(2) [Reserved]

(h) *Applicability.* A State must comply with the requirements in paragraphs (a) through (e) and (g) of this section beginning January 1, 2021, and with the requirements in paragraph (f) of this section beginning in 2026, with regard to data:

(1) With a date of service on or after January 1, 2016; and

(2) That are maintained by the State.

[85 FR 25634, May 1, 2020, as amended at 89 FR 8977, Feb. 8, 2024]