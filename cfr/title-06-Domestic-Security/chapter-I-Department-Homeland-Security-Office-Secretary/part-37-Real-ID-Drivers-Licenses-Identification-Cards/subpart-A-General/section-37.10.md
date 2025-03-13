##### § 37.10 Application criteria for issuance of temporary waiver for mDLs; audit report; waiver application guidance. #####

(a) *Application criteria.* A State requesting a certificate of waiver must establish in its application that the mDLs for which the State seeks a waiver are issued with controls sufficient to resist compromise and fraud attempts, provide privacy protections sufficient to safeguard an mDL holder's identity data, and provide interoperability for secure acceptance by Federal agencies under the terms of a certificate of waiver. To demonstrate compliance with such requirements, a State must provide information, documents, and/or data sufficient to explain the means, which includes processes, methodologies, or policies, that the State has implemented to comply with requirements in this paragraph (a).

(1) *Provisioning.* For both remote and in-person provisioning, a State must explain the means it uses to address or perform the following—

(i) *Data encryption.* Securely encrypt mDL data and an mDL holder's Personally Identifiable Information when such data is transferred during provisioning, and when stored on the State's system(s) and on mDL holders' mobile devices.

(ii) *Escalated review.* Review repeated failed attempts at provisioning, resolve such failures, and establish criteria to determine when the State will deny provisioning an mDL to a particular mDL applicant.

(iii) *Authentication.* Confirm that an mDL applicant has control over the mobile device to which an mDL is being provisioned at the time of provisioning.

(iv) *Device identification keys.* Confirm that the mDL applicant possesses the mDL device private key bound to the mDL during provisioning.

(v) *User identity verification.* Prevent an individual from falsely matching with the licensing agency's records, including portrait images, of other individuals.

(vi) *Applicant presentation.* Prevent physical and digital presentation attacks by detecting the liveness of an individual and any alterations to the individual's appearance during remote and in-person provisioning.

(vii) *DHS\_compliance data element.* Set the value of data element “DHS\_compliance”, as required by paragraph (a)(4)(ii) of this section, to correspond to the REAL ID compliance status of the underlying physical driver's license or identification card that a State has issued to an mDL holder as follows—

(A) “F” if the underlying card is REAL ID-compliant, or as otherwise required by AAMVA Mobile Driver's License (mDL) Implementation Guidelines, Section 3.2 (incorporated by reference; see § 37.4); or

(B) “N” if the underlying card is not REAL ID-compliant.

(viii) *Data record.* Issue mDLs using data, including portrait image, of an individual that matches corresponding data in the database of the issuing State's driver's licensing agency for that individual.

(ix) *Records retention.* Manage mDL records and related records, consistent with requirements set forth in AAMVA Mobile Driver's License (mDL) Implementation Guidelines (incorporated by reference; see § 37.4).

(2) *Issuance.* A State must explain the means it uses to manage the creation, issuance, use, revocation, and destruction of the State's certificate systems and keys in full compliance with the requirements set forth in appendix A to this subpart.

(3) *Privacy.* A State must explain the means it uses to protect Personally Identifiable Information during processing, storage, and destruction of mDL records and provisioning records.

(4) *Interoperability.* A State must explain the means it uses to issue mDLs that are interoperable with ISO/IEC 18013-5:2021(E) and the “AAMVA mDL data element set” defined in the AAMVA Mobile Driver's License (mDL) Implementation Guidelines (incorporated by reference; see § 37.4) as follows:

(i) A State must issue mDLs using the data model defined in ISO/IEC 18103-5:2021(E) section 7 (incorporated by reference; see § 37.4), using the document type “org.iso.18013.5.1.mDL”, and using the name space “org.iso.18013.5.1”. States must include the following mDL data elements defined as mandatory in ISO/IEC 18103-5:2021(E) Table 5: “family\_name”, “given\_name”, “birth\_date”, “issue\_date”, “expiry\_date”, “issuing\_authority”, “document\_number”, “portrait”, and must include the following mDL data elements defined as optional in Table 5: “sex”, “resident\_address”, “portrait\_capture\_date”, “signature\_usual\_mark”.

(ii) States must use the AAMVA mDL data element set defined in AAMVA Mobile Driver's License (mDL) Implementation Guidelines, Section 3.2 (incorporated by reference; see § 37.4), using the namespace “org.iso.18013.5.1.aamva” and must include the following data elements in accordance with the AAMVA mDL Implementation Guidelines: “DHS\_compliance”, and “DHS\_temporary\_lawful\_status”.

(iii) States must use only encryption algorithms, secure hashing algorithms, and digital signing algorithms as defined by ISO/IEC 18103-5:2021(E), section 9 and Annex B (incorporated by reference; see § 37.4), and which are included in the following NIST Federal Information Processing Standards (FIPS): NIST FIPS PUB 180-4, NIST FIPS PUB 186-5, NIST FIPS PUB 197-upd1, NIST FIPS PUB 198-1, and NIST FIPS PUB 202 (incorporated by reference; see § 37.4).

(b) *Audit report.* States must include with their applications a report of an audit that verifies the information provided under paragraph (a) of this section.

(1) The audit must be conducted by a recognized independent entity, which may be an entity that is employed or contracted by a State and independent of the State's driver's licensing agency,—

(i) Holding an active Certified Public Accountant license in the issuing State;

(ii) Experienced with information systems security audits;

(iii) Accredited by the issuing State; and

(iv) Holding a current and active American Institute of Certified Public Accountants (AICPA) Certified Information Technology Professional (CITP) credential or ISACA (F/K/A Information Systems Audit and Control Association) Certified Information System Auditor (CISA) certification.

(2) States must include information about the entity conducting the audit that identifies—

(i) Any potential conflicts of interest; and

(ii) Mitigation measures or other divestiture actions taken to avoid conflicts of interest.

(c) *Waiver application guidance*—(1) *Generally.* TSA will publish “Mobile Driver's License Waiver Application Guidance” to facilitate States' understanding of the requirements set forth in paragraph (a) of this section. The non-binding Guidance will include recommendations and examples of possible implementations for illustrative purposes only. TSA will publish the Guidance on the REAL ID website at *www.tsa.gov/real-id/mDL.*

(2) *Updates.* TSA may periodically update its Waiver Application Guidance as necessary to provide additional information or recommendations to mitigate evolving threats to security, privacy, or data integrity. TSA will publish a notification in the Federal Register advising that updated Guidance is available, and TSA will publish the updated Guidance at *www.tsa.gov/real-id/mDL* and provide a copy to all States that have applied for or been issued a certificate or waiver.

[89 FR 85377, Oct. 25, 2024]