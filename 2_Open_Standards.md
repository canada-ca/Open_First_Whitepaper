[« Previous Page : Introduction](1_Introduction.md) | [Table of Content](TOC.md) | [Next Page: Open Source Software »](3_Open_Source_Software.md)

## Open Standards
Open standards refer to file formats, protocols and application interfaces that can be implemented by everyone (in open source and proprietary software alike) since the specifications are available no cost and development / standardization is open and transparent. This standardization work is done by specialized agencies that are usually either government agencies or organizations created by professionals from a given industry sector. These organizations include the Internet Engineering Task Force (IETF), the International Organization for Standardization (ISO) and the Organization for the Advancement of Structured Information Standards (OASIS).

The exact definition of open standards can vary depending on who has jurisdiction, but there is a high level of convergence in the [RGI](http://references.modernisation.gouv.fr/interoperabilite) (France's ''Référentiel Général d'Interopérabilité'', or General Guidelines for Interoperability), the [CCIGQ](http://www.tresor.gouv.qc.ca/fileadmin/PDF/ressources_informationnelles/architecture_entreprise_gouvernementale/AEG_3.1-CCIGQinteroperabilite.pdf) (''Cadre Commun d'Interopérabilité du Gouvernement du Québec'', or the Quebec government's common interoperability framework), the [European Interoperability Framework](https://ec.europa.eu/isa2/eif_en) and the British Cabinet Office's [Open Standards Principles](https://www.gov.uk/government/publications/open-standards-principles/open-standards-principles#open-standard-definition).

Inspired by the four policy documents, the following criteria define open standards:
- A process for the standard's development that is open and transparent to all interested parties and cannot be controlled by any single person or entity with any vested interests
- Platform independent, vendor neutral and usable for multiple implementations
- Specifications and supporting material are freely available with limited restrictions
- must be supported by the community and demonstrate independence or approved through due process by rough consensus among participants

Open source software (OSS) tends to use and help define open standards and publicly available specifications. OSS products are, by their nature, publicly available specifications, and the availability of their source code promotes open, democratic debate around their specifications, making them both more robust and interoperable. From a design standpoint, interoperability and OSS are clearly separate, as are OSS and open standards. From a cultural and historical standpoint, however, there are strong ties between these concepts. This can be explained by the "community of values" - due to their open nature, open-source software economic models are based less on strategies to lock in the user and more on interoperability to benefit the user. The use of open standards is necessary to ensure interoperability between products or systems.

### Interoperability
For any organization, especially public adminstrations, the need for interoperability is at two distinct yet overlapping levels: internal interoperability with its own IM-IT environment, and interoperability with the IM-IT environments of external stakeholders (other administrations, the public, businesses, associations), whether directly or indirectly, through the availability of open data.

#### External interoperability
The crux of the matter is not only technical, but also based on a set of concerns at various levels. The [European Interoperability Framework](https://ec.europa.eu/isa2/eif_en) (EIF) defines these as:
- **Interoperability governance** refers to decisions on interoperability frameworks, institutional arrangements, organisational structures, roles and responsibilities, policies, agreements and other aspects of ensuring and monitoring interoperability at national and EU levels.
- **Legal interoperability** is about ensuring that organisations operating under different legal frameworks, policies and strategies are able to work together;
- **Organisational interoperability** refers to the way in which public administrations align their business processes, responsibilities and expectations to achieve commonly agreed and mutually beneficial goals;
- **Semantic interoperability** ensures that the precise format and meaning of exchanged data and information is preserved and understood throughout exchanges between parties, in other words ‘what is sent is what is understood’. In the EIF, semantic interoperability covers both semantic and syntactic aspects;
- **Technical interoperability** covers the applications and infrastructures linking systems and services. Aspects of technical interoperability include interface specifications, interconnection services, data integration services, data presentation and exchange, and secure communication protocols.

This the EIF definition of general interoperability:
>  Interoperability is the ability of organisations to interact towards mutually beneficial goals, involving the sharing of information and knowledge between these organisations, through the business processes they support, by means of the exchange of data between their ICT systems.

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
Internally, interoperability can be viewed in two dimensions: the horizontal dimension (between two separate applications), which by nature is the dimension at play when two different systems interact; and the vertical dimension, which concerns the components of a single application. This is typically the case between the application itself and the underlying infrastructure components (for example, an application may require a specific database that, itself, works only on a particular operating system, without any functionalities coming into play). This is where application adherence factor in, falling outside the scope of interoperability but nevertheless sharing a number of fundamental principles with it.

#### Cloud computing
Cloud computing consists of providing infrastructure services and application services on demand. This is made possible through a high level of virtualization of hardware components by way of service infrastructure software. Cloud computing is based on a complex software architecture that simultaneously manages the elasticity of resources (processors, random access memory, storage and networks) and the ability of applications to make optimal use of these resources.

In terms of interoperability, there is no fundamental difference between a conventional infrastructure and a cloud, other than the complexity of the latter and the need to standardize vertical and horizontal components to a much greater degree. In particular, any outsourcing of infrastructure or applications to a public cloud must take into account the private or third-party organization's ability to apply standards that allow for the possibility of changing providers or reinstating a certain number of services, if necessary. In this context, the lack of an interoperability framework and open standards accepted by the provider poses a significant risk to the sustainability of the solution.

With respect to deploying a private cloud, interoperability promotes competition between providers, with respect to both hardware and software, as well as the ability to further develop the infrastructure over time. Indeed, the use of standards, through APIs for example, increases independence from the different drivers specific to the hardware components, and makes these infrastructure services independent from the software it deploys.

The implementation of a cloud is therefore a unique opportunity to standardize these processes and agree on a common framework. The use of an interoperability framework and the use of standards makes it easier and less costly to outsource part of the infrastructure of it to a third-party organization, or to migrate onto Shared Services Canada, in a hybrid solution.

#### Interoperability framework
An interoperability framework is defined as a set of policies, guidelines, standards, rules and recommendations made by a network of actors with a view to achieving the highest level of interoperability possible.

It also describes the operating rules that govern the analysis, selection, adoption and updating of each of these elements.

To ensure the deployment and longevity of interoperable systems, it is necessary to jointly select the standards to be adopted as well as the conditions for their implementation.

This is why several European countries (including France and the UK) and Canadian provinces such as Quebec have chosen to establish interoperability frameworks. The results are compelling, as open standards are regularly and widely used, and always the first approach to be considered when new requirements emerge.

As mentioned in the various interoperability frameworks that have already been published, they are designed only to identify key standards and not to offer predefined, unique solutions (for example, in terms of which software to choose). The objective of an interoperability framework is, therefore, to facilitate and guide an organization's interoperability choices while also limiting the number of potential standards in order to guarantee maximum clarity.


### Actions
The GC will:
- publish an interoperability framework with selected open standards for use by all departments and agencies (ex.: HTML5/EPUB3 for publications and ODF for sharing/collaborating on documents);
- configure existing solutions to use open standards where possible;
- use commonly accepted open standards for open data and information;
- require that all new purchases, upgrades or migrations (including cloud solutions) store and manage data with open standards, starting immediately;
- factor in the use of open standards when calculating total cost of ownership of a solutions including exit or transition costs;



### Examples
#### UK
- [Open standards for government](https://www.gov.uk/government/publications/open-standards-for-government)
- [Open Standards principles](https://www.gov.uk/government/publications/open-standards-principles/open-standards-principles)

#### Canada
- TBS [Open Data Principles](http://open.canada.ca/en/open-data-principles) (Use of Commonly Owned Standards)
