##### § 1311.120 Electronic prescription application requirements. #####

(a) A practitioner may only use an electronic prescription application that meets the requirements in paragraph (b) of this section to issue electronic controlled substance prescriptions.

(b) The electronic prescription application must meet the requirements of this subpart including the following:

(1) The electronic prescription application must do the following:

(i) Link each registrant, by name, to at least one DEA registration number.

(ii) Link each practitioner exempt from registration under § 1301.22(c) of this chapter to the institutional practitioner's DEA registration number and the specific internal code number required under § 1301.22(c)(5) of this chapter.

(2) The electronic prescription application must be capable of the setting of logical access controls to limit permissions for the following functions:

(i) Indication that a prescription is ready for signing and signing controlled substance prescriptions.

(ii) Creating, updating, and executing the logical access controls for the functions specified in paragraph (b)(2)(i) of this section.

(3) Logical access controls must be set by individual user name or role. If the application sets logical access control by role, it must not allow an individual to be assigned the role of registrant unless that individual is linked to at least one DEA registration number as provided in paragraph (b)(1) of this section.

(4) The application must require that the setting and changing of logical access controls specified under paragraph (b)(2) of this section involve the actions of two individuals as specified in §§ 1311.125 or 1311.130. Except for institutional practitioners, a practitioner authorized to sign controlled substance prescriptions must approve logical access control entries.

(5) The electronic prescription application must accept two-factor authentication that meets the requirements of § 1311.115 and require its use for signing controlled substance prescriptions and for approving data that set or change logical access controls related to reviewing and signing controlled substance prescriptions.

(6) The electronic prescription application must be capable of recording all of the applicable information required in part 1306 of this chapter for the controlled substance prescription.

(7) If a practitioner has more than one DEA registration number, the electronic prescription application must require the practitioner or his agent to select the DEA registration number to be included on the prescription.

(8) The electronic prescription application must have a time application that is within five minutes of the official National Institute of Standards and Technology time source.

(9) The electronic prescription application must present for the practitioner's review and approval all of the following data for each controlled substance prescription:

(i) The date of issuance.

(ii) The full name of the patient.

(iii) The drug name.

(iv) The dosage strength and form, quantity prescribed, and directions for use.

(v) The number of refills authorized, if applicable, for prescriptions for Schedule III, IV, and V controlled substances.

(vi) For prescriptions written in accordance with the requirements of § 1306.12(b) of this chapter, the earliest date on which a pharmacy may fill each prescription.

(vii) The name, address, and DEA registration number of the prescribing practitioner.

(viii) The statement required under § 1311.140(a)(3).

(10) The electronic prescription application must require the prescribing practitioner to indicate that each controlled substance prescription is ready for signing. The electronic prescription application must not permit alteration of the DEA elements after the practitioner has indicated that a controlled substance prescription is ready to be signed without requiring another review and indication of readiness for signing. Any controlled substance prescription not indicated as ready to be signed shall not be signed or transmitted.

(11) While the information required by paragraph (b)(9) of this section and the statement required by § 1311.140(a)(3) remain displayed, the electronic prescription application must prompt the prescribing practitioner to authenticate to the application, using two-factor authentication, as specified in § 1311.140(a)(4), which will constitute the signing of the prescription by the practitioner for purposes of § 1306.05(a) and (e) of this chapter.

(12) The electronic prescription application must not permit a practitioner other than the prescribing practitioner whose DEA number (or institutional practitioner DEA number and extension data for the individual practitioner) is listed on the prescription as the prescribing practitioner and who has indicated that the prescription is ready to be signed to sign the prescription.

(13) Where a practitioner seeks to prescribe more than one controlled substance at one time for a particular patient, the electronic prescription application may allow the practitioner to sign multiple prescriptions for a single patient at one time using a single invocation of the two-factor authentication protocol provided the following has occurred: The practitioner has individually indicated that each controlled substance prescription is ready to be signed while the information required by paragraph (b)(9) of this section for each such prescription is displayed along with the statement required by § 1311.140(a)(3).

(14) The electronic prescription application must time and date stamp the prescription when the signing function is used.

(15) When the practitioner uses his two-factor authentication credential as specified in § 1311.140(a)(4), the electronic prescription application must digitally sign at least the information required by part 1306 of this chapter and electronically archive the digitally signed record. If the practitioner signs the prescription with his own private key, as provided in § 1311.145, the electronic prescription application must electronically archive a copy of the digitally signed record, but need not apply the application's digital signature to the record.

(16) The digital signature functionality must meet the following requirements:

(i) The cryptographic module used to digitally sign the data elements required by part 1306 of this chapter must be at least FIPS 140-2 Security Level 1 validated. FIPS 140-2 is incorporated by reference in § 1311.08.

(ii) The digital signature application and hash function must comply with FIPS 186-3 and FIPS 180-3, as incorporated by reference in § 1311.08.

(iii) The electronic prescription application's private key must be stored encrypted on a FIPS 140-2 Security Level 1 or higher validated cryptographic module using a FIPS-approved encryption algorithm. FIPS 140-2 is incorporated by reference in § 1311.08.

(iv) For software implementations, when the signing module is deactivated, the application must clear the plain text password from the application memory to prevent the unauthorized access to, or use of, the private key.

(17) Unless the digital signature created by an individual practitioner's private key is being transmitted to the pharmacy with the prescription, the electronic prescription application must include in the data file transmitted an indication that the prescription was signed by the prescribing practitioner.

(18) The electronic prescription application must not transmit a controlled substance prescription unless the signing function described in § 1311.140(a)(4) has been used.

(19) The electronic prescription application must not allow alteration of any of the information required by part 1306 of this chapter after the prescription has been digitally signed. Any alteration of the information required by part 1306 of this chapter after the prescription is digitally signed must cancel the prescription.

(20) The electronic prescription application must not allow transmission of a prescription that has been printed.

(21) The electronic prescription application must allow printing of a prescription after transmission only if the printed prescription is clearly labeled as a copy not for dispensing. The electronic prescription application may allow printing of prescription information if clearly labeled as being for informational purposes. The electronic prescription application may transfer such prescription information to medical records.

(22) If the transmission of an electronic prescription fails, the electronic prescription application may print the prescription. The prescription must indicate that it was originally transmitted electronically to, and provide the name of, a specific pharmacy, the date and time of transmission, and that the electronic transmission failed.

(23) The electronic prescription application must maintain an audit trail of all actions related to the following:

(i) The creation, alteration, indication of readiness for signing, signing, transmission, or deletion of a controlled substance prescription.

(ii) Any setting or changing of logical access control permissions related to the issuance of controlled substance prescriptions.

(iii) Notification of a failed transmission.

(iv) Auditable events as specified in § 1311.150.

(24) The electronic prescription application must record within each audit record the following information:

(i) The date and time of the event.

(ii) The type of event.

(iii) The identity of the person taking the action, where applicable.

(iv) The outcome of the event (success or failure).

(25) The electronic prescription application must conduct internal audits and generate reports on any of the events specified in § 1311.150 in a format that is readable by the practitioner. Such internal audits may be automated and need not require human intervention to be conducted.

(26) The electronic prescription application must protect the stored audit records from unauthorized deletion. The electronic prescription application shall prevent modifications to the audit records.

(27) The electronic prescription application must do the following:

(i) Generate a log of all controlled substance prescriptions issued by a practitioner during the previous calendar month and provide the log to the practitioner no later than seven calendar days after that month.

(ii) Be capable of generating a log of all controlled substance prescriptions issued by a practitioner for a period specified by the practitioner upon request. Prescription information available from which to generate the log must span at least the previous two years.

(iii) Archive all logs generated.

(iv) Ensure that all logs are easily readable or easily rendered into a format that a person can read.

(v) Ensure that all logs are sortable by patient name, drug name, and date of issuance of the prescription.

(28) Where the electronic prescription application is required by this part to archive or otherwise maintain records, it must retain such records electronically for two years from the date of the record's creation and comply with all other requirements of § 1311.305.