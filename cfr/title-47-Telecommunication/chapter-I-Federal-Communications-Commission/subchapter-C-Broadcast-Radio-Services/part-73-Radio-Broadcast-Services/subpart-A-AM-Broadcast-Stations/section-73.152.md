##### § 73.152 Modification of directional antenna data. #####

(a) If, after construction and final adjustment of a directional antenna, a measured inverse distance field in any direction exceeds the field shown on the standard radiation pattern for the pertinent mode of directional operation, an application shall be filed, specifying a modified standard radiation pattern and/or such changes as may be required in operating parameters so that all measured effective fields will be contained within the modified standard radiation pattern. Permittees may also file an application specifying a modified standard radiation pattern, even when measured radiation has not exceeded the standard pattern, in order to allow additional tolerance for monitoring point limits.

(b) If, following a partial proof of performance, a licensee discovers that radiation exceeds the standard pattern on one or more radials because of circumstances beyond the licensee's control, a modified standard pattern may be requested. The licensee shall submit, concurrently, Forms 301-AM and 302-AM. Form 301-AM shall include an exhibit demonstrating that no interference would result from the augmentation. Form 302-AM shall include the results of the partial proof, along with full directional and nondirectional measurements on the radial(s) to be augmented, including close-in points and a determination of the inverse distance field in accordance with § 73.186.

(c) Normally, a modified standard pattern is not acceptable at the initial construction permit stage, before a proof-of-performance has been completed. However, in certain cases, where it can be shown that modification is necessary, a modified standard pattern will be acceptable at the initial construction permit stage. Following is a non-inclusive list of items to be considered in determining whether a modification is acceptable at the initial construction permit stage:

(1) When the proposed pattern is essentially the same as an existing pattern at the same antenna site. (e.g., A DA-D station proposing to become a DA-1 station.)

(2) Excessive reradiating structures, which should be shown on a plat of the antenna site and surrounding area.

(3) Other environmental factors; they should be fully described.

(4) Judgment and experience of the engineer preparing the engineering portion of the application. This must be supported with a full discussion of the pertinent factors.

(d) The following general principles shall govern the situations in paragraphs (a), (b), and (c) in this section:

(1) Where a measured field in any direction will exceed the authorized standard pattern, the license application may specify the level at which the input power to the antenna shall be limited to maintain the measured field at a value not in excess of that shown on the standard pattern, and shall specify the common point current corresponding to this power level. This value of common point current will be specified on the license for that station.

(2) Where any excessive field does not result in objectionable interference to another station, a modification of construction permit application may be submitted with a modified standard pattern encompassing all augmented fields. The modified standard pattern shall supersede the previously submitted standard radiation pattern for that station in the pertinent mode of directional operation. Following are the possible methods of creating a modified standard pattern:

(i) The modified pattern may be computed by making the entire pattern larger than the original pattern (*i.e.*, have a higher RMS value) if the measured fields systematically exceed the confines of the original pattern. The larger pattern shall be computed by using a larger multiplying constant, k, in the theoretical pattern equation (Eq. 1) in § 73.150(b)(1).

(ii) Where the measured field exceeds the pattern in discrete directions, but objectionable interference does not result, the pattern may be expanded over sectors including these directions. When this “augmentation” is desired, it shall be achieved by application of the following equation:

E(φ,θ)aug = √ { E(φ,θ)std }2 + A{*g*(θ) *cos (180 D*A*/S* }2where:E(φ,θ)std is the standard pattern field at some particular azimuth and elevation angle, before augmentation, computed pursuant to Eq. 2, § 73.150(b)(1)(i).E(φ,θ)aug. is the field in the direction specified above, after augmentation.A = E(φ, O)2aug−E(φ, O)2std in which φ is the central azimuth of augmentation. E(φ, O)aug and E(φ, O)std are the fields in the horizontal plane at the central azimuth of augmentation.Note:

“A” must be positive, except during the process of converting non-standard patterns to standard patterns pursuant to the *Report and Order in Docket No. 21473,* and in making minor changes to stations with patterns developed during the conversion. However, even when “A” is negative, “A” cannot be so negative that E(φ,α)aug is less than E(φ,θ)th at any azimuth or vertical elevation angle.

g(θ) is defined in § 73.150(b)(1)(i).S is the angular range, or “span”, over which augmentation is applied. The span is centered on the central azimuth of augmentation. At the limits of the span, the augmented pattern merges into the unaugmented pattern. Spans may overlap.DA is the absolute horizontal angle between the azimuth at which the augmented pattern value is being computed and the central azimuth of augmentation. (DA cannot exceed 1/2 S.)In the case where there are spans which overlap, the above formula shall be applied repeatedly, once for each augmentation, in ascending order of central azimuth of augmentation, beginning with zero degrees representing true North. Note that, when spans overlap, there will be, in effect, an augmentation of an augmentation. And, if the span of an earlier augmentation overlaps the central azimuth of a later augmentation, the value of “A” for the later augmentation will be different than the value of “A” without the overlap of the earlier span.

(iii) A combination of paragraphs (d)(2)(i) and (d)(2)(ii), of this section, with (d)(2)(i) being applied before (d)(2)(ii) is applied.

(iv) Where augmentation is allowable under the terms of this section, the requested amount of augmentation shall be centered upon the measured radial and shall not exceed the following:

(A) The actual measured inverse distance field value, where the radial does not involve a required monitoring point.

(B) 120% of the actual measured inverse field value, where the radial has a monitoring point required by the instrument of authorization.

Whereas some pattern smoothing can be accommodated, the extent of the requested span(s) shall be minimized and in no case shall a requested augmentation span extend to a radial azimuth for which the analyzed measurement data does not show a need for augmentation.

(3) A Modified Standard Pattern shall be specifically labeled as such, and shall be plotted in accordance with the requirements of paragraph (b)(2) of § 73.150. The effective (RMS) field strength in the horizontal plane of E(φ,α)std, E(φ,α)th, and the root sum square (RSS) value of the inverse fields of the array elements (derived from the equation for E(φ,α)th), shall be tabulated on the page on which the horizontal plane pattern is plotted. Where sector augmentation has been employed in designing the modified pattern, the direction of maximum augmentation (*i.e.*, the central azimuth of augmentation) shall be indicated on the horizontal plane pattern for each augmented sector, and the limits of each sector shall also be shown. Field values within an augmented sector, computed prior to augmentation, shall be depicted by a broken line.

(4) There shall be submitted, for each modified standard pattern, complete tabulations of final computed data used in plotting the pattern. In addition, for each augmented sector, the central azimuth of augmentation, span, and radiation at the central azimuth of augmentation (E(φ,α)aug) shall be tabulated.

(5) The parameters used in computing the modified standard pattern shall be specified with realistic precision. Following is a list of the maximum acceptable precision:

(i) Central Azimuth of Augmentation: to the nearest 0.1 degree.

(ii) Span: to the nearest 0.1 degree.

(iii) Radiation at Central Azimuth of Augmentation: 4 significant figures.

(e) Sample calculations for a modified standard pattern follow. First, assume the existing standard pattern in § 73.150(c). Then, assume the following augmentation parameters:

|Augmentation number|Central azimuth|Span|Radiation at central azimuth|
|-------------------|---------------|----|----------------------------|
|         1         |      110      | 40 |           1,300            |
|         2         |      240      | 50 |             52             |
|         3         |      250      | 10 |            130             |

Following is a tabulation of part of the modified standard pattern:

|Azimuth|   0    |  30  |  60  |Vertical angle|
|-------|--------|------|------|--------------|
|   0   | 28.86  |68.05 |72.06 |              |
|  105  |1,299.42|872.14|254.21|              |
|  235  | 39.00  |35.74 |38.71 |              |
|  247  | 100.47 |66.69 |32.78 |              |

[46 FR 11992, Feb. 12, 1981, as amended at 56 FR 64862, Dec. 12, 1991; 66 FR 20756, Apr. 25, 2001]