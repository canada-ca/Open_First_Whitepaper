[« Previous Page : Open Source Software Use](33_Open_Source_Software_Use.md) | [Table of Contents](../README.md#table-of-contents) | [Next Page: Open Markets »](5_Open_Markets.md)

## Open Source Software Contribution

- [Releasing Open Source Software](#releasing-open-source-software)
- [Benefits](#benefits)
- [Risks and Drawbacks](#risks-and-drawbacks)
- [Best Practices for releasing OSS](#best-practices-for-releasing-oss)
- [OSS licences](#oss-licences)
- [Code Repositories](#code-repositories)
- [Examples](#examples)

### Releasing Open Source Software

The Government of Canada creates greater transparency and accountability, increases citizen engagement, and drives innovation and economic opportunities through open data, open information, and open dialogue.

When developing entirely new software a business or government organization needs to make a choice between keeping the source code restricted or releasing it as OSS. Governments and non-profit organizations may wish to release software as OSS to provide a range of additional benefits to OSS communities, businesses, and the general public. Software vendors and other businesses often release software as OSS where it is ancillary to their core business. They thereby benefit from others collaborating on the software, spreading out the development costs, without reducing their market share for their core competencies.

Developers who contribute to OSS and distribute it come from wide and varied environments across the public sector, private sector and academia. Studies show numerous and diverse motivations for FOSS participation, ranging from economic gain to a sense of civic duty towards social and technological advancement. Risks and drawbacks of OSS participation also widely differ, depending on the context. ([source](http://www.irma-international.org/viewtitle/10083/))

### Benefits

#### Collaboration to Lower Development Costs

When we publicly release an in-house software program under an OSS licence, it encourages external contributions from governments, companies, students and citizens in the form of source code, bugs and documentation. The project can be a joint effort amongst multiple companies, public sector workers, and individual volunteers. Companies regularly invest a share of resources to participate in OSS projects: 40% of developers in OSS communities are paid to participate. ([source](http://www.mitpressjournals.org/doi/pdf/10.1162/itgg.2007.2.3.97))

When collaborating to develop new features or creating a new project built on existing OSS, a company or organization also leverages all the work that collaborators have previously invested. If distributing modifications as OSS, prior work can even include code and libraries under reciprocal licences (which a company or organization can only ever distribute if its project is OSS as well).

With increasing global competition, rising R&D costs and shortening product life cycles, companies are reducing their reliance on traditional models of closed innovation. Increasingly they depend on accessing external sources of knowledge and collaborating with individuals, companies and other organizations that possess relevant knowledge that may be used to benefit the organization's innovation process. ([source](papers.ssrn.com/sol3/papers.cfm?abstract_id=2493736))

#### Long-term Feasibility

Releasing software as OSS to encourage others to collaborate on it can also help ensure the viability of a project into the future. For example, an organization or company may develop a software tool with a fixed and limited research and development budget. For the project to continue and grow, the participation of other collaborators is necessary.

#### Reputation Building

For individuals participating in OSS development, a common motivating factor and concrete benefit is building a good reputation. In some cases, the goal is to exhibit skills and talents to employers; in other cases, it is to earn status with a community.

Most OSS projects are open for any developer to contribute. Thus, participants are able to develop and demonstrate their talent to potential employers. Not only can participants add their involvement to a C.V., but employers can also screen and hire talent directly from a pool of the developers contributing to a OSS project. These developers may have proven competencies in desirable areas of expertise. ([source](http://www.mitpressjournals.org/doi/pdf/10.1162/itgg.2007.2.3.97))

A culture of “meritocracy” popular within many FOSS projects also serves to benefit contributors with status and privilege. In general, the strongest contributors tend to have the most control over the project - for example, in deciding upon priorities for new features. ([source](http://oss-watch.ac.uk/resources/meritocraticgovernancemodel))

Of course, reputation and good will are also extremely important to public sector contributors. Participation in OSS can help build a positive reputation amongst other developers and amongst OSS users.

#### Public Benefits

OSS can align well with the role of public sector agencies in providing wide benefits to the public-at-large, such as in maintaining society’s technological infrastructure and helping it evolve.

A newer phenomenon is the emergence of social enterprises and entrepreneurial interest in making governments work better, particularly at the local level. Civically-engaged technologists develop OSS applications to solve social issues such as bureaucratic delays. Although not all software projects with broader social aims are OSS, the benefits of OSS in improving the overall availability of re-usable technology in society often aligns well with the aims of these social entrepreneurs.

Even outside of social enterprises, the release of OSS by public sector organizations can help stimulate innovation in the private sector. It enables companies to create specialized offerings built on OSS, even where such software might otherwise be too expensive for the company to develop in-house.

OSS can also help maximize overall economic efficiency within society. Where software is freely available, and where anyone can add any new features needed, companies can make use of these existing resources rather than expend effort duplicating an existing project.

#### Employer Benefits

During hiring processes IT management may use contributions as a metric to assess the quality of potential hires. Further, applicants can be encouraged to familiarize themselves with parts of the source code in preparation for the interview process. As a result, employees can enter the workplace familiar with parts of the code base reducing the amount of time required to train the employee to become a maximally productive member of the team.

#### Security

As discussed with respect to [Open Source Software](3_Open_Source_Software.md), OSS distribution likewise has security pros and cons. OSS puts more eyes on the code to fix security issues but, at the same time, it makes the code available to those with malicious aims.

#### Open Science

The scope of data sets used in scientific research has expanded dramatically recently. Genetic studies now routinely use terabytes of sequence data. The technologies that generate these data are developing rapidly, and rigorous analysis increasingly requires scientists to modify existing software, or create entirely new programs. This is only possible because standard practice in the scientific community has embraced the creation and sharing of computer code using Open Software licensing.

Consequently, full participation in the scientific community will increasingly require government scientists to produce and share computer code. Indeed, as software becomes more important to science, journals are starting to require the release of code as a condition of publication. [PLOSOne](http://journals.plos.org/plosone/s/materials-and-software-sharing "PLOSOne"), one of the premier open-access science publishers, expects "that all researchers submitting to PLOS submissions in which software is the central part of the manuscript will make all relevant software available without restrictions upon publication of the work". As the proportion of research in which "software is central" to the work increases, it is clear that government scientists will need supportive policies in order to continue to participate.

#### Transparency

Canada has set a very clear Open Government mandate to "create greater transparency and accountability, increase citizen engagement, and drive innovation and economic opportunities through open data, open information, and open dialogue". Sharing in-house software programs under an open source licence naturally align to these objectives and is a great way to give back to taxpayers. Also, open access to an OSS project (e.g. source code, issues/bugs, governance/meeting minutes, support documentation/forum) allows real assessment of its maturity along with the level of activity of its community and support provider(s). Therefore, it's easier to compare the development velocity and health of multiple projects/solutions.

### Risks and Drawbacks

#### Lack of Direct Licensing Revenue

The fact that anyone can redistribute OSS for free is an obvious barrier for many software vendors who are not engaging the OSS business model. Other than nominal charges for distribution on physical media, it is generally not feasible to profit from OSS using the traditional business model of directly selling software licences. The lack of direct licensing revenue can also pose a barrier in public sector organizations where “cost recovery” policies are in place. Even though OSS may aid numerous public service goals, these do not necessarily help to offset the costs and risks of developing the software.

It should be noted, however, that for many software projects in which government employees, and particularly scientists, may be engaged, the economic value of an individual program will be minimal. In organizations where there is no established mechanism for selling software, the effort necessary to establish and manage the sale of programs, and to provide the level of support that would be expected in a commercial marketplace, is likely to exceed any potential revenues that may be realized.

#### Community May Not Coalesce

There are many examples of thriving OSS projects such as the Linux kernel, the Apache web server and the Firefox Web Browser. These projects involve active communities with hundreds, and in some cases thousands, of software developers. However, there is also a relatively high count of OSS projects where active development has ceased. Of course, many of these projects are likely those of individual developers who registered a project but made no subsequent efforts or headway in developing a community. In any case, the numbers do suggest a cautionary tale: to properly execute a OSS project, you should be prepared to invest the resources to see a project through a first release and any lag in community involvement. To address this risk the GoC should create systems which promote, or introduce a reward system for, open-source contributions which is geared to promoting the efforts of employees toward the achievement of open, collaborative outcomes (source?).

#### Legal Complexities

Releasing software as OSS usually requires a careful legal consideration of the licences, especially when the software includes libraries and code from multiple sources. Although closed-source licences also require careful legal scrutiny, many OSS licences are long and contain legal complexities with which in-house legal staff may not be familiar. Some international interoperability agreements may include clauses that prevent use of OSS components. (example?)

#### Patent Liability Risk

Opinions are equally divided on whether releasing software as OSS increases or decreases the risk of patent liability. On the one hand, distributing your code as OSS opens it up to further scrutiny. Others can look through the code and attempt to find patent infringements. On the other hand, collaborators on OSS projects may help re-engineer around patents as soon as an infringement is discovered. The potential adverse consequences on public relations and good will in launching a patent lawsuit against a OSS community can also have a strong deterrent effect. Non-profit organizations such as the [Software Freedom Law Center](http://www.softwarefreedom.org/) also offer resources to help OSS projects defend against patent infringement suits and invalid patent claims. Another drawback is that individual volunteers rarely have defensive patent portfolios. However, by the same token, going after individuals is also expensive for patent litigators. Most individuals alone do not have enough net worth to make a patent lawsuit against them worthwhile.

### Best Practices for releasing OSS

#### Deciding to Distribute Software as OSS

A decision on whether to license software as OSS should always start with an assessment of the business requirements and the aims of the project. The business requirements will greatly impact the weight that you should give to various benefits and drawbacks. Companies and organizations release software as OSS at many different stages of the development cycle. In some cases, software has seen many releases and iterations before it becomes OSS. In other cases, software may commence its life as a collaborative OSS project amongst several parties. The OSS development philosophy is sometimes described as: "release early, release often and listen to your customers". However, it is generally a good practice to have a plan for the initial project architecture before starting distribution as OSS. The plan may be as simple as having several collaborators start working on the architecture when the project commences. Where no plan exists, however, developers working on different pieces of the project might run into difficulties integrating their respective pieces or working into a cohesive application.

#### Security Classification

The Treasury Board [Directive on Departmental Security Management (DDSM)](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=16579) defines protected information as one that "may qualify for an exemption or exclusion under the Access to Information Act or the Privacy Act because its disclosure would reasonably be expected to compromise the non-national interest."

In order for source code to potentially be deemed protected, it would have to contain any of the following information:

- Information obtained in confidence
- Information about federal-provincial affairs
- Information about international affairs and defence
- Information about law enforcement and investigations
- Information about the safety of individuals
- Information about the economic interests of Canada
- Personal information
- Third party information
- Advice about certain aspects of operations of government
- Information about testing procedures, tests, and audits
- Information that is subject to solicitor-client privilege
- Information that is subject to statutory prohibitions
- Certain types of information held by the Canadian Broadcasting Corporation and Atomic Energy of Canada Limited
- Confidences of the Queen’s Privy Council for Canada

It is highly unlikely that developers would intentionally include such information in their source code. As a result, the proposed categorization for the confidentiality of source code is considered unclassified unless the developer has included, inadvertently or otherwise, information that falls under the [exemptions](http://laws-lois.justice.gc.ca/eng/acts/a-1/page-3.html#h-10) and [exclusions](http://laws-lois.justice.gc.ca/eng/acts/a-1/page-10.html#h-29) of the [Access to Information Act](http://laws-lois.justice.gc.ca/eng/acts/A-1/) as listed above. Where feasible, this information should be removed from the source code to increase the ability for code to be shared.

Some security considerations to keep in mind when developing software:

- Keep sensitive data such as credentials secure and separate from source code.
- Avoid storing keys and other sensitive material in systems not approved for that purpose.
- Code reviews increase the likelihood of catching bugs, security vulnerabilities, and reduces the risk of committing sensitive data.
- Implement controls sufficient to prevent unauthorized or inadvertent changes.

#### Choosing a Licence

You will not always have a choice as to which licence you apply. Where a reciprocal licence obligation is in force, you need to license your code under the same licence - see the section on Due Diligence / Licence Management, below. As well, even if you are not under a strict legal obligation to apply a particular licence, you may still wish to adopt the same licence as an existing software project or community in order to become involved with it.

Where you distribute a project consisting entirely of your own code, or consisting of your own code along with permissively-licenced code and code which does not engage reciprocal obligations, you can choose the OSS licence yourself. The licence you choose should reflect your business requirements. All common OSS licences can be adopted for works by government, industry, or the education sector - you need to look at particular project aims.

Choosing an appropriate licence tends to revolve around the decision of whether to apply a reciprocal or permissive licence:

- Permissive licences maximize the scope of downstream users (with broad appeal to the entire private sector); while
- Reciprocal licences are appropriate in cases where it is important to receive back downstream changes, or where it is important to ensure that work built on an initial investment remains open and free. Reciprocal licences can also put a focus on benefiting other private-sector businesses that provide services and support.

The following chart details other key differences in this decision:

|                                          | Permissive | Reciprocal |
| ---------------------------------------- | ---------- | ---------- |
| **Beneficiaries of the OSS release**         | Everyone: commercial software vendors, support services, etc. | Everyone, but only where they are willing to release their software as OSS, under the same licensing terms as were granted to them (note that some closed-source software vendors absolutely prohibit reciprocal licences such as the GPL). |
| **Beneficiaries of downstream code changes** | The whole community, but only where the business (or other developer) chooses to contribute modifications back under the permissive licence. | The whole community in every case where a business, organization, or individual distributes the modifications, as the licence then mandates releasing the changes under the same OSS licence. |
| **Licence complexity**                       | Often very simple and understandable (e.g., popular "2-clause BSD"). | Relatively complex, requiring careful legal analysis (and some risk of misinterpretation). |
| **Interoperability**                         | Permissively-licenced code can be included in projects under reciprocal licences, other permissive licences, or closed-source licences. | Reciprocal-licenced code cannot generally be included in a project under any other single licence. |

[Choosealicence.com](https://choosealicense.com/) simplifies the process of selecting an OSS licence by presenting definitions of the most widely used licenses.

#### Managing Project Participation

Open source software often brings together a disparate community of developers, ranging from volunteer hobbyists to commercial enterprises. In the absence of a formal management and communication structure as found in a unified corporate development environment, OSS communities use a variety of techniques to self-manage their projects in this environment.

### OSS licences

You should publish your code under an [Open Source Initiative approved licence](https://opensource.org/licenses). For example, CDS uses the MIT licence.

All code produced by civil servants is automatically covered by Crown Copyright.

### Code Repositories

- Gitlab
- Github
- Framagit
- GCcode (internal)

### Examples

#### US

- [Digital Services Playbook](https://playbook.cio.gov/) - If the codebase has not been released under an open source license, explain why.
- [18F Open Source Policy](https://github.com/18F/open-source-policy/blob/master/policy.md) - Develop our work in the open - publish publicly all source code created or modified by 18F, whether developed in-house by government staff or through contracts negotiated by 18F.
- [Federal Source Code Policy](https://sourcecode.cio.gov/) - Pilot program that requires agencies, when commissioning new custom software, to release at least 20% of new custom-developed code as OSS.

#### UK

- [Technology Code of Practice](https://www.gov.uk/government/publications/technology-code-of-practice/technology-code-of-practice) - Make things open by making all new source code open by default.

#### Canada

- [Natural Resources Canada Free and Open Source Software Licensing Primer](http://ftp.maps.canada.ca/pub/nrcan_rncan/publications/ess_sst/295/295663/cgdi_ip_33_e.pdf)
