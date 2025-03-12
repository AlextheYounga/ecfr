##### § 1236.54 Metadata requirements. #####

(a) *General.* To ensure that intellectual and physical control of the digital records can be maintained, this regulation specifies metadata elements that must be captured in a recordkeeping system, or embedded in each file, or both captured in a recordkeeping system and embedded in each file. Ensure that the metadata remains accurate and consistent regardless of where it is stored.

(1) If using metadata to capture relationships between source records as required in § 1236.42(b), agencies must use the “Relation” metadata elements in table 1 to paragraph (c)(1) of this section for basic administrative metadata.

(2) If using different metadata labels from the ones required in this section, agencies must document the labels that the agency uses and note this in the Details section of the ERA (Electronic Records Archive) Transfer Request (TR).

(3) Determine the appropriate level to be used as the source of descriptive metadata. Depending on the agency's existing recordkeeping practices and level of intellectual control, use information from the project, record series, file unit, or item level as the source for administrative, technical, and descriptive metadata fields. If the components of a record have not been individually indexed with unique descriptions, apply the series or file unit-level descriptions to all of the image files within that grouping. If the components of the record do not have individual titles, the agency must apply the item Record IDs instead.

(4) Include additional metadata if it is captured. If other metadata elements are provided in addition to the metadata requirements in this subpart, NARA will accept that metadata as part of the transfer process.

(b) *Metadata capture requirements.* Agencies must:

(1) Capture the metadata specified by paragraphs (c) through (e) of this section at the file or item level as part of the digitization project;

(2) Create file names and record IDs that are unique to each image file;

(3) Embed the metadata specified by paragraph (c) of this section in each image file, capture and maintain it in a recordkeeping system, associate it with the records it describes, and keep it consistent and accurate in both places;

(4) Ensure that scanning equipment embeds the system-generated technical metadata specified by table 4 to paragraph (e)(1) of this section for format technical metadata and table 5 to paragraph (e)(2) of this section for processing technical metadata in each image file, and ensure that image processing does not alter or delete it; and

(5) Transfer metadata to NARA in CSV format.

(c) *Administrative metadata.* (1) Capture in a recordkeeping system and embed in each image file the following administrative metadata:

|          Metadata label           |                                                                                                    Description                                                                                                     |                                                    Requirement level                                                     |
|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|
|       Identifier: File Name       |                                                                          The complete name of the computer file, including its extension                                                                           |Mandatory (file names are an inherent attribute of each file so there is no need to embed them as an element of metadata).|
|       Identifier: Record ID       |                          The unique identifier assigned by an agency or a records management system. 36 CFR 1236.20(b)(1) requires that agencies assign unique identifiers to each record                          |                                                        Mandatory.                                                        |
|Identifier: Records Schedule Item #|                                                             The number assigned to the agency records schedule or GRS item to which the record belongs                                                             |                                                        Mandatory.                                                        |
|        Relation: Has Part         |A related record that is either physically or logically required in order to form a complete record. Mixed-media files that contain records on multiple media types must use this element to identify all components|      Mandatory if a record includes multiple parts, such as the component parts of a case file or mixed-media file.      |
|       Relation: Is Part Of        |                    A related record or file in which the described record is physically or logically included. Use this element to indicate that a record is a component of a mixed-media file                     |                                 Mandatory if file is a component of a multi-part record.                                 |

(2) Capture in a recordkeeping system and embed in each file any of the following access and use restrictions the metadata inherited from the source records:

|   Metadata label    |      Required fields      |                                                                                                                 Description                                                                                                                 |          Requirement level           |
|---------------------|---------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------|
| Access Restrictions | Access Restriction Status |                                                                                     Indicate whether or not there are access restrictions on the record                                                                                     |              Mandatory.              |
|                     |Specific Access Restriction|Specific access restrictions on the record, based on national security considerations, donor restrictions, court orders, and other statutory or regulatory provisions, including Privacy Act and Freedom of Information Act (FOIA) exemptions|Mandatory if access restriction exists|
|  Use Restrictions   |  Use Restriction Status   |                                                                                      Indicate whether or not there are use restrictions on the record                                                                                       |              Mandatory.              |
|                     | Specific Use Restriction  |                                                           The type of use restrictions on the record, based on copyright, trademark, service mark, donor, or statutory provisions                                                           | Mandatory if use restriction exists. |
|Rights: Rights Holder|                           |                                                                       A person or organization owning or managing intellectual property rights relating to the record                                                                       |Mandatory if there is a rights holder.|

(d) *Descriptive metadata.* Capture the following descriptive metadata from source records at the lowest level needed to support access and preservation and to maintain contextual information. Depending on the agency's existing recordkeeping practices and level of intellectual control, it may use information from the project level, record series, file unit, or item, as the source for descriptive metadata. If the components of a record have not been individually indexed with unique descriptions, apply the series or file unit-level descriptions to all of the image files within that grouping. If source records share a common material type or dimensions, auto-populate the source type and source dimension metadata. If the components of the record do not have individual titles, the agency must apply the item Record IDs instead. Capture the metadata in a recordkeeping system for each image file:

|  Metadata label   |                                                                    Description                                                                     |Requirement level|
|-------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|-----------------|
|       Title       |A name given to the source record. If a name does not exist, the mandatory metadata element Identifier: Record ID serves as the title for the record|   Mandatory.    |
|    Description    |                               A narrative description of the content of the record, including abstracts of documents                               |   Mandatory.    |
|      Creator      |                     The agent (person, agency, other organization, etc.) primarily responsible for creating the source record                      |   Mandatory.    |
|Date: Creation Date|                          The date or date range indicating when the source record met the definition of a Federal record                           |   Mandatory.    |
|    Source Type    |                                  The medium of the source record that was scanned to create a digital still image                                  |   Mandatory.    |
| Source Dimensions |                                          The dimensions of the source record (including unit of measure)                                           |   Mandatory.    |

(e) *Technical metadata.* (1) Ensure that the following values are embedded in each image file and that image processing does not delete or alter them:

| Metadata label  |                                       Definition                                       |Requirement level|
|-----------------|----------------------------------------------------------------------------------------|-----------------|
|Date Time Created|                The date or date-and-time the digital image was created                 |   Mandatory.    |
|   Image Width   |       The width of the digital image, i.e., horizontal or X dimension, in pixels       |   Mandatory.    |
|  Image Height   |       The height of the digital image, i.e., vertical or Y dimension, in pixels        |   Mandatory.    |
|   Color Space   |           The name of the International Color Consortium (ICC) profile used            |   Mandatory.    |
| Bits Per Sample |                              Number of bits per component                              |   Mandatory.    |
|Samples Per Pixel|The number of components per pixel. Usually, 1 for grayscale images and 3 for RGB images|   Mandatory.    |

(2) Ensure that the following process metadata elements are recorded for each image file:

|       Metadata label        |                               Definition                                |          Requirement level          |
|-----------------------------|-------------------------------------------------------------------------|-------------------------------------|
|   Scanner Make and Model    |   The manufacturer and model of the scanner used to create the image    |    Mandatory if using a scanner.    |
|Digital Camera Make and Model|The manufacturer and model of the digital camera used to create the image|Mandatory if using a digital camera. |
|  Software Name and Version  |     The name and version of the software used to capture the image      |Mandatory if using scanning software.|

(3) Capture the following technical metadata in a recordkeeping system for each image file, and use them to monitor digital records for corruption or alteration:

|  Fixity metadata label  |                                          Description                                          |                      Requirement level                      |
|-------------------------|-----------------------------------------------------------------------------------------------|-------------------------------------------------------------|
|Message Digest Algorithm |The specific algorithm used to construct the message digest for the digital object or bitstream|Mandatory if using checksums as described in § 1236.42(e)(1).|
|Message Digest (checksum)|                            The output of Message Digest Algorithm                             |Mandatory if using checksums as described in § 1236.42(e)(1).|