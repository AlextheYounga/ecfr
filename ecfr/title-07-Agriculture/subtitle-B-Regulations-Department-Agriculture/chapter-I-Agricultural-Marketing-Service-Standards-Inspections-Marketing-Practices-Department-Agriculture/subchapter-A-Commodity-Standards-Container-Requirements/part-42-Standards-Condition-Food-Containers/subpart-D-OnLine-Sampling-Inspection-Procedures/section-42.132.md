##### § 42.132 Determining cumulative sum values.

(a) The parameters for the on-line cumulative sum sampling plans for AQL's applicable to origin inspection are as follows:

| Acceptable quality levels | Type of inspection |
| ------------------------- | ------------------ |
| 0.25                      | 0.05               |
| 1.5                       | 0.5                |
| 6.5                       | 2                  |

(b) At the beginning of the basic inspection period, the CuSum value is set equal to the starting value (“S”) for the specified CuSum plan. The CuSum value is then determined for each consecutive subgroup as follows:

(1) Add the number of defects for the present subgroup to the CuSum value of the previous subgroup.

(2) Subtract the subgroup tolerance (“T”).

(3) The CuSum value is reset in the following situations; however, determine portion of production acceptability (see § 42.133) prior to resetting the CuSum value:

(i) Reset the CuSum value to zero (0) if the CuSum value is less than zero (0).

(ii) Reset the CuSum value to the acceptance limit (“L”) if the CuSum value exceeds the acceptance limit (“L”).