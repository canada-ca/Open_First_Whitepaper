[« Previous Page : Open Standards](2_Open_Standards.md) | [Table of Content](TOC.md) | [Next Page: Open Source Code »](4_Open_Source_Code.md)

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
- [Actions](#actions)
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

Even amongst the licences that the FSF and OSI approve as sharing the basic characteristics of OSS, the various terms and obligations vary greatly. However, there are several categories of clauses commonly encountered:
- General disclaimers of warranty and/or liability;
- Notice obligations, which generally require you to notify downstream users of the particular FOSS licence that applies to the work;
- Source code obligations, which generally require you to provide the source code of the software when you distribute it; and
- Hereditary licensing obligations, which generally require you to only release any modifications or improvements as FOSS, under the same licence.

The first two types of clauses - disclaimers and notice obligations – are present in nearly every OSS licence. In fact, the short and popular 2-Clause BSD License contains little more than these two bare obligations. Other more expansive licences, such as the GNU General Public License (GPL), contain clauses setting out all four of these obligations.

##### Disclaimers
Most FOSS licences include a disclaimer of warranty that aims to be as exhaustive as possible in ensuring that no warranty applies. For example, the following clause in the Mozilla Public License Version 2 (MPLv2) demonstrates a typical incarnation of this licence term:
>  Covered Software is provided under this License on an “as is” basis, without warranty of any kind, either expressed, implied, or statutory, including, without limitation, warranties that the Covered Software is free of defects, merchantable, fit for a particular purpose or non-infringing. The entire risk as to the quality and performance of the Covered Software is with You. Should any Covered Software prove defective in any respect, You (not any Contributor) assume the cost of any necessary servicing, repair, or correction. This disclaimer of warranty constitutes an essential part of this License. No use of any Covered Software is authorized under this License except under this disclaimer.

As shown, in addition to setting out that the licence is “without warranty of any kind”, these clauses are most often careful to exclude any warranty of “merchantability” or “fitness for a particular purpose”. This serves to clarify and make certain that these two warranties do not apply, as some legislation might otherwise impose them as implicit terms of a contract or licence. For example, where software is sold in Ontario, the Sale of Goods Act imposes implied warranties relating to merchantability and, in some cases, warranties of fitness for a particular purpose (source?). However, with the explicit exclusions in typical FOSS licences, these warranties do not apply.

Many licences also explicitly disclaim warranties of non-infringement (for example, the MPLv2, as set out above). This disclaimer aims to exclude the U.S. doctrine of an implied warranty of non infringement, which otherwise warrants that the software does not infringe any third party's copyright. For example, if a software developer uploaded a piece of code to a FOSS project and it originally came from copyright-protected restricted-source software, anyone downloading or using the FOSS application would technically infringe the copyright. If sued for such an infringement, the warranty of non infringement would result in such a user having no recourse against the distributors or developers – it is “users beware”. In Canada, even though a specific doctrine of a warranty of non-infringement does not exist, this licence clause still likely disclaims similar warranties of title (especially when considered in conjunction with a broad disclaimer against warranties of “any kind”). As well as disclaiming warranties, nearly all FOSS licences disclaim liability. For example, the MPLv2 states:
>  Under no circumstances and under no legal theory, whether tort (including negligence), contract, or otherwise, shall any Contributor, or anyone who distributes Covered Software as permitted above, be liable to You for any direct, indirect, special, incidental, or consequential damages of any character including, without limitation, damages for lost profits, loss of goodwill, work stoppage, computer failure or malfunction, or any and all other commercial damages or losses, even if such party shall have been informed of the possibility of such damages. This limitation of liability shall not apply to liability for death or personal injury resulting from such party’s negligence to the extent applicable law prohibits such limitation. Some jurisdictions do not allow the exclusion or limitation of incidental or consequential damages, so this exclusion and limitation may not apply to You.

Again, this disclaimer broadly aims to cover all bases of liability and all types of damages that could occur. The result is that when you use FOSS, you do so at your own risk. The only exceptions are perhaps circumstances where notice of the disclaimer is not sufficiently brought to the user’s attention, or the clause is unconscionable, in light of a particularly high-risk context.

Although these disclaimers are standard in nearly all FOSS licences, licensors can modify them. In some cases, a FOSS licence allows the licensor to set out additional disclaimers. For example, the MPLv2 allows a licensor to “include additional disclaimers of warranty and limitations of liability specific to any jurisdiction.” 12 In other cases, a licensor may do the opposite and choose to offer a warranty or accept liability, removing the effect of the disclaimer of warranty. For instance, the MPLv2 provides that “You may choose to offer and to charge a fee for warranty, support, indemnity or liability obligations to one or more recipients of Covered Software”.

##### Notice Obligations
Like disclaimers, a notice obligation clause comes standard in nearly every FOSS licence. This is an obligation to reproduce the licence text (either directly or through a hyperlink) whenever you reproduce the licenced work. In addition, notice obligations usually require distributions of the work to retain other notices that come with it – for example, copyright assertions, additional disclaimers of warranty or liability, or patent notices. Notice obligations usually at least apply to distribution of the source code, but, depending on the licence, often apply to redistribution of the object code as well. As one example of a typical notice obligation, the MPLv2 licence provides:
>  You may not remove or alter the substance of any license notices (including copyright notices, patent notices, disclaimers of warranty, or limitations of liability) contained within the Source Code Form of the Covered Software, except that You may alter any license notices to the extent required to remedy known factual inaccuracies.

##### Reciprocal Licensing
There is one distinctive and commonly-encountered feature of OSS that tends to divide licences into two categories: those with a reciprocal obligation (also called “copyleft”, “share-alike”, or
“hereditary”) and those without. Licences in the reciprocal category stipulate that modifications to the software must also come under the same licence. Therefore, if a person makes a change to reciprocal software or includes some reciprocal-licensed code in his or her own software, that person cannot distribute the new work as restricted-source software: he or she must only redistribute the new code under the same OSS licence. The GPL, which is the most popular copyleft licence, sets out the rationale for this stipulation as follows:
>  To protect your rights, we need to prevent others from denying you these rights or asking you to surrender the rights. Therefore, you have certain responsibilities if you distribute copies of the software, or if you modify it: responsibilities to respect the freedom of others.
>  For example, if you distribute copies of such a program, whether gratis or for a fee, you must pass on to the recipients the same freedoms that you received. You must make sure that they, too, receive or can get the source code.

Only some FOSS licences contain this stipulation: other popular licences such as the MIT, BSD and Apache licences do not. Licences without this stipulation are generally referred to as permissive. In these cases, the author of any modifications is under no obligation to place his or her changes under the same licence, or even under a FOSS licence at all. In general, the author of the modifications can even use and redistribute the modified software as a restricted-source software application. The two different types of FOSS licences are illustrated in the figure below.

(Image?)

However, blurring the distinction between these types of licences, different reciprocal licences stipulate varying degrees of when this reciprocal obligation to distribute under the same licence engages. This is perhaps the most confusing aspect of OSS licences and deserves careful attention. To determine whether a certain activity implicates a reciprocal obligation, one must consider (1) the type of distribution and (2) the extent of integration with the original code.

With respect to the type of distribution, reciprocal obligations only arise upon certain “distribution”-like activities. Where there is no such distribution, the licences almost always allow a person to use and modify reciprocal-licensed software without ever releasing their code. For example, a company can change and customize software under a hereditary licence for in-house use, and it does not need to share this software or the software source code. However, a “distribution” does trigger a hereditary obligation to distribute under the original licence. There are two common types of triggers found in OSS licences:
- **Distribution of Source or Object Code**: Distribution of the software, either through the internet or on a physical medium such as a CD, whether as source code or object code, is the most common trigger for a hereditary obligation. For example, this is the trigger set out in the popular GPL licence.
- **Access over a computer network**: Found in the Affero GPL license, access over a computer network is a much broader trigger that imposes a hereditary obligation whenever others access the licenced software over a computer network. This trigger aims to capture web service businesses that run their platforms on FOSS – these businesses must make their source code available to others.

Even if the software is distributed, the reciprocal obligations still only extend to certain modifications (depending on the licence):
- **Derivative works**: As set out in the GPL, this type of hereditary clause stipulates that the obligation applies to all “derivative works” (the U.S. analog of an “adaptation” under Canadian copyright law, likely with similar scope). The exact boundary of what constitutes a “derivative work” is hotly debated; however, it is clear that a mere “collection” of works does not trigger hereditary obligations.
- **Collections** is where multiple software programs are distributed together (such as on the same CD-ROM), but where the programs do not tightly interact.
- **Derivative works w/a linking allowance**: The most prominent example of this type of clause is that found in the GNU Lessor General Public License (LGPL). This licence is similar to the GPL, but it explicitly allows a person to statically or dynamically link their code to a LGPL software library, without triggering the hereditary obligation (in software development, “linking” involves a loose coupling where one piece of the software communicates with other software and makes use of its functionality).
- **Modified files only**: Unique to the Mozilla Public License (MPL), this type of clause only imposes hereditary obligations on modified files. If a derivative work contains files which are modified versions form the original work, as well as entirely new files, only the directly-modified original files implicate and fall under the hereditary obligation.

The differences amongst the various licences in the popular GNU suite illustrate how the type of distribution and extent of integration interact to determine when a hereditary obligation engages, as shown in the following table.

(table?)

##### Source Code Obligations
Reciprocal licences usually include a “source code obligation” that requires anyone distributing the work to include, or at least link to, the source code. This ensures that the software remains in a format that downstream users can continue to modify. Without such a requirement, someone could make changes to software under a reciprocal licence, but only redistribute the object code. This would make it impossible for others to make further changes or re-integrate any of the changes back into the original project.

Although a source code obligation usually goes hand-in-hand with a reciprocal licence, it is worth noting that, in some cases, it may only attach to the originally-licensed code. This becomes particularly important when using software libraries. For example, restricted-sourced software vendors can link-to and make use of FOSS libraries that fall under a Lesser GNU Public License. As long as the restricted-source software merely links to these libraries, the reciprocal obligation does not engage. The vendor has no obligation to release its own source code. However, the source code obligation still applies to the libraries themselves. The vendor has an obligation to redistribute or otherwise provide the original library source code along with the restricted-source product.

In some cases, it is not feasible for a person to directly provide the source code along with the object code. If distributing software on a CD or DVD, space constraints may make it difficult to include both – especially considering the fact that source code can be much larger than object code. For this reason, licences are usually flexible about the manner in which you must provide the source code. For instance, the GPLv3 allows a person to provide, in lieu of the source code itself, a written offer to distribute the source code on a separate CD or through a network server. If distributing the object code over the internet, a person may also simply provide instructions on how to download the source code from another internet-connected server.


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
