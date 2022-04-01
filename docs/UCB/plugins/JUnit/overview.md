
JUnit for IBM UrbanCode Build - Overview Documentation
======================================================

# Overview




### Overview




 


JUnit is a unit testing framework for the Java programming language.


The JUnit plug-in is used 
to publish results from a JUnit test into a report as part of the build process. This plug-in includes the following 
step:


* [JUnit Report](#junit_report)



### Step palette


To access this plug-in in the palette, click **Quality** >
 **Testing** > **JUnit**.


### Compatibility


This plug-in requires IBM UrbanCode Build version 6.1 and later.


The 
plug-in runs on any agents that the IBM UrbanCode Build server supports.


### Installation


No special steps are 
required for installation. See [Installing plug-ins in UrbanCode](https://www.urbancode.com/resource/installing-plug-
ins-in-urbancode-products/ "Installing plug-ins in UrbanCode").


### History


#### Version 10


Replace the markup 
builder with streaming markup builder for a performance improvement.


#### Version 9


Address a potential 500 server 
response due to having test suites with no names.


#### Version 8


Add optional timeout setting for calls to UCB 
server.


#### Version 7


Support property file encryption.


#### Version 6


Update the description of step 
properties


#### Version 5


Version 5 includes the following features and fixes:


* Added RPX dependency.
* 
Translation for step information.


#### Version 4


Version 4 includes the following features and fixes:


* Fixed a 
communication issue where the UrbanCode Build server would fail if it was running with an IBM JDK or JRE.


#### Version
 3


Version 3 includes the following features and fixes:


* Update to a newer version of a library for HTTP 
communication.


|Back to ...|||
| :---: | :---: | :---: |
|[**List of Plugins**](../../index.md)|[Steps](./steps.md)|[Downloads](./downloads.md)|
