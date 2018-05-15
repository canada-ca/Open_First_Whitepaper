[« Previous Page : Introduction](1_Introduction.md) | [Table of Contents](../README.md#table-of-contents) | [Next Page: Open Source Software »](3_Open_Source_Software.md)

## Open Standards

- [Interoperability](#interoperability)
- [Preferred Open Standards](#preferred-open-standards)
- [Examples](#examples)

[Open source software](3_Open_Source_Software.md) (OSS) tends to use and help define open standards and publicly available specifications. OSS products are, by their nature, publicly available specifications, and the availability of their source code promotes open, democratic debate around their specifications, making them both more robust and interoperable. From a design standpoint, interoperability and OSS are clearly separate, as are OSS and open standards. From a cultural and historical standpoint, however, there are strong ties between these concepts. This can be explained by the "community of values" - due to their open nature, open-source software economic models are based less on strategies to lock in the user and more on interoperability to benefit the user. The use of open standards is necessary to ensure interoperability between products or systems.

### Interoperability

For any organization, especially public administrations, the need for interoperability is at two distinct yet overlapping levels: internal interoperability with its own IM-IT environment, and interoperability with the IM-IT environments of external stakeholders (other administrations, the public, businesses, associations), whether directly or indirectly, through the availability of open data.

#### External interoperability

The crux of the matter is not only technical, but also based on a set of concerns at various levels. The [EFI](https://ec.europa.eu/isa2/eif_en) defines these as:

- **Interoperability governance** refers to decisions on interoperability frameworks, institutional arrangements, organizational structures, roles and responsibilities, policies, agreements and other aspects of ensuring and monitoring interoperability at national and EU levels.
- **Legal interoperability** is about ensuring that organizations operating under different legal frameworks, policies and strategies are able to work together;
- **Organisational interoperability** refers to the way in which public administrations align their business processes, responsibilities and expectations to achieve commonly agreed and mutually beneficial goals;
- **Semantic interoperability** ensures that the precise format and meaning of exchanged data and information is preserved and understood throughout exchanges between parties, in other words ‘what is sent is what is understood’. In the [EFI](https://ec.europa.eu/isa2/eif_en), semantic interoperability covers both semantic and syntactic aspects;
- **Technical interoperability** covers the applications and infrastructures linking systems and services. Aspects of technical interoperability include interface specifications, interconnection services, data integration services, data presentation and exchange, and secure communication protocols.

This the EIF definition of general interoperability:
>  Interoperability is the ability of organizations to interact towards mutually beneficial goals, involving the sharing of information and knowledge between these organizations, through the business processes they support, by means of the exchange of data between their ICT systems.

#### Internal interoperability

Internal interoperability is much more focused on the technical dimension. Particular attention should be paid to its definition, to ensure that it faithfully reflects expectations associated with the term, particularly in terms of independence - the term sovereignty is sometimes used - and neutrality.

A commonly used definition is the one proposed by the [Interoperability Working Group of the French speaking Libre Software Users' Association](http://interoperability-definition.info/en/):
>  Interoperability is a property of a product or system, whose interfaces are completely understood, to work with other products or systems, present or future, without any restricted access or implementation.

This definition is also a reminder of the vital link between interoperability and open standards. The specified interfaces undergo standardization processes to ensure the emergence and maintenance of common, documented references.

A major obstacle to interoperability arises from legacy systems. Historically, applications and information systems in public administrations were developed in a bottom-up fashion, trying to solve domain-specific and local problems. This resulted in fragmented IM-IT which are difficult to interoperate. Due to the size of public administration and the fragmentation of IM-IT solutions, the plethora of legacy systems creates an additional interoperability barrier in the technical layer.

Technical interoperability should be ensured, whenever possible, via the use of open standards.

##### Independence and substitutability

From an internal perspective, interoperability is closely linked to the issue of enterprise architecture, in that it allows its various components to be decoupled while remaining integrated. Thus, the [Quebec government's common interoperability framework](http://www.tresor.gouv.qc.ca/ressources-informationnelles/architecture-dentreprise-gouvernementale/standards-et-normes/cadre-commun-dinteroperabilite/) (CCIGQ) is linked to the Cadre de référence de l'architecture d'entreprise gouvernementale (government enterprise architecture reference framework); and version 2 of France's [Référentiel général d'interopérabilité](http://references.modernisation.gouv.fr/interoperabilite) (General Guidelines for Interoperability) refers back to the [Cadre Commun d'Urbanisation du Système d'Information de l'État](http://references.modernisation.gouv.fr/sites/default/files/Cadre%20Commun%20d%27Urbanisation%20du%20SI%20de%20l%27Etat%20v1.0_0.pdf) (common enterprise architecture framework for the State information system).

In the context of enterprise architecture fully under your control, one option to ensure the components' integration is standardization, either of the products directly or within a family of products generally offered by a single vendor. This approach can have functional advantages (generally in terms of a smooth integration between products), but it has the disadvantage of tying internal information technologies to an external system or a particular vendor. This connection can become both a technical handicap (by ruling out the possibility of adopting new, more relevant solutions) and an economic handicap (by decreasing opportunities to negotiate and by increasing switching costs). In an ideal interoperability scenario, however, the building blocks are substitutable: each one can be changed more easily and independently. This approach strengthens the freedom of choice and makes enterprise architecture more flexible, because each building block can be replaced by another with the same functionality without impacting the rest of the systems.

##### Application adherence - Vendor lock-in

Internally, interoperability can be viewed in two dimensions: the horizontal dimension (between two separate applications), which by nature is the dimension at play when two different systems interact; and the vertical dimension, which concerns the components of a single application. This is typically the case between the application itself and the underlying infrastructure components (for example, an application may require a specific database that, itself, works only on a particular operating system, without any functionalities coming into play). This is where application adherence factors in, falling outside the scope of interoperability but nevertheless sharing a number of fundamental principles with it.

#### Cloud computing

Cloud computing consists of providing infrastructure services and application services on demand. This is made possible through a high level of virtualization of hardware components by way of service infrastructure software. Cloud computing is based on a complex software architecture that simultaneously manages the elasticity of resources (processors, random access memory, storage and networks) and the ability of applications to make optimal use of these resources.

In terms of interoperability, there is no fundamental difference between a conventional infrastructure and a cloud, other than the complexity of the latter and the need to standardize vertical and horizontal components to a much greater degree. In particular, any outsourcing of infrastructure or applications to a public cloud must take into account the private or third-party organization's ability to apply standards that allow for the possibility of changing providers or reinstating a certain number of services, if necessary. In this context, the lack of an interoperability framework and open standards accepted by the provider poses a significant risk to the sustainability of the solution.

With respect to deploying a private cloud, interoperability promotes competition between providers, with respect to both hardware and software, as well as the ability to further develop the infrastructure over time. Indeed, the use of standards, through APIs for example, increases independence from the different drivers specific to the hardware components, and makes these infrastructure services independent from the software it deploys.

The implementation of a cloud is therefore a unique opportunity to standardize these processes and agree on a common framework. The use of an interoperability framework and the use of standards makes it easier and less costly to outsource part of the infrastructure of it to a third-party organization, or to migrate onto Shared Services Canada, in a hybrid solution.

#### Interoperability framework

An interoperability framework is defined as a set of policies, guidelines, standards, rules and recommendations made by a network of actors with a view to achieving the highest level of interoperability possible. It also describes the operating rules that govern the analysis, selection, adoption and updating of each of these elements.

To ensure the deployment and longevity of interoperable systems, it is necessary to jointly select the standards to be adopted as well as the conditions for their implementation. This is why several European countries (including France and the UK) and Canadian provinces such as Quebec have chosen to establish interoperability frameworks. The results are compelling, as open standards are regularly and widely used, and always the first approach to be considered when new requirements emerge.

As mentioned in the various interoperability frameworks that have already been published, they are designed only to identify key standards and not to offer predefined, unique solutions (for example, in terms of which software to choose). The objective of an interoperability framework is, therefore, to facilitate and guide an organization's interoperability choices while also limiting the number of potential standards in order to guarantee maximum clarity.

### Preferred Open Standards

The [GC Standard on Web Interoperability](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=25875) make the following open standards mandatory for GC Websites.

- **Mark-up language**: [HTML5](https://www.w3.org/TR/html5/)
- **Character encoding**: [UTF-8](https://tools.ietf.org/html/rfc3629)
- **HTML data and data vocabulary**: [RDFa Lite](https://www.w3.org/TR/rdfa-lite/), [Schema.org](http://schema.org/)
- **Web feed**: [Atom Syndication Format](https://tools.ietf.org/html/rfc4287)

The [GC Standard on Web Accessibility](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=23601) make the following open standard mandatory for GC Websites.

- [Web Content Accessibility Guidelines (WCAG) 2.0](https://www.w3.org/TR/WCAG20/)

### Examples

#### Canada

The Library and Archives Canada (LAC) [Guidelines on File Formats for Transferring Information Resources of Enduring Value](http://www.bac-lac.gc.ca/eng/services/government-information-resources/guidelines/Pages/guidelines-file-formats-transferring-information-resources-enduring-value.aspx) recommends the following open standards.

### Text

- [American Standard Code for Information Interchange (ASCII)](https://www.iso.org/standard/4777.html)
- [Electronic Publication (EPUB) 3.0](http://idpf.org/epub/30)
- [Open Document Format (ODF)](https://www.iso.org/standard/66363.html)
- [Portable Document Format/Archival (PDF/A) 1](https://www.iso.org/standard/38920.html)
- [Portable Document Format/Archival (PDF/A) 2](https://www.iso.org/standard/50655.html)
- [UTF-8](https://tools.ietf.org/html/rfc3629)
- [UTF-16](https://tools.ietf.org/html/rfc2781)

### Presentation

- [Open Document Format (ODF)](https://www.iso.org/standard/66363.html)
- [Portable Document Format/Archival (PDF/A) 1](https://www.iso.org/standard/38920.html)

The LAC guidelines also lists recommended formats for email, still images, audio, video, geospatial, computer aided design (CAD) and data sets. France's [Référentiel Général d'Interopérabilité](http://references.modernisation.gouv.fr/sites/default/files/Referentiel_General_Interoperabilite_V2.pdf), Québec's [Cadre Commun d'Interopérabilité du Gouvernement du Québec](http://www.tresor.gouv.qc.ca/fileadmin/PDF/ressources_informationnelles/architecture_entreprise_gouvernementale/AEG_3.1-CCIGQinteroperabilite.pdf) and the Canadian Heritage `Elements of a Technical Interoperability Framework` report (available on GCpedia) identify a lot of the same open standards as recommended.

The [GC Open Data Principles](http://open.canada.ca/en/open-data-principles) list "Use of Commonly Owned Standards" as a principle, with the intent that datasets released by the Government of Canada be in freely available file formats as often as possible.

Public Services and Procurement Canada (PSPC) has been piloting the [Open Contracting Data Standard](http://standard.open-contracting.org/latest/en/) to demonstrate use of the standard by linking the phases of the procurement process using data from procurements conducted by PSPC on behalf of government departments and agencies. ([source](https://buyandsell.gc.ca/procurement-data/open-contracting-data-standard-pilot))

#### UK

The UK government is selecting a set of open standards for use in government technology. The aim is to apply these consistently across government bodies, making our services better for users. Open standards are selected after a period of peer review and public comment through the [Standards Hub](https://github.com/alphagov/open-standards). The following are the endorsed [Open standards for government](https://www.gov.uk/government/publications/open-standards-for-government).

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
