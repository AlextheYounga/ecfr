##### § 1311.145 Digitally signing the prescription with the individual practitioner's private key. #####

(a) An individual practitioner who has obtained a digital certificate as provided in § 1311.105 may digitally sign a controlled substance prescription using the private key associated with his digital certificate.

(b) The electronic prescription application must require the individual practitioner to complete a two-factor authentication protocol as specified in § 1311.140(a)(4) to use his private key.

(c) The electronic prescription application must digitally sign at least all information required under part 1306 of this chapter.

(d) The electronic prescription application must electronically archive the digitally signed record.

(e) A prescription that is digitally signed with a practitioner's private key may be transmitted to a pharmacy without the digital signature.

(f) If the electronic prescription is transmitted without the digital signature, the electronic prescription application must check the certificate revocation list of the certification authority that issued the practitioner's digital certificate. If the digital certificate is not valid, the electronic prescription application must not transmit the prescription. The certificate revocation list may be cached until the certification authority issues a new certificate revocation list.

(g) When the individual practitioner digitally signs a controlled substance prescription with the private key associated with his own digital certificate obtained as provided under § 1311.105, the electronic prescription application is not required to digitally sign the prescription using the application's private key.