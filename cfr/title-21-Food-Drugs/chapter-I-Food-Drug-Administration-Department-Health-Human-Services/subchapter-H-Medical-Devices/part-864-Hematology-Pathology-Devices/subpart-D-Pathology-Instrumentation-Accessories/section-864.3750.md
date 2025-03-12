##### § 864.3750 Software algorithm device to assist users in digital pathology. #####

(a) *Identification.* A software algorithm device to assist users in digital pathology is an in vitro diagnostic device intended to evaluate acquired scanned pathology whole slide images. The device uses software algorithms to provide information to the user about presence, location, and characteristics of areas of the image with clinical implications. Information from this device is intended to assist the user in determining a pathology diagnosis.

(b) *Classification.* Class II (special controls). The special controls for this device are:

(1) The intended use on the device's label and labeling required under § 809.10 of this chapter must include:

(i) Specimen type;

(ii) Information on the device input(s) (*e.g.,* scanned whole slide images (WSI), etc.);

(iii) Information on the device output(s) (*e.g.,* format of the information provided by the device to the user that can be used to evaluate the WSI, etc.);

(iv) Intended users;

(v) Necessary input/output devices (*e.g.,* WSI scanners, viewing software, etc.);

(vi) A limiting statement that addresses use of the device as an adjunct; and

(vii) A limiting statement that users should use the device in conjunction with complete standard of care evaluation of the WSI.

(2) The labeling required under § 809.10(b) of this chapter must include:

(i) A detailed description of the device, including the following:

(A) Detailed descriptions of the software device, including the detection/analysis algorithm, software design architecture, interaction with input/output devices, and necessary third-party software;

(B) Detailed descriptions of the intended user(s) and recommended training for safe use of the device; and

(C) Clear instructions about how to resolve device-related issues (*e.g.,* cybersecurity or device malfunction issues).

(ii) A detailed summary of the performance testing, including test methods, dataset characteristics, results, and a summary of sub-analyses on case distributions stratified by relevant confounders, such as anatomical characteristics, patient demographics, medical history, user experience, and scanning equipment, as applicable.

(iii) Limiting statements that indicate:

(A) A description of situations in which the device may fail or may not operate at its expected performance level (*e.g.,* poor image quality or for certain subpopulations), including any limitations in the dataset used to train, test, and tune the algorithm during device development;

(B) The data acquired using the device should only be interpreted by the types of users indicated in the intended use statement; and

(C) Qualified users should employ appropriate procedures and safeguards (e.g., quality control measures, etc.) to assure the validity of the interpretation of images obtained using this device.

(3) Design verification and validation must include:

(i) A detailed description of the device software, including its algorithm and its development, that includes a description of any datasets used to train, tune, or test the software algorithm. This detailed description of the device software must include:

(A) A detailed description of the technical performance assessment study protocols (e.g., regions of interest (ROI) localization study) and results used to assess the device output(s) (e.g., image overlays, image heatmaps, etc.);

(B) The training dataset must include cases representing different pre-analytical variables representative of the conditions likely to be encountered when used as intended (e.g., fixation type and time, histology slide processing techniques, challenging diagnostic cases, multiple sites, patient demographics, etc.);

(C) The number of WSI in an independent validation dataset must be appropriate to demonstrate device accuracy in detecting and localizing ROIs on scanned WSI, and must include subsets clinically relevant to the intended use of the device;

(D) Emergency recovery/backup functions, which must be included in the device design;

(E) System level architecture diagram with a matrix to depict the communication endpoints, communication protocols, and security protections for the device and its supportive systems, including any products or services that are included in the communication pathway; and

(F) A risk management plan, including a justification of how the cybersecurity vulnerabilities of third-party software and services are reduced by the device's risk management mitigations in order to address cybersecurity risks associated with key device functionality (such as loss of image, altered metadata, corrupted image data, degraded image quality, etc.). The risk management plan must also include how the device will be maintained on its intended platform (*e.g.* a general purpose computing platform, virtual machine, middleware, cloud-based computing services, medical device hardware, etc.), which includes how the software integrity will be maintained, how the software will be authenticated on the platform, how any reliance on the platform will be managed in order to facilitate implementation of cybersecurity controls (such as user authentication, communication encryption and authentication, etc.), and how the device will be protected when the underlying platform is not updated, such that the specific risks of the device are addressed (such as loss of image, altered metadata, corrupted image data, degraded image quality, etc.).

(ii) Data demonstrating acceptable, as determined by FDA, analytical device performance, by conducting analytical studies. For each analytical study, relevant details must be documented (e.g., the origin of the study slides and images, reader/annotator qualifications, method of annotation, location of the study site(s), challenging diagnoses, etc.). The analytical studies must include:

(A) Bench testing or technical testing to assess device output, such as localization of ROIs within a pre-specified threshold. Samples must be representative of the entire spectrum of challenging cases likely to be encountered when the device is used as intended; and

(B) Data from a precision study that demonstrates device performance when used with multiple input devices (e.g., WSI scanners) to assess total variability across operators, within-scanner, between-scanner and between-site, using clinical specimens with defined, clinically relevant, and challenging characteristics likely to be encountered when the device is used as intended. Samples must be representative of the entire spectrum of challenging cases likely to be encountered when the device is used as intended. Precision, including performance of the device and reproducibility, must be assessed by agreement between replicates.

(iii) Data demonstrating acceptable, as determined by FDA, clinical validation must be demonstrated by conducting studies with clinical specimens. For each clinical study, relevant details must be documented (e.g., the origin of the study slides and images, reader/annotator qualifications, method of annotation, location of the study site(s) (on-site/remote), challenging diagnoses, etc.). The studies must include:

(A) A study demonstrating the performance by the intended users with and without the software device (e.g., unassisted and device-assisted reading of scanned WSI of pathology slides). The study dataset must contain sufficient numbers of cases from relevant cohorts that are representative of the scope of patients likely to be encountered given the intended use of the device (e.g., subsets defined by clinically relevant confounders, challenging diagnoses, subsets with potential biopsy appearance modifiers, concomitant diseases, and subsets defined by image scanning characteristics, etc.) such that the performance estimates and confidence intervals for these individual subsets can be characterized. The performance assessment must be based on appropriate diagnostic accuracy measures (e.g., sensitivity, specificity, predictive value, diagnostic likelihood ratio, etc.).

(B) [Reserved]

[88 FR 7009, Feb. 2, 2023]