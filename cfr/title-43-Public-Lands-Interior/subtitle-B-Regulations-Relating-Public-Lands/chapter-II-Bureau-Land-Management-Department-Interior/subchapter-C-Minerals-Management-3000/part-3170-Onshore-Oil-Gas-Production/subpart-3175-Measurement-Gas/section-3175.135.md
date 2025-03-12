##### § 3175.135 Uncertainty determination. #####

(a) Reference uncertainty calculations for each transducer of a given make, model, URL, and turndown must be determined as follows (the result for each transducer is denoted by the subscript i):

(1) *Maximum error* (*E*i). The maximum error for each transducer is the maximum difference between any input value from the test device and the corresponding output from the transducer under test for any required test point, and must be expressed in percent of transducer span.

(2) *Hysteresis* (*H*i). The testing required in § 3175.132 requires at least three pairs of tests using both ascending test points (low to high) and descending test points (high to low) of the same value. Hysteresis is the maximum difference between the ascending value and the descending value for any single input test value of a test pair. Hysteresis must be expressed in percent of span.

(3) *Repeatability* (*R*i). The testing required under § 3175.132 requires at least three pairs of tests using both ascending test points (low to high) and descending test points (high to low) of the same value. Repeatability is the maximum difference between the value of any of the three ascending test points for a given input value or of the three descending test points for a given value. Repeatability must be expressed in percent of span.

(b) *Reference uncertainty of a transducer.* The reference uncertainty of each transducer of a given make, model, URL, and turndown (Ur,i) must be determined as follows:

![](/graphics/er17no16.068.gif)Where Ei, Hi, and Ri, are described in paragraph (a) of this section. Reference uncertainty is expressed in percent of span.

(c) Reference uncertainty for the make, model, URL, and turndown of a transducer (Ur) must be determined as follows:

*U*r = s × *t*distWhere:s = the standard deviation of the reference uncertainties determined for each transducer (Ur,i)tdist = the “t-distribution” constant as a function of degrees of freedom (n-1) and at a 95 percent confidence level, where n = the number of transducers of a specific make, model, URL, and turndown tested (minimum of 5)

(d) *Influence effects.* The uncertainty from each influence effect required to be tested under § 3175.133 must be determined as follows:

(1) *Zero-based errors of each transducer.* Zero-based errors from each influence test must be determined as follows:

![](/graphics/er17no16.069.gif)Where:subscript i represents the results for each transducer tested of a given make, model, URL, and turndownsubscript n represents the results for each influence effect test required under § 3175.133Ezero,n,i = Zero-based error for influence effect n, for transducer i, in percent of span per increment of influence effectMn = the magnitude of influence effect n (*e.g.,* 1,000 psi for static-pressure effects, 50 °F for ambient temperature effects)And:D*Z*n,i = *Z*n,i−*Z*ref ,iWhere:Zn,i = the average output from transducer i with zero input from the test device, during the testing of influence effect nZref,i = the average output from transducer i with zero input from the test device, during reference testing.

(2) *Span-based errors of each transducer.* Span-based errors from each influence effect must be determined as follows:

![](/graphics/er17no16.070.gif)Where:Espan,n,i = Span-based error for influence effect n, for transducer i, in percent of reading per increment of influence effectSn,i = the average output from transducer i, with full span applied from the test device, during the testing for influence effect n.

(3) Zero- and span-based errors due to influence effects for a make, model, URL, and turndown of a transducer must be determined as follows:

*E*z,n = sz,n × tdist*E*s,n = ss,n × *t*distWhere:Ez,n = the zero-based error for a make, model, URL, and turndown of transducer, for influence effect n, in percent of span per unit of magnitude for the influence effectEs,n = the span-based error for a make, model, URL, and turndown of transducer, for influence effect n, in percent of reading per unit of magnitude for the influence effectsz,n = the standard deviation of the zero-based differences from the influence effect tests under § 3175.133 and the reference uncertainty tests, in percentss,n = the standard deviation of the span-based differences from the influence effect tests under § 3175.133 and the reference uncertainty tests, in percenttdist = the “t-distribution” constant as a function of degrees of freedom (n-1) and at a 95 percent confidence level, where n = the number of transducers of a specific make, model, URL, and turndown tested (minimum of 5).