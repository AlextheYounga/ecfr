##### § 17.00 Information to be furnished by futures commission merchants, clearing members and foreign brokers. #####

Link to an amendment published at 89 FR 47457, June 3, 2024.

(a) *Special accounts—reportable futures and options positions, delivery notices, and exchanges of futures.* (1) Each futures commission merchant, clearing member and foreign broker shall submit a report to the Commission for each business day with respect to all special accounts carried by the futures commission merchant, clearing member or foreign broker, except for accounts carried on the books of another futures commission merchant or clearing member on a fully-disclosed basis. Except as otherwise authorized by the Commission or its designee, such report shall be made in accordance with the format and coding provisions set forth in paragraph (g) of this section. The report shall show each futures position, separately for each reporting market and for each future, and each put and call options position separately for each reporting market, expiration and strike price en each special account as of the close of market on the day covered by the report and, in addition, the quantity of exchanges of futures for commodities or for derivatives positions and the number of delivery notices issued for each such account by the clearing organization of a reporting market and the number stopped by the account. The report shall also show all positions in all contract months and option expirations of that same commodity on the same reporting market for which the special account is reportable.

(2) A report covering the first day upon which a special account is no longer reportable shall also be filed showing the information specified in paragraph (a)(1) of this section.

(b) *Interest in or control of several accounts.* Except as otherwise instructed by the Commission or its designee and as specifically provided in § 150.4 of this chapter, if any person holds or has a financial interest in or controls more than one account, all such accounts shall be considered by the futures commission merchant, clearing member, or foreign broker as a single account for the purpose of determining special account status and for reporting purposes.

(1) *Accounts of eligible entities*—Accounts of eligible entities as defined in § 150.1 of this chapter that are traded by an independent account controller shall, together with other accounts traded by the independent account controller or in which the independent controller has a financial interest, be considered a single account.

(2) *Accounts controlled by two or more persons*—Accounts that are subject to day-to-day trading control by two or more persons shall, together with other accounts subject to control by exactly the same persons, be considered a single account.

(3) *Account ownership.* Multiple accounts owned by a trader shall be considered a single account as provided under §§ 150.4(b), (c) and (d) of this chapter.

(c) [Reserved]

(d) *Net positions.* Futures commission merchants, clearing members and foreign brokers shall report positions net long or short in each future of a commodity and each strike price of a put or call option for each expiration month in all special accounts, except as specified in paragraph (e) of this section.

(e) *Gross positions.* In the following cases, the futures commission merchant, clearing member or foreign broker shall report gross long and short positions in each future of a commodity and each strike price of a put or call option for each expiration month in all special accounts:

(1) Positions which are reported to an exchange or the clearinghouse of an exchange on a gross basis, which the exchange uses for calculating total open interest in a commodity;

(2) Positions in accounts owned or held jointly with another person or persons;

(3) Positions in multiple accounts subject to trading control by the same trader; and

(4) Positions in omnibus accounts.

(f) *Omnibus accounts.* If the total open long positions or the total open short positions for any future of a commodity carried in an omnibus account is a reportable position, the omnibus account is in Special Account status and shall be reported by the futures commission merchant or foreign broker carrying the account in accordance with paragraph (a) of this section.

(g) *Media and file characteristics.* (1) Except as otherwise approved by the Commission or its designee, all required records shall be submitted together in a single file. Each record will be 80 characters long. The specific record format is shown in the table below:

|                     Beginning column                      |Length|Type <sup>1</sup>|        Name        |
|-----------------------------------------------------------|------|-----------------|--------------------|
|                             1                             |  2   |       AN        |    Report Type.    |
|                             3                             |  3   |       AN        |  Reporting Firm.   |
|                             6                             |  2   |                 |     Reserved.      |
|                             8                             |  12  |       AN        |  Account Number.   |
|                            20                             |  8   |       AN        |    Report Date.    |
|                            28                             |  2   |       AN        |   Exchange Code.   |
|                            30                             |  1   |       AN        |    Put or Call.    |
|                            31                             |  5   |       AN        |Commodity Code (1). |
|                            36                             |  8   |       AN        |Expiration Date (1).|
|                            44                             |  7   |        S        |   Strike Price.    |
|                            51                             |  1   |       AN        |  Exercise Style.   |
|                            52                             |  7   |        N        | Long—Buy—Stopped.  |
|                            59                             |  7   |        N        | Short—Sell—Issued. |
|                            66                             |  5   |       AN        |Commodity Code (2). |
|                            71                             |  8   |       AN        |Expiration Date (2).|
|                            79                             |  2   |                 |     Reserved.      |
|                            80                             |  1   |       AN        |    Record Type.    |
|<sup>1</sup> AN—Alpha—numeric, N—Numeric, S—Signed numeric.|      |                 |                    |

(2) Field definitions are as follows:

(i) *Report type.* This report format will be used to report three types of data: long and short futures and options positions, futures delivery notices issued and stopped, and exchanges of futures for a commodity or for a derivatives position bought and sold. Valid values for the report type are “RP” for reporting positions, “DN” for reporting notices, and “EP” for reporting exchanges of futures for a commodity or for a derivatives position.

(ii) *Reporting firm.* The clearing member number assigned by an exchange or clearing house to identify reporting firms. If a firm is not a clearing member, a three-character alpha-numeric identifier assigned by the Commission.

(iii) *Account Number.* A unique identifier assigned by the reporting firm to each special account. The field is zero filled with the account number right-justified. Assignment of the account number is subject to the provisions of paragraph (b) of this section and appendix A of this part (Form 102).

(iv) *Report date.* The format is YYYYMMDD, where YYYY is the year, MM is the month, and DD is the day of the month.

(v) *Exchange.* This is a two-character field approved by the Commission to identify the exchange on which a position is held.

(vi) *Put or Call.* Valid values for this field are “C” for a call option and “P” for a put option. For futures, the field is blank.

(vii) *Commodity* (1). An exchange-assigned commodity code for the futures or options contract.

(viii) *Expiration date* (1). The date format is YYYYMMDD and represents the expiration date or delivery date of the reported futures or options contract. For date-specific instruments such as flexible products, the full date must be reported. For other options and futures, this field is used to report the expiration year and month for an options contract or a delivery year and month for a futures contract. The day portion of the field for these contracts contains spaces.

(ix) *Strike price.* This is a signed numeric field for reporting options strike prices. The strike prices should be right-justified and the field zero-filled. Strike prices must be reported in the same formats that are used by an exchange. For futures, the field is left blank.

(x) *Exercise style.* Valid values for this field are “A” for American style options, i.e., those that can be exercised at any time during the life of the options; and “E” for European, i.e., those that can be exercised only at the end of an option's life. This field is required only for flexible instruments or as otherwise specified by the Commission.

(xi) *Long-Buy-Stopped (Short-Sell-Issued).* When report type is “RP”, report long (short) positions open at the end of a trading day. When report is “DN”, report delivery notices stopped (issued) on behalf of the account. When report type is “EP”, report purchases (sales) of futures for a commodity or for a derivatives position for the account. Report all information in contracts. Position data are reported on a net or gross basis in accordance with paragraphs (d) and (e) of this section.

(xii) *Commodity* (2). The exchange assigned commodity code for a futures contract or other instrument that a position is exercised into from a date-specific or flexible option.

(xiii) *Expiration date* (2). Similar to other dates, the format is YYYYMMDD and represents the expiration date or delivery month and year of the future or other instrument that a position is exercised into from a date-specific or flexible option.

(xiv) *Record type* (1). Record type is used to correct errors or delete records that have previously been submitted. Valid values are “A”, “C”, “D” or “blank”. An A or “blank” is used in this field for all new records. If the record corrects information for a previously provided record, this field must contain a “C” or “blank” and the record must contain all information on the previously transmitted record. If the record deletes information on a previously provided record, this field must contain a “D” and all information on the previously transmitted record.

(h) *Correction of errors and omissions.* Unless otherwise approved by the Commission or its designee, corrections to errors and omissions in data provided pursuant to § 17.00(a) shall be filed on series ‘01 forms or in the format, coding structure and data transmission procedures approved in writing by the Commission or its designee.

(i) *Exclusively self-cleared contracts.* Unless determined otherwise by the Commission, reporting markets that list exclusively self-cleared contracts shall meet the requirements of paragraphs (a) through (h) of this section, as they apply to trading in such contracts by all clearing members, on behalf of all clearing members.

(Approved by the Office of Management and Budget under control number 3038-0009)[41 FR 3207, Jan. 21, 1976]Editorial Note:For Federal Register citations affecting § 17.00, see the List of CFR Sections Affected, which appears in the Finding Aids section of the printed volume and at *www.govinfo.gov.*