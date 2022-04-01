
NUnit - Steps Documentation
===========================

# Steps




### Steps




 



### Process steps in the NUnit plug-in


* [NUnit Report](#nunit_report)




### NUnit Report



Publish NUnit test results for reporting and trending.




*Input properties for the  

NUnit Report step*  | Name | 
Type | Description | Required |
| --- | --- | --- | --- |
| Exclude Patterns | String | Patterns for excluded files from
 the report, one per line. Files matching these
patterns are unconditionally excluded from the report. Patterns can 
include ?, *,
or **. | No |
| Include Patterns | String | Patterns for including NUnit XML in the report, one per line. 
Patterns can include
?, *, or **. | Yes |
| Report Name | String | The name for the published report | No |
| Source 
Directory | String | A offset location of where the NUnit XML files are located. | Yes |





|Back to ...|||
| :---: | :---: | :---: |
|[**List of Plugins**](../../index.md)|[Overview](./overview.md)|[Downloads](./downloads.md)|
