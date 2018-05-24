#Airbnb
Airbnb Automation This is project structure for airbnb Web Automation.
#Description:
Airbnb is a website for the visiting of different places and finding accomdation and experience of the place by filtering the date and guest list.
As a base, it has implementation of different profiles and including RemoteWebDriver.
the project is implemented in **PAGE OBJECT MODEL WITH PAGE FACTORY**, 
this is a design pattern where declaration of locators in one class and intialization of functions in another class
this is similar to binding the data with functions.
 
##Prerequisites##
Eclipse IDE.
maven in local machine.
TestNG from eclipse market store.

##Running the test ##
In order to run the project simple execute " **testrun**" batch file consists in the project folder. This will execution the browser and get the results of tests.
### for windows  ###
click on "Testrun" bat file so you can see the bat files will start the automation in windows machine.
### For Linux  ###
click on "Testrun" sh file so you can see the sh file will start the automation in linux machine. 

##Project structure##
install eclipse IDE from official http://www.eclipse.org/downloads/eclipse-packages/
install maven from https://maven.apache.org/install.html

Once complete the installation of IDE integrate the automation pom to eclipse ide by 
Open the IDE click on "File" and click on "open file" then select the project called Automationpom folder which was unzipped 

you will find a project structure in Package explorer tab 
In automationpom you will find a folder called src/test/java
 src/test/java- this folder contains package of test which need to be executed 
1.**browser.utility**: This package contains the BrowserFactory.java this code will open the chrome browser to perform the Automation of airbnb
2.**com.airbnb.page**: This package contains the BaseHomepage.java where we have website locators and operations  to be performed in it.
3.**com.airbnb.test**:This package contains the testcase1.java where we have actual test case which run to automate the task given

Once we run the "**Testcases1.java**" as Testng either right clicking on java file or clicking on run.
we will find file running in **TESTNG** once test completed you will find a file created in testng.xml and test-output folder which consits html reports and xml format files

**MAVEN DEPENDENCIES**
This is the file contains dependencies of project like testng and selenium server and selenium java in the jar 

all this dependencies will be integrated in POM.XML file where all the version of selenium and testng will be integrated in XML format which added up.

##BUILD WITH##
**Maven**- Dependency managament.


**AUTHOR**
**TEJA SURISETTY**


