##### § 1037.555 Special procedures for testing Phase 1 hybrid systems. #####

This section describes a powertrain testing procedure for simulating a chassis test with a pre-transmission or post-transmission hybrid system to perform A to B testing of Phase 1 vehicles. These procedures may also be used to perform A to B testing with non-hybrid systems. See 40 CFR 1036.545 for Phase 2 and later hybrid systems.

(a) Set up the engine according to 40 CFR 1065.110 to account for work inputs and outputs and accessory work.

(b) Collect CO2 emissions while operating the system over the test cycles specified in § 1037.510(a)(1).

(c) Collect and measure emissions as described in 40 CFR part 1066. Calculate emission rates in grams per ton-mile without rounding. Determine values for *A, B, C,* and *M* for the vehicle being simulated as specified in 40 CFR part 1066. If you will apply an improvement factor or test results to multiple vehicle configurations, use values of *A, B, C, M,**k*a, and *r* that represent the vehicle configuration with the smallest potential reduction in greenhouse gas emissions as a result of the hybrid capability.

(d) Calculate the transmission output shaft's angular speed target for the driver model, *f*nref,driver, from the linear speed associated with the vehicle cycle using the following equation:

![](/graphics/er29jn21.145.gif)Where:*v*cyclei = vehicle speed of the test cycle for each point, *i,* starting from *i* = 1.*k*a = drive axle ratio, as declared by the manufacturer.*r* = radius of the loaded tires, as declared by the manufacturer.

(e) Use speed control with a loop rate of at least 100 Hz to program the dynamometer to follow the test cycle, as follows:

(1) Calculate the transmission output shaft's angular speed target for the dynamometer, *f*nref,dyno, from the measured linear speed at the dynamometer rolls using the following equation:

![](/graphics/er29jn21.146.gif)![](/graphics/er29jn21.147.gif)Where:*T* = instantaneous measured torque at the transmission output shaft.*F*brake = instantaneous brake force applied by the driver model to add force to slow down the vehicle.*t* = elapsed time in the driving schedule as measured by the dynamometer, in seconds.

(2) For each test, validate the measured transmission output shaft's speed with the corresponding reference values according to 40 CFR 1065.514(e). You may delete points when the vehicle is stopped. Perform the validation based on speed values at the transmission output shaft. For steady-state tests (55 mi/hr and 65 mi/hr cruise), apply cycle-validation criteria by treating the sampling periods from the two tests as a continuous sampling period. Perform this validation based on the following parameters:

|                 Parameter                  |        Speed control         |
|--------------------------------------------|------------------------------|
|            Slope, a<sub>1</sub>            |0.950 ≤ a<sub>1</sub> ≤ 1.030.|
|Absolute value of intercept, |a<sub>0</sub>|| ≤2.0% of maximum test speed. |
|    Standard error of the estimate, SEE     |  ≤5% of maximum test speed.  |
|Coefficient of determination, r<sup>2</sup> |           ≥0.970.            |

(f) Send a brake signal when operator demand is equal to zero and vehicle speed is greater than the reference vehicle speed from the test cycle. Set a delay before changing the brake state to prevent the brake signal from dithering, consistent with good engineering judgment.

(g) The driver model should be designed to follow the cycle as closely as possible and must meet the requirements of § 1037.510 for steady-state testing and 40 CFR 1066.425 for transient testing. The driver model should be designed so that the brake and throttle are not applied at the same time.

(h) Correct for the net energy change of the energy storage device as described in 40 CFR 1066.501(a)(3).

(i) Follow the provisions of § 1037.510 to weight the cycle results and § 1037.615 to calculate improvement factors and benefits for advanced technologies for Phase 1 vehicles.

[81 FR 74048, Oct. 25, 2016, as amended at 86 FR 34483, June 29, 2021; 88 FR 4652, Jan. 24, 2023; 89 FR 29786, Apr. 22, 2024]