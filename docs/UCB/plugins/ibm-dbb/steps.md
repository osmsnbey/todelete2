
IBM Dependency Based Build - Steps Documentation
================================================

# Steps




### Steps




   




Process steps in the IBM DBB plug-in
------------------------------------


* [Build](#build)





### Build


Run a build using IBM Dependency Based Build.




*Input properties for the Build step*  | Name | Type 
| Description | Required | Property Name |
| Build Script Path | String | Specify the location of the build script to be
 used by IBM DBB in order to conduct
thebuild. | Yes | buildScriptPath |
| DBB Home Directory | String | The home 
directory of IBM Dependency Based Build. For example: /usr/lpp/IBM/dbb. If
notspecified, the value of the environment 
variable
DBB\_HOME will be used. | Yes | DBB\_HOME |
| Groovy Arguments | String | Specify any arguments to be passed to
 Groovy when executing the build script. Enter
each argument in a separate line. | No | groovyArgs |
| Groovy Options | 
String | Specify any options to be passed to Groovy when executing the build script. Enter
each option in a separate 
line. | No | groovyOptions |
| Reports Directory | String | Specify the directory where the IBM DBB build script places 
the report files. Leave
empty to skip uploading reports. | No | reportsDir |







|Back to ...|||
| :---: | :---: | :---: |
|[**List of Plugins**](../../index.md)|[Overview](./overview.md)|[Downloads](./downloads.md)|
