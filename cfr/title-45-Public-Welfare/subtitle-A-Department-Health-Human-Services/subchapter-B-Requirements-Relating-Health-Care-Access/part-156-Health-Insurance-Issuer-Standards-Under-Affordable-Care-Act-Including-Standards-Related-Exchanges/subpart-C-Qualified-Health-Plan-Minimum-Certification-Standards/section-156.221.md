##### § 156.221 Access to and exchange of health data and plan information. #####

(a) *Application Programming Interface to support enrollees.* Subject to paragraph (h) of this section, a QHP issuer on a Federally-Facilitated Exchange must implement and maintain a standards-based Application Programming Interface (API) that permits third-party applications to retrieve, with the approval and at the direction of a current individual enrollee or the enrollee's personal representative, data specified in paragraph (b) of this section through the use of common technologies and without special effort from the enrollee.

(b) *Accessible content.* (1) A QHP issuer on a Federally-facilitate Exchange must make the following information accessible to its current enrollees or the enrollee's personal representative through the API described in paragraph (a) of this section:

(i) Data concerning adjudicated claims, including claims data for payment decisions that may be appealed, were appealed, or are in the process of appeal, and provider remittances and enrollee cost-sharing pertaining to such claims, no later than one (1) business day after a claim is processed;

(ii) Encounter data from capitated providers, no later than one (1) business day after data concerning the encounter is received by the QHP issuer;

(iii) All data classes and data elements included in a content standard in 45 CFR 170.213 that are maintained by the Qualified Health Plan (QHP) issuer no later than 1 business day after the QHP issuer receives the data; and

(iv) For plan years beginning on or after January 1, 2027, the information in paragraph (b)(1)(iv)(A) of this section about prior authorizations for items and services (excluding drugs, as defined in paragraph (b)(1)(v) of this section), according to the timelines in paragraph (b)(1)(iv)(B) of this section.

(A) The prior authorization request and decision, including all of the following, as applicable:

(*1*) The prior authorization status.

(*2*) The date the prior authorization was approved or denied.

(*3*) The date or circumstance under which the prior authorization ends.

(*4*) The items and services approved.

(*5*) If denied, a specific reason why the request was denied.

(*6*) Related structured administrative and clinical documentation submitted by a provider.

(B) The information in paragraph (b)(1)(iv)(A) of this section must—

(*1*) Be accessible no later than 1 business day after the QHP issuer receives a prior authorization request;

(*2*) Be updated no later than 1 business day after any status change; and

(*3*) Continue to be accessible for the duration that the authorization is active and at least 1 year after the prior authorization's last status change.

(v) Drugs are defined for the purposes of paragraph (b)(1)(iv) of this section as any and all drugs covered by the QHP issuer.

(2) [Reserved]

(c) *Technical requirements.* A QHP issuer on a Federally-facilitated Exchange implementing an API under paragraph (a) of this section:

(1) Must implement and maintain API technology conformant with 45 CFR 170.215(a)(1), (b)(1)(i), (c)(1), and (e)(1);

(2) Must conduct routine testing and monitoring, and update as appropriate, to ensure the API functions properly, including assessments to verify the API is fully and successfully implementing privacy and security features such as, but not limited to, those required to comply with HIPAA privacy and security requirements in parts 160 and 164, 42 CFR parts 2 and 3, and other applicable law protecting privacy and security of individually identifiable data;

(3) Must comply with the content and vocabulary standard requirements in paragraphs (c)(3)(i) and (ii) of this section, as applicable, to the data type or data element, unless alternate standards are required by other applicable law:

(i) Content and vocabulary standards at 45 CFR 170.213 where such are applicable to the data type or element, as appropriate; and

(ii) Content and vocabulary standards at part 162 of this subchapter and 42 CFR 423.160 where required by law, or where such standards are applicable to the data type or element, as appropriate.

(4) May use an updated version of any standard or all standards required under paragraphs (c)(1) or (3) of this section, where:

(i) Use of the updated version of the standard is required by other applicable law, or

(ii) Use of the updated version of the standard is not prohibited under other applicable law, provided that:

(A) For content and vocabulary standards other than those at 45 CFR 170.213, the Secretary has not prohibited use of the updated version of a standard for purposes of this section or part 170 of this subchapter;

(B) For standards at 45 CFR 170.213 and 45 CFR 170.215, the National Coordinator has approved the updated version for use in the ONC Health IT Certification Program; and

(C) Using the updated version of the standard, implementation guide, or specification does not disrupt an end user's ability to access the data specified in paragraph (b) of this section or §§ 156.221, 156.222, and 156.223 through the required APIs.

(d) *Documentation requirements for APIs.* For each API implemented in accordance with paragraph (a) of this section, a QHP issuer on a Federally-Facilitated Exchange must make publicly accessible, by posting directly on its website and/or via publicly accessible hyperlink(s), complete accompanying documentation that contains, at a minimum the information listed in this paragraph. For the purposes of this section, “publicly accessible” means that any person using commonly available technology to browse the internet could access the information without any preconditions or additional steps, such as a fee for access to the documentation; a requirement to receive a copy of the material via email; a requirement to register or create an account to receive the documentation; or a requirement to read promotional material or agree to receive future communications from the organization making the documentation available;

(1) API syntax, function names, required and optional parameters supported and their data types, return variables and their types/structures, exceptions and exception handling methods and their returns;

(2) The software components and configurations an application must use in order to successfully interact with the API and process its response(s); and

(3) All applicable technical requirements and attributes necessary for an application to be registered with any authorization server(s) deployed in conjunction with the API.

(e) *Denial or discontinuation of access to the API.* A QHP issuer on a Federally-Facilitated Exchange may deny or discontinue any third party application's connection to the API required under paragraph (a) of this section if the QHP issuer:

(1) Reasonably determines, consistent with its security risk analysis under 45 CFR part 164 subpart C, that allowing an application to connect or remain connected to the API would present an unacceptable level of risk to the security of personally identifiable information, including protected health information, on the QHP issuer's systems; and

(2) Makes this determination using objective, verifiable criteria that are applied fairly and consistently across all apps and developers through which parties seek to access electronic health information, as defined in 45 CFR 171.102, including but not limited to criteria that rely on automated monitoring and risk mitigation tools.

(f) *Reporting on Patient Access API usage.* Beginning in 2026, by March 31 following any calendar year that it offers a QHP on a Federally-facilitated Exchange, a QHP issuer must report to CMS the following metrics, in the form of aggregated, de-identified data, for the previous calendar year at the issuer level in the form and manner specified by the Secretary:

(1) The total number of unique enrollees whose data are transferred via the Patient Access API to a health app designated by the enrollee.

(2) The total number of unique enrollees whose data are transferred more than once via the Patient Access API to a health app designated by the enrollee.

(g) *Enrollee resources regarding privacy and security.* A QHP issuer on a Federally-facilitated Exchange must provide in an easily accessible location on its public website and through other appropriate mechanisms through which it ordinarily communicates with current and former enrollees seeking to access their health information held by the QHP issuer, educational resources in non-technical, simple and easy-to-understand language explaining at a minimum:

(1) General information on steps the individual may consider taking to help protect the privacy and security of their health information, including factors to consider in selecting an application including secondary uses of data, and the importance of understanding the security and privacy practices of any application to which they will entrust their health information; and

(2) An overview of which types of organizations or individuals are and are not likely to be HIPAA covered entities, the oversight responsibilities of the Office for Civil Rights (OCR) and the Federal Trade Commission (FTC), and how to submit a complaint to:

(i) The HHS Office for Civil Rights (OCR); and

(ii) The Federal Trade Commission (FTC).

(h) *Exception.* (1) If a plan applying for QHP certification to be offered through a Federally-facilitated Exchange believes it cannot satisfy the requirements in paragraphs (a) through (g) of this section, the issuer must include as part of its QHP application a narrative justification describing the reasons why the plan cannot reasonably satisfy the requirements for the applicable plan year, the impact of non-compliance upon enrollees, the current or proposed means of providing health information to enrollees, and solutions and a timeline to achieve compliance with the requirements of this section.

(2) The Federally-facilitated Exchange may grant an exception to the requirements in paragraphs (a) through (g) of this section if the Exchange determines that making such health plan available through such Exchange is in the interests of qualified individuals in the State or States in which such Exchange operates.

(i) *Applicability.* A QHP issuer on an individual market Federally-facilitated Exchange, not including QHP issuers offering only stand-alone dental plans, must comply with the requirements in paragraphs (a) through (e) and (g) of this section beginning with plan years beginning on or after January 1, 2021, and with the requirements in paragraph (f) of this section beginning in 2026, with regard to data:

(1) With a date of service on or after January 1, 2016; and

(2) That are maintained by the QHP issuer for enrollees in QHPs.

[85 FR 25638, May 1, 2020, as amended at 89 FR 8986, Feb. 8, 2024]