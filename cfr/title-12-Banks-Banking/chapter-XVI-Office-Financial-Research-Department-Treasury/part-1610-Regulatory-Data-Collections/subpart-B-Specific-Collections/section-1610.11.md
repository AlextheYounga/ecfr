##### § 1610.11 Non-centrally Cleared Bilateral Repurchase Agreement Data. #####

(a) *Definitions.* The terms used in this section have the following meanings:

*Business day* is the period beginning at 6 p.m. Eastern Time on any day that the Fedwire Funds Service is open to 6 p.m. Eastern Time on the next day that the Fedwire Funds Service is open.

*Covered reporter* means any financial company that meets the criteria set forth in paragraph (b)(2) of this section; provided, however, that any covered reporter shall cease to be a covered reporter only if it does not meet the dollar thresholds specified in paragraph (b)(2) of this section for at least four consecutive calendar quarters.

*File observation date* means the date on which any business day ends.

*Financial company* has the same meaning as in 12 U.S.C. 5341(2).

*Government securities broker* means any financial company registered as a government securities broker under the Securities Exchange Act of 1934.

*Government securities dealer* means any financial company registered as a government securities dealer under the Securities Exchange Act of 1934.

*Investment adviser* means any financial company registered as an investment adviser with the Securities and Exchange Commission under the Investment Advisers Act of 1940.

*Non-centrally cleared bilateral repurchase agreement transaction* means an agreement of one party to sell securities to a second party in exchange for the receipt of cash, and the simultaneous agreement of the former party to later reacquire the same securities (or any subsequently substituted securities) from that same second party in exchange for the payment of cash; or an agreement of a party to acquire securities from a second party in exchange for the payment of cash, and the simultaneous agreement of the former party to later transfer back the same securities (or any subsequently substituted securities) to the latter party in exchange for the receipt of cash. The agreement does not involve a tri-party custodian and is not cleared with a central counterparty. This definition includes, but is not limited to, transactions that are executed under a Master Repurchase Agreement (MRA) or Global Master Repurchase Agreement (GMRA), or which are agreed to by the parties as subject to the provisions of 11 U.S.C. 559. Notwithstanding the above, transactions conducted under a Securities Lending Agreement (SLA) or a Master Securities Lending Agreement (MSLA) are not considered repurchase agreements, nor are repurchase agreements arising from either participation in a commercial mortgage loan or the initial securitization of a residential mortgage loan.

*Outstanding commitment* means the amount of financial obligations entered into pursuant to any repurchase agreement that opens on any business day or is outstanding as of the end of any business day, including transactions which both opened and closed on the same business day. These financial obligations include all of those that exist prior to netting.

*Securities broker* means any financial company registered as a broker with the Securities and Exchange Commission under the Securities Exchange Act of 1934.

*Securities dealer* means any financial company registered as a dealer with the Securities and Exchange Commission under the Securities Exchange Act of 1934.

(b) *Purpose and scope*—(1) *Purpose.* The purpose of this data collection is to require the reporting of certain information to the Office about non-centrally cleared bilateral repurchase agreement transactions. The information will be used by the Office to fulfill its responsibilities under Title I of the Dodd-Frank Wall Street Reform and Consumer Protection Act, including support of the Council and Council member agencies by facilitating financial stability monitoring and research consistent with support of the Council and its member agencies.

(2) *Scope of application.* Reporting under this section is required by any financial company that participates in a non-centrally cleared bilateral repurchase agreement transaction and that is:

(i) A securities broker, securities dealer, government securities broker, or government securities dealer whose average daily outstanding commitments to borrow cash and extend guarantees in non-centrally cleared bilateral repurchase agreement transactions with counterparties over all business days during the prior calendar quarter is at least $10 billion, or

(ii) Any other financial company with over $1 billion in assets or assets under management whose average daily outstanding commitments to borrow cash and extend guarantees in non-centrally cleared bilateral repurchase agreement transactions, including commitments of all funds for which the company serves as an investment adviser, with counterparties that are not securities brokers, securities dealers, government securities brokers, or government securities dealers over all business days during the prior calendar quarter is at least $10 billion.

(c) *Data required.* (1) Covered reporters shall report trade and collateral information on all non-centrally cleared bilateral repurchase agreement transactions, subject to paragraph (c)(2) of this section, in accordance with the prescribed reporting format in this section.

(2) Covered reporters shall only report trade and collateral information with respect to any non-centrally cleared bilateral repurchase agreement transaction which opens on, or is outstanding at any time during the business day, including transactions which both opened and closed during the business day.

(3) Covered reporters shall submit the following data elements for all transactions:

|              Data element              |                                                                         Explanation                                                                         |
|----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
|         File observation date          |                                                          The date on which the business day ends.                                                           |
|          Covered reporter LEI          |                                                    The Legal Entity Identifier of the covered reporter.                                                     |
|            Cash lender LEI             |                                                       The Legal Entity Identifier of the cash lender.                                                       |
|            Cash lender name            |                                                             The legal name of the cash lender.                                                              |
|           Cash borrower name           |                                                            The legal name of the cash borrower.                                                             |
|           Cash borrower LEI            |                                                      The Legal Entity Identifier of the cash borrower.                                                      |
|               Guarantee                |                               Indicator for whether the covered reporter issued a guarantee with respect to the transaction.                                |
|             Transaction ID             |                               The covered reporter-generated unique transaction identifier in an alphanumeric string format.                                |
|         Unique transaction ID          |                                                   If available, the Unique Transaction Identifier (UTI).                                                    |
|            Trading platform            |                                 For transactions arranged using an outside vendor's platform, the provider of the platform.                                 |
|            Trade timestamp             |                The timestamp that the trade became an obligation of the covered reporter or the covered reporter's affiliate or subsidiary.                 |
|               Start date               |                                                                 The start date of the repo.                                                                 |
|                End date                |                                                                 The date the repo matures.                                                                  |
|         Minimum maturity date          |          The earliest possible date on which the transaction could end in accordance with its contractual terms (taking into account optionality).          |
|    Cash lender internal identifier     |                The internal identifier assigned to the cash lender by the covered reporter, if the covered reporter is not the cash lender.                 |
|   Cash borrower internal identifier    |              The internal identifier assigned to the cash borrower by the covered reporter, if the covered reporter is not the cash borrower.               |
|            Start leg amount            |                 The amount of cash transferred to the cash borrower on the open leg of the transaction at the inception of the transaction.                 |
|            Close leg amount            |                                The amount of cash to be transferred by the cash borrower on the end date of the transaction.                                |
|          Current cash amount           |The amount of cash to be transferred by the cash borrower, inclusive of principal, accrued interest and other adjustments, as of the end of the business day.|
|           Start leg currency           |                                                  The currency which is used in the Start leg amount field.                                                  |
|                  Rate                  |            The rate of interest paid by the cash borrower on the transaction, expressed as an annual percentage rate on an actual/360-day basis.            |
|        Floating rate benchmark         |                                        The name of the benchmark interest rate upon which the transaction is based.                                         |
|     Floating rate reset frequency      |                                  The time period, in calendar days, describing the frequency of the floating rate resets.                                   |
|                 Spread                 |                              The contractual spread over (or below) the benchmark rate referenced in the repurchase agreement.                              |
|       Securities identifier type       |                                  The identifier type for the securities transferred between cash borrower and cash lender.                                  |
|          Security identifier           |                             The identifier of securities transferred between the cash borrower and the cash lender in the repo.                             |
|          Securities quantity           |                  The number of units (e.g., shares, bonds, bills, notes) transferred to the cash lender as of the end of the business day.                  |
|            Securities value            |                      The market value of the transferred securities as of the end of the business day, inclusive of accrued interest.                       |
|     Securities value at inception      |                     The market value of the transferred securities at the inception of the transaction, inclusive of accrued interest.                      |
|       Securities value currency        |                                     The currency used in the Securities value and Securities value at inception fields.                                     |
|                Haircut                 |           The difference between the market value of the transferred securities and the purchase price paid at the inception of the transaction.            |
|Special instructions, notes, or comments|                     The covered reporter may characterize any detail of the transaction with special instructions, notes, or comments.                      |

(d) *Reporting process.* Covered reporters shall submit the required data for each business day by 11 a.m. Eastern Time on the following business day. The Office may either collect the data itself or designate a collection agent for that purpose.

(e) *Compliance date.* (1) Any financial company that meets the criteria set forth in paragraph (b)(2)(i) of this section as of the effective date of this section shall comply with the reporting requirements pursuant to this section 150 days after the effective date of this section. Any such covered reporter's first submission shall be submitted on the first business day after such compliance date.

(2) Any financial company that meets the criteria set forth in paragraph (b)(2)(ii) of this section as of the effective date of this section shall comply with the reporting requirements pursuant to this section 270 days after the effective date of this section. Any such covered reporter's first submission shall be submitted on the first business day after such compliance date.

(3) Any financial company not described in subparagraph (e)(1) or (2) of this section that meets the criteria set forth in paragraph (b)(2)(i) of this section after the effective date of this section shall comply with the reporting requirements pursuant to this section 150 days after the last day of the calendar quarter in which such financial company becomes a covered reporter.

(4) Any financial company not described in subparagraph (e)(1) or (2) of this section that meets the criteria set forth in paragraph (b)(2)(ii) of this section after the effective date of this section shall comply with the reporting requirements pursuant to this section 270 days after the last day of the calendar quarter in which such financial company becomes a covered reporter.

[89 FR 37107, May 6, 2024]