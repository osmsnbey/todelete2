
Welcome to UrbanCode Release Plugins
====================================

Contents
========

* [List of all Plugins](#list-of-all-plugins)
	* [Deployment Reports](#deployment-reports)
	* [Rational Team Concert v6](#rational-team-concert-v6)
	* [Rally](#rally)
	* [jenkins-ucr-plugin](#jenkins-ucr-plugin)
	* [reporting-ucd-plugin](#reporting-ucd-plugin)
	* [sync-ucd-plugin](#sync-ucd-plugin)
	* [sync-ucr-plugin](#sync-ucr-plugin)
	* [Jenkins for IBM UrbanCode Release](#jenkins-for-ibm-urbancode-release)
	* [Ansible Tower](#ansible-tower)
	* [ucr-plugin-deploy](#ucr-plugin-deploy)
	* [HP Quality Center (ALM)](#hp-quality-center-alm)
	* [ucr-plugin-jenkins](#ucr-plugin-jenkins)
	* [Jira for IBM UrbanCode Release](#jira-for-ibm-urbancode-release)
	* [CA Nolio](#ca-nolio)
	* [ucr-plugin-servicenow](#ucr-plugin-servicenow)
	* [Slack for IBM UrbanCode Release](#slack-for-ibm-urbancode-release)
	* [Microsoft Team Foundation Server (TFS)](#microsoft-team-foundation-server-tfs)
	* [ucr-plugin-uccloud](#ucr-plugin-uccloud)
	* [XL Deploy](#xl-deploy)
	* [IBM UrbanCode Deploy](#ibm-urbancode-deploy)
	* [ServiceNow](#servicenow)

# List of all Plugins

## Deployment Reports



The IBM UrbanCode Release Deployment Reports plugin provides an example of using the UCR plugin framework and Java REST
 API client introduced in UCR 6.1.1.0 to generate email based reports. Two example report formats are included, which 
are rendered using data extracted from UCR via the REST API and rendered into HTML content via the Apache Velocity 
template engine. The reports are delivered using the same email notification configuration used by the main UCR product 
into which the plugin is deployed.


To assist with demonstrating the plugin’s capabilities, two additional functions 
are provided to generate a sample data set and to remove the generated data.




|Latest Version|||||
| :---: | :---: | :---: | :---: | :---: |
|[**7.1018228**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/DeployReport/ucr-plugin-deployment-reports-7.1018228.zip)|[Overview](plugins/DeployReport/overview.md)|[Usage](plugins/DeployReport/usage.md)|[Settings](plugins/DeployReport/settings.md)|[Downloads](plugins/DeployReport/downloads.md)|


---
## Rational Team Concert v6



IBM Rational Team Concert integrates task tracking, source control, and agile planning with continuous builds and a 
configurable process to adapt to the way you work.


Compatibility:


* This plug-in works with Rational Team Concert 
6.0 and later.
* For IBM UrbanCode Release 6.1 and earlier, the Rational Team Concert integration is built into the 
server. There is no need to install this plug-in. For more information on the built-in integration, see [the product 
help](http://www.ibm.com/support/knowledgecenter/SS4GCC_6.1.2/com.ibm.urelease.doc/topics/rtcintegrat_cpt.html).




|Latest Version|||||
| :---: | :---: | :---: | :---: | :---: |
|[**3.969559**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/RTC/ucr-plugin-rtc-3.969559.zip)|[Overview](plugins/RTC/overview.md)|[Usage](plugins/RTC/usage.md)|[Settings](plugins/RTC/settings.md)|[Downloads](plugins/RTC/downloads.md)|


---
## Rally



Rally is an Agile project management tool for planning, scheduling, and tracking iterations and releases.




|Latest Version|||||
| :---: | :---: | :---: | :---: | :---: |
|[**2.690437**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/Rally/ucr-plugin-rally-2.690437.zip)|[Overview](plugins/Rally/overview.md)|[Usage](plugins/Rally/usage.md)|[Settings](plugins/Rally/settings.md)|[Downloads](plugins/Rally/downloads.md)|


---
## jenkins-ucr-plugin

|Latest Version||
| :---: | :---: |
|[**1.919098**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/jenkins-ucr-plugin/ibm-ucrelease-pipeline-1.919098.hpi)|[Downloads](plugins/jenkins-ucr-plugin/downloads.md)|


---
## reporting-ucd-plugin

|Latest Version||
| :---: | :---: |
|[**10.907592**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/reporting-ucd-plugin/reporting-ucd-plugin-10.907592.zip)|[Downloads](plugins/reporting-ucd-plugin/downloads.md)|


---
## sync-ucd-plugin

|Latest Version||
| :---: | :---: |
|[**4.869522**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/sync-ucd-plugin/sync-ucd-plugin-4.869522.zip)|[Downloads](plugins/sync-ucd-plugin/downloads.md)|


---
## sync-ucr-plugin

|Latest Version||
| :---: | :---: |
|[**9.956642**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/sync-ucr-plugin/sync-ucr-plugin-9.956642.zip)|[Downloads](plugins/sync-ucr-plugin/downloads.md)|


---
## Jenkins for IBM UrbanCode Release


Jenkins is a continuous integration server that utilizes a plug-in model to support interactions with other DevOps 
products. Jenkins jobs can be synchronized using the Jenkins plug-in for IBM UrbanCode Release with the UrbanCode 
Release server allowing Jenkin jobs to be ran as part of a release plan.
|Latest Version|||||
| :---: | :---: | :---: | :---: | :---: |
|[**2.1124702**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/ucr-jenkins-ci/plugins-ucr-jenkins-ci-2.1124702.zip)|[Overview](plugins/ucr-jenkins-ci/overview.md)|[Usage](plugins/ucr-jenkins-ci/usage.md)|[Steps](plugins/ucr-jenkins-ci/steps.md)|[Downloads](plugins/ucr-jenkins-ci/downloads.md)|


---
## Ansible Tower



The Red Hat© Ansible© Tower centralize and control your IT infrastructure with a visual dashboard, role-based access 
control, job scheduling, integrated notifications and graphical inventory management.


The Ansible Tower plug-in 
provides for the integration of UrbanCode Release with an Ansible Tower server. The plug-in imports templates and 
workflows from Ansible Tower as plugin tasks to be executed in UrbanCode Release.


This plug-in requires IBM UrbanCode 
Release version 6.2.5.1 or later.



|Latest Version|||||
| :---: | :---: | :---: | :---: | :---: |
|[**2.1106038**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/ucr-plugin-ansible/ucr-plugin-ansible-tower-2.1106038.zip)|[Overview](plugins/ucr-plugin-ansible/overview.md)|[Usage](plugins/ucr-plugin-ansible/usage.md)|[Steps](plugins/ucr-plugin-ansible/steps.md)|[Downloads](plugins/ucr-plugin-ansible/downloads.md)|


---
## ucr-plugin-deploy

|Latest Version||
| :---: | :---: |
|[**1.1053195**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/ucr-plugin-deploy/ucr-plugin-deploy-1.1053195.zip)|[Downloads](plugins/ucr-plugin-deploy/downloads.md)|


---
## HP Quality Center (ALM)



The HP ALM plugin for UrbanCode Release provides visibility into project entities, such as defects and requirements, 
from the impact analysis view of UrbanCode Release.




|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**5.942932**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/ucr-plugin-hp-alm/HP-ALM-5.942932.zip)|[Overview](plugins/ucr-plugin-hp-alm/overview.md)|[Settings](plugins/ucr-plugin-hp-alm/settings.md)|[Downloads](plugins/ucr-plugin-hp-alm/downloads.md)|


---
## ucr-plugin-jenkins

|Latest Version||
| :---: | :---: |
|[**1.1078299**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/ucr-plugin-jenkins/ucr-plugin-jenkins-1.1078299.zip)|[Downloads](plugins/ucr-plugin-jenkins/downloads.md)|


---
## Jira for IBM UrbanCode Release



Jira is an issue tracking tool. You can use the tool to capture and organize issues, assign work, and track activities.
 Issues can be anything from development tasks, code errors, project tasks, help-desk tickets, or human resource request
 forms. The JIRA product is developed by Atlassian.


The Jira plug-in provides integration with Jira. You can map Jira 
projects to IBM UrbanCode Release applications. All issues in a mapped project are represented by change items in IBM 
UrbanCode Release. The integration is not bi-directional; you cannot export from IBM UrbanCode Release to Jira.



**Platform Support:**


* This plug-in is supported for use with JIRA version 5 and later.
* The built-in Jira 
integration for the IBM Urban Code Release server is deprecated. Install this plugin for Jira integration.




|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**18.1079383**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/ucr-plugin-jira/ucr-plugin-jira-18.1079383.zip)|[Overview](plugins/ucr-plugin-jira/overview.md)|[Settings](plugins/ucr-plugin-jira/settings.md)|[Downloads](plugins/ucr-plugin-jira/downloads.md)|


---
## CA Nolio



The CA Nolio plug-in provides for the integration of UrbanCode Release with CA Release Automation Server. The plugin 
supports sync of Applications, Environments, Application Processes, Snapshots (Deployment Plan), and Inventories. It 
also handles the execution of generic processes. Both full and delta synchronization is supported.



|Latest Version|||
| :---: | :---: | :---: |
|[**4.1036957**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/ucr-plugin-nolio/ucr-plugin-nolio-4.1036957.zip)|[Overview](plugins/ucr-plugin-nolio/overview.md)|[Downloads](plugins/ucr-plugin-nolio/downloads.md)|


---
## ucr-plugin-servicenow

|Latest Version||
| :---: | :---: |
|[**7.1007909**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/ucr-plugin-servicenow/ucr-plugin-servicenow-7.1007909.zip)|[Downloads](plugins/ucr-plugin-servicenow/downloads.md)|


---
## Slack for IBM UrbanCode Release


Slack is a team collaboration tool. This plug-in sends notifications to Slack in a specified channel.
|Latest Version|||||
| :---: | :---: | :---: | :---: | :---: |
|[**3.1105509**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/ucr-plugin-slack/ucr-plugin-slack-3.1105509.zip)|[Overview](plugins/ucr-plugin-slack/overview.md)|[Usage](plugins/ucr-plugin-slack/usage.md)|[Steps](plugins/ucr-plugin-slack/steps.md)|[Downloads](plugins/ucr-plugin-slack/downloads.md)|


---
## Microsoft Team Foundation Server (TFS)



The Microsoft TFS plugin for UrbanCode Release provides visibility into work items from the impact analysis view of 
UrbanCode Release. Visual Studio Team Services (formerly VSO) is also supported.




|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**5.95354**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/ucr-plugin-tfs/ucr-plugin-tfs-5.953540.zip)|[Overview](plugins/ucr-plugin-tfs/overview.md)|[Settings](plugins/ucr-plugin-tfs/settings.md)|[Downloads](plugins/ucr-plugin-tfs/downloads.md)|


---
## ucr-plugin-uccloud

|Latest Version||
| :---: | :---: |
|[**1.767382**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/ucr-plugin-uccloud/ucr-plugin-mobile-1.767382.zip)|[Downloads](plugins/ucr-plugin-uccloud/downloads.md)|


---
## XL Deploy



The XL Deploy plug-in provides for integration of UrbanCode Release with an XebiaLabs XL Deploy server. The plug-in 
imports applications, environments, deployment packages, and deployment tasks from XL Deploy as objects in UrbanCode 
Release. Both full and delta synchronization are supported.


If you have issues or questions about the plug-in, 
complete one of these actions: 


* Enter search terms in the **Search** field on the Answers page: [dW Answers: 
urbancode | release | plugins | xl 
deploy](https://developer.ibm.com/answers/search.html?f=&type=question&redirect=search%2Fsearch&sort=relevance&q=urbancode+%7C+release+%7C+plugins+%7C+xl+deploy).
 **Note** The Open Link in New Tab function can interfere with the search terms in the link.
* If no search results are 
found, submit your question on the [answers page](https://developer.ibm.com/answers/smart-spaces/23/urbancode.html). 
Categorize your question with the following tags so that the most qualified people see and answer your inquiry: 
urbancode, release, plugins, and xl deploy.



Available Steps
---------------


ExecuteTaskRun an automated task.



IntegrationIntegrate with the XL Deploy server.





|Latest Version|||||
| :---: | :---: | :---: | :---: | :---: |
|[**6.1039808**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCR/ucr-xl-deploy/plugins-ucr-xl-deploy-6.1039808.zip)|[Overview](plugins/ucr-xl-deploy/overview.md)|[Usage](plugins/ucr-xl-deploy/usage.md)|[Steps](plugins/ucr-xl-deploy/steps.md)|[Downloads](plugins/ucr-xl-deploy/downloads.md)|


---
## IBM UrbanCode Deploy



The IBM UrbanCode Deploy plug-in provides a full integration between IBM UrbanCode Release and IBM UrbanCode Deploy. It
 replaces the built-in integration for versions 6.1.1.5 and later of IBM UrbanCode Release. The plug-in also improves 
performance for the first full synchronization and for delta updates on subsequent synchronizations. 


A full 
synchronization is needed at first to import all objects from IBM UrbanCode Deploy. All synchronization after that 
imports objects that change and typically does not take more than a few seconds.


The plug-in imports applications, 
components, component versions, snapshots, environments, deployment processes from IBM UrbanCode Deploy for release 
management purposes and allow the execution of UrbanCode Deploy deployment processes from IBM UrbanCode Release 
scheduled deployments.


The plug-in is compatible with IBM UrbanCode Release version 6.1.1.5 and later. It requires IBM
 UrbanCode Deploy version 6.1.1.4 and later.




|Latest Version|||||
| :---: | :---: | :---: | :---: | :---: |
|[**0.0**]()|[Overview](plugins//overview.md)|[Usage](plugins//usage.md)|[Settings](plugins//settings.md)|[Downloads](plugins//downloads.md)|


---
## ServiceNow


The ServiceNow plug-in allows UrbanCode Release to perform create, read, update and delete operations on ServiceNow 
records. This plug-in also evaluates SNOW approvals and resolve UrbanCode Release Deployments phase approvals. 
|Latest Version|||||
| :---: | :---: | :---: | :---: | :---: |
|[**0.0**]()|[Overview](plugins//overview.md)|[Usage](plugins//usage.md)|[Steps](plugins//steps.md)|[Downloads](plugins//downloads.md)|


---