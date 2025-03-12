##### § 1311.55 Requirements for systems used to process digitally signed orders. #####

(a) A CSOS certificate holder and recipient of an electronic order may use any system to write, track, or maintain orders provided that the system has been enabled to process digitally signed documents and that it meets the requirements of paragraph (b) or (c) of this section.

(b) A system used to digitally sign Schedule I or II orders must meet the following requirements:

(1) The cryptographic module must be FIPS 140-2, Level 1 validated, as incorporated by reference in § 1311.08.

(2) The digital signature system and hash function must be compliant with FIPS 186-2 and FIPS 180-2, as incorporated by reference in § 1311.08.

(3) The private key must be stored on a FIPS 140-2 Level 1 validated cryptographic module using a FIPS-approved encryption algorithm, as incorporated by reference in § 1311.08.

(4) The system must use either a user identification and password combination or biometric authentication to access the private key. Activation data must not be displayed as they are entered.

(5) The system must set a 10-minute inactivity time period after which the certificate holder must reauthenticate the password to access the private key.

(6) For software implementations, when the signing module is deactivated, the system must clear the plain text private key from the system memory to prevent the unauthorized access to, or use of, the private key.

(7) The system must be able to digitally sign and transmit an order.

(8) The system must have a time system that is within five minutes of the official National Institute of Standards and Technology time source.

(9) The system must archive the digitally signed orders and any other records required in part 1305 of this chapter, including any linked data.

(10) The system must create an order that includes all data fields listed under § 1305.21(b) of this chapter.

(c) A system used to receive, verify, and create linked records for orders signed with a CSOS digital certificate must meet the following requirements:

(1) The cryptographic module must be FIPS 140-2, Level 1 validated, as incorporated by reference in § 1311.08.

(2) The digital signature system and hash function must be compliant with FIPS 186-2 and FIPS 180-2, as incorporated by reference in § 1311.08.

(3) The system must determine that an order has not been altered during transmission. The system must invalidate any order that has been altered.

(4) The system must validate the digital signature using the signer's public key. The system must invalidate any order in which the digital signature cannot be validated.

(5) The system must validate that the DEA registration number contained in the body of the order corresponds to the registration number associated with the specific certificate by separately generating the hash value of the registration number and certificate subject distinguished name serial number and comparing that hash value to the hash value contained in the certificate extension for the DEA registration number. If the hash values are not equal the system must invalidate the order.

(6) The system must check the Certificate Revocation List automatically and invalidate any order with a certificate listed on the Certificate Revocation List.

(7) The system must check the validity of the certificate and the Certification Authority certificate and invalidate any order that fails these validity checks.

(8) The system must have a time system that is within five minutes of the official National Institute of Standards and Technology time source.

(9) The system must check the substances ordered against the schedules that the registrant is allowed to order and invalidate any order that includes substances the registrant is not allowed to order.

(10) The system must ensure that an invalid finding cannot be bypassed or ignored and the order filled.

(11) The system must archive the order and associate with it the digital certificate received with the order.

(12) If a registrant sends reports on orders to DEA, the system must create a report in the format DEA specifies, as provided in § 1305.29 of this chapter.

(d) For systems used to process CSOS orders, the system developer or vendor must have an initial independent third-party audit of the system and an additional independent third-party audit whenever the signing or verifying functionality is changed to determine whether it correctly performs the functions listed under paragraphs (b) and (c) of this section. The system developer must retain the most recent audit results and retain the results of any other audits of the software completed within the previous two years.