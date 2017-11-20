## Open Source Software
- [Terminology](#terminology)
- [History](#history)
- [Intellectual property](#intellectual-property)
- [Benefits](#benefits)
- [Security](#security)
- [Economic models](#economic-models)
- [Using and Procuring](#using-and-procuring)
- [Development](#development)
- [Publishing code](#publishing-code)
- [Examples](#examples)

### Terminology
Source code is the human readable version of software.  The code is written by developers and can be read and modified by others.  The code can be compiled into an executable or binary, that is not readable.

Free software and open source software is software where the source code is distributed and can be used, copied, studied and redistributed without restrictions.

Free software is the original name put forward by Richard Stallman and defended by the Free Software Foundation (FSF).  Free software is defined by [four essential freedoms](https://www.gnu.org/philosophy/free-sw.en.html).  The freedom to run the program, study how it works, modify it and redistribute it.  Access to the source code is a precondition for these freedoms and not the end goal itself.

Open Source Software is the name used by the Open Source Initiative. They're the authority on certifying whether a software licence is an open source licence.  Open source software is defined in the [Open Source Definition](https://opensource.org/docs/osd) by 10 criteria.

Free in English can mean something is available at no cost, or that it gives you certain freedoms. Much is available online comparing free speech, free beer & even free kittens as metaphors for free software.

Free software and open source software are almost equivalent but represent two different visions and neither want to be included in the other.  You will find authors using "free open source software (FOSS)" or "free/Libre open source software (FLOSS)".  For the purposes of this whitepaper we opted to use "open source software (OSS)" to talk about free (in the sense of freedom) software and open source software.

### History
OSS goes back to the beginnings of computer science. Many of the successes of Open Government could only be possible because of open source code and the generosity of internet communities. We should pay that back.

Software licensing (open source and proprietary) trace their origins from a common source: the Unix operating system.  This story is detailed in the [Origins and History of Unix](http://www.faqs.org/docs/artu/ch02s01.html). Unix was developed by AT&T Bell Laboratories in the late 1960s and early 1970s and was the first general-purpose operating system. At that time, the US Justice Department issued a consent decree barring AT&T from engaging in commercial activities outside the field of its primary business, telephone service. Because of the consent decree, AT&T could not exploit Unix as a commercial product, so Bell Labs gave Unix away in source code form under terms that allowed its modification and redistribution. This led to Unix’s widespread use and popularity among computer scientists in the 1970s and 1980s.

After the US Justice Department lifted the consent decree in 1983, AT&T commercialized Unix as a proprietary product and adopted more restrictive licensing terms. Meanwhile, the 1980s saw the advent of microcomputers (PCs), which led to the standardization of software. This standardization, in turn, encouraged companies to distribute their software in binary-only form because there was less need for users to investigate or troubleshoot source code. And so proprietary licensing became the dominant model for licensing software.

Following to this change, Richard Stallman and the GNU Project started to build an operating system that would be a free alternative to UNIX.  This is around the same time as the Free Software Foundation was started to promote the use of free software. The operating system needed both kernel and the tools necessary to install, run and develop programs for it.  The GNU Project developed the tools but was missing a working kernel.  This is when Linus Torvalds, a teenager in Finland, developed the first Linux kernel as a school project.

The combination of the Linux kernel and the GNU tools - most commonly called Linux - was released under the GNU General Public License (GPL), a licensing model that was created by the GNU Project. The GPL granted recipients unfettered rights to redistribute software with the condition that the source code could not be kept secret. As Linux grew in popularity, with thousands of contributors and billions of users, the industry learned to follow and adopt GPL’s terms. By the late 1990s, GPL and the open source licensing paradigm more broadly gained traction and industry-wide acceptance.

### Intellectual property
#### Licences
Today, the GPL license is in its third version (GNU GPLv3) and is only one of several dozen types of open source licenses. The Open Source Initiative has approved more than 80 open source licenses. These generally fall into one of two categories: permissive licenses and reciprocal licenses.

A permissive license is simple and is the most basic type of open source license: It allows you to do whatever you want with the software as long as you abide by the notice requirements. Permissive licenses provide the software as-is, with no warranties. So permissive licenses can be summarized as follows:
- Do whatever you want with the code
- Use at your own risk
- Acknowledge the author/contributor

Examples of permissive licenses include: BSD, MIT and Apache

Reciprocal licenses add requirements to the permissive license. In addition to the requirements listed above, reciprocal licenses also require that:
- If you distribute binaries, you must make the source code for those binaries available
- Code must be available under the same reciprocal terms under which you got the code
- You cannot place additional restrictions on the licensee's exercise of the license

Examples of reciprocal licenses include: GNU licenses (GPL, AGPL, LGPL), Mozilla Public License and Eclipse Public License.

#### Copyright
License and copyright are two seperate things.  In some cases the license may grant additionnal rights to the copyright holder(s). Work done by Government of Canada employees during work hours is Copyright (c) Crown Copyright, Government of Canada.

### Benefits
Using OSS allows for product customization, advances interoperability between tools, and improves the overall quality of the final product. Other benefits include:
- **Flexible usage.** The benefits of using OSS compel GC to meet user needs by modifying existing or creating new OSS. OSS is particularly suitable for rapid prototyping and experimentation. The testing process generates minimal costs, and the process encourages the identification and elimination of defects not recognized by the original development team.
- **Community involvement.** Publicly available source code enables continuous and broad peer review. Whether simply publishing the completed code or opening the development process, the practice of expanding the review and testing process to a wider audience—beyond the development team—ensures increased software reliability and security. Developing in the open also allows for other opinions to help adjust the direction of a product to maximize its usefulness to the community it serves.
- **Cost-savings.** The ability to modify OSS enables GC to respond rapidly to changing missions and markets. Support and maintenance of open source code—as opposed to more burdensome usages of proprietary software—provides a real cost advantage where multiple copies of software are required, or when the user base grows. The total cost of ownership is shared with a community, rather than solely the Government of Canada.
- **Reusability.** The code we create belongs to the public as a part of the public domain. The code we work on was paid for by the American people, but the end-product is not the only way they should be able to interact with their government. By coding in OSS, we help populate a larger commons that cities, states, businesses, and individuals can participate in. This creates real economic value by lowering the burden of replicating similar work or by allowing the private sector to build off of and create new businesses around code developed at GC.

### Security
One of the most misunderstood aspects of the Open Source Software (OSS) development model is the security benefits it offers. OSS security relies on genuinely hardened code that is tested by a large number of reviewers in a wide variety of circumstances. Linus Torvalds simply noted, "talk is cheap, show me the code."

#### Reliance on Hardening, Not Obfuscation
Open Source Software relies on security over obscurity. A common misconception is that hiding code helps to prevent successful attacks. Open Source development practices rely on hardening (or improving the security of) code by making it available for peers to test and try to break, and then fixing the problems found.

OSS is not always more secure, however in both theory and practice the OSS security model has proven that it can more quickly respond to and correct security issues. 

Obfuscation relies on attacker ignorance and hides poor security practices. Within five months of the source code release of InterBase version 6, a hard-coded backdoor that had existed for seven years was found by the OSS community and fixed.

#### Wide Peer Review
Assuming that the goal is to make secure software, it is obvious that the easiest way to find flaws in a project is to make all of the project's code completely transparent. This approach may seem counter-intuitive, if the ultimate goal is anything other than the integrity of the technology.

By openly releasing a project's code and making it readily available via the Internet the community of peer reviewers is expanded exponentially across the globe. The community will quickly find flaws and the project team can take action to fix them. This simultaneously garners exceptionally wide and deep testing feedback from developers who need the code to be as secure as possible for their own use as well as the community's. Both the project owners and community benefit from sharing flaws and fixes.

Because the OSS security model is established on industry-accepted best practices and the actual code is widely available, projects are widely reviewed, thoroughly scrutinized, practically improved and quickly hardened.

Sound security and accessibility practices are only possible with open peer review. This is the basis of a evidence based approach to any field of study. Technology is no different and shouldn't be treated as if vendors have special access to the truth.

### Economic models
#### Market

### Using and Procuring
#### Support

### Development
OSS is how modern organizations build software. Documented advantages over software built by a handful of developers include the quality of solutions generated through the diversity of ideas and communities that form around a shared challenge. Exposing the problem space to other interested organizations also provides additional human capital to tackle challenges. For example, Linux, an open source operating system, is the largest development project in the world, with thousands of people contributing to every release. Many competing companies contribute to Linux and other OSS, allowing them to leverage the work of a global community of OSS developers and shift developers from low-value work to high-value work.

#### Contributing to projects

### Publishing code
See [Open Source Code](https://github.com/canada-ca/Open_First_Whitepaper/blob/master/4_Open_Source_Code.md).
Need to look at different licensing options. Government of Québec (https://www.forge.gouv.qc.ca/licence/fr/)


### Actions
The GC will:
- publish OSS adoption guidelines, update IM-IT strategic plan and cloud adoption stratagy to reflect direction on OSS;
- plan to eliminate current lock-in to propriatary operating system by favoring use of multiplatform or Web applications;
- select open source Web browser and office suite for use by all departments and agencies;
- require that all new purchases, upgrades or migrations activly and fairly consider OSS, starting immediately;
- factor in the use of OSS when calculating total cost of ownership (TCO) of a solutions including exit or transition costs;
- select OSS on the basis of its additional inherent flexibility, when there is no significant overall (full-lifecycle) cost diference with propriatary solutions;


### Examples
#### US
- [Digital Services Playbook](https://playbook.cio.gov/) - Contract ensures open source solutions are evaluated when technology choices are made and consider OSS solutions at every layer of the stack.
- [18F Open Source Policy](https://github.com/18F/open-source-policy/blob/master/policy.md) - Use FOSS in our projects and contribute back to the open source community.
- [DoD Open Source Software FAQ](http://dodcio.defense.gov/Open-Source-Software-FAQ/) - Educational resource for government employees and government contractors to understand the policies and legal issues relating to the use of OSS in the DoD.
- [DoD Memorandum on Guidance Regarding Open Source Software](http://dodcio.defense.gov/Portals/0/Documents/OSSFAQ/2009OSS.pdf) - There have been misconceptions and misinterpretations of the existing laws, policies and regulations that deal with software and apply to OSS, that have hampered effective DoD use and development of OSS.

#### UK
- [Technology Code of Practice](https://www.gov.uk/government/publications/technology-code-of-practice/technology-code-of-practice) - Make things open by giving equal consideration to free or open source software when you choose technology - taking account of the total cost of ownership of the service, including exit and transition costs.

#### France
- [Socle interministériel des logiciels libres](http://references.modernisation.gouv.fr/sites/default/files/SILL-2016-socle-interministeriel-logiciels-libres.pdf) - L’ensemble des logiciels libres préconisés se présente sous la forme du SILL. Dans sa version actuelle, il porte sur le poste de travail, la gestion de parc, l’exploitation de serveurs, les base de données et les environnements de développement.

#### Australia
- [Australian Government Open Source Software Policy](http://www.finance.gov.au/sites/default/files/australian-government-open-source-software-policy-2013.pdf) - Procurement processes must actively and fairly consider all types of available software. Agencies will actively participate in OSS communities and contribute back where appropriate.

