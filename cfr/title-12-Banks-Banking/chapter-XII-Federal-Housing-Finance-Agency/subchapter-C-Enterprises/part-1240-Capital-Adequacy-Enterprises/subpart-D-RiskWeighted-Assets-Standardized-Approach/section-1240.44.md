##### § 1240.44 Credit risk transfer approach (CRTA). #####

(a) *General requirements for the CRTA.* To use the CRTA to determine the risk weighted assets for a retained CRT exposure, an Enterprise must have data that enables it to assign accurately the parameters described in paragraph (b) of this section. Data used to assign the parameters described in paragraph (b) of this section must be the most currently available data; if the contracts governing the underlying exposures of the credit risk transfer require payments on a monthly or quarterly basis, the data used to assign the parameters described in paragraph (b) of this section must be no more than 91 calendar days old. An Enterprise that does not have the appropriate data to assign the parameters described in paragraph (b) of this section must assign a risk weight of 1,250 percent to the retained CRT exposure.

(b) *CRTA parameters.* To calculate the risk weighted assets for a retained CRT exposure, an Enterprise must have accurate information on the following ten inputs to the CRTA calculation.

(1) Parameter *A* is the attachment point for the exposure, which represents the threshold at which credit losses will first be allocated to the exposure. Parameter *A* equals the ratio of the current dollar amount of underlying exposures that are subordinated to the exposure of the Enterprise to the current dollar amount of underlying exposures. Any reserve account funded by the accumulated cash flows from the underlying exposures that is subordinated to the Enterprise's exposure may be included in the calculation of parameter *A* to the extent that cash is present in the account. Parameter *A* is expressed as a value between 0 and 100 percent.

(2) Parameter *AggUPB*$ is the aggregate unpaid principal balance of the underlying mortgage exposures.

(3) Parameter *CM*% is the percentage of a tranche sold in the capital markets. *CM*% is expressed as a value between 0 and 100 percent.

(4) Parameter *Collat*%RIF is the amount of financial collateral posted by a counterparty under a loss sharing contract expressed as a percentage of the risk in force. For multifamily lender loss sharing transactions where an Enterprise has the contractual right to receive future lender guarantee-fee revenue, the Enterprise may include up to 12 months of estimated lender retained servicing fees in excess of servicing costs on the multifamily mortgage exposures subject to the loss sharing contract. *Collat*%RIF is expressed as a value between 0 and 100 percent.

(5) Parameter *D* is the detachment point for the exposure, which represents the threshold at which credit losses of principal allocated to the exposure would result in a total loss of principal. Parameter *D* equals parameter *A* plus the ratio of the current dollar amount of the exposures that are *pari passu* with the exposure (that is, have equal seniority with respect to credit risk) to the current dollar amount of the underlying exposures. Parameter *D* is expressed as a value between 0 and 100 percent.

(6) Parameter *EL*$ is the remaining lifetime net expected credit risk losses of the underlying mortgage exposures. *EL*$ must be calculated internally by an Enterprise. If the contractual terms of the CRT do not provide for the transfer of the counterparty credit risk associated with any loan-level credit enhancement or other loss sharing on the underlying mortgage exposures, then the Enterprise must calculate *EL*$ assuming no counterparty haircuts. Parameter *EL*$ is expressed in dollars.

(7) Parameter *HC* is the haircut for the counterparty in contractual loss sharing transactions.

(i) For a CRT with respect to single-family mortgage exposures, the counterparty haircut is set forth in table 12 to paragraph (e)(3)(ii) in § 1240.33, determined as if the counterparty to the CRT were a counterparty to loan-level credit enhancement (as defined in § 1240.33(a)) and considering the counterparty rating and mortgage concentration risk of the counterparty to the CRT and the single-family segment and product of the underlying single-family mortgage exposures.

(ii) For a CRT with respect to multifamily mortgage exposures, the counterparty haircut is set forth in table 1 to this paragraph (b)(7)(ii), with counterparty rating and mortgage concentration risk having the meaning given in § 1240.33(a).

![](/graphics/er17de20.046.gif)

(8) Parameter *LS*% is the percentage of a tranche that is either insured, reinsured, or afforded coverage through lender reimbursement of credit losses of principal. *LS*% is expressed as a value between 0 and 100 percent.

(9) Parameter *LTF*% is the loss timing factor which accounts for maturity differences between the CRT and the underlying mortgage exposures. Maturity differences arise when the maturity date of the CRT is before the maturity dates of the underlying mortgage exposures. *LTF*% is expressed as a value between 0 and 100 percent.

(i) An Enterprise must have the following information to calculate *LTF*% for a CRT with respect to multifamily mortgage exposures:

(A) The remaining months to the contractual maturity of the CRT (*CRT*RMM).

(B) The UPB-weighted-average remaining months to maturity of the underlying multifamily mortgage exposures that have remaining months to maturity greater than *CRT*RMM (*MME*RMM). If the underlying multifamily mortgage exposures all have maturity dates less than or equal to *CRT*RMM, *MME*RMM should equal *CRT*RMM.

(C) The sum of UPB on the underlying multifamily mortgage exposures that have remaining loan terms less than or equal to *CRT*RMM expressed as a percent of total UPB on the underlying multifamily mortgage exposures (*LTFUPB%*).

(D) An Enterprise must use the following method to calculate LTF% for multifamily CRTs:

![](/graphics/er17de20.047.gif)

(ii) An Enterprise must have the following information to calculate *LTF*% for a newly issued CRT with respect to single-family mortgage exposures:

(A) The original closing date (or effective date) of the CRT and the maturity date on the CRT.

(B) UPB share of single-family mortgage exposures that have original amortization terms of less than or equal to 189 months (*CRTF15*%).

(C) UPB share of single-family mortgage exposures that have original amortization terms greater than 189 months and OLTVs of less than or equal to 80 percent (*CRT80NotF15*%).

(D) The duration of seasoning.

(E) An Enterprise must use the following method to calculate LTF% for single-family CRTs: Calculate CRT months to maturity (*CRTMthstoMaturity*) using one of the following methods:

(*1*) For single-family CRTs with reimbursement based upon occurrence or resolution of delinquency, *CRTMthstoMaturity* is the difference between the CRT's maturity date and original closing date, except for the following:

(*i*) If the coverage based upon delinquency is between one and three months, add 24 months to the difference between the CRT's maturity date and original closing date; and

(*ii*) If the coverage based upon delinquency is between four and six months, add 18 months to the difference between the CRT's maturity date and original closing date.

(*2*) For all other single-family CRTs, *CRTMthstoMaturity* is the difference between the CRT's maturity date and original closing date.

(*i*) If *CRTMthstoMaturity* is a multiple of 12, then an Enterprise must use the first column of Table 2 to paragraph (b)(9)(ii)(E)(*2*)(*iii*) of this section to identify the row matching *CRTMthstoMaturity* and take a weighted average of the three loss timing factors in columns 2, 3, and 4 as follows:

*LTF*% = (*CRTLT*15 \* *CRTLT*15%) + (*CRTLT*80*Not*15 \* *CRTLT*80*NotF*15%) + (*CRTLTGT*80*Not*15 \* (1 − *CRT*80*NotF*15% − *CRTF*15%))

(*ii*) If *CRTMthstoMaturity* is not a multiple of 12, an Enterprise must use the first column of Table 2 to paragraph (b)(9)(ii)(E)(*2*)(*iii*) of this section to identify the two rows that are closest to *CRTMthstoMaturity* and take a weighted average between the two rows of loss timing factors using linear interpolation, where the weights reflect *CRTMthstoMaturity.*

(*iii*) For seasoned single-family CRTs, the *LTF%* is calculated:

![](/graphics/er17de20.049.gif)where:*CRTLT*M is the loss timing factor calculated under (ii) of this subsection.*CRTLT*S is the loss timing factor calculated under (ii) of this subsection replacing *CRTMthstoMaturity* with the duration of seasoning.*CRTMthstoMaturity* is calculated as per (E) of this section.*CRTLT*15 is the CRT loss timing factor for pool groups backed by single-family mortgage exposures with original amortization terms \<= 189 months.*CRTLT*80*Not*15: is the CRT loss timing factor for pool groups backed by single-family mortgage exposures with original amortization terms \> 189 months and OLTVs \<=80 percent.*CRTLTGT*80*Not*15 is the CRT loss timing factor for pool groups backed by single-family mortgage exposures with original amortization terms \> 189 months and OLTVs \> 80 percent.![](/graphics/er17de20.050.gif)

(10) Parameter *RWA*$ is the aggregate credit risk-weighted assets associated with the underlying mortgage exposures.

(11) Parameter *CntptyRWA*$ is the aggregate credit risk-weighted assets due to counterparty haircuts from loan-level credit enhancements. *CntptyRWA*$ is the difference between:

(i) Parameter *RWA*$; and

(ii) Aggregate credit risk-weighted assets associated with the underlying mortgage exposures where the counterparty haircuts for loan-level credit enhancements are set to zero.

(c) *Mechanics of the CRTA.* The risk weight assigned to a retained CRT exposure, or portion of a retained CRT exposure, as appropriate, is the larger of *RW*% determined in accordance with paragraph (d) of this section and a risk weight of 10 percent.

(1) When the detachment point, parameter *D,* for a retained CRT exposure is less than or equal to the sum of *K*A and *AggEL*%, the exposure must be assigned a risk weight of 1,250 percent.

(2) When the attachment point, parameter *A,* for a retained CRT exposure is greater than or equal to or equal to the sum of *K*A and *AggEL*%,
determined in accordance with paragraph (d) of this section, the exposure must be assigned a risk weight of 10 percent.

(3) When parameter *A* is less than or equal to the sum of *K*A and*AggEL*%, and
parameter *D* is greater than the sum of *K*A and *AggEL*%, the Enterprise must calculate the risk weight as the sum of:

(i) 1,250 percent multiplied by the ratio of (A) the sum of *K*A and*AggEL*% minus parameter *A* to (B) the difference between parameter *D* and parameter *A*; and

(ii) 10 percent multiplied by the ratio of (A) parameter *D* minus the sum of *K*A and *AggEL*% to (B) the difference between parameter *D* and parameter *A.*

(d) *CRTA equations.*

![](/graphics/er17de20.052.gif)

If the contractual terms of the CRT do not provide for the transfer of the counterparty credit risk associated with any loan-level credit enhancement or other loss sharing on the underlying mortgage exposures, then the Enterprise shall calculate *K*A as follows:

![](/graphics/er17de20.053.gif)

Otherwise the Enterprise shall calculate *K*A as follows:

![](/graphics/er17de20.054.gif)

(e) *Limitations.* Notwithstanding any other provision of this section, an Enterprise must assign an overall risk weight of not less than 10 percent to a retained CRT exposure.

(f) *Adjusted exposure amount (AEA)* - (1) *In general.* The adjusted exposure amount (AEA) of a retained CRT exposure is equal to:

![](/graphics/er17de20.055.gif)

(2) *Inputs* - (i) *Enterprise adjusted exposure.* The adjusted exposure (EAE) of an Enterprise with respect to a retained CRT exposure is as follows:

*EAE*%,Tranche = 100% − (*CM*%,Tranche \**LTEA*%,Tranche,CM \* *OEA*%) − (*LS*%,Tranche \* *LSEA*%,Tranche \* *LTEA*%,Tranche,LS \* *OEA*%),Where the loss timing effectiveness adjustments (LTEA) for a retained CRT exposure are determined under paragraph (g) of this section, the loss sharing effectiveness adjustment (LSEA) for a retained CRT exposure is determine under paragraph (h) of this section, and the overall effectiveness adjustment (OEA) is determined under paragraph (i) of this section.

(ii) *Expected loss share.* The expected loss share is the share of a tranche that is covered by expected loss (ELS):

![](/graphics/er17de20.056.gif)

(iii) *Risk weight.* The risk weight of a retained CRT exposure is determined under paragraph (d) of this section.

(g) *Loss timing effectiveness adjustments.* The loss timing effectiveness adjustments (LTEA) for a retained CRT exposure is calculated according to the following calculation:

*i*ƒ (*SLS*%,Tranche − *ELS*%,Tranche) \> 0 *then**LTEA*%,Tranche,CM![](/graphics/er17de20.057.gif)*LTEA*%,Tranche,LS![](/graphics/er17de20.058.gif)

*Otherwise LTEA*%,Tranche,CM = 100% *and LTEA*%,Tranche,LS = 100%

where KA adjusted for loss timing (LTKA) is as follows:*LTK*A,CM = max ((*K*A + *AggEL*%) \* *LTF*%,CM − *AggEL*%, 0%)*LTK*A,LS = max ((*K*A + *AggEL*%) \* *LTF*%,LS − *AggEL*%, 0%)and

*LTF*%,CM is LTF% calculated for the capital markets component of the tranche,

*LTF*%,LS is LTF% calculated for the loss sharing component of the tranche, and the share of the tranche that is covered by expected loss (ELS) and the share of the tranche that is covered by stress loss (SLS) are as follows:

![](/graphics/er17de20.059.gif)

(h) *Loss sharing effectiveness adjustment.* The loss sharing effectiveness adjustment (LSEA) for a retained CRT exposure is calculated according to the following calculation:

*if* (*RW*%,Tranche − *ELS*%,Tranche \* 1250%) \> 0 *then*![](/graphics/er17de20.060.gif)*Otherwise**LSEA*%,Tranche = 100%*where**UnCollatUL*%,Tranche = *max*(0%,*SLS*%,Tranche − *max*(*Collat*%RIF,Tranche, *ELS*%,Tranche))*SRIF*%,Tranche = 100% − *max*(*SLS*%,Tranche, *Collat*%RIF,Tranche)and the share of the tranche that is covered by expected loss (ELS) and the share of the tranche that is covered by stress loss (SLS) are as follows:![](/graphics/er17de20.061.gif)

(i) *Overall effectiveness adjustment.* The overall effectiveness adjustment (OEA) for a retained CRT exposure is calculated according to the following calculation:

![](/graphics/er17de20.062.gif)

(j) *RWA supplement for retained loan-level counterparty credit risk.* If the Enterprise elects to use the CRTA for a retained CRT exposure and if the contractual terms of the CRT do not provide for the transfer of the counterparty credit risk associated with any loan-level credit enhancement or other loss sharing on the underlying mortgage exposures, then the Enterprise must add the following risk-weighted assets supplement (*RWASup*$) to risk weighted assets for the retained CRT exposure.

*RWASup*$,Tranche = *CntptyRWA*$ \* (*D*−*A*)Otherwise the Enterprise shall add an *RWASup*$,Tranche of $0.

(k) *Retained CRT Exposure.* Credit risk-weighted assets for the retained CRT exposure are as follows:

*RWA*$,Tranche = *AEA*$,Tranche \* *RW*%,Tranche + *RWASup*$,Tranche