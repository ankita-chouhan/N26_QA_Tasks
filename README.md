Task 1
============
See `Task 1` folder for test suite in Markdown on Monefy Android application.

Task 2
============
See `Task 2` folder for test suite in Microsoft Excel format. Here is short summary for this task:

* I use both(Markdown & xls) from time to time for writing test cases. For purpose of demonstration I have created this test suite in tabular format(Microsoft Excel). 
* I have prioritized test cases as per business impact. Test Cases with `High` priority should be automated first.
* Test cases could be automated on the following levels:
	
	- User Interface Level
		pros: Improved user experience as test cases would focus on UI. 
		cons: Need to update test-cases frequently as underlying api(s)/libraries change often.
	- Functional Level
		pros: Improved feature stability as test cases focus on core functional part of the application. 
		cons: Might not reflect end user experience with the application.
	

(Note: since I am doing this task as an optional task, I didn't create automated test cases for this). 

Task 3 
=============
I used Rest-Assured library write automated test cases for REST API endpoints. These Test cases  are mainly focus on testing correct functionality of endpoints with broad coverage. See below for the instructions on setup information. 

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

Setup [Rest-Assured](https://github.com/rest-assured/rest-assured) Library in Eclipse
-----------------------------------------
1. Download Rest-Assured Jars `rest-assured-3.0.6-dist.zip ` from: [link](https://github.com/rest-assured/rest-assured/wiki/Downloads)
2. Unzip the downloaded file and again unzip the `*-deps.zip` file inside it.
3. Add these jars into your project's build path: 
	Right click on Project -> Properties->Java Build Path->Add External Jars. 
	Choose `rest-assured-*.jar` and all the jars inside `*-deps` folder.
	
Run Automation Tests from Eclipse
----------------------
Right click on the project folder -> Run As -> JUnit Test