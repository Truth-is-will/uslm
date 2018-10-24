>In the coming weeks, GPO is planning to release Beta USLM XML in the draft 2.0 schema on the govinfo Bulk Data Repository for enrolled bills from the 113th Congress forward, public laws from the 113th Congress forward, and the Statutes at Large from the 108th Congress forward. For enrolled bills, the Beta USLM XML will be made available in addition to the existing Bill DTD XML. The Beta USLM XML will use the same file naming convention as the Bill DTD XML but the Beta USLM XML will be in a /bulkdata/BILLS/uslm/ folder. We are also planning to make the Beta USLM XML available on the govinfo website through "USLM" buttons and in the ZIP files. Beta USLM XML will be added to the govinfo API and Link Service in an upcoming release. See the [proposed branch](https://github.com/usgpo/uslm/tree/proposed)  for more information. 

>In December 2018, the FDsys website including the FDsys Bulk Data Repository, FDsys Sitemaps, and the FDsys Link Service will be retired. Please migrate tools and processes to [govinfo](https://www.govinfo.gov/developers).


# USLM Schema #


In support of the United States Legislative Branch XML Working Group and in accordance with [2 U.S.C. 181](https://api.fdsys.gov/link?collection=uscode&title=2&year=mostrecent&section=181), the Government Publishing Office (GPO) is making the United States Legislative Markup (USLM) XML schema available as an authoritative source on GitHub. 



## Versions ##
The current version of the schema is in the master branch. If there are any proposed changes to the schema, the changes will be in a proposed branch. A major.minor.point structure is used to identify the version, and the version is recorded as an attribute at the root level. The point number is incremented to indicate a non-breaking change while the minor number is incremented to indicate a breaking change. Breaking changes will only be implemented after all other options have been exhausted. Please refer to [CHANGELOG.md](CHANGELOG.md) for a summary of proposed and approved changes.  


## Draft USLM 2.0 Schema ##
The [proposed branch](https://github.com/usgpo/uslm/tree/proposed) contains the [draft USLM 2.0 schema](https://github.com/usgpo/uslm/blob/proposed/uslm-2.0.0.xsd), a [schema review guide](https://github.com/usgpo/uslm/blob/proposed/USLM-2_0-Review-Guide.md), sample USLM enrolled bill files, CSS files, and additional schema required to validate the sample files. Additional sample files for public laws, the Statutes at Large, the Federal Register, and the Code of Federal Regulations will be added in the coming weeks. 


To submit feedback, questions, or comments, please open a [GitHub issue](https://github.com/usgpo/uslm/issues/new).


## User Guide and Review Guide ##
Please refer to the User Guide in [PDF](USLM-User-Guide.pdf) or [Markdown](USLM-User-Guide.md) and Review Guide in [PDF](https://github.com/usgpo/uslm/blob/proposed/USLM-2_0-Review-Guide.pdf) or [Markdown](https://github.com/usgpo/uslm/blob/proposed/USLM-2_0-Review-Guide.md) for additional information about the schema. 
