[« Previous Page : Introduction](1_Introduction.md) | [Table of Contents](../README.md#table-of-contents) | [Next Page: Open Source Software - Use »](3_Open_Source_Software_Use.md)

## Open Standards

- [Benefits](#benefits)
- [Risks and Drawbacks](#risks-and-drawbacks)
- [Best Practices for Adopting Open Standards](#best-practices-for-adopting-open-standards)
- [Preferred Open Standards](#preferred-open-standards)
- [Other open standards in GC](#other-open-standards-in-GC)
- [UK Open Standards for Government](#uk-open-standards-for-government)

Open standards are a set of rules designed to do a specific job in technology. They are also designed collaboratively and free to use. Open standards allow open source software and closed-source software to work together.

### Benefits

#### Interoperability

For any organization, especially public administrations, the need for interoperability is at two distinct yet overlapping levels: internal interoperability with its own IM-IT environment, and interoperability with the IM-IT environments of external stakeholders (other administrations, the public, businesses, associations), whether directly or indirectly, through the availability of open data.

##### Independence and substitutability

From an internal perspective, interoperability is closely linked to the issue of enterprise architecture, in that it allows its various components to be decoupled while remaining integrated. Thus, the [Quebec government's common interoperability framework](http://www.tresor.gouv.qc.ca/ressources-informationnelles/architecture-dentreprise-gouvernementale/standards-et-normes/cadre-commun-dinteroperabilite/) (CCIGQ) is linked to the Cadre de référence de l'architecture d'entreprise gouvernementale (government enterprise architecture reference framework); and version 2 of France's [Référentiel général d'interopérabilité](http://references.modernisation.gouv.fr/interoperabilite) (General Guidelines for Interoperability) refers back to the [Cadre Commun d'Urbanisation du Système d'Information de l'État](http://references.modernisation.gouv.fr/sites/default/files/Cadre%20Commun%20d%27Urbanisation%20du%20SI%20de%20l%27Etat%20v1.0_0.pdf) (common enterprise architecture framework for the State information system).

In the context of enterprise architecture fully under your control, one option to ensure the components' integration is standardization, either of the products directly or within a family of products generally offered by a single vendor. This approach can have functional advantages (generally in terms of a smooth integration between products), but it has the disadvantage of tying internal information technologies to an external system or a particular vendor. This connection can become both a technical handicap (by ruling out the possibility of adopting new, more relevant solutions) and an economic handicap (by decreasing opportunities to negotiate and by increasing switching costs). In an ideal interoperability scenario, however, the building blocks are substitutable: each one can be changed more easily and independently. This approach strengthens the freedom of choice and makes enterprise architecture more flexible, because each building block can be replaced by another with the same functionality without impacting the rest of the systems.

##### Application adherence - Vendor lock-in

Internally, interoperability can be viewed in two dimensions: the horizontal dimension (between two separate applications), which by nature is the dimension at play when two different systems interact; and the vertical dimension, which concerns the components of a single application. This is typically the case between the application itself and the underlying infrastructure components (for example, an application may require a specific database that, itself, works only on a particular operating system, without any functionalities coming into play). This is where application adherence factors in, falling outside the scope of interoperability but nevertheless sharing a number of fundamental principles with it.

##### Cloud computing

Cloud computing consists of providing infrastructure services and application services on demand. This is made possible through a high level of virtualization of hardware components by way of service infrastructure software. Cloud computing is based on a complex software architecture that simultaneously manages the elasticity of resources (processors, random access memory, storage and networks) and the ability of applications to make optimal use of these resources.

In terms of interoperability, there is no fundamental difference between a conventional infrastructure and a cloud, other than the complexity of the latter and the need to standardize vertical and horizontal components to a much greater degree. In particular, any outsourcing of infrastructure or applications to a public cloud must take into account the private or third-party organization's ability to apply standards that allow for the possibility of changing providers or reinstating a certain number of services, if necessary. In this context, the lack of an interoperability framework and open standards accepted by the provider poses a significant risk to the sustainability of the solution.

With respect to deploying a private cloud, interoperability promotes competition between providers, with respect to both hardware and software, as well as the ability to further develop the infrastructure over time. Indeed, the use of standards, through APIs for example, increases independence from the different drivers specific to the hardware components, and makes these infrastructure services independent from the software it deploys.

The adoption of a cloud-first approach for an organization is therefore a unique opportunity to standardize these processes and agree on a common framework. The use of an interoperability framework and the use of open standards makes it easier and less costly to outsource part of the infrastructure of it to a third-party organization, or to migrate onto Shared Services Canada, in a hybrid solution.

#### Open source software

[Open source software](3_Open_Source_Software_Use.md) (OSS) is a way of developing and distributing software. The code is often written collaboratively, and it can be downloaded, used and changed by anyone.

OSS tends to use and help define open standards and publicly available specifications. These products are, by their nature, publicly available specifications, and the availability of their source code promotes open, democratic debate around their specifications, making them both more robust and interoperable. From a design standpoint, interoperability and OSS are clearly separate, as are OSS and open standards. From a cultural and historical standpoint, however, there are strong ties between these concepts. This can be explained by the "community of values" - due to their open nature, OSS economic models are based less on strategies to lock in the user and more on interoperability to benefit the user. The use of open standards is necessary to ensure interoperability between products or systems.

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

### Other open standards in GC

The Library and Archives Canada (LAC) [Guidelines on File Formats for Transferring Information Resources of Enduring Value](http://www.bac-lac.gc.ca/eng/services/government-information-resources/guidelines/Pages/guidelines-file-formats-transferring-information-resources-enduring-value.aspx) recommends the following open standards.

#### Text

- [American Standard Code for Information Interchange (ASCII)](https://www.iso.org/standard/4777.html)
- [Electronic Publication (EPUB) 3.0](http://www.idpf.org/epub/301/spec/epub-publications.html)
- [Open Document Format (ODF)](https://www.iso.org/standard/66363.html)
- [Portable Document Format/Archival (PDF/A) 1](https://www.iso.org/standard/38920.html)
- [Portable Document Format/Archival (PDF/A) 2](https://www.iso.org/standard/50655.html)
- [UTF-8](https://tools.ietf.org/html/rfc3629)
- [UTF-16](https://tools.ietf.org/html/rfc2781)

#### Presentation

- [Open Document Format (ODF)](https://www.iso.org/standard/66363.html)
- [Portable Document Format/Archival (PDF/A) 1](https://www.iso.org/standard/38920.html)

The LAC guidelines also lists recommended formats for email, still images, audio, video, geospatial, computer aided design (CAD) and data sets. France's [Référentiel Général d'Interopérabilité](http://references.modernisation.gouv.fr/sites/default/files/Referentiel_General_Interoperabilite_V2.pdf), Québec's [Cadre Commun d'Interopérabilité du Gouvernement du Québec](http://www.tresor.gouv.qc.ca/fileadmin/PDF/ressources_informationnelles/architecture_entreprise_gouvernementale/AEG_3.1-CCIGQinteroperabilite.pdf) and the Canadian Heritage `Elements of a Technical Interoperability Framework` report (available on GCpedia) identify a lot of the same open standards as recommended.

The [GC Open Data Principles](http://open.canada.ca/en/open-data-principles) list "Use of Commonly Owned Standards" as a principle, with the intent that datasets released by the Government of Canada be in freely available file formats as often as possible.

Public Services and Procurement Canada (PSPC) has been piloting the [Open Contracting Data Standard](http://standard.open-contracting.org/latest/en/) to demonstrate use of the standard by linking the phases of the procurement process using data from procurements conducted by PSPC on behalf of government departments and agencies. ([source](https://buyandsell.gc.ca/procurement-data/open-contracting-data-standard-pilot))

### UK open standards for government

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
