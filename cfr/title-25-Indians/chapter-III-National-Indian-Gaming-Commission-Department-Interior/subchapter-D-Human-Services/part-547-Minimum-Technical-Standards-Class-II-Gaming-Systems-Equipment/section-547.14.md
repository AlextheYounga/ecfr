##### § 547.14 What are the minimum technical standards for electronic random number generation? #####

(a) *Properties.* All RNGs must produce output having the following properties:

(1) Statistical randomness;

(2) Unpredictability; and

(3) Non-repeatability.

(b) *Statistical randomness.* (1) Numbers or other designations produced by an RNG must be statistically random individually and in the permutations and combinations used in the application under the rules of the game. For example, if a bingo game with 75 objects with numbers or other designations has a progressive winning pattern of the five numbers or other designations on the bottom of the card, and the winning of this prize is defined to be the five numbers or other designations that are matched in the first five objects drawn, the likelihood of each of the 75C5 combinations are to be verified to be statistically equal.

(2) Numbers or other designations produced by an RNG must pass the statistical tests for randomness to a 99% confidence level, which may include:

(i) Chi-square test;

(ii) Runs test (patterns of occurrences must not be recurrent); and

(iii) Serial correlation test potency and degree of serial correlation (outcomes must be independent from the previous game).

(iv) Equi-distribution (frequency) test;

(v) Gap test;

(vi) Poker test;

(vii) Coupon collector's test;

(viii) Permutation test;

(ix) Spectral test; or

(x) Test on subsequences.

(c) *Unpredictability.* (1) It must not be feasible to predict future outputs of an RNG, even if the algorithm and the past sequence of outputs are known.

(2) Unpredictability must be ensured by reseeding or by continuously cycling the RNG, and by providing a sufficient number of RNG states for the applications supported.

(3) Re-seeding may be used where the re-seeding input is at least as statistically random as, and independent of, the output of the RNG being re-seeded.

(d) *Non-repeatability.* The RNG may not be initialized to reproduce the same output stream that it has produced before, nor may any two instances of an RNG produce the same stream as each other. This property must be ensured by initial seeding that comes from:

(1) A source of “true” randomness, such as a hardware random noise generator; or

(2) A combination of timestamps, parameters unique to a Class II gaming system, previous RNG outputs, or other, similar method.

(e) *General requirements.* (1) Software that calls an RNG to derive game outcome events must immediately use the output returned in accordance with the game rules.

(2) The use of multiple RNGs is permitted as long as they operate in accordance with this section.

(3) RNG outputs must not be arbitrarily discarded or selected.

(4) Where a sequence of outputs is required, the whole of the sequence in the order generated must be used in accordance with the game rules.

(5) The Class II gaming system must neither adjust the RNG process or game outcomes based on the history of prizes obtained in previous games nor use any reflexive software or secondary decision that affects the results shown to the player or game outcome.

(f) *Scaling algorithms and scaled numbers.* An RNG that provides output scaled to given ranges must:

(1) Be independent and uniform over the range;

(2) Provide numbers scaled to the ranges required by game rules, and notwithstanding the requirements of paragraph (e)(3) of this section, may discard numbers that do not map uniformly onto the required range but must use the first number in sequence that does map correctly to the range;

(3) Be capable of producing every possible outcome of a game according to its rules; and

(4) Use an unbiased algorithm. A scaling algorithm is considered to be unbiased if the measured bias is no greater than 1 in 50 million.