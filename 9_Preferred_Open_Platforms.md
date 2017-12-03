[« Previous Page : Definitions](8_Definitions.md) | [Table of Content](TOC.md)

## Open Platforms
It is recognized that different departments and organizations across the GC need specialized development tools and platforms, however, there are many common lines of business across the GC that would benefit from the sharing of tools and information. As such, it is of value, to develop an inventory of open source tools that are being used with the GC, and have been approved through the GC Enterprise Architecture Review Board (EARB). Having these preferred tools in place will reduce redundant development and foster an open community where best practices can be shared, co-development can be done, and tools and information can be effeciently re-used. 

This list will be regularly updated to ensure the most up-to-date list of tools are being offered to the community.
Below you will find a list of recommended platforms by domain, based on standards co-developed by the community, with best of breed tools assessed against this criteria. 

More information about how these assessments are being done in the open can be found on our [Assessment Approach page](https://github.com/canada-ca/Open_First_Whitepaper/blob/master/Assessments/Assessment%20Approach.md). 

If you are interested in a particular assessment, see [Assessment folder](https://github.com/canada-ca/Open_First_Whitepaper/tree/master/Assessments) for all completed Assessments against tools. 

If you would like to submit a tool for assessment, please add a through a pull request using the [template](https://github.com/canada-ca/Open_First_Whitepaper/blob/master/Assessments/Template.md). 

### Web Development

The GC vision to take an "open first" approach to web development using open source tools and create an open culture that co-develops, re-uses and shares requires the development of standards for web development. 
Below is a set of criteria by which standards and tools should be judged for the following categories of web development (particularly for primary functions for business critical applications):

**General Guidelnes (applicable to all)**
- Growing or consistent community support 
- Optional enterprise support options 

**Conetent Management Systems**


**Web Development Technical Stack**

***Database*** 
- Wide variety of OS capatible server operating systems 
- Has been active for strictly greater than a decade 
- Support of SQL

According to solid IT (https://db-engines.com/en/ranking) the top ten databases are as follows ... 

1.  Oracle X
2.  MySQL X
3.  Microsoft SQL Server X
4.  PostgreSQL
5.  MongoDB X
6.  DB2 X
7.  Microsoft Access X
8.  Redis X
9.  Cassandra X
10. ElasticsearchX 

Firstly, we will eliminate those options which do not adhere to an OS model. The eliminates Oracle, Microsoft SQL Server, DB2, and Microsoft Access.
Using our criteria of a growing or consistence popularity we can eliminate the following MySQL, and Cassandra. 
Given that we are searching for defaults and standards most business critical applications should use commonly known standards which have withstood the test of time - RDB SQL databases. Applying this rule, we can eliminate Elasticsearch, Redis and MongoDB.
The last remaining database remaining, then, becomes PostgreSQL which also have optional enterprise support in the form of EnterpriseDB.

***Web Server*** 

****Java****

****Standard****

****JavaEE****

**Data Distribution**

**Visualizations**

Below, you will find the development stack used by the Public Service Commission of Canada for its new development initiatives since 2017.

### Pubic Service Commision Development Stack
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
