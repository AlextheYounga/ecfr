##### § 1610.10 Centrally cleared repurchase agreement data. #####

(a) *Definitions.*

*Central counterparty* means a clearing agency that interposes itself between the counterparties to transactions, acting functionally as the buyer to every seller and the seller to every buyer.

*Clearing agency* has the same meaning as set forth in 15 U.S.C. 78c(a)(23).

*Covered reporter* means any central counterparty for repurchase agreement transactions that meets the criteria set forth in paragraph (b)(2) of this section; provided, however, that any covered reporter shall cease to be a covered reporter only if it does not meet the dollar threshold specified in paragraph (b)(2) for at least four consecutive calendar quarters.

*General collateral trade* means a repurchase agreement transaction in which the trade reported to the central counterparty is for a category of securities as opposed to a specific security.

*Repurchase agreement transaction* or transaction means an agreement of a counterparty to transfer securities to another counterparty in exchange for the receipt of cash, and the simultaneous agreement of the former counterparty to later reacquire the same securities (or any subsequently substituted securities) from that same counterparty in exchange for the payment of cash; or an agreement of a counterparty to acquire securities from another counterparty in exchange for the payment of cash, and the simultaneous agreement of the former party to later transfer back the same securities (or any subsequently substituted securities) to the latter counterparty in exchange for the receipt of cash.

*Specific-security trade* means a repurchase agreement transaction where the trade as reported to the central counterparty is for a mutually agreed upon specific security.

(b) *Purpose and scope*—(1) *Purpose.* The purpose of this data collection is to require the reporting of certain information to the Office about repurchase agreement transactions cleared through a central counterparty. The information will be used by the Office to support the Council and Council member agencies by facilitating financial stability monitoring including research consistent with support of the Council and its member agencies, and to support the calculation of certain reference rates.

(2) *Scope of application.* Reporting under this Section is required by any central counterparty for repurchase agreement transactions that meets the definition of financial company set forth in 12 U.S.C. 5341(2) and whose average daily total open commitments in repurchase agreement contracts (gross cash positions prior to netting) across all services over all business days during the prior calendar quarter is at least $50 billion.

(c) *Data required.* (1) Covered reporters shall report trade and collateral information on all repurchase agreement transactions cleared through any of its services, subject to paragraph (c)(2) of this section, in accordance with the prescribed reporting format in this section.

(2) Covered reporters shall only report trade and collateral information with respect to any repurchase agreement transaction for which there is a current or future delivery obligation as of the file observation date, including forward-starting transactions.

(3) Covered reporters shall submit the following data elements for all general collateral trades:

|                         Data element                         |                                                                        Explanation                                                                        |
|--------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
|                    File Observation Date                     |                            The observation date of the file (typically one business day before the day the file is submitted).                            |
|                     Covered Reporter LEI                     |                                                   The Legal Entity Identifier of the covered reporter.                                                    |
|                        Transaction ID                        |                                                    Respondent-generated unique transaction identifier.                                                    |
|                     Submission Timestamp                     |                                                  Time that trade is first submitted to clearing service.                                                  |
|                       Match Timestamp                        |                                                      Time that trade is matched by clearing service.                                                      |
|           Securities Asset Class Identifier Value            |                                                                  Asset class identifier.                                                                  |
|            Securities Asset Class Identifier Type            |                                Type of securities identifier used (the numbering system to which the identifier belongs).                                 |
|                      Cash Provider LEI                       |                                                     The Legal Entity Identifier of the cash provider.                                                     |
|                      Cash Provider Name                      |                                                           The legal name of the cash provider.                                                            |
|              Cash Provider Internal Identifier               |                                      The internal identifier assigned by the covered reporter to the cash provider.                                       |
|           Cash Provider Direct Clearing Member LEI           |                 The Legal Entity Identifier of the direct clearing member through which the cash provider accessed the clearing service.                  |
|          Cash Provider Direct Clearing Member Name           |                    The legal name of the of the direct clearing member through which the cash provider accessed the clearing service.                     |
|   Cash Provider Direct Clearing Member Internal Identifier   |   The internal identifier assigned by the covered reporter to the direct clearing member through which the cash provider accessed the clearing service.   |
|                   Securities Provider LEI                    |                                                  The Legal Entity Identifier of the securities provider.                                                  |
|                   Securities Provider Name                   |                                                        The legal name of the securities provider.                                                         |
|           Securities Provider Internal Identifier            |                                   The internal identifier assigned by the covered reporter to the securities provider.                                    |
|        Securities Provider Direct Clearing Member LEI        |              The Legal Entity Identifier of the direct clearing member through which the securities provider accessed the clearing service.               |
|       Securities Provider Direct Clearing Member Name        |                     The legal name of the direct clearing member through which the securities provider accessed the clearing service.                     |
|Securities Provider Direct Clearing Member Internal Identifier|The internal identifier assigned by the covered reporter to the direct clearing member through which the securities provider accessed the clearing service.|
|                          Broker LEI                          |                                                        The Legal Entity Identifier of the broker.                                                         |
|                         Broker Name                          |                                                               The legal name of the broker.                                                               |
|                  Broker Internal Identifier                  |                                          The internal identifier assigned by the covered reporter to the broker.                                          |
|                          Start Date                          |                                                        The start date of the repurchase agreement.                                                        |
|                           End Date                           |                                                        The date the repurchase agreement matures.                                                         |
|                             Rate                             |                             The repurchase agreement rate, expressed as an annual percentage rate on an actual/360-day basis.                             |
|                          Principal                           |                                                           The amount of cash borrowed or lent.                                                            |
|                         Optionality                          |                                               The type of optionality, if any, in the repurchase agreement.                                               |
|                       Minimum Maturity                       |         The earliest possible date on which the transaction could end in accordance with its contractual terms (taking into account optionality).         |

(4) Covered reporters shall submit the following data elements on the collateral delivered against net general collateral exposures for all general collateral trades:

|               Data element               |                                               Explanation                                               |
|------------------------------------------|---------------------------------------------------------------------------------------------------------|
|          File Observation Date           |   The observation date of the file (typically one business day before the day the file is submitted).   |
|           Covered Reporter LEI           |                          The Legal Entity Identifier of the covered reporter.                           |
|        Direct Clearing Member LEI        |           The Legal Entity Identifier of the direct clearing member of the clearing service.            |
|       Direct Clearing Member Name        |                              The legal name of the direct clearing member.                              |
|Direct Clearing Member Internal Identifier|         The internal identifier assigned by the covered reporter to the direct clearing member.         |
|             Transaction Side             |Indicates the side of the transaction: Collateral was received by or delivered from the covered reporter.|
|       Securities Identifier Value        |                                  Identifier of securities transferred.                                  |
|        Securities Identifier Type        |       Type of securities identifier used (the numbering system to which the identifier belongs).        |
|           Securities Quantity            |                    Par value or quantity (as applicable) of securities transferred.                     |
|             Securities Value             |   The market value as of most recent valuation of securities transferred, including accrued interest.   |

(5) Covered reporters shall submit the following data elements for all specific-security trades:

|                         Data element                         |                                                                        Explanation                                                                        |
|--------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
|                    File Observation Date                     |                            The observation date of the file (typically one business day before the day the file is submitted).                            |
|                     Covered Reporter LEI                     |                                                   The Legal Entity Identifier of the covered reporter.                                                    |
|                        Transaction ID                        |                                                    Respondent-generated unique transaction identifier.                                                    |
|                      Cash Provider LEI                       |                                                     The Legal Entity Identifier of the cash provider.                                                     |
|                      Cash Provider Name                      |                                                           The legal name of the cash provider.                                                            |
|              Cash Provider Internal Identifier               |                                      The internal identifier assigned by the covered reporter to the cash provider.                                       |
|           Cash Provider Direct Clearing Member LEI           |                 The Legal Entity Identifier of the direct clearing member through which the cash provider accessed the clearing service.                  |
|          Cash Provider Direct Clearing Member Name           |                    The legal name of the of the direct clearing member through which the cash provider accessed the clearing service.                     |
|   Cash Provider Direct Clearing Member Internal Identifier   |   The internal identifier assigned by the covered reporter to the direct clearing member through which the cash provider accessed the clearing service.   |
|                   Securities Provider LEI                    |                                                  The Legal Entity Identifier of the securities provider.                                                  |
|                   Securities Provider Name                   |                                                        The legal name of the securities provider.                                                         |
|           Securities Provider Internal Identifier            |                                   The internal identifier assigned by the covered reporter to the securities provider.                                    |
|        Securities Provider Direct Clearing Member LEI        |              The Legal Entity Identifier of the direct clearing member through which the securities provider accessed the clearing service.               |
|       Securities Provider Direct Clearing Member Name        |                     The legal name of the direct clearing member through which the securities provider accessed the clearing service.                     |
|Securities Provider Direct Clearing Member Internal Identifier|The internal identifier assigned by the covered reporter to the direct clearing member through which the securities provider accessed the clearing service.|
|                          Broker LEI                          |                                                        The Legal Entity Identifier of the broker.                                                         |
|                         Broker Name                          |                                                               The legal name of the broker.                                                               |
|                  Broker Internal Identifier                  |                                          The internal identifier assigned by the covered reporter to the broker.                                          |
|                     Submission Timestamp                     |                                                  Time that trade is first submitted to clearing service.                                                  |
|                       Match Timestamp                        |                                                      Time that trade is matched by clearing service.                                                      |
|                          Start Date                          |                                                        The start date of the repurchase agreement.                                                        |
|                           End Date                           |                                      The date when the repurchase agreement matures; the close leg settlement date.                                       |
|                         Optionality                          |                                                             The type of optionality, if any.                                                              |
|                       Minimum Maturity                       |         The earliest possible date on which the transaction could end in accordance with its contractual terms (taking into account optionality).         |
|                  Security Identifier Value                   |                                                              Identifier of pledged security.                                                              |
|                  Securities Identifier Type                  |                                Type of securities identifier used (the numbering system to which the identifier belongs).                                 |
|                     Securities Quantity                      |                                             Par value or quantity (as applicable) of securities transferred.                                              |
|           Substitution Collateral Identifier Value           |                                                        Asset class identifier or no substitution.                                                         |
|           Substitution Collateral Identifier Type            |                                Type of securities identifier used (the numbering system to which the identifier belongs).                                 |
|                Cash Provider Start Leg Amount                |                                  The amount of cash transferred by the cash provider on the open leg of the transaction.                                  |
|             Securities Provider Start Leg Amount             |                                The amount of cash received by the securities provider on the open leg of the transaction.                                 |
|                      Cash Provider Rate                      |                  The rate of interest received by the cash provider, expressed as an annual percentage rate on an actual/360-day basis.                   |
|                   Securities Provider Rate                   |                 The rate of interest paid by the securities provider, expressed as an annual percentage rate on an actual/360-day basis.                  |
|          Cash Provider Close Leg Settlement Amount           |                                   The amount of cash received by the cash provider on the close leg of the transaction.                                   |
|       Securities Provider Close Leg Settlement Amount        |                                  The amount of cash paid by the securities provider on the close leg of the transaction.                                  |

(d) *Reporting process and collection agent.* The Office may designate a collection agent for the data reporting. Covered reporters shall submit the required data for each business day by 6:00 a.m. Eastern time on the following business day.

(e) *Compliance.* (1) Any central counterparty that is a covered reporter as of the effective date of this Section shall comply with the reporting requirements pursuant to this Section in the following manner:

(i) Subject to paragraph (e)(1)(iii) of this section, a covered reporter shall begin reporting all data elements required to be submitted pursuant to paragraph (c)(5) of this section within 180 days after April 22, 2019.

(ii) Subject to paragraph (e)(1)(iii) of this section, a covered reporter shall begin reporting all data elements required to be submitted pursuant to paragraphs (c)(3) and (4) of this section within 240 days after April 22, 2019.

(iii) If a covered reporter is able to effect a rulemaking through the Securities and Exchange Commission requiring each direct clearing member, counterparty, and broker associated with a repurchase agreement transaction to obtain an LEI and provide it to the covered reporter, the covered reporter shall begin reporting all data elements requiring an LEI other than its own pursuant to paragraphs (c)(3) through (5) of this section by the later of the effective date of its rulemaking, or 420 days April 22, 2019, and continue to report all data elements requiring a legal name or internal identifier until 365 days after the date the covered reporter begins reporting all data elements requiring an LEI pursuant to this section. If a covered reporter is unable to effect such a rulemaking, the covered reporter is not required to report any data elements requiring an LEI other than its own pursuant to paragraphs (c)(3) through (5) of this section, except, if available, the LEI for any direct clearing member, counterparty, or broker associated with a repurchase agreement transaction that has an LEI, and shall report all data elements requiring a legal name or internal identifier in any report submitted under this section regardless of whether the relevant entity has an LEI. A covered reporter shall report its own LEI in accordance with the schedules set forth in paragraphs (e)(1)(i) and (ii) of this section.

(2) The first submission by any central counterparty that is a covered reporter as of the effective date of this Section shall be submitted on the first business day after the applicable compliance date under paragraph (e)(1) of this section.

Note 1 to paragraph (e)(2):

For example, if this section became effective on March 20, 2019, a central counterparty that meets the dollar threshold specified in paragraph (b)(2) of this section for the calendar quarter ending December 31, 2018, would be required to submit its first report under paragraph (e)(1)(i) of this section on the first business day after September 16, 2019, its first report under paragraph (e)(1)(ii) of this section on November 15, 2019, and its first report with data elements requiring an LEI (other than that of the covered reporter) on May 13, 2020 (if the covered reporter effected the rulemaking described in paragraph (e)(1)(iii) of this section).

(3) Any central counterparty that becomes a covered reporter after the effective date of this Section shall comply with the reporting requirements pursuant to this Section beginning on the later of the schedule set forth in paragraphs (e)(1)(i) through (iii) of this section or the first business day of the third calendar quarter following the calendar quarter in which such central counterparty meets the dollar threshold specified in paragraph (b)(2) of this section.

Note 2 to paragraph (e)(3):

For example, if this section became effective on March 20, 2019, a central counterparty that first meets the dollar threshold specified in paragraph (b)(2) of this section for the calendar quarter ending June 30, 2019, would be required to submit its first report under paragraphs (e)(1)(i) and (ii) of this section on January 2, 2020, and its first report with data elements requiring an LEI (other than that of the covered reporter) on May 13, 2020 (if the covered reporter effected the rulemaking described in paragraph (e)(1)(iii) of this section by May 13, 2020).

Note 3 to paragraph (e)(3):

For example, if this section became effective on March 20, 2019, a central counterparty that first met the dollar threshold specified in paragraph (b)(2) for the calendar quarter ending June 30, 2020, would be required to comply with all of the reporting requirements under this section on January 2, 2021 (and would continue to be required to report all data elements requiring a legal name or internal identifier for at least 365 days after the effective date of the covered reporter's rulemaking described in paragraph (e)(1)(iii) if such effective date occurred after January 2, 2021).