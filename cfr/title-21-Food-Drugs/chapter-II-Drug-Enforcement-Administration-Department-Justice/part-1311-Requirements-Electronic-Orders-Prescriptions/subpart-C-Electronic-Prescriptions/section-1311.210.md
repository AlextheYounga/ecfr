##### § 1311.210 Archiving the initial record. #####

(a) Except as provided in paragraph (c) of this section, a copy of each electronic controlled substance prescription record that a pharmacy receives must be digitally signed by one of the following:

(1) The last intermediary transmitting the record to the pharmacy must digitally sign the prescription immediately prior to transmission to the pharmacy.

(2) The first pharmacy application that receives the electronic prescription must digitally sign the prescription immediately on receipt.

(b) If the last intermediary digitally signs the record, it must forward the digitally signed copy to the pharmacy.

(c) If a pharmacy receives a digitally signed prescription that includes the individual practitioner's digital signature, the pharmacy application must do the following:

(1) Verify the digital signature as provided in FIPS 186-3, as incorporated by reference in § 1311.08.

(2) Check the validity of the certificate holder's digital certificate by checking the certificate revocation list. The pharmacy may cache the CRL until it expires.

(3) Archive the digitally signed record. The pharmacy record must retain an indication that the prescription was verified upon receipt. No additional digital signature is required.