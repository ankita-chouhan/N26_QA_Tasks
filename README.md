Task 1
============
See Task 1 folder for test suite in Markdown on Monefy Android application.

Task 2
============
See Task 2 folder for test suite in Microsoft Excel format. Note that I purposefully created this test suite in tabular format. I use both(Markdown & xls) from time to time. 

Task 3 
=============

Prerequisites
----------------
1. Download and install [Eclipse IDE for Java](https://www.eclipse.org/downloads/packages/eclipse-ide-java-developers/indigo)
2. Make sure Bestbuy API playground server is running.

Open Eclipse and setup this project in Eclipse
---------------------------------------------
1. Clone this Repository
```
git clone https://github.com/ankita-chouhan/N26_QA_Tasks.git
```
2. Import this cloned repository as java project in Eclipse:
	a) File->Import->Existing Projects into Workspace 
	b) Choose the `N26_QA_Tasks` folder.

Setup [Rest-Assured](https://github.com/rest-assured/rest-assured) Library
-----------------------------------------
1. Download Rest-Assured Jars `rest-assured-3.0.6-dist.zip ` from: [link](https://github.com/rest-assured/rest-assured/wiki/Downloads)
2. Unzip the downloaded file and again unzip the `*-deps.zip` file inside it.
3. Add these jars into your project's build path: 
	Right click on Project -> Properties->Java Build Path->Add External Jars. 
	Choose `rest-assured-*.jar` and all the jars inside `*-deps` folder.
	
Run Automation Tests
----------------------
Right click on the project folder -> Run As -> JUnit Test