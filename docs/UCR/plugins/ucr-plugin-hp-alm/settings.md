
HP Quality Center (ALM) - Settings Documentation
================================================

# Settings




### Settings




 



### Process steps in the HP ALM Plugin plug-in


* [ALM Integration](#alm_integration)
* 
[ALMCheckAuthenticationButton](#almcheckauthenticationbutton)
* [ALMDefectSeverities](#almdefectseverities)
* 
[ALMDefectStatuses](#almdefectstatuses)
* [ALMDeleteAllChanges](#almdeleteallchanges)
* [ALMDomains](#almdomains)
* 
[ALMPingServerButton](#almpingserverbutton)
* [ALMProjects](#almprojects)
* [ALMReleases](#almreleases)
* 
[ALMReleases](#almreleases)
* [ALMReqSeverities](#almreqseverities)
* [ALMReqStatuses](#almreqstatuses)
* 
[ALMTypes](#almtypes)




### ALM Integration


Integration




*Input properties for the ALM Integration step*  | Name 
| Type | Description | Required |
| --- | --- | --- | --- |
| ALM Domain |  | Domain on ALM server | No |
| ALM Project 
|  | Project on ALM server | No |
| ALM User Login | String | User Login | No |
| ALM User Password | Password | User 
Password | No |
| ALM server URL | String | The ALM server URL | No |
| Automap Releases | Boolean | Check this box to 
automap any releases on the HP ALM serverthat exist with
the same name of a release on the UrbancodeRelease server. | No
 |
| Check Authentication |  | Button to check if the connection can be established withthe HP ALM Server | No |
| 
Configuring an Integration Provider for HP ALMusing the HP ALM Rest API |  | Run this integrationto import any 
requirements or defects from the HP ALM
server.Only the specified requirement types or defects will be
imported, and 
only items that have been modified since the lastexectuion
are imported. However, running the integration forthe first 
time can take
a long time if there are many itemsto import. | No |
| Delete All Changes |  | Button to and delete all 
existing HP ALM changes on theUrbancode Release
server. | No |
| Ping the ALM Server |  | Button to check if the 
connection can be established withthe HP ALM Server | No |
| Query Types |  | Check all requirement types or defects 
that you want toquery for. | No |


### ALMCheckAuthenticationButton


Check authentication credentials with the HP ALM 
Server


This step has no input properties.


### ALMDefectSeverities


Generate a list of defect severities that exist 
on the ALM server.


This step has no input properties.


### ALMDefectStatuses


Generate a list of defect statuses 
that exist on the ALM server.


This step has no input properties.


### ALMDeleteAllChanges


Delete all existing HP 
ALM changes on the UCR server.


This step has no input properties.


### ALMDomains


Generate a list of domains on the
 ALM server.


This step has no input properties.


### ALMPingServerButton


Ping the ALM Server


This step has no 
input properties.


### ALMProjects


Generate a list of projects on the ALM server.


This step has no input 
properties.


### ALMReleases


Generate a list of releases in a given Domain and Project on an ALM server.


This step 
has no input properties.


### ALMReleases


Generate a list of releases in a given Domain and Project on an ALM server.



This step has no input properties.


### ALMReqSeverities


Generate a list of requirement severities that exist on 
the ALM server.


This step has no input properties.


### ALMReqStatuses


Generate a list of requirement statuses that
 exist on the ALM server.


This step has no input properties.


### ALMTypes


Generate a list of all requirement types
 and/or defects on the HP ALM server.


This step has no input properties.





|Back to ...|||
| :---: | :---: | :---: |
|[**List of Plugins**](../../index.md)|[Overview](./overview.md)|[Downloads](./downloads.md)|
