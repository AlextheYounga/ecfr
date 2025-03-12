##### § 510.301 Determination of reconciliation target prices. #####

Beginning with performance year 6, the quality-adjusted target price computed under § 510.300 is further adjusted for risk and market trends as described in this section to arrive at the reconciliation target price amount, with the exception of episodes that are reconciled in performance year 6 but subject to a performance year subset 5.2 target price. Specifically:

(a) *Risk adjustment.* (1) The quality-adjusted target prices computed under § 510.300 are risk adjusted at a beneficiary level by a CJR HCC count risk adjustment factor, an age bracket risk adjustment factor, and a dual-eligibility status risk adjustment factor. All three factors are binary, yes/no variables, meaning that a beneficiary either does or does not meet the criteria for a specific variable.

(i) The CJR HCC count risk adjustment factor uses five variables, representing beneficiaries with zero, one, two, three, or four or more CMS-HCC conditions.

(ii) The age bracket risk adjustment factor uses four variables, representing beneficiaries aged—

(A) Less than 65 years;

(B) 65 to 74 years;

(C) 75 years to 84 years; or

(D) 85 years or more.

(iii) The dual-eligibility status factor uses two variables, representing beneficiaries that are eligible for full Medicaid benefits or beneficiaries that are not eligible for full Medicaid benefits.

(2) All three factors are computed prior to the start of performance years 6 and 8 via a linear regression analysis. The regression analysis is computed using 1 year of claims data as follows:

(i) For performance year 6, CMS uses claims data with dates of service dated January 1, 2019 to December 31, 2019.

(ii) For performance year 7, CMS uses the same regression analysis results and corresponding coefficients that were calculated for performance year 6.

(iii) For performance year 8, CMS uses claims data with dates of service dated January 1, 2021 to December 31, 2021.

(3)(i) The dependent variable in the annual regression that produces the risk adjustment coefficients is equal to the difference between the log transformed target price calculated under § 510.300 and the capped episode costs as described in § 510.300(b)(5)(ii).

(ii) The independent variables are binary values assigned to each CJR HCC count variable, age bracket variable and dual-eligibility status variable.

(iii) Using these variables, the annual regression produces exponentiated coefficients to determine the anticipated marginal effect of each risk adjustment factor on episode costs. CMS transforms, or exponentiate, these coefficients in order to “reverse” the previous logarithmic transformation, and the resulting coefficients are the CJR HCC count risk adjustment factor, the age bracket risk adjustment factor, and the dual-eligibility status factor that would be used during reconciliation for the subsequent performance year.

(4)(i) At the time of reconciliation, the quality adjusted target prices computed under § 510.300 are risk adjusted at the beneficiary level by applying the applicable CJR HCC count risk adjustment factor, the age bracket risk adjustment factor, and the dual-eligibility risk adjustment factor specific to the beneficiary in the episode.

(ii)(A) For the CJR HCC count risk adjustment factor, applicable means the coefficient that applies to the CMS-HCC condition count for the beneficiary in the episode;

(B) For the age bracket risk adjustment factor, applicable means the coefficient for the age bracket into which the beneficiary falls on the first day of the episode; and

(C) For the dual-eligibility risk adjustment factor, applicable means the coefficient for beneficiaries that are eligible for full Medicaid benefits on the first day of the episode.

(5)(i) The risk-adjusted target prices are normalized at reconciliation to remove the overall impact of adjusting for age, CJR HCC count, and dual-eligibility status on the national average target price.

(ii) The normalization factor is the national mean of the target price for all episode types divided by the national mean of the risk-adjusted target price.

(iii) CMS applies the normalization factor to the previously calculated, beneficiary-level, risk-adjusted target prices specific to each episode region and MS-DRG combination (as specified in paragraph (a)(4) of this section).

(iv) These normalized target prices are then further adjusted for market trends (as specified in paragraph (b) of this section) and quality performance (as specified at § 510.300) to become the reconciliation target prices, which are compared to actual episode costs at reconciliation, as specified in § 510.305(m)(1)(i).

(b) *Market trend adjustment factor.* (1) The risk-adjusted quality-adjusted target price computed under § 510.300 and paragraph (a) of this section is further adjusted for market trend changes at the region and MS-DRG level.

(2) This adjustment is accomplished by multiplying each risk-adjusted quality-adjusted target price computed under § 510.300 and paragraph (a) of this section by the applicable market trend adjustment factor.

(3) The applicable market trend adjustment factor is calculated as the percent difference between the average regional MS-DRG episode costs computed using the performance year claims data and comparison average regional MS-DRG fracture episode costs computed using historical calendar year claims data used to calculate the regional target prices in effect for that performance year.

[86 FR 23571, May 3, 2021]