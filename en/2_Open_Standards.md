[<- Previous Page : Introduction](1_Introduction.md) | [Table of Contents](../README.md#table-of-contents) | [Next Page: Open Source Software - Use ->](3_Open_Source_Software_Use.md)

## Open Standards

- [Interoperability](#interoperability)
- [Benefits](#benefits)
- [Risks and Drawbacks](#risks-and-drawbacks)
- [Best Practices for Adopting Open Standards](#best-practices-for-adopting-open-standards)
- [Preferred Open Standards](#preferred-open-standards)
- [Government of Canada Digital Standards](#government-of-canada-digital-standards)

Open standards are a set of rules designed to do a specific job in technology. Open standards refer to file formats, protocols and application interfaces that can be implemented by everyone (in open source and proprietary software alike) since the specifications are available at no cost, and since their development and standardization is open and transparent. This standardization work is done by specialized agencies that are usually either government agencies or organizations created by professionals from a given industry sector. Examples of such organizations include the Internet Engineering Task Force (IETF), the International Organization for Standardization (ISO) and the Organization for the Advancement of Structured Information Standards (OASIS).

The exact definition of open standards can vary by jurisdiction, but there is a high level of convergence in France's [Référentiel Général d'Interopérabilité](http://references.modernisation.gouv.fr/interoperabilite) (RGI) or "General Guidelines for Interoperability", the [Cadre Commun d'Interopérabilité du Gouvernement du Québec](http://www.tresor.gouv.qc.ca/fileadmin/PDF/ressources_informationnelles/architecture_entreprise_gouvernementale/AEG_3.1-CCIGQinteroperabilite.pdf) (CCIGQ) of the "Quebec government's common interoperability framework", the [European Interoperability Framework](https://ec.europa.eu/isa2/eif_en) (EIF) and the British Cabinet Office's [Open Standards Principles](https://www.gov.uk/government/publications/open-standards-principles/open-standards-principles#open-standard-definition).

Inspired by the four policy documents, the following criteria define open standards:

- process for the standard's development is open and transparent to all interested parties and cannot be controlled by any single person or entity with any vested interests;
- platform independent, vendor neutral and usable for multiple implementations;
- specifications and supporting material are freely available with limited restrictions;
- supported by the community and demonstrate independence or approved through due process by rough consensus among participants.

### Interoperability

The ability of organizations to interact towards mutually beneficial goals, and involves the sharing of information and knowledge between these organizations, through the business processes they support, by means of the exchange of data between their ICT systems. Interoperability is a characteristic of a product or system, whose interfaces are completely understood, to work with other products or systems, present or future, in either implementation or access, without any restrictions.

This definition is also a reminder of the vital link between interoperability and open standards. The specified interfaces undergo standardization processes to ensure the emergence and maintenance of common, documented references.

The crux of the matter is not only technical, but also based on a set of concerns at various levels. The [EFI](https://ec.europa.eu/isa2/eif_en) defines these as:

- **Interoperability governance** refers to decisions on interoperability frameworks, institutional arrangements, organizational structures, roles and responsibilities, policies, agreements and other aspects of ensuring and monitoring interoperability at national and EU levels.
- **Legal interoperability** is about ensuring that organizations operating under different legal frameworks, policies and strategies are able to work together;
- **Organisational interoperability** refers to the way in which public administrations align their business processes, responsibilities and expectations to achieve commonly agreed and mutually beneficial goals;
- **Semantic interoperability** ensures that the precise format and meaning of exchanged data and information is preserved and understood throughout exchanges between parties, in other words ‘what is sent is what is understood’. In the [EFI](https://ec.europa.eu/isa2/eif_en), semantic interoperability covers both semantic and syntactic aspects;
- **Technical interoperability** covers the applications and infrastructures linking systems and services. Aspects of technical interoperability include interface specifications, interconnection services, data integration services, data presentation and exchange, and secure communication protocols.

#### Internal interoperability

Internal interoperability is much more focused on the technical dimension. Particular attention should be paid to its definition, to ensure that it faithfully reflects expectations associated with the term, particularly in terms of independence - the term sovereignty is sometimes used - and neutrality.

A major obstacle to interoperability arises from legacy systems. Historically, applications and information systems in public administrations were developed in a bottom-up fashion, trying to solve domain-specific and local problems. This resulted in fragmented IM-IT which are difficult to interoperate. Due to the size of public administration and the fragmentation of IM-IT solutions, the plethora of legacy systems creates an additional interoperability barrier in the technical layer.

Technical interoperability should be ensured, whenever possible, via the use of open standards.

### Benefits

#### Interoperability

For any organization, especially public administrations, the need for interoperability is at two distinct yet overlapping levels: internal interoperability with its own information and communication technologies (ICT), and interoperability with the ICT of external stakeholders (other administrations, the public, businesses, associations), whether directly or indirectly, synchronous or asynchronous, through the availability of open data.

##### Independence and substitutability

From an internal perspective, interoperability is closely linked to the issue of enterprise architecture, in that it allows its various components to be decoupled while remaining integrated. Thus, the [Quebec government's common interoperability framework](http://www.tresor.gouv.qc.ca/ressources-informationnelles/architecture-dentreprise-gouvernementale/standards-et-normes/cadre-commun-dinteroperabilite/) (CCIGQ) is linked to the Cadre de référence de l'architecture d'entreprise gouvernementale (government enterprise architecture reference framework); and version 2 of France's [Référentiel général d'interopérabilité](http://references.modernisation.gouv.fr/interoperabilite) (General Guidelines for Interoperability) refers back to the [Cadre Commun d'Urbanisation du Système d'Information de l'État](http://references.modernisation.gouv.fr/sites/default/files/Cadre%20Commun%20d%27Urbanisation%20du%20SI%20de%20l%27Etat%20v1.0_0.pdf) (common enterprise architecture framework for the State information system).

In the context of enterprise architecture fully under the organization's control, one option is to ensure the components have clear integration patterns, either via the products directly or by using a family of products generally offered by a single vendor. This approach can have functional advantages (generally in terms of a smooth integration between products), but it has the disadvantage of tying internal information technologies to an external system or a particular vendor. This connection can become both a technical handicap (by ruling out the possibility of adopting new, more relevant solutions) and an economic handicap (by decreasing opportunities to negotiate and by increasing switching costs). In an ideal interoperability scenario, however, the building blocks are substitutable: each one can be changed more easily and independently. This approach strengthens the freedom of choice and makes enterprise architecture more flexible, because each building block can be replaced by another with the same functionality without impacting the rest of the systems.

##### Application adherence - Lock-in

Internally, interoperability can be viewed in two dimensions: the horizontal dimension (between two separate applications), which by nature is the dimension at play when two different systems interact; and the vertical dimension, which concerns the components of a single application. This is typically the case between the application itself and the underlying infrastructure components (for example, an application may require a specific database that, itself, works only on a particular operating system, without any functionalities coming into play). This is where application adherence factors in, falling outside the scope of interoperability but nevertheless sharing a number of fundamental principles with it.

##### Cloud computing

Cloud computing consists of providing infrastructure services and application services on demand. This is made possible through a high level of virtualization of hardware components by way of service infrastructure software. Cloud computing is based on a software architecture that simultaneously manages the elasticity of resources (processors, random access memory, storage and networks) and the ability of applications to make use of these resources through self service interfaces.

While the fundamental primitives of the underlying infrastructure and application architectures remain relatively consistent between cloud deployments and traditional infrastructure deployments, the key difference is in the accessibility and programmability of the infrastructure. Cloud computing enables, through APIs and orchestration integrations, the ability for applications to be deployed and managed through code. The use of programmatic orchestration improves the ability to establish standards through reference implementations and pre-approved architectures.

A notable difference between cloud computing and traditional infrastructure is the availability of higher level services in cloud computing.  These services, while offering substantial ecosystem benefits, are often not transferrable to other providers.  The use of these services can have strong implications on interoperability as they can create a sort of lock-in.  These services are often integrated directly into the application layer, making for a tighter coupling between the application and the provider.  When choosing services from a cloud provider, it is important to ask the question; "Is this service available from another provider and what are the challenges in switching?".  Leveraging Infrastructure-as-Code (IaC) and DevOps practices can help alleviate some of the risks of lock-in as they provide an interface for evolving the details of a deployment.

Any outsourcing of infrastructure or applications to a public cloud must take into account the private or third-party organization's ability to apply standards that allow for the possibility of changing providers or reinstating a certain number of services, if necessary. In this context, the lack of an interoperability framework and open standards accepted by the provider poses a significant risk to the sustainability of the solution.

With respect to deploying a private cloud, interoperability promotes competition between providers, with respect to both hardware and software, as well as the ability to further develop the infrastructure over time. Indeed, the use of standards, through APIs for example, increases independence from the different drivers specific to the hardware components, and makes these infrastructure services independent from the software it deploys.

The adoption of a cloud-first approach for an organization is therefore a unique opportunity to standardize these processes and agree on a common framework. The use of an interoperability framework and the use of open standards makes it easier and less costly to outsource part of the infrastructure of it to a third-party organization, or to migrate onto Shared Services Canada, in a hybrid solution.

#### Open source software

[Open source software](3_Open_Source_Software_Use.md) (OSS) is a way of developing and distributing software. The code is often written collaboratively, and it can be downloaded, used and changed by anyone.

OSS tends to use and help define open standards and publicly available specifications. OSS are, by their nature, publicly available specifications, and the availability of their source code promotes open, democratic debate around their specifications, making them both more robust and interoperable. From a design standpoint, interoperability and OSS are clearly separate, as are OSS and open standards. From a cultural and historical standpoint, however, there are strong ties between these concepts. This can be explained by the "community of values" - due to their open nature, OSS economic models are based less on strategies to lock in the user and more on interoperability to benefit the user. The use of open standards is necessary to ensure interoperability between products or systems.

### Risks and Drawbacks

#### Standards Proliferation

Standards are created to answer specific needs and the proliferation of competing standards may increase the required time spent selecting the right one to reduce the issues in the long term management of data, information and applications. Co-creation of standards may take time and the emergence of new ones when an agreement can not be reached amongst stakeholders may increase the risk of settling for an other standard as the broader market may take a different direction.

### Best Practices for Adopting Open Standards

#### Define principles for selecting open standards

- Principles used to evaluate specific open standards and require them to be used where relevant
- Ensure that the selected standards will enable software to interoperate through open protocols and data exchange to occur between software and data stores

#### Identify open standards for use in GC

- Interoperability framework that lists mandatory and recommended open standards
- Possible alignment and collaboration with [UK Open Standards Board](https://www.gov.uk/government/groups/open-standards-board) on selecting open standards for government

#### Training and Support

Training and support around the migration to and adoption of open standards are similar to [best practices on training and support for use of OSS](3_Open_Source_Software_Use.md#training-and-support).

#### Format conversion

- Make a significant effort to ensure that closed files and data formats can be converted to open standards;
- Keep in mind that document conversion, such as between MS Office and LibreOffice, can become a labour-intensive task for any complex documents, especially where they include precise formatting or macros.

### Preferred Open Standards

The [GC Standard on Web Interoperability](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=25875) make the following open standards mandatory for GC Websites.

- **Mark-up language**: [HTML5](https://www.w3.org/TR/html5/)
- **Character encoding**: [UTF-8](https://tools.ietf.org/html/rfc3629)
- **HTML data and data vocabulary**: [RDFa Lite](https://www.w3.org/TR/rdfa-lite/), [Schema.org](http://schema.org/)
- **Web feed**: [Atom Syndication Format](https://tools.ietf.org/html/rfc4287)

The [GC Standard on Web Accessibility](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=23601) make the following open standard mandatory for GC Websites.

- [Web Content Accessibility Guidelines (WCAG) 2.0](https://www.w3.org/TR/WCAG20/)

The Treasury Board information or technology standard (TBITS) [Implementation Criteria for Codes for the Representation of Currencies and Funds (TBITS 12)](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=17280) make the following open standard mandatory for the representation of currencies and funds in the exchange of data both inside and outside the GC.

- **Currency codes**: [ISO 4217](https://www.iso.org/iso-4217-currency-codes.html)

The TBITS [Implementation Criteria for all-Numeric Representation of Dates and Times (TBITS 36)](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=17284) make the following open standard mandatory for the numeric format of calendar dates for the purpose of exchanging machine-readable data between departments and agencies.

- **Date and time**: [ISO 8601](https://www.iso.org/iso-8601-date-and-time-format.html)

#### Other open standards in GC

The Library and Archives Canada (LAC) [Guidelines on File Formats for Transferring Information Resources of Enduring Value](http://www.bac-lac.gc.ca/eng/services/government-information-resources/guidelines/Pages/guidelines-file-formats-transferring-information-resources-enduring-value.aspx) lists recommended formats for texts, presentations, emails, still images, audio, video, geospatial, computer aided design (CAD) and data sets. The Canadian Heritage [Elements of a Technical Interoperability Framework report](https://wiki.gccollab.ca/Elements_of_a_Technical_Interoperability_Framework_for_Canadian_Heritage), Québec's [Cadre Commun d'Interopérabilité du Gouvernement du Québec](http://www.tresor.gouv.qc.ca/fileadmin/PDF/ressources_informationnelles/architecture_entreprise_gouvernementale/AEG_3.1-CCIGQinteroperabilite.pdf) and France's [Référentiel Général d'Interopérabilité](http://references.modernisation.gouv.fr/sites/default/files/Referentiel_General_Interoperabilite_V2.pdf) identify a lot of the same open standards as recommended.

The [GC Open Data Principles](http://open.canada.ca/en/open-data-principles) list "Use of Commonly Owned Standards" as a principle, with the intent that datasets released by the GC be in freely available file formats as often as possible.

Public Services and Procurement Canada (PSPC) has been piloting the [Open Contracting Data Standard](http://standard.open-contracting.org/latest/en/) to demonstrate use of the standard by linking the phases of the procurement process using data from procurements conducted by PSPC on behalf of government departments and agencies. ([source](https://buyandsell.gc.ca/procurement-data/open-contracting-data-standard-pilot))

#### UK open standards for government

The [UK Open Standards Board](https://www.gov.uk/government/groups/open-standards-board) is selecting a set of open standards for use in government technology. The aim is to apply these consistently across government bodies, making our services better for users. Open standards are selected after a period of peer review and public comment through the [Standards Hub](https://github.com/alphagov/open-standards). The following are the endorsed [Open standards for government](https://www.gov.uk/government/publications/open-standards-for-government).

- **Viewing government documents**: [HTML5](https://www.w3.org/TR/html5/), [Portable Document Format/Archival (PDF/A) 1](https://www.iso.org/standard/38920.html), [Portable Document Format/Archival (PDF/A) 2](https://www.iso.org/standard/50655.html)
- **Sharing or collaborating with government documents**: [Open Document Format (ODF)](https://www.iso.org/standard/66363.html)
- **Cross platform character encoding profile**: [Unicode 6.2](http://www.unicode.org/versions/Unicode6.2.0/), [UTF-8](https://tools.ietf.org/html/rfc3629)
- **Open contracting data**: [Open Contracting Data Standard](http://standard.open-contracting.org/latest/en/)
- **Country codes**: [ISO 3166-1:2013](https://www.iso.org/standard/63545.html)
- **Language tags**: [ISO 639-1:2002](https://www.iso.org/standard/22109.html)
- **International development data**: [IATI](http://iatistandard.org/202/)
- **Publishing vacancies**: [JobPosting - Schema.org](http://schema.org/JobPosting)
- **Exchange of location point**: [European Terrestrial Reference System (ETRS) 89](http://etrs89.ensg.ign.fr/), [World Geodetic System (WGS) 84)](https://www.nga.mil/ProductsServices/GeodesyandGeophysics/Pages/WorldGeodeticSystem.aspx)
- **Persistent resolvable identifiers**: [Hypertext Transfer Protocol (HTTP) 1.1](https://tools.ietf.org/html/rfc2616), [Uniform Resource Identifier (URI)](https://tools.ietf.org/html/rfc3986)
- **Exchange of contact information**: [vCard](https://tools.ietf.org/html/rfc6350)
- **Exchange of calendar events**: [iCalendar](https://tools.ietf.org/html/rfc5545)

### Government of Canada Digital Standards

The [GC Digital Standards](https://www.canada.ca/en/government/publicservice/modernizing/government-canada-digital-standards.html) include a standard to use open standards and solutions.

The GC Enterprise Architecture Review Board (GC EARB) will use the [Architectural Standards](https://canada-ca.github.io/digital-playbook-guide-numerique/views-vues/gc-earb-ceai/en/gc-earb.html) to evaluate digital solutions to ensure the GC acts as a single enterprise. The Architectural Standards build upon the Government of Canada Digital Standards, focusing on best practices for architectural and design planning. Under [Application Architecture](https://canada-ca.github.io/digital-playbook-guide-numerique/views-vues/gc-earb-ceai/en/gc-earb.html#application-architecture) they include a standard to Use Open Standards and Open Source Software to avoid lock-in where open source software or open standards are available.
