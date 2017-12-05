[« Previous Page : Definitions](8_Definitions.md) | [Table of Content](TOC.md)

## Open Platforms

It is recognized that different departments and organizations across the GC need specialized development tools and platforms, however, there are many common lines of business across the GC that would benefit from the sharing of tools and information. As such, it is of value, to develop an inventory of open source tools that are being used with the GC, and have been approved through the GC Enterprise Architecture Review Board (EARB). Having these preferred tools in place will reduce redundant development and foster an open community where best practices can be shared, co-development can be done, and tools and information can be efficiently re-used. 

This list will be regularly updated to ensure the most up-to-date list of tools are being offered to the community.
Below you will find a list of recommended platforms by domain, based on standards co-developed by the community, with best of breed tools assessed against this criteria.

More information about how these assessments are being done in the open can be found on our [Assessment Approach page](https://github.com/canada-ca/Open_First_Whitepaper/blob/master/Assessments/Assessment%20Approach.md).

If you are interested in a particular assessment, see [Assessment folder](https://github.com/canada-ca/Open_First_Whitepaper/tree/master/Assessments) for all completed Assessments against tools.

If you would like to submit a tool for assessment, please add a through a pull request using the [template](https://github.com/canada-ca/Open_First_Whitepaper/blob/master/Assessments/Template.md).

### Web Development

The GC vision to take an "open first" approach to web development using open source tools and create an open culture that co-develops, re-uses and shares requires the development of standards for web development.
Below is a set of criteria by which standards and tools should be judged for the following categories of web development (particularly for primary functions for business critical applications):

**General Guidelines (applicable to all)**

- Growing or consistent community support
- Optional enterprise support options

**Content Management Systems**

**Web Development Technical Stack**

***Database***

- Wide variety of OS compatible server operating systems
- Has been active for strictly greater than a decade
- Support of SQL

According to solid IT (https://db-engines.com/en/ranking) the top ten databases are as follows ...

1.  Oracle
2.  MySQL
3.  Microsoft SQL Server
4.  PostgreSQL
5.  MongoDB
6.  DB2
7.  Microsoft Access
8.  Redis
9.  Cassandra
10. Elasticsearch

Firstly, we will eliminate those options which do not adhere to an OS model. The eliminates Oracle, Microsoft SQL Server, DB2, and Microsoft Access.
Using our criteria of a growing or consistence popularity we can eliminate the following MySQL, and Cassandra.
Given that we are searching for defaults and standards most business critical applications should use commonly known standards which have withstood the test of time - RDB SQL databases. Applying this rule, we can eliminate Elasticsearch, Redis and MongoDB.
The last remaining database remaining, then, becomes PostgreSQL which also have optional enterprise support in the form of EnterpriseDB.

## Web Server

- Viability with up and coming technologies (specifically containerization)

### Java

#### Servlet Containers

Despite servlet containers falling out of favour for application servers Tomcat, a long standing project, still maintains an active community and is regularly updated. In the current environment there seems to be no notable competitor for servlet containers next to Tomcat. As such, this should be the default servlet container for basic Java development.

#### Application Servers

The following options have had releases since 2016 accompanied by relevant statistics from github (as of 12-03-2017)...

Payara (based on GlassFish)

- 37 releases
- 10,499 commits
- 35 branches
- 43 contributors

GlassFish

- 29 releases
- 35,461 commits
- 2 branches
- 82 contributors

TomEE (based on Tomcat)

- 24 releases
- 10,622 commits
- 18 contributors
- 36 branches

Apache Geronimo

- 4,560 commits
- 35 releases
- 6 contributors
- 36 branches

Wildfly (previously JBoss)

- 24,309 commits
- 78 releases
- 290 contributors
- 10 branches

WebLogic Server

ColdFusion

Of these options neither ColdFusion nor WebLogic Server are OS solutions.

Looking to the future of web development environments are shifting towards containerized solutions. As such, it is important to take into account the likely future technological ecosystem. Limiting our list to projects with a longer life span and a more popular community we will further analyze the viability of Tomee, GlassFish, Payara, and Wildfly. By looking at each projects popularity on [Docker Hub](https://hub.docker.com/) we can paint a more accurate picture of each projects viability moving forward.

GlassFish

- 100 stars
- 500K+ pulls

Payara

- 29 stars
- 100K+ pulls

Wildfly

- 358 stars
- 1M+ pulls

TomcatEE

- 43 stars
- 1M+ pulls

Using these metrics Wildfly is the most popular containerized solution, however, Tomcat (the base project of Tomee) far surpasses all other options:

Tomcat

- 1.6k stars
- 10M+ pulls

Taking the above into consideration the conclusion is that Wildfly is a viable option if an application server with built in JEE compliance is required. However, Tomcat is the preferred solution as it is a lightweight, long-standing community standard, and remains the favoured choice for containerized solutions which are becoming a vital aspect of web development.

**Data Distribution**

**Visualizations**

Below, you will find the development stack used by the Public Service Commission of Canada for its new development initiatives since 2017.

### Pubic Service Commission Development Stack

*Approved for use in 2017*

**Programming language and framework**

- Java SE 9
- Java EE 8
- Spring Framework 5 (Spring Boot, Spring MVC and Thymeleaf, and Hibernate (JPA))

**Source repository**

- GitHub

**Testing (unit/functional testing)**

- JUnit
- Selenium

**Database**

- PostgreSQL 10.0

**Application server / servlet container**

- Tomcat 9

**Web server**

- Apache HTTP Server 2.4

**Build / Automation / integration**

- Maven
- Flyway
- Jenkins
- Nexus Repository Manager

**OS**

- Red Hat Enterprise Linux 7

**Container**

- Docker
