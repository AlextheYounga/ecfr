##### § 45.6 Legal entity identifiers #####

Each counterparty to any swap subject to the jurisdiction of the Commission shall be identified in all recordkeeping and all swap data reporting pursuant to this part by means of a single legal entity identifier as specified in this section.

(a) *Definitions.* As used in this section:

*Control* (“controlling,” “controlled by,” “under common control with”) means, for the purposes of § 45.6, the possession, direct or indirect, of the power to direct or cause the direction of the management and policies of a person, whether through the ownership of voting interest, by contract, or otherwise. A person is presumed to control another person if the person: is a director, general partner or officer exercising executive responsibility (or having similar status or functions); directly or indirectly has the right to vote 25 percent or more of a class of voting interest or has the power to sell or direct the sale of 25 percent or more of a class of voting interest; or, in the case of a partnership, has the right to receive upon dissolution, or has contributed, 25 percent or more of the capital.

*Legal identifier system* means an LEI utility conforming with the requirements of this section that issues or is capable of issuing an LEI conforming with the requirements of this section, and is capable of maintaining LEI reference data as required by this section.

*Level one reference data* means the minimum information needed to identify, on a verifiable basis, the legal entity to which a legal entity identifier is assigned. Level one reference data shall include, without limitation, all of the data elements included in ISO Standard 17442. Examples of level one reference data include, without limitation, a legal entity's official legal name, its place of incorporation, and the address and contact information of its corporate headquarters.

*Level two reference data* means information concerning the corporate affiliations or company hierarchy relationships of the legal entity to which a legal entity identifier is assigned. Examples of level two reference data include, without limitation, the identity of the legal entity's ultimate parent.

*Parent* means, for the purposes of § 45.6, a legal person that controls a counterparty to a swap required to be reported pursuant to this section, or that controls a legal entity identified or to be identified by a legal entity identifier provided by the legal identifier system designated by the Commission pursuant to this section.

*Self-registration* means submission by a legal entity of its own level one or level two reference data, as applicable.

*Third-party registration* means submission of level one or level two reference data, as applicable, for a legal entity that is or may become a swap counterparty, made by an entity or organization other than the legal entity identified by the submitted reference data. Examples of third-party registration include, without limitation, submission by a swap dealer or major swap participant of level one or level two reference data for its swap counterparties, and submission by a national numbering agency, national registration agency, or data service provider of level one or level two reference data concerning legal entities with respect to which the agency or service provider maintains information.

*Ultimate parent* means, for the purposes of § 45.6, a legal person that controls a counterparty to a swap required to be reported pursuant to this section, or that controls a legal entity identified or to be identified by a legal entity identifier provided by the legal identifier system designated by the Commission pursuant to this section, and that itself has no parent.

(b) *International standard for the legal entity identifier.* The legal entity identifier used in all recordkeeping and all swap data reporting required by this part, following designation of the legal entity identifier system as provided in paragraph (c)(2) of this section, shall be issued under, and shall conform to, ISO Standard 17442, Legal Entity Identifier (LEI), issued by the International Organisation for Standardisation.

(b) *Technical principles for the legal entity identifier.* The legal entity identifier used in all recordkeeping and all swap data reporting required by this part shall conform to the technical principles set forth in paragraphs (b)(1) through (6) of this section.

(1) *Uniqueness.* Only one legal entity identifier shall be assigned to any legal entity, and no legal entity identifier shall ever be reused. Each entity within a corporate organization or group structure that acts as a counterparty in any swap shall have its own legal entity identifier.

(2) *Neutrality.* To ensure the persistence of the legal entity identifier, it shall have a format consisting of a single data field, and shall contain either no embedded intelligence or as little embedded intelligence as practicable. Entity characteristics of swap counterparties identified by legal entity identifiers shall constitute separate elements within a reference data system as set forth in paragraphs (a), (c)(2), (d), and (e) of this section.

(3) *Reliability.* The legal entity identifier shall be supported by a trusted and auditable method of verifying the identity of the legal entity to which it is assigned, both initially and at appropriate intervals thereafter. The issuer of legal entity identifiers shall maintain minimum reference or identification data sufficient to verify that a user has been correctly identified. Issuance and maintenance of the legal entity identifier, and storage and maintenance of all associated data, shall involve robust quality assurance practices and system safeguards. At a minimum, such system safeguards shall include the system safeguards applied to swap data repositories by part 49 of this chapter.

(4) *Open Source.* The schema for the legal entity identifier shall have an open standard that ensures to the greatest extent practicable that the legal entity identifier is compatible with existing automated systems of financial market infrastructures, market participants, and regulators.

(5) *Extensibility.* The legal entity identifier shall be capable of becoming the single international standard for unique identification of legal entities across the financial sector on a global basis. Therefore, it shall be sufficiently extensible to cover all existing and potential future legal entities of all types that may be counterparties to swap, OTC derivative, or other financial transactions; that may be involved in any aspect of the financial issuance and transactions process; or that may be subject to required due diligence by financial sector entities.

(6) *Persistence.* The legal entity identifier assigned to an entity shall persist despite all corporate events. When a corporate event results in a new entity, the new entity shall receive a new legal entity identifier, while the previous legal entity identifier or identifiers continue to identify the predecessor entity or entities in the record.

(c) *Governance principles for the legal entity identifier.* The legal entity identifier used in all recordkeeping and all swap data reporting required by this part shall conform to the governance principles set forth in paragraphs (c)(1) through (4) of this section.

(1) *International governance.* The issuance of the legal entity identifier used pursuant to this section, and any legal entity identifier utility formed for the purpose of issuing legal entity identifiers that are used pursuant to this section, shall be subject to international supervision as follows:

(i) With respect to operations, by a governance structure that includes the Commission and other financial regulators in any jurisdiction requiring use of the legal entity identifier pursuant to applicable law. The governance structure shall have authority sufficient to ensure, and shall ensure, that issuance and maintenance of the legal entity identifier system adheres on an ongoing basis to the principles set forth in this section.

(ii) With respect to adherence to ISO Standard 17442, by the International Organisation for Standardisation.

(2) *Reference data access.* Access to reference data associated with the legal entity identifier shall enable use of the legal entity identifier as a public good, while respecting applicable law regarding data confidentiality. Accordingly:

(i) Reference data associated with the legal entity identifier that is public under applicable law shall be available publicly and free of charge. Such data shall include, without limitation, level one reference data (i.e., the minimum reference data needed to verify the identity of the legal entity receiving each legal entity identifier), and a current directory of all issued legal entity identifiers.

(ii) Collection and maintenance of, and access to, reference data associated with the legal entity identifier shall comply with applicable laws on data protection and confidentiality.

(3) *Non-profit operation and funding.* Funding of both start-up and ongoing operation of the legal entity identifier system, including, without limitation, any legal entity identifier utility formed for the purpose of issuing legal entity identifiers that are used pursuant to this section, shall be conducted on a non-profit, reasonable cost-recovery basis, and shall be subject to international governance as provided in paragraph (c)(1) of this section.

(4) *Unbundling and non-restricted use.* Issuance of the legal entity identifier shall not be tied to other services, if any, offered by the issuer, and information concerning the issuance process for new legal entity identifiers must be available publicly and free of charge. Restrictions shall not be imposed on use of the legal entity identifier by any person in its own products and services, or on use of the legal entity identifier and associated reference data by any financial regulator. Any intellectual property created as part of the legal entity identifier system shall be treated in a manner consistent with open source principles.

(5) *Commercial advantage prohibition.* The legal entity identifier utility providing legal entity identifiers for use in compliance with this part shall not make any commercial or business use (other than the operation of the utility) of any reference data associated with the legal entity identifier that is not available to the public free of charge. This restriction shall also apply to any entity or person that participates in the utility, that is legally or otherwise affiliated or associated with the utility, or that provides third-party services to the utility or to any component, partner, affiliate, or associate thereof.

(e) *Designation of the legal entity identifier system.* (1) The Commission shall determine, as provided in paragraphs (e)(1)(i) through (iii) of this section, whether a legal entity identifier system that satisfies the requirements set forth in this section is available to provide legal entity identifiers for registered entities and swap counterparties required to comply with this part.

(i) In making this determination, the Commission shall consider, without limitation, the following factors:

(A) Whether the LEI provided by the LEI utility is issued under, and conforms to, *ISO Standard 17442, Legal Entity Identifier (LEI).*

(B) Whether the LEI provided by the LEI utility complies with all of the technical principles set forth in this rule.

(C) Whether the LEI utility complies with all of the governance principles set forth in this rule.

(D) Whether the LEI utility has demonstrated that it in fact can provide LEIs complying with this section for identification of swap counterparties in swap data reporting commencing as of the compliance dates set forth in § 45.5.

(E) The acceptability of the LEI utility to industry participants required to use the LEI in complying with this part.

(ii) In making this determination, the Commission shall consider all candidates meeting the criteria set forth in paragraph (e)(1)(i) of this section, but shall not consider any candidate that does not demonstrate that it in fact can provide LEIs for identification of swap counterparties in swap data reporting commencing as of the compliance dates set forth in this part.

(iii) The Commission shall make this determination at a time it believes is sufficiently prior to the compliance dates set forth this part to enable issuance of LEIs far enough in advance of those compliance dates to enable compliance with this part.

(2) If the Commission determines pursuant to paragraph (e)(1) of this section that such a legal entity identifier system is available, the Commission shall designate the legal entity identifier system as the provider of legal entity identifiers to be used in recordkeeping and swap data reporting pursuant to this part, by means of a Commission order that is published in the Federal Register and on the Web site of the Commission, as soon as practicable after such determination is made. The order shall include notice of this designation, the contact information of the LEI utility, and information concerning the procedure and requirements for obtaining legal entity identifiers.

(3) If the Commission determines pursuant to paragraph (e)(1) of this section that such a legal entity identifier system is not yet available, the Commission shall publish notice of the determination in the Federal Register and on the Web site of the Commission, as soon as practicable after the determination is made. If the Commission later determines, pursuant to paragraphs (e)(1)(i) and (ii) of this section, that such a legal entity identifier system has become available, the Commission shall designate the legal entity identifier system as the provider of legal entity identifiers to be used in recordkeeping and swap data reporting pursuant to this part, by means of a Commission order that is published in the Federal Register and on the Web site of the Commission, as soon as practicable after such determination is made. The order shall include notice of this designation, the contact information of the LEI utility, and information concerning the procedure and requirements for obtaining legal entity identifiers.

(e) *Reference data reporting* - (1) *Reporting of level one reference data.* Level one reference data for each counterparty to any swap subject to the jurisdiction of the Commission shall be reported, by means of self-registration, third-party registration, or both, into a public level one reference database maintained by the issuer of the legal entity identifier designated by the Commission pursuant to paragraph (d) of this section. Such level one reference data shall be reported at a time sufficient to ensure that the counterparty's legal entity identifier is available for inclusion in recordkeeping and swap data reporting as required by this section. All subsequent changes and corrections to level one reference data previously reported shall be reported to the issuer, by means of self-registration, third-party registration, or both, as soon as technologically practicable following occurrence of any such change or discovery of the need for a correction.

(2) *Reporting of level two reference data.* (i) Level two reference data for each counterparty to any swap subject to the jurisdiction of the Commission, consisting of the identity of the counterparty's ultimate parent, shall be reported, by means of self-registration, third-party registration, or both, into a level two reference database. Where applicable law forbids such reporting, that fact and the citation of the law in question shall be reported in place of the data to which such law applies.

(ii) All non-public level two reference data reported to the level two reference database shall be confidential, non-public, and available only to financial regulators in any jurisdiction requiring use of the legal entity identifier pursuant to applicable law.

(iii) The Commission shall determine the location of the level two reference database by means of a Commission order that is published in the Federal Register and on the Web site of the Commission, as soon as practicable after such determination is made. The order shall include notice of the location of the level two reference database, and information concerning the procedure and requirements for reporting level two reference data to the database.

(iv) The obligation to report level two reference data does not apply until the Commission has determined the location of the level two reference database as provided in paragraph (e)(2)(iii) of this section.

(v) After the Commission determines the location of the level two reference database pursuant to paragraph (e)(2)(iii) of this section, required level two reference data shall be reported at a time sufficient to ensure that it is included in the database when the counterparty's legal entity identifier is included in recordkeeping and swap data reporting as required by this section.

(vi) All subsequent changes and corrections to required level two reference data previously reported shall be reported into the level two reference database, by means of self-registration, third-party registration, or both, as soon as technologically practicable following occurrence of any such change or discovery of the need for a correction.

(f) *Use of the legal entity identifier system by registered entities and swap counterparties.* (1) When a legal entity identifier system has been designated by the Commission pursuant to paragraph (e) of this section, each registered entity and swap counterparty shall use the legal entity identifier provided by that system in all recordkeeping and swap data reporting pursuant to this part.

(2) Before a legal entity identifier system has been designated by the Commission, each registered entity and swap counterparty shall use a substitute counterparty identifier created and assigned by a swap data repository in all recordkeeping and swap data reporting pursuant to this part, as follows:

(i) When a swap involving one or more counterparties for which no substitute counterparty identifier has yet been created and assigned is reported to a swap data repository, the swap data repository shall create a substitute counterparty identifier for each such counterparty as provided in paragraph (f)(2)(ii) of this section, and assign the substitute counterparty identifier to that counterparty, as soon as technologically practicable after that swap is first reported to the swap data repository. In lieu of creating a substitute identifier as provided in paragraph (f)(2)(ii), the swap data repository may assign a unique substitute identifier provided by a third party service provider, if such identifier complies with all of the principles for LEIs set forth in this part.

(ii) Each such substitute counterparty identifier created by a swap data repository shall consist of a single data field that contains two components, including:

(A) The unique alphanumeric code assigned to the swap data repository by the Commission for the purpose of identifying the swap data repository; and

(B) An alphanumeric code generated and assigned to that counterparty by the automated systems of the swap data repository, which shall be unique with respect to all such substitute counterparty identifier codes generated and assigned by that swap data repository.

(iii) The swap data repository shall transmit each substitute counterparty identifier thus created to each counterparty to the swap, to each other registered entity associated with the swap, to each registered entity or swap counterparty who has made any report of any swap data to the swap data repository, and to each swap data repository registered with the Commission, as soon as technologically practicable after creation and assignment of the substitute counterparty identifier.

(iv) Once any swap data repository has created and assigned such a substitute counterparty identifier to a swap counterparty and has transmitted it as required by paragraph (f)(2)(iii) of this section, all registered entities and swap counterparties shall use that substitute counterparty identifier to identify that counterparty in all swap data recordkeeping and reporting, until such time as the Commission designates a legal entity identifier system pursuant to paragraph (e) of this section.

(3) For swaps reported pursuant to this part prior to Commission designation of a legal entity identifier system, after such designation each swap data repository shall map the legal entity identifiers for the counterparties to the substitute counterparty identifiers in the record for each such swap.

(4) Prior to October 15, 2012, if a legal entity identifier system has been designated by the Commission as provided in this section, but a reporting counterparty's automated systems are not yet prepared to include legal entity identifiers in recordkeeping and swap data reporting pursuant to this part, the counterparty shall be excused from complying with paragraph (f)(1) of this section, and shall instead comply with paragraph (f)(2) of this section, until its automated systems are prepared with respect to legal entity identifiers, at which time it must commence compliance with paragraph (f)(1) of this section. This paragraph shall have no effect on or after October 15, 2012.

Editorial Note:At 77 FR 2197, Jan. 13, 2012,part 45 was added, with two paragraphs (b) in § 45.6.