##### § 274.8 Functional and technical EBT system requirements. #####

(a) *Functional requirements.* The State agency shall ensure that the EBT system is capable of performing the following functional requirements prior to implementation:

(1) *Authorizing household benefits.* (i) Issuing and replacing EBT cards to eligible households;

(ii) Permitting eligible households to select a personal identification number (PINs) at least four digits in length;

(iii) Establishing benefit cards and accounts with the central computer database;

(iv) Maintaining the master household issuance record file data and current authorization information;

(v) Training households and other users in system usage;

(vi) Authorizing benefit delivery;

(vii) Posting benefits to each household's account for regular and supplemental issuances;

(viii) Providing households with access to information on benefit availability;

(ix) Ensuring the privacy of household data and providing benefit and data security;

(x) Inventorying and securing accountable documents; and

(xi) Zeroing out benefit accounts and other account authorization activity.

(2) *Providing food benefits to households.* (i) Verifying the identity of authorized households or authorized household representatives at issuance terminals or POS;

(ii) Verifying the PIN and/or PIN off-set, primary account number (PAN), terminal identification number and retailer identification number;

(iii) Determining the sufficiency of the household's account balance in order to debit or credit household benefit accounts at the point of sale;

(iv) Sending messages authorizing or rejecting purchases;

(v) Providing back-up purchase procedures when the system is unavailable;

(vi) Ensuring that benefits are available and carried over from month-to-month.

(vii) Responding to issuance problems in a timely manner.

(3) *Crediting retailers and financial institutions for redeemed benefits.* (i) Verifying electronic transactions flowing to or from participating retailers' bank accounts;

(ii) Creating and maintaining a file containing the individual records of EBT transactions;

(iii) Totaling all credits accumulated by each retailer;

(iv) Providing balance information to retailers or third party processors from individual POS terminals, as needed;

(v) Providing each retailer information on total deposits in the system on a daily basis;

(vi) Preparing a daily tape in a National Automated Clearinghouse format or other process approved by FNS with information on benefits redeemed for each retailer and in summary;

(vii) Transmitting the ACH tape to a financial institution for transmission through the ACH or other method approved by FNS;

(viii) Transferring the information on the ACH tape or other process approved by FNS containing daily redemption activity of each retailer to the FNS Minneapolis Computer Support Center at least once weekly. Transmittal may be by tape, disc, remote job entry or other means acceptable to FNS.

(4) Managing retailer participation in accordance with § 274.3(e).

(b) *Performance and technical standards.* The State agency shall ensure that EBT systems comply with POS technical standards established by the American National Standards Institute (ANSI) or International Organization for Standardization (ISO) where applicable. This includes the draft EBT ISO 8583 Processor Interface Technical Specifications contained in the ANSI standards, which delineates a standard message format for retailers and third parties. In addition, the State agency shall ensure that the EBT system meets performance and technical standards in the areas of system processing speeds, system availability and reliability, system security, system ease-of-use, minimum card and terminal requirements, performance bonding, and a minimum transaction set. With prior written approval from FNS, the State agency may utilize the prevailing industry performance standards in its region in lieu of those identified in this section. The standards shall be included in all requests for proposals and contracts.

(1) *System processing speeds.* (i) For leased line systems, 98 percent of EBT transactions shall be processed within 10 seconds or less and all EBT transactions shall be processed within 15 seconds. Leased line systems rent telecommunications carriers specifically to connect to the central authorizing computer. For dial-up systems, 95 percent of the EBT transactions shall be processed within 15 seconds or less and all EBT transactions shall be processed within 20 seconds or less. Dial-up systems utilize existing telecommunications lines to dial up and connect to the central computer at the time of the transaction. Processing response time shall be measured at the POS terminal from the time the ‘enter’ or ‘send’ key is pressed to the receipt and display of authorization or disapproval information. Third party processors, as defined in paragraph (h)(5) of this section, shall be required by the State agency to comply with the same processing response times required of the primary processor.

(ii) The EBT system shall provide re-ports, as determined by the State agency, that document transaction processing response time and the number and type of problematic transactions that could not be processed within the standard response time.

(2) *System availability and reliability.* (i) The EBT system central computer shall be available 99.9 percent of scheduled up-time, 24 hours a day, 7 days per week. Scheduled up-time shall mean the time the database is available for transactions excluding scheduled downtime for routine maintenance. The total system, including the system's central computer, any network or intermediate processing facilities and cardholder authorization processors, shall be available 98 percent of scheduled up-time, 24 hours per day, 7 days per week. Scheduled downtime for routine maintenance shall occur during non-peak transaction periods. State certification procedures shall determine whether intermediate processing facilities and cardholder authorization processors are capable of complying with system availability standards prescribed herein prior to permitting the interface with the central computer system.

(ii) The system central computer shall permit no more than 2 inaccurate EBT transactions for every 10,000 EBT transactions processed. The transactions to be included in measuring system accuracy shall include all types of SNAP transactions permitted at POS terminals and processed through the host computer, manual transactions entered into the system, credits to household accounts, and funds transfers to retailer accounts.

(iii) Reconciliation reports and other information regarding problematic transactions shall be made available to the State agency by the system operator, individual retailers, households or financial institutions as appropriate. Reports on problematic transactions, including inaccurate transactions shall be delineated by the source of the problem such as card failure, POS terminal failure, interruption of telecommunications, or other component failure. Errors shall be resolved in a timely manner.

(3) *System security.* As an addition to or component of the Security Program required of Automated Data Processing systems prescribed under § 277.18(m) of this chapter, the State agency shall ensure that the following EBT security requirements are established:

(i) Storage and control measures to control blank unissued EBT cards and PINs, and unused or spare POS devices;

(ii) Measures to ensure communication access control. Communication controls shall include the transmission of transaction data and issuance information from POS terminals to work-stations and terminals at the data processing center. The following specific security measures shall be included, as appropriate, in the system design documentation, operating procedures or the State agency Security Program:

(A) Computer hardware controls that ensure acceptance of data from authorized terminals only. These controls shall include the use of mechanisms such as retailer identification codes, terminal identifiers and user identification codes, and/or other mechanisms and procedures recognized by the industry;

(B) Software controls, placed at either the terminal or central computer or both, that establish separate control files containing lists of authorized retailers, terminal identifying codes, and user access and identification codes. EBT system software controls shall include separate checks against the control files in order to validate each transaction prior to authorization and limiting the number of unsuccessful PIN attempts that can be made utilizing standard industry practices before the card is deactivated;

(C) Communications network security that utilizes the Data Encryption Standard algorithm to encrypt the PIN, at a minimum, from the point of entry. Other security may include authentication codes and check-sum digits, in combination with data encoded on the magnetic stripe such as the PIN and/or PIN offset, to ensure data security during electronic transmission. Any of the network security measures may be utilized together or separately and may be applied at the terminal or central computer as indicated in the approved system design to ensure communications control;

(D) Manual procedures that provide for secure access to the system with minimal risk to household or retailer accounts. Manual procedures may include the utilization of manager identification codes in obtaining telephonic authorization from the central computer system; requirements for separate entry with audio response unit verification and authorization number; and/or the utilization of 24 hour hotline telephone numbers to authorize transactions.

(iii) Message validation shall include but shall not be limited to:

(A) Message format checks for completeness of the message, correct order of data, existence of control characters, number and size of data fields and appropriate format standards as specified in the approved system design;

(B) Range checks for acceptable date fields, number and valid account numbers, purchase and refund upper limitations in order to prevent and control damage to the system accounts;

(C) Reversal of messages that are not fully processed and recorded.

(iv) Administrative and operational procedures shall ensure that:

(A) Functions affecting an account balance are separated or dually controlled during processing and when requesting Federal reimbursement through a concentrator bank under the provisions of paragraph (i) of this section. These functions may include but are not limited to the set up of accounts, transmittal of funds to and from accounts, access to files to change account records, and transmittal of retailer deposits to the ACH network or other means approved by FNS for crediting retailer bank accounts;

(B) Passwords, identity codes or other security procedures must be utilized by State agency or local personnel and at data processing centers;

(C) Software programming changes shall be dual controlled to the extent possible;

(D) System operations functions shall be segregated from reconciliation duties;

(v) A separate EBT security component shall be incorporated into the State agency Security Program for Automated Data Processing (ADP) systems where appropriate as prescribed under § 277.18(m) of this chapter. The periodic risk analyses required by the Security Program shall address the following items specific to an EBT system:

(A) EBT system vulnerability to theft and unauthorized use;

(B) Completeness and timeliness of the reconciliation system;

(C) Vulnerability to tampering with or creating household accounts;

(D) Erroneous posting of issuances to household accounts;

(E) Manipulation of retailers' accounts such as creation of false transactions or intrusion by unauthorized computer users;

(F) Capability to monitor systematic abuses at POS terminals such as debits for a complete allotment, excessive manual issuances, and multiple manual transactions at the same time. Such monitoring may be accomplished through the use of exception reporting;

(G) Tampering with information on the ACH tape or similar information utilized in a crediting method approved by FNS; and,

(H) The availability of a complete audit trail. A complete audit trail shall, at a minimum, be able to provide a complete transaction history of each individual system activity that affects an account balance. The audit trail shall include the tracking of issuances from the Master File and Issuance File, network transactions from POS terminals to EBT central computer database and system file updates.

(vi) The State agency shall incorporate the contingency plan approved by FNS into the Security Program.

(4) *System ease-of-use.* (i) For all system users, the State agency shall ensure that the system:

(A) Minimizes the number of separate steps required to complete a transaction;

(B) Minimizes the number of codes or commands needed to make use of the system;

(C) Makes available clear and comprehensive account balance information with a minimum number of actions necessary;

(D) Provides training and instructions for all system users especially those persons with disabilities;

(E) Makes available prompts on POS terminals or balance only terminals, where appropriate;

(F) Identifies procedures for problem resolution;

(G) Provides reasonable accommodation for the needs of households with disabilities in keeping with the Americans with Disabilities Act of 1990.

(ii) In addition to the requirements of paragraph (h)(4)(i) of this section, the State agency shall ensure that retailers utilizing the EBT system:

(A) Have available manual backup procedures;

(B) Can obtain timely information on daily credits to their banks;

(C) Have available deposit information in a format readily comparable to information maintained in the store; and

(D) Have available instructions on resolving problems with equipment and retailer accounts.

(5) *Minimum card requirements.* (i) The address of the office where a card can be returned if found or no longer in use should be printed on the card.

(ii) State agencies that implement the photo EBT card option in accordance with paragraph (f) of this section must print on the EBT cards the text “Any user with valid PIN can use SNAP benefits on card and need not be pictured.” or similar alternative text approved by FNS.

(iii) FNS reserves the right to require State agencies to place a Department logo on the EBT card and/or sleeves or jackets.

(iv) EBT cards and/or sleeves or jackets shall not contain the name of any State or local official. EBT informational materials shall not indicate association with any political party or other political affiliation.

(v) State agencies may require the use of a photograph of one or more household members on the card. If the State agency does require the EBT cards to contain a photo, it must establish procedures to ensure that all appropriate household members or authorized representatives are able to access benefits from the account as necessary.

(6) *POS terminals.* POS terminals shall meet the following requirements:

(i) Balance information shall not be displayed on the screen of the POS terminal except for balance-only inquiry terminals;

(ii) PINs shall not be displayed at the terminal; and

(iii) PIN encryption shall occur from the point of entry in a manner which prevents the unsecured transmission between any point in the system.

(7) *Transaction receipts.* Households shall be provided printed receipts at the time of transaction. At a minimum this information shall:

(i) State the date, merchant's name and location, transaction type, transaction amount and remaining balance for the SNAP account;

(ii) Comply with the requirements of 12 CFR part 205 (Regulation E) in addition to the requirements of this section; and

(iii) Identify the SNAP households member's account number (the PAN) using a truncated number or coded transaction number. The households' name shall not appear on the receipt except when a signature is required when utilizing a manual transaction voucher.

(8) *Performance bonding.* The State agency may require a performance bond in accordance with § 277.8 of this chapter or utilize other contractual clauses it deems necessary to enforce the requirements of this section.

(9) *Minimum transaction set.* At a minimum, the State agency shall ensure that the EBT system, including third party processors and retailers driving their own terminals, is capable of providing for authorizing or rejecting purchases, refunds or customer credits, voids or cancellations, key entered transactions, balance inquiries and settlement or close-out transactions. The system must be capable of completing this transaction set across State borders nationwide in accordance with standards specified in paragraph (h)(10) of this section.

(10) *Interoperability.* State agencies must adopt uniform standards to facilitate interoperability and portability nationwide. The term “interoperability” means the EBT system must enable benefits issued in the form of an EBT card to be redeemed in any State. The term “portability” means the EBT system must enable benefits issued in the form of an EBT card to be used in any State by a household to purchase food at a retail food store or a wholesale food concern approved under the Food and Nutrition Act of 2008. The standards must include the following:

(i) *EBT system connectivity.* State agencies are responsible for establishing telecommunications links, transaction switching facilities and any other arrangements with other State agencies necessary for the routing of interoperable transactions to such other State EBT authorization systems. State agencies are also responsible for facilitating the settlement of such interoperable transactions and the handling of adjustments. These connections need not be direct connections between State authorization systems but may be facilitated through agreements and linkages with other designated agents or third party processors. All State agencies must agree to the timing and disposition of disputes, error resolution, and adjustments in accordance with Department regulations at § 273.13(a) and § 273.15(k) of this chapter and paragraph (f) of this section. State agencies or their designated agents must draw funds from State SNAP accounts for SNAP benefits transacted by that State's SNAP recipients, regardless of where benefits were transacted.

(ii) *Message format.* Each authorization system must use the ISO 8583 message format, modified for EBT, in a version mutually agreed to between the authorization agent and the party connected for all transactions. Each authorization system must process each financial transaction as a single message financial transaction, except for pre-authorized transactions and reversals, processed as paired transactions.

(iii) *Card Primary Account Number (PAN) Requirements.* Track 2 on each card shall contain the PAN. Each Government entity must obtain an Issuer Identification Number (IIN) from the American Banker's Association (ABA). The IIN should be included as the first six digits of the PAN. The PAN must comply with ISO 7812, Identification Cards—Numbering System and Registration Procedures for Issuer Identifiers. Each State agency must be responsible for generating, updating, and distributing IIN files of all States to each retailer, processor, or acquirer that is directly connected to the State's authorization system. Each terminal operator that uses a routing table for routing acquired transactions must, within 7 calendar days of receiving an IIN routing table update, modify its routing tables to reflect the updated routing information.

(iv) *Third Party Processor requirements.* Each Third Party Processor or terminal operator must have primary responsibility and liability for operating the telecommunications and processing system (including software and hardware) through which transactions initiated at POS terminals it owns, operates, controls or for which it has signed an agreement to accept EBT transactions, are processed and routed, directly or indirectly, to the appropriate State authorization system. Each terminal operator must maintain the necessary computer hardware and software to interface either directly with a State authorization system or with a third party service provider to obtain access to one or more State authorization systems. Each terminal operator must also establish a direct or indirect telecommunications connection for the routing of transactions to the State authorization system or to a processor directly or indirectly connected to the State authorization system.

(v) *REDE File.* The State agency must ensure that their EBT system verifies FNS retailer numbers for all interstate transactions against the National REDE file of all FNS EBT retailers to validate these transactions.

(c) *Concentrator bank responsibilities.* The concentrator bank shall be a Federally-insured financial institution or other entity acceptable to the Federal Reserve which has the capability to take retailer credits and/or debits, obtained from the EBT system operator, and transmit them to the ACH network operated by the Federal Reserve or through another process for crediting retailers approved by FNS. Transmittal shall be by tape or on-line in a format suitable for the ACH or as approved by FNS.

(1) The minimum functions of the concentrator bank are:

(i) Preparing a daily ACH tape or other crediting process approved by FNS with information on benefits redeemed and creditable to each retailer;

(ii) Transferring the ACH tape or other crediting process approved by FNS to the Federal Reserve or other entity approved by FNS;

(iii) Initiating and accepting reimbursement from the appropriate U.S. Treasury account through the ASAP system or other payment process approved by FNS. At the option of FNS, the State agency may designate another entity as the initiator of reimbursement for SNAP redemptions provided the entity is acceptable to FNS and U.S. Treasury;

(iv) Cooperating in the reconciliation of discrepancies and error resolution when necessary.

(2) With the approval of FNS, another procedure, other than the ACH system, may be utilized to credit retailer accounts and/or debit FNS' account, if it meets the needs of FNS and the EBT system.

(3) The State agency shall be liable for any errors in the creation of the ACH tape or its transmission. The State agency may transfer the liability associated with creation of the ACH tape, its transmission or another crediting process approved by FNS as appropriate to the EBT system operator or the concentrator bank. Appropriate system security administrative and operational procedures shall be instituted in accordance with paragraph (h)(3) of this section.

(d) *Re-presentation.* The State agency shall ensure that a manual purchase system is available for use during times when the EBT system is inaccessible.

(1) Under certain circumstances, when a manual transaction occurs due to the inaccessibility of the host computer and the transaction is rejected because insufficient funds are available in a household's account, the State agency may permit the re-presentation of the transaction during subsequent months. At the State agency's option, re-presentation may be permitted within the EBT system as follows:

(i) Re-presentation of manual vouchers when there are insufficient funds in the EBT account to cover the manual transaction may be permitted only under the following circumstances:

(A) The manual transaction occurred because the host computer was down and authorization was obtained by the retailer for the transaction; or

(B) The manual transaction occurred because telephone lines were down.

(ii) Re-presentation of manual vouchers shall not be permitted when the EBT card, magnetic stripe, PIN pad, card reader, or POS terminal fails and telephone lines are operational. Manual transactions shall not be utilized to extend credit to a household via re-presentation when the household's account balance is insufficient to cover the planned purchase.

(iii) The State agency may debit the benefit allotment of a household following the insufficient funds transaction in either of two ways:

(A) Any amount which equals at least $10 or up to 10 percent of the transaction. This amount will be deducted monthly until the total balance owed is paid-in-full. State agencies may opt to re-present at a level that is less than the 10 percent maximum, however, this lesser amount must be applied to all households.

(B) $50 in the first month and the greater of $10 or 10 percent of the allotment in subsequent months until the total balance owed is paid-in-full. If the monthly allotment is less than $50, the State shall debit the account for $10.

(2) The State agency shall establish procedures for determining the validity of each re-presentation and subsequent procedures authorizing a debit from a household's monthly benefit allotment. The State agency may ask households to voluntarily pay the amount of a represented transaction or arrange for a faster schedule of payment than identified in paragraph (d)(1)(iii) of this section.

(3) The State agency shall ensure that retailers provide notice to households at the time of the manual transaction that re-presentation may occur if there are insufficient benefits in the account to cover the transaction. The statement shall be printed on the paper voucher or on a separate sheet of paper. The State agency shall also provide notice to the household prior to the month when a benefit allotment is reduced when a re-presentation is necessary. Notice shall be provided to the household for each insufficient transaction that is to be re-presented in a future month. The notice shall be provided prior to the month it occurs and shall state the amount of the reduction in the benefit allotment.

(4) The Department shall not accept liability under any circumstances for the overissuance of benefits due to the utilization of manual vouchers, including those situations when the host computer is inaccessible or telecommunications lines are not functioning. However, the State agency, in consultation with authorized retailers and with the mutual agreement of the State agency's vendor, if any, may accept liability for manual purchases within a specified dollar limit. Costs associated with liabilities accepted by the State agency shall not be reimbursable.

(5) The State agency shall be strictly liable for manual transactions that result in excess deductions from a household's account.

(e) *Store-and-forward.* As an alternative to manual transactions:

(1) State agencies may opt to allow retailers, at the retailer's own choice and liability, to perform store-and-forward transactions when the EBT system cannot be accessed for any reason. The retailer may forward the transaction to the host one time within 24 hours of when the system again becomes available. Should the 24-hour window cross into the beginning of a new benefit issuance period, retailers may draw against all available benefits in the account.

(2) State agencies may also opt, in instances where there are insufficient funds to authorize an otherwise approvable store-and-forward transaction, to allow the retailer to collect the balance remaining in the client's account, in accordance with the requirements detailed in this section.

(i) State Agencies may elect to allow store-and-forward to provide remaining balances to retailers as follows:

(A) The EBT processor may provide partial approval of the store-and-forward transaction, crediting the retailer with the balance remaining in the account through a one-step process;

(B) The transaction should be in accordance with the standard message format requirements for store and forward; and

(C) Re-presentation, as described in paragraph (d) of this section, to obtain the uncollected balance from current or future months' benefits shall not be allowed for store-and-forward transactions.

(ii) In States that elect not to give retailers the option described in this paragraph, all store-and-forward transactions with insufficient funds will be denied in full.

(f) *State agency requirements for photo EBT card implementation*—(1) Minimum requirements. Prior to implementation, State agencies must be performing sufficiently well in program administration to be eligible to implement the photo EBT card option.

Prior to implementation, State agencies must demonstrate to FNS successful administration of SNAP based on SNAP performance standards. Successful program administration will take into account at a minimum the metrics related to program access, the State's payment error rate, the State's Case and Procedural Error Rate, application processing timeliness, including both the 7-day expedited processing and the 30-day processing standards, timeliness of recertification actions, and other metrics, as determined by the Secretary, that may be relevant to the State agency's implementation of photo EBT cards.

(2) *Function of issuance.* The photo EBT card option is a function of issuance and not a condition of eligibility. Any implementation of the option to place a photo on the EBT card must not impact the certification of households. An application will be considered complete with or without a photo and a case shall be certified regardless of the status of a photo in accordance with timeframes established under 7 CFR 273.2. If a State agency chooses to implement a voluntary photo EBT card policy, issuance shall not be impacted. If a State agency chooses to implement a mandatory photo EBT card policy, a State agency may not deny or terminate a household because a household member who is exempted by paragraph (f)(4) of this section does not comply with the requirement to place a photo on the EBT card.

(3) *Mandatory vs. voluntary.* (i) State agencies shall have the option to implement a photo on EBT cards on a mandatory or voluntary basis. Regardless of whether the photo is mandatory or voluntary, the certification process must not be altered in order to facilitate photos, and clients must be informed that certification will not be impacted by whether or not a photo is on the card.

(ii) Under mandatory implementation, State agencies must exempt certain clients, as stated in paragraph (f)(4) of this section. State agencies must establish which member(s) of the household would be required to be photographed and the procedures that allow eligible nonexempt household members who do not agree to the photo to come into compliance at a later time.

(iii) Under voluntary implementation, clients must be clearly informed of the voluntary nature of the option. All applicant members of households, whether or not they are in an exempted category, must opt in to have a photo on their EBT card. States shall not require a photo be taken if the State is implementing a voluntary option.

(4) *Exemptions.* Under a mandatory implementation, the State agency must exempt, at a minimum, the elderly, the disabled, children under 18, homeless households, and victims of domestic violence. A victim of domestic violence shall be able to self-attest and cannot be required to submit documentation to prove domestic violence. The ability to self-attest must be applied equally regardless of if the victim is a female or male. Non-applicants cannot have a photo taken for an EBT card whether or not they desire to have their photo taken. A State agency may establish additional exempted categories.

(5) *Serving clients with hardship.* State agencies must have sufficient capacity to issue photo EBT cards and a process or procedure in place to address, on a case-by-case basis, household hardship situations as determined by the State agency so that such household benefits are not unduly withheld. Examples of hardship conditions include, but are not limited to: Illness, transportation difficulties, care of a household member, hardships due to residency in a rural area, prolonged severe weather, or work or training hours which prevent the household from being available during the hours that photos are taken in-office. These are households that do not already fall under the mandatory exemptions or other exemptions established by the State under paragraph (f)(4) of this section .

(6) *Issuance of photo EBT card.* (i) States can require households to come in to be photographed, but cannot do so for the purposes of certification. The amount of time provided to households to come in and be photographed needs to be sufficient and reasonable and be documented in the Implementation Plan as required in paragraph (f)(14) of this section.

(ii) Regardless of whether the State's photo EBT card policy is voluntary or mandatory, if a household meets expedited criteria, the State must issue the EBT card without a photo and provide the full benefit allotment to the entire household without delay. The State agency may require a nonexempt head of household member to comply at the next recertification.

(iii) Card issuance procedures for new SNAP households must ensure adherence to application processing standards as required at 7 CFR 273.2(g) and (i) and benefit issuance standards at § 274.2(b).

(iv) State agencies shall not store photos that are collected in conjunction with its photo EBT card policy but are not placed on an EBT card.

(v) The process for issuing and activating photo EBT cards must not disrupt, inhibit or delay access to benefits nor cause a gap in access for ongoing benefits for eligible households.

(vi) Any card issued as part of the implementation of the photo EBT card option may not count against the household with respect to card replacement fees or the card replacement threshold defined in § 274.6(b).

(7) *Prorating household benefits when photo EBT cards are mandatory.* For multi-person households, State agencies shall not withhold benefits for an entire household because nonexempt household members do not comply with the photo EBT card policy. If benefits of the nonexempt household member(s) are to be withheld, a prorated share of benefits shall be issued to the household member(s) that are in compliance with or are exempt from the photo requirement. For example, if there are four household members and one household member is not in compliance with the photo requirement, 3-4 of the household's monthly benefit allotment must be issued, and 1-4 of the benefit allotment must be held in abeyance and allowed to accrue until the household member complies. For a single person household, the State agency would hold all the benefits in abeyance until the household complies.

(8) *Benefits held for noncompliance.* Benefits held for noncompliance with the photo EBT card requirement must be withheld from issuance in accordance with paragraph (f)(7) of this section. Benefits withheld for noncompliance shall not remain authorized for perpetuity, and States must treat such benefits in accordance with the same timeframe used for handling expungements under § 274.2(i). If the noncompliant member comes into compliance, the non-expired benefits must be issued within two business days of when the State agency obtains the client photo. Any action to withhold benefits from issuance is subject to fair hearings in accordance with 7 CFR 273.15.

(9) *Household and authorized representative card usage.* The State agency must establish procedures to ensure that all appropriate household members and authorized representatives (including individuals permitted by the household to purchase food or meals on their behalf, as provided for in 7 CFR 273.2(n)(3) and § 274.7(a)), can access SNAP benefits for the household regardless of who is pictured on the card or if there is no picture. States shall not require households to notify or provide the State information regarding individuals making purchases permitted by the household on an ad-hoc basis.

(10) *Client and staff training.* State agencies must ensure staff and clients are properly trained on photo EBT card requirements. At a minimum, this training shall include: Whether the State option is voluntary or mandatory, who must comply with the photo requirement, which household members are exempt, and that all appropriate household members and authorized representatives (including individuals permitted by the household to purchase food or meals on its behalf) are able to use the card regardless of who is pictured on the card or if there is no picture.

(i) All staff and client training materials must clearly describe the following statutory and regulatory requirements:

(A) Retailers must allow all appropriate household members and authorized representatives (including individuals permitted by the household to purchase food or meals on its behalf), regardless of whether they are pictured on the card, to utilize the card without having to submit additional verification of identity as long as the transaction is secured by the use of the PIN;

(B) EBT cards with or without a photo are valid in any State; and

(C) Retailers must treat all SNAP clients in the same manner as non-SNAP clients;

(ii) State agencies may not specifically reference which categories of individuals are exempt from the photo EBT requirement in any materials to retailers.

(11) *Retailer education and responsibility.* State agencies must conduct sufficient education of retailers if photos are used on cards. The State agency must clearly inform all retailers in the State and contiguous areas of implementation. State agency communications with retailers must clearly state:

(i) All household members and authorized representatives (including individuals permitted by the household to purchase food or meals on its behalf) are entitled to use the EBT card regardless of the picture on the card if the EBT card is presented with the valid PIN;

(ii) Retailers must treat all SNAP clients in the same manner as non-SNAP clients in accordance with 7 CFR 278.2(b);

(iii) Retailers must not prohibit individuals who have a EBT card and valid PIN, including but not limited to authorized representatives (including individuals permitted by the household to purchase food or meals on its behalf), from using an EBT card because they are not pictured on the card or there is no picture on the card;

(iv) EBT cards from any State are valid with or without a photo.

(12) *Interoperability.* Interoperability of EBT cards will remain the same regardless of whether or not there is a photo and regardless of which State issued the card. State agencies must conduct sufficient education of clients and retailers, including retailers in contiguous areas, to inform them that the photo EBT cards remain interoperable and authorized retailers must accept EBT cards from all States as long as the user has a valid PIN.

(13) *Advance Planning Document.* Appropriate implementation and administration of the photo EBT card consistent with all applicable requirements is an allowable State administrative cost that FNS shall reimburse at 50 percent in accordance with 7 CFR part 277. Increased costs related to placing photos on the EBT card, whether contractual or produced from other sources, require an Implementation Advance Planning Document Update.

(14) *Implementation Plan.* (i) State agencies must submit an Implementation Plan for approval prior to implementation that delineates how the State agency will operationalize the photo EBT option. FNS shall review the plan and issue an approval, request modifications prior to granting approval or issue an approval subject to conditions. In cases where FNS finds that the steps outlined in the Implementation Plan are not sufficient for a successful implementation, FNS may deny the Implementation Plan or issue an approval subject to conditions, such as requiring the State agency to implement a successful pilot in a selected region of the State before a statewide implementation. Should a State be required to implement a pilot before statewide implementation, that requirement would be documented in the State's Implementation Plan approval, along with any information the State must report to FNS before expansion approval would be provided by FNS.

(ii) State agencies must demonstrate successful administration of SNAP based on SNAP performance standards as established in paragraph (f)(1) of this section. State agencies shall not issue EBT cards with photos before the State's Implementation Plan is approved and the State agency has also received FNS authorization to proceed to issue photo EBT cards.

(iii) The Implementation Plan shall include but not be limited to:

(A) A description of card issuance procedures;

(B) The text required at paragraph (b)(5)(ii) of this section;

(C) A detailed description of how client protections and ability to use SNAP benefits will be preserved;

(D) Specific information about exempted recipients, the State agency's exemption criteria, and how it will address the needs of household members with hardships;

(E) A description of how the State agency will obtain photographs for the EBT card;

(F) The procedures for opting into a voluntary photo EBT card policy and how the State agency will document that a household voluntarily chose to have a photo on its EBT card;

(G) Training materials and training plans for State agency staff;

(H) A description of any planned stakeholder assistance with implementation;

(I) Communication plans for informing clients, retailers and other stakeholders of the State agency's photo EBT card policy, including copies of letters and other materials communicating the policy to clients, retailers, and other stakeholders. Communication plans must describe compliance with language requirements at 7 CFR 272.4(b);

(J) A timeline for the implementation; and

(K) Draft memoranda of understanding if the State agency plans to share SNAP client data in accordance with 7 CFR 272.1(c) for purposes of implementing its photo EBT card option. The memoranda of understanding must state how any information collected will be securely stored and that the information can only be shared for the purpose of SNAP in accordance with 7 CFR 272.1(c).

(iv) The Implementation Plan shall also address the anticipated timetable with specific action steps for the State agency and contractors, if any, that may be involved regarding implementation of the photo EBT card option, the State agency's capacity to issue photo EBT cards, and the logistics that shall allow for activation of the photo EBT card simultaneously or followed by deactivation of the active non-photo EBT card. This shall also include the description of the capacity at the facility where the photo EBT cards will be produced, both for transition and ongoing production, and confirmation that the State agency and any contractor will continue to meet regulatory time requirements for all EBT card issuances and replacements, including for expedited households. The Implementation Plan must also include indicators related to the photo EBT card implementation that the State will collect and analyze for the post implementation evaluation required by paragraph (f)(16) of this section in addition to the State's approach for continued oversight, which may include activities as such as the use of test shoppers.

(v) The State agency shall provide all applicable proposed written policy for staff to implement the photo EBT card option to FNS for review. State agencies shall include copies of all materials that will be used to inform clients, retailers and other stakeholders regarding photo EBT card implementation. In addition, the State agencies shall provide a detailed description of how the notifications, communication, policies, and procedures regarding the implementation of any new photo EBT card option will comply with applicable civil rights laws specified at 7 CFR 272.4(b)and 272.6(a).

(vi) The State agency's Implementation Plan shall also include: (A) An education component for retailers and clients to ensure all eligible household members and authorized representatives (including individuals permitted by the household to purchase food or meals on their behalf) are able to use the EBT card, and understand the timeframes associated with the implementation and rollout.

(B) A description of the resources that will be in place to handle comments, questions and complaints from clients, retailers, and external stakeholders, and

(C) A description of procedures to address unexpected events related to the photo EBT card option.

(vii) Upon approval of the Implementation Plan by FNS, the State may proceed with tasks described in the Implementation Plan, as modified by the approval, but may not proceed to issuing actual cards until it receives FNS authorization to do so. FNS may also require the State to implement in a phased manner, which may include criteria as determined by the Secretary.

(15) *Authorization to issue photo EBT cards.* States agencies shall not be permitted to issue EBT cards with photos until FNS provides an explicit authorization to issue photo EBT cards. After an Implementation Plan is approved, FNS will review the State agency's actions at an appropriate time interval to ensure that the process and steps outlined by the State agency in the Implementation Plan are fulfilled. In cases where the State agency has not acted consistently with the process and steps outlined in its photo EBT card Implementation Plan, FNS may deny authorization for the State agency to issue EBT cards with photos until the State agency has done so successfully.

(16) *Post implementation assessment and evaluation.* State agencies must submit to FNS a post-implementation assessment that provides FNS with a report of the results of its implementation, including any issues that arose and how they were resolved, the degree to which State agency staff, clients and retailers properly understood and implemented the new provisions.

(i) This report shall be delivered to FNS within 120 days of implementation. This report shall cover the first 90 days of implementation. The Department also reserves the right to conduct its own review of the State agency's implementation. The State agency's post-implementation report shall include at a minimum:

(A) A survey of clients conducted by an independent evaluator to demonstrate the clients' clear understanding of the State agency's photo EBT policy;

(B) A survey of retailers conducted by an independent evaluator that demonstrates evidence that at least 80 percent of retailers, including smaller independent retailers, demonstrate a full understanding of the policies related to the photo EBT card, which may include the use of test shoppers;

(C) The amount and percent of benefits held for noncompliance if mandatory;

(D) The number and percent of households with photo EBT cards;

(E) The number of households affected by withholding for noncompliance, if mandatory;

(F) The number and percent of households exempt from the photo EBT card requirement if mandatory;

(G) The number and percent of exempted households who opted for photo EBT cards if mandatory;

(H) The number and scope of complaints related to the implementation of the policy;

(I) The State agency's Case and Procedural Error Rate; and

(J) SNAP performance metrics as established in paragraph (f)(1) of this section and other SNAP performance metrics that may have been adversely affected by the implementation of the State agency's photo EBT card option, as determined by the Secretary.

(ii) [Reserved]

(17) *Ongoing monitoring.* FNS will continue to monitor and evaluate the operation of the option. State agencies shall provide FNS additional information upon request or as may be required by other guidelines established by the Secretary to conduct such evaluations.

(18) *Modifying implementation of photo EBT card option.* If any review or evaluation of a State's operations, including photo EBT operation implementation, finds deficiencies, FNS may require a corrective action plan consistent with 7 CFR 275.16 to reduce or eliminate deficiencies. If a State does not take appropriate actions to address the deficiencies, FNS would consider possible actions such as requiring an updated photo EBT Implementation Plan, suspension of the photo EBT policy and/or withholding funds in accordance with 7 CFR 276.4.

[75 FR 18381, Apr. 12, 2010, as amended at 79 FR 11, Jan. 2, 2014; 81 FR 89840, Dec. 13, 2016; 85 FR 52033, Aug. 24, 2020]