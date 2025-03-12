##### § 387.323T Electronic filing of surety bonds, trust fund agreements, certificates of insurance and cancellations. #####

(a) Insurers may, at their option and in accordance with the requirements and procedures set forth in paragraphs (a) through (d) of this section, file forms BMC 34, BMC 35, BMC 36, BMC 82, BMC 83, BMC 84, BMC 85, BMC 91, and BMC 91X electronically, in lieu of using the prescribed printed forms.

(b) Each insurer must obtain authorization to file electronically by registering with the FMCSA. An individual account number and password for computer access will be issued to each registered insurer.

(c) Filings may be transmitted online via the Internet at: *http://fhwa-li.volpe.dot.gov* or via American Standard Code Information Interchange (ASCII). All ASCII transmission must be in fixed format, *i.e.,* all records must have the same number of fields and same length. The record layouts for ASCII electronic transactions are described in the following table:

Electronic Insurance Filing Transactions

|           Field name           |Number of  <br/>positions|                                                        Description                                                         |Required  <br/>F = filing  <br/>C = cancel  <br/>B = both|Start field|End field|
|--------------------------------|-------------------------|----------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------|-----------|---------|
|          Record type           |        1 Numeric        |                                                1 = Filing, 2 = Cancellation                                                |                            B                            |     1     |    1    |
|         Insurer number         |         8 Text          |           FMCSA Assigned Insurer Number (Home Office) With Suffix (Issuing Office), If Different, e.g., 12345-01           |                            B                            |     2     |    9    |
|          Filing type           |        1 Numeric        |                                       1 = BI&PD, 2 = Cargo, 3 = Bond, 4 = Trust Fund                                       |                            B                            |    10     |   10    |
|      FMCSA docket number       |         8 Text          |                                       FMCSA Assigned MC or FF Number, e.g., MC000045                                       |                            B                            |    11     |   18    |
|       Insured legal name       |        120 Text         |                                                         Legal Name                                                         |                            B                            |    19     |   138   |
|       Insured d/b/a name       |         60 Text         |                                    Doing Business As Name If Different From Legal Name                                     |                            B                            |    139    |   198   |
|        Insured address         |         35 Text         |                                              Either street or mailing address                                              |                            B                            |    199    |   233   |
|          Insured city          |         30 Text         |                                                                                                                            |                            B                            |    234    |   263   |
|         Insured state          |         2 Text          |                                                                                                                            |                            B                            |    264    |   265   |
|        Insured zip code        |        9 Numeric        |                                        (Do not include dash if using 9 digit code)                                         |                            B                            |    266    |   274   |
|        Insured country         |         2 Text          |                                                   (Will default to U.S.)                                                   |                            B                            |    275    |   276   |
|           Form code            |         10 Text         |                                            BMC-91, BMC-91X, BMC-34, BMC-35, etc                                            |                            B                            |    277    |   286   |
|Full, primary or excess coverage|         1 Text          |If BMC-91X, P or E = indicator of primary or excess policy; 1 = Full under § 387.303T(b)(1); 2 = Full under § 387.303T(b)(2)|                            F                            |    287    |   287   |
|       Limit of liability       |        5 Numeric        |                                                       $ in Thousands                                                       |                            F                            |    288    |   292   |
| Underlying limit of liability  |        5 Numeric        |                                      $ in Thousands (will default to $000 if Primary)                                      |                            F                            |    293    |   297   |
|         Effective date         |         8 Text          |                                      MM/DD/YY Format for both Filing or Cancellation                                       |                            B                            |    298    |   305   |
|         Policy number          |         25 Text         |                                           Surety companies may enter bond number                                           |                            B                            |    306    |   330   |

(d) All registered insurers agree to furnish upon request to the FMCSA a duplicate original of any policy (or policies) and all endorsements, surety bond, trust fund agreement, or other filing.

[82 FR 5308, Jan. 17, 2017]