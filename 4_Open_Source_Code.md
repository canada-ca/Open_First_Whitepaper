[« Previous Page : Open Source Software](3_Open_Source_Software.md) | [Table of Content](TOC.md) | [Next Page: Open Markets »](5_Open_Markets.md)

## Open Source Code
- [Benefits](#benefits)
- [Drawbacks and Risks](#drawbacks-and-risks)
- [Best Practices](#best-practices)
- [Code Repositories](#code-repositories)
- [Actions](#actions)
- [Preferred OSS Licences](#preferred-oss-licences)
- [Preferred Code Repositories](#preferred-code-repositories)
- [Examples](#examples)

The Government of Canada creates greater transparency, accountability, increases citizen engagement, and drives innovation and economic opportunities through open data, open information, and open dialogue.

When developing entirely new software a business or government organization needs to make a choice between keeping the source code restricted or releasing it as OSS. Governments and non-profit organizations may wish to release software as OSS to provide a range of additional benefits to OSS communities, businesses, and the general public. Software vendors and other businesses often release software as OSS where it is ancillary  to  their  core  business. They thereby benefit from others collaborating on the software, spreading out the development costs, without reducing their market share for their core competencies.

Developers who contribute to OSS and distribute it come from wide and varied environments across the public sector, private sector and academia. Risks and drawbacks of OSS participation also widely differ, depending on the context.


### Benefits
#### Collaboration to Lower Development Costs
Distributing code as OSS allows others to join in on the development effort, making a project a joint effort amongst multiple companies, public sector workers, and individual volunteers. Companies regularly invest a share of resources to participate in OSS projects. When collaborating to develop new features or creating a new project built on existing OSS, a company or organization also leverages all the work that collaborators have previously invested. If distributing modifications as OSS, prior work can even include code and libraries under reciprocal licences (which a company or organization can only ever distribute if its project is OSS as well). 
With increasing global competition, rising R&D costs and shortening product life cycles, companies are reducing their reliance on  traditional models of closed innovation. Increasingly they depend on accessing external sources of knowledge and collaborating with individuals, companies and other organizations that possess relevant knowledge that may be used to benefit the organization's innovation process (papers.ssrn.com/sol3/papers.cfm?abstract_id=2493736). 

#### Long-term Feasibility
Releasing software as OSS to encourage others to collaborate on it can also help ensure the viability of a project into the future. For example, an organization or company may develop a software tool with a fixed and limited research and development budget. For the project to continue and grow, the participation of other collaborators is necessary.

#### Reputation Building
For individuals participating in OSS development, a common motivating factor and concrete benefit is building a good reputation. In some cases, the goal is to exhibit skills and talents to employers; in other cases, it is to earn status with a community. Most OSS projects are open for any developer to contribute. Thus, participants are able to develop and demonstrate their talent to potential employers. These developers may have proven competencies in desirable areas of expertise. In general, the strongest contributors tend to have the most control over the project - for example, in deciding upon priorities for new features. Of course, reputation and good will are also extremely important to public sector contributors. Participation in OSS can help build a positive reputation amongst other developers and amongst OSS users.

#### Public Benefits
OSS can align well with the role of public sector agencies in providing wide benefits to the public-at-large, such as in maintaining society’s technological infrastructure and helping it evolve.

A newer phenomenon is the emergence of social enterprises and entrepreneurial interest in making governments work better, particularly at the local level. Civically-engaged technologists develop OSS applications to solve social issues such as bureaucratic delays. Although not all software projects with broader social aims are OSS, the benefits of OSS in improving the overall availability of re-usable technology in society often aligns well with the aims of these social entrepreneurs.

Even outside of social enterprises, the release of OSS by public sector organizations can help stimulate innovation in the private sector. It enables companies to create specialized offerings built on OSS, even where such software might otherwise be too expensive for the company to develop in-house. 

OSS can also help maximize overall economic efficiency within society. Where software is freely available, and where anyone can add any new features needed, companies can make use of these existing resources rather than expend efforts duplicating an existing project.

### GOC Benefits 
During hiring processes IT management may use contributions as a metric to assess the quality of potential hires. Further, applicants can be encouraged to familiarize themselves with parts of the source code in preparation for the interview process. As a result, employees can enter the workplace familiar with parts of the code base reducing the amount of time required to train the employee to become a maximally productive member of the team.

#### Security
As discussed with respect to [Open Source Software](3_Open_Source_Software.md), OSS distribution likewise has security pros and cons. OSS puts more eyes on the code to fix security issues but, at the same time, it makes the code available to those with malicious aims.


### Drawbacks and Risks
#### Lack of Direct Licensing Revenue
The fact that anyone can redistribute OSS for free is an obvious barrier for many software vendors who are not engaging the OSS business model. Other than nominal charges for distribution on physical media, it is generally not feasible to profit from OSS using the traditional business model of directly selling software licences. The lack of direct licensing revenue can also pose a barrier in public sector organizations where “cost recovery” policies are in place. Even though OSS may aid numerous public service goals, these do not necessarily help to offset the costs and risks of developing the software.

#### Community May Not Coalesce
There are many examples of thriving OSS projects such as the Linux kernel, the Apache web server and the Firefox Web Browser. These projects involve active communities with hundreds, and in some cases thousands, of software developers. However, there is also a relatively high count of OSS projects where active development has ceased. Of course, many of these projects are likely those of individual developers who registered a project but made no subsequent efforts or headway in developing a community. In any case, the numbers do suggest a cautionary tale: to properly execute a OSS project, you should be prepared to invest the resources to see a project through a first release and any lag in community involvement. To address this risk the GoC should create systems which promote, or introduce a reward system for, open-source contributions which is geared to promoting the efforts of employees toward the achievement of open, collaborative outcomes[2].

#### Legal Complexities
Releasing software as OSS usually requires a careful legal consideration of the licences, especially when the software includes libraries and code from multiple sources. Although closed-source licences also require careful legal scrutiny, many OSS licences are long and contain legal complexities with which in-house legal staff may not be familiar.

#### Patent Liability Risk
Opinions are equally divided on whether releasing software as OSS increases or decreases the risk of patent liability. On the one hand, distributing your code as OSS opens it up to further scrutiny. Others can look through the code and attempt to find patent infringements. On the other hand, collaborators on OSS projects may help re-engineer around patents as soon as an infringement is discovered. The potential adverse consequences on public relations and good will in launching a patent lawsuit against a OSS community can also have a strong deterrent effect. Non-profit organizations such as the [Software Freedom Law Center](http://www.softwarefreedom.org/) also offer resources to help OSS projects defend against patent infringement suits and invalid patent claims. Another drawback is that individual volunteers rarely have defensive patent portfolios. However, by the same token, going after individuals is also expensive for patent litigators. Most individuals alone do not have enough net worth to make a patent lawsuit against them worthwhile.

### Best Practices
#### Deciding to Distribute Software as OSS
A decision on whether to license software as OSS should always start with an assessment of the business requirements and the aims of the project. The business requirements will greatly impact the weight that you should give to various benefits and drawbacks. Companies and organizations release software as OSS at many different stages of the development cycle. In some cases, software has seen many releases and iterations before it becomes OSS. In other cases, software may commence its life as a collaborative OSS project amongst several parties.  The OSS development philosophy is sometimes described as: "release early, release often and listen to your customers". However, it is generally a good practice to have a plan for the initial project architecture before starting distribution as OSS. The plan may be as simple as having several collaborators start working on the architecture when the project commences. Where no plan exists, however, developers working on different pieces of the project might run into difficulties integrating their respective pieces or working into a cohesive application.

#### Choosing a Licence
You will not always have a choice as to which licence you apply. Where a reciprocal licence obligation is in force, you need to license your code under the same licence - see the section on Due Diligence / Licence Management, below. As well, even if you are not under a strict legal obligation to apply a particular licence, you may still wish to adopt the same licence as an existing software project or community in order to become involved with it.

Where you distribute a project consisting entirely of your own code, or consisting of your own code along with permissively-licenced code and code which does not engage reciprocal obligations, you can choose the OSS licence yourself. The licence you choose should reflect your business requirements. All common OSS licences can be adopted for works by government, industry, or the education sector - you need to look at particular project aims.

Overall, licensing decisions tend to involve one primary and consequential decision: whether to apply a reciprocal or permissive licence:
- Permissive licences maximize the scope of downstream users (with broad appeal to the entire private sector); while
- Reciprocal licences are appropriate in cases where it is important to receive back downstream changes, or where it is important to ensure that work built on an initial investment remains open and free. Reciprocal licences can also put a focus on benefiting other private-sector businesses that provide services and support.

#### Due Diligence / Licence Management
##### Managing Licence Obligations
Where reciprocal licensing obligations apply, you do not have the benefit of being able to choose a licence. Your code - to the extent specified in the reciprocal licence - must come under the exact same licence when you distribute it (or, if the licence permits, a later version of the same licence). In such a case where you encounter a reciprocal licensing obligation, there are three ways to comply:
1. Do not distribute your software;
2. License your software under the exact same licence (or, where the licence permits, a compatible licence); or
3. Re-implement parts of your software such that it does not include any code or libraries that come under a reciprocal licence (or, at least, ensure that your code does not integrate tightly with reciprocal code such that the obligation engages).

Closed-source software vendors typically opt for solution three when they notice inadvertent reciprocal code, given that they need to distribute their software to paying customers but do not usually want to open up the rest of their source code to others. It is therefore important for these vendors to conduct a “due diligence” audit on their software projects, checking that their software does not include any OSS code or libraries that engage a reciprocal licensing obligation.

Likewise, organizations and businesses releasing their code as OSS should also conduct due diligence audits. Although they are already applying a OSS licence, a reciprocal licensing obligation generally imposes a requirement to licence the code under the exact same licence. Thus, releasing code under a different OSS licence may not always comply. It may be necessary to dual-license your own code under the other reciprocal licence, or, in a similar manner to the closed-source context, ensure that the software does not include any code or libraries that engage the reciprocal obligation. Although reciprocal obligations pose the strictest set of parameters, organizations and businesses must also ensure they comply with other licensing terms. For example, they must comply with notice requirements and obligations to distribute the original source code. A due diligence audit ensures that this compliance is in place.

There are two general methods to conduct a due diligence audit: provenance checking and code scanning.

##### Provenance Checking
Provenance checking involves maintaining a careful audit trail: the developers maintain internal records of what code is in the project, how that code is used, and what licence applies to each element. Some build automation tools such as Maven (which developers use to automate code compilation and deployment) help with functionality to indicate, track, and report licences in a project, thereby assisting and standardizing the task of keeping records.

Looking at the internal audit records, a licensing expert can check a project for compliance either when a developer adds a new external element or upon release of the software (or both). A fresh legal analysis of the licence text is not required for each and every new library imported into a project. Once a licence manager approves use of a particular licence within a project, developers can generally safely use other libraries under the same licence, as long as they use them in a similar manner. For example, a business or organization might establish a policy for a project that: grants automatic approval for specific permissive licences including BSD, MIT and Apache; grants approval for weak reciprocal licences such as the LGPL on a case-by-case basis; and grants approval for strong reciprocal licences, such as the GPL, only after a careful and thorough legal analysis.

##### Automated Code Scanning
In many cases, provenance checking should prove sufficient for smaller projects. However, it may prove impractical for larger companies or larger projects. A large company often owns code purchased from other parties, or code received from acquisitions and mergers, that may have no accurate licence audit for the code. In this case, it is best to use automated code scanning tools that search through the entire code base to determine the licences that apply. Automated code scanning utilities search text files and embedded code comments that may indicate the licence applicable to a particular element of the software. Some tools even compare the code itself against known third-party OSS code.

Of course, while these tools can prove highly useful, it must be kept in mind that the results do not provide certainty that the source code is under only the reported licences, nor that it is free of copyright or patent infringements. An inherent limitation of the audit is that it can only compare the client’s source code to a wide, but not exhaustive, collection of other source code repositories. It may not detect copyrighted source code from closed-source vendors, or source code from smaller OSS projects. Where possible, businesses and organizations may also wish to reduce their risks and ease the auditing task by using software libraries from trustworthy organizations that have already audited the library code.


#### Patent Management and Other Legal Issues
All of the OSS legal considerations which apply when using OSS equally apply when you distribute OSS. For code that you distribute, the lack of a disclaimer and warranty can work in your favour. The lack of a choice of forum or choice of law clause generates equal legal uncertainty for all parties. In addition to these legal issues, OSS distribution raises concerns related to patents. By licensing your code under a OSS licence, you may either implicitly or explicitly license the patents you own if any of the code implicates them. It is important to understand the nature and scope of the patent licences you grant.

##### Patent Licence Scope
The treatment of patents varies greatly throughout different OSS licences. The traditional approach – still seen in popular permissive licences such as BSD and MIT – is an implicit patent licence: the licence makes no specific mention of patents, but rather the stated right to use the software implicitly grants the licensee permission to “use” any relevant patents held by the licensor. An implicit patent licence almost certainly grants others the right to use the original code as distributed, including where such use implicates patent held by the licensor. However, the scope of an implicit patent licence becomes less clear when downstream parties modify the original code. If the modifications change the typical “use” of the software, does the original patent licence still cover a use that is different from what the licensor originally intended? If a new use infringes a different patent held by the original licensor, does the broad grant of rights to make modifications also end up licensing this other patent? Most likely, the answer to these two questions in “no”: the implicit patent grant often covers only uses implicated by the licensor's original contributions, but not other uses that additional features and modifications might involve. Most modern OSS licences attempt to increase clarity and legal certainty by making this scope limitation explicit. For example, the Apache Version 2.0 licence provides:
>  Subject to the terms and conditions of this License, each Contributor hereby grants to You a perpetual, worldwide, non-exclusive, no-charge, royalty-free, irrevocable (except as stated in this section) patent license to make, have made, use, offer to sell, sell, import, and otherwise transfer the Work, where such license applies only to those patent claims licensable by such Contributor that are necessarily infringed by their Contribution(s) alone or by combination of their Contribution(s) with the Work to which such Contribution(s) was submitted. Under this clause, the patent licence only extends to uses of the software applicable to existing contributions. Where further downstream contributions alter the software's use, the original patent licence may no longer apply.

Although a OSS licence could feasibly grant a broader patent licence that would cover downstream modifications, no popular licences presently take this approach. Not even the highly freedom-assertive GPLv3 licence makes such a grant. Given the nearly limitless number of ways that additional features could alter the typical use of a software application, such a broad patent licence is likely untenable for most businesses managing a patent portfolio.

Therefore, as a best practice, whenever you modify OSS you should consider whether the modifications change the use of the software in a way that might implicate other patent licences, or in such a way that existing patent licences may not cover the new use.

##### Patent Termination and Retaliation Clauses
Many OSS licences attempt to protect the software against patent infringement lawsuits by including automatic-termination clauses. These clauses trigger whenever a licensee alleges that any part of the software infringes his or her patent. For example, the Apache Version 2.0 licence succinctly states:
>  If You institute patent litigation against any entity (including a cross-claim or counterclaim in a lawsuit) alleging that the Work or a Contribution incorporated within the Work constitutes direct or contributory patent infringement, then any patent licenses granted to You under this License for that Work shall terminate as of the date such litigation is filed.

These triggers differ amongst licences. For example, unlike the Apache Version 2.0 licence, the Mozilla Public License Version 2 (MPLv2) explicitly allows parties to defend themselves with patent infringement counterclaims and crossclaims, all without triggering the termination clause.

Some licences also include broader retaliation clauses - that is, a broader termination of rights. The Apache Version 2.0 patent termination clause, set out above, only terminates patent licences. The MPLv2, on the other hand, terminates all rights under both copyright and patent law. When involved in patent infringement litigation - whether initiating an originating action or a counterclaim - it is important to carefully assess the impact this could have on any OSS that you use or contribute towards.

#### Managing Project Participation
Open source software often brings together a disparate community of developers, ranging from volunteer hobbyists to commercial enterprises. In the absence of a formal management and communication structure as found in a unified corporate development environment, OSS communities use a variety of techniques to self-manage their projects in this environment.


### Actions
The GC will:
- publish guidance for departments and agencies to release code developed interaly as OSS;
- use OSS in our projects and contribute back to the open source community;
- publish as OSS all source code created or modified, whether developed in-house by government staff or through negotiated contracts, starting immediately;
- be an active contributor to OSS projects that it or its clients utilize;
- encourages contributions to its OSS projects, whether it be code, commentary, bug reports, feature requests, or overall strategic direction;
- adopt permissive licenses for its OSS projects and comply to the licenses of OSS projects they contribute to.


### Preferred OSS licences
- **Permissive**: MIT
- **reciprocal**: GPL


### Preferred Code Repositories
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
