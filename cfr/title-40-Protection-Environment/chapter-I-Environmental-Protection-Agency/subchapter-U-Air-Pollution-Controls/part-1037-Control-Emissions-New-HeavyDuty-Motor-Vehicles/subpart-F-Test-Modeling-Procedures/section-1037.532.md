##### § 1037.532 Using computational fluid dynamics for calculating drag area (*C*dA). #####

This section describes an alternate method for calculating drag area, *C*dA, for tractors using commercially available computational fluid dynamics (CFD) software.

(a) For Phase 2 and later vehicles, use SAE J2966 (incorporated by reference, see § 1037.810), with the following clarifications and exceptions:

(1) Vehicles are subject to the requirement to meet standards based on the average of testing at yaw angles of +4.5° and −4.5°; however, you may submit your application for certification with CFD results based on only one of those yaw angles.

(2) For CFD code with a Navier-Stokes based solver, follow the additional steps in paragraph (d) of this section. For Lattice-Boltzmann based CFD code, follow the additional steps in paragraph (e) of this section.

(3) Simulate a Reynolds number of 5.1 million (based on a 102-inch trailer width) and an air speed of 65 mi/hr.

(4) Perform an open-road simulation (not the Wind Tunnel Simulation).

(5) Use a free stream turbulence intensity of 0.0%.

(6) Choose time steps that can accurately resolve intrinsic flow instabilities, consistent with good engineering judgment.

(7) The result must be drag area (*C*d*A*), not drag coefficient (*C*d), based on an air speed of 65 mi/hr.

(8) Submit information as described in paragraph (g) of this section.

(b) For Phase 1 tractors, apply the procedures as specified in paragraphs (c) through (f) of this section. Paragraphs (c) through (f) apply for Phase 2 and later vehicles only as specified in paragraph (a) of this section.

(c) To determine *C*dA values, perform CFD modeling based on a tractor-trailer combination using the manufacturer's tractor and a standard trailer. Perform all CFD modeling as follows:

(1) Specify a blockage ratio at or below 0.2% to simulate open-road conditions.

(2) Assume zero yaw angle.

(3) Model the tractor with an open grill and representative back pressures based on available data describing the tractor's pressure characteristics.

(4) Enable the turbulence model and mesh deformation.

(5) Model tires and ground plane in motion to simulate a vehicle moving forward in the direction of travel.

(6) Apply the smallest cell size to local regions on the tractor and trailer in areas of high flow gradients and smaller-geometry features (*e.g.,* the A-pillar, mirror, visor, grille and accessories, trailer-leading edge, trailer-trailing edge, rear bogey, tires, and tractor-trailer gap).

(7) Simulate a vehicle speed of 55 mi/hr.

(d) Take the following steps for CFD code with a Navier-Stokes formula solver:

(1) Perform an unstructured, time-accurate analysis using a mesh grid size with a total volume element count of at least 50 million cells of hexahedral and/or polyhedral mesh cell shape, surface elements representing the geometry consisting of no less than 6 million elements, and a near-wall cell size corresponding to a y+ value of less than 300.

(2) Perform the analysis with a turbulence model and mesh deformation enabled (if applicable) with boundary layer resolution of ±95%. Once the results reach this resolution, demonstrate the convergence by supplying multiple, successive convergence values for the analysis. The turbulence model may use k-epsilon (k-ε), shear stress transport k-omega (SST k-ω), or other commercially accepted methods.

(e) For Lattice-Boltzmann based CFD code, perform an unstructured, time-accurate analysis using a mesh grid size with total surface elements of at least 50 million cells using cubic volume elements and triangular and/or quadrilateral surface elements with a near-wall cell size of no greater than 6 mm on local regions of the tractor and trailer in areas of high flow gradients and smaller geometry features, with cell sizes in other areas of the mesh grid starting at twelve millimeters and increasing in size from this value as the distance from the tractor and trailer increases.

(f) You may ask us to allow you to perform CFD analysis using parameters and criteria other than those specified in this section, consistent with good engineering judgment. In your request, you must demonstrate that you are unable to perform modeling based on the specified conditions (for example, you may have insufficient computing power, or the computations may require inordinate time), or you must demonstrate that different criteria (such as a different mesh cell shape and size) will yield better results. In your request, you must also describe your recommended alternative parameters and criteria, and describe how this approach will produce results that adequately represent a vehicle's in-use performance. We may require that you supply data demonstrating that your selected parameters and criteria will provide a sufficient level of detail to yield an accurate analysis. If you request an alternative approach because it will yield better results, we may require that you perform CFD analysis using both your recommended criteria and parameters and the criteria and parameters specified in this section to compare the resulting key aerodynamic characteristics, such as pressure profiles, drag build-up, and turbulent/laminar flow at key points around the tractor-trailer combination.

(g) Include the following information in your request to determine *C*d*A* values using CFD:

(1) The name of the software.

(2) The date and version number of the software.

(3) The name of the company producing the software and the corresponding address, phone number, and Web site.

(4) Identify whether the software uses Navier-Stokes or Lattice-Boltzmann equations.

(5) Describe the input values you will use to simulate the vehicle's aerodynamic performance for comparing to coastdown results.

[81 FR 74048, Oct. 25, 2016, as amended at 86 FR 34476, June 29, 2021; 89 FR 29785, Apr. 22, 2024]