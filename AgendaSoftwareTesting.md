# System is operational
	Zero Defect Product

	80%------20% Rule

	## Agenda:
		Introduction to Software Testing
		Why Software Testing important
		Validatation and Verification
		Quality Assurance Vs. Quality Control
		Principles of Softwar Testing
		V Model
		Types of Testing
		Mannual Testing
		Automation Testing
		Tools for Software Testing
		Selenium Testing tool



		## Software Engg. phases:
			
			Analysis, Design ,Development, Testing, Deployment, maintainance


		* Analysis:
		   Requirement---------Customers, their business people, actual end user, stake holder
		   Architecting Solution--Architect, Domain Experts , QA Team (Quality Assurance team)
		   Development Team------programmers, Developers, UI Designers
		   Release Team---------Build managers, Release experts-----Building binaries for appln.

		   Software Testing Team--Testers, QA Team, End Users, Customer

		   Operations team------System Administrators, Monitoring Team using  checking log files,
					Customer support Team (maintainance)
		   DevOps team-----------CD/CI--------DevOps



		 Software Testing Team:
				Quality Assurance
				Quality Control
				Zero Defect Product
				Test Strategy
				Test plan
				Test Cases
				QA Process 



What is Quality Assurance?

Quality Assurance is popularly known as QA Testing, is defined as an activity to ensure that an organization is providing the best possible product or service to customers.
1.It is a procedure that focuses on providing assurance that quality requested will be achieved QA aims to prevent the defect
2.It is a method to manage the quality- Verification
3.It does not involve executing the program
4.It's a Preventive technique
5.It's a Proactive measure
6.It is the procedure to create the deliverables
6.QA involves in full software development life cycle
7.In order to meet the customer requirements, QA defines standards and methodologies
8.It is performed before Quality Control
9.It is a Low-Level Activity, it can identify an error and mistakes which QC cannot
10.Its main motive is to prevent defects in the system. It is a less time-consuming activity
11.QA ensures that everything is executed in the right way, and that is why it falls under verification activity
12.It requires the involvement of the whole team
13.The statistical technique applied on QA is known as SPC or Statistical Process Control (SPC)

Quality Control in Software Testing is a systematic set of processes used to ensure the quality of software products or services. The main purpose of the quality control process is ensuring that the software product meets the actual requirements by testing and reviewing its functional and non-functional requirements. Quality control is popularly abbreviated as QC.
1.It is a procedure that focuses on fulfilling the quality requested.
3.It is a method to verify the quality-Validation
4.It always involves executing a program
5.It's a Corrective technique
6.It's a Reactive measure
7.It is the procedure to verify that deliverables
8.QC involves in full software testing life cycle
9.QC confirms that the standards are followed while working on the product
10.It is performed only after QA activity is done
11.It is a High-Level Activity, it can identify an error that QA cannot
12.Its main motive is to identify defects or bugs in the system. It is a more time-consuming activity
13.QC ensures that whatever we have done is as per the requirement, and that is why it falls under validation activity
14.It requires the involvement of the Testing team
15.The statistical technique applied to QC is known as SQC or Statistical Quality Control

Software Testing:
	Finding bugs
	Finding loop holes in a software
	Defining test plan
	Writing test cases
	Executing test cases
	Collecting Test results
	Report test results to Developers
	Escalate vulenrabilities in build of software		
	Always check for expected output from the system

Software testing is a method
	Wheather your software meets the SRS guidlines ( Product, service, Application) matches expected requirements it ensures software is bug free (Zero defect Product)

purpose of ST>:
	 Identify errors, gaps which missing in software.
Software Testing is a method to check whether the actual software product matches expected requirements and to ensure that software product is Defect free. It involves execution of software/system components using manual or automated tools to evaluate one or more properties of interest. The purpose of software testing is to identify errors, gaps or missing requirements in contrast to actual requirements.


V model Software Testing:

Verification in Software Testing is a process of checking documents, design, code, and program in order to check if the software has been built according to the requirements or not. 
The main goal of verification process is to ensure quality of software application, design, architecture etc. 
The verification process involves activities like reviews, walk-throughs and inspection.

Validation in Software Engineering is a dynamic mechanism of testing and validating if the software product actually meets the exact needs of the customer or not. 
The process helps to ensure that the software fulfills the desired use in an appropriate environment. 
The validation process involves activities like unit testing, integration testing, system testing and user acceptance testing.


KEY DIFFERENCE

Verification process includes checking of documents, design, code and program whereas 
Verification does not involve code execution.
Verification uses methods like reviews, walkthroughs, inspections and desk-checking.
Verification checks whether the software confirms a specification.
Verification finds the bugs early in the development cycle.
Verification process targets on software architecture, design, database, etc.
Verification is done by the QA team.
Verification process comes before validation.

Validation process includes testing and validation of the actual product.
Validation involves code execution.
Validation uses methods like black box testing, white box testing and non-functional testing.
Validation checks whether the software meets the requirements and expectations.
Validation finds the bugs that verification can not catch.
Validation process targets the actual software product.
Validation is done by the involvement of testing team with QA team.
Validation process comes after verification.

Advantages of Software Testing:
	Cost Effective
	Product Quality
	Customer statisfaction
	Secure


Types of Software Testing:
	Functional Testing
	Unit Testing
	Integration Testing

Non Functional Testing:
   Performance
   Endurance
   Load Testing
   Scalability
   Usability
				

What are principles of Software Testing:

7 principles of Software Testing:

1.Exhastive testing is not possible.
 Exhaustive testing is not possible. 
 Instead, we need the optimal amount of testing based on the risk assessment of the application.
		 
2.Defect Clustring
Defect Clustering which states that a small number of modules contain most of the defects detected. 
This is the application of the Pareto Principle to software testing:
 approximately 80% of the problems are found in 20% of the modules.

By experience, you can identify such risky modules. But this approach has its own problems.If the same tests are repeated over and over again, eventually the same test cases will no longer find new bugs.

3.Testing always shows a presence of Defects.
Hence, testing principle states that – Testing talks about the presence of defects and don’t talk about the absence of defects. i.e. Software Testing reduces the probability of undiscovered defects remaining in the software but even if no defects are found, 
it is not a proof of correctness.But what if, you work extra hard, taking all precautions & make your software product 99% bug-free. 
And the software does not meet the needs & requirements of the clients.

4.Pesticide paradox
Repetitive use of the same pesticide mix to eradicate insects during farming will over time lead to the insects developing resistance to the pesticide Thereby ineffective of pesticides on insects. The same applies to software testing. If the same set of repetitive tests are conducted, the method will be useless for discovering new defects.To overcome this, the test cases need to be regularly reviewed & revised, adding new & different test cases to help find more defects.

5.Absence of Error-----(Defective product)-----(Zero defect product)
It is possible that software which is 99% bug-free is still unusable. This can be the case if the system is tested thoroughly for the wrong requirement.Software testing is not mere finding defects, but also to check that software addresses the business needs. 
The absence of Error is a Fallacy i.e. Finding and fixing defects does not help if the system build is unusable and does not fulfill the user’s needs & requirements.

6.Early Testing
Early Testing – Testing should start as early as possible in the Software Development Life Cycle.
So that any defects in the requirements or design phase are captured in early stages. 
It is much cheaper to fix a Defect in the early stages of testing.
But how early one should start testing? 
It is recommended that you start finding the bug the moment the requirements are defined. 

7.Testing is a context dependent(Abstraction)
Testing is context dependent which basically means that the way you test an e-commerce site will be different from the way you test a commercial off the shelf application. All the developed software’s are not identical. You might use a different approach, methodologies, techniques, and types of testing depending upon the application type. For instance testing, any POS system at a retail store will be different than testing an ATM machine.


How do I Write a Test ?

		1.Define a scenario
		2.Define expected output
		3.Define required input to the System

		  Authentication
				with proper crednetials  user redirected to profile pages
				output success: with proper crendentials
				output fail:   with improper credentails

		  Product Catalog Display
		  Prouduct Details Display
		  Select product to add to shopping cart
		  Remove item from ShoppingCart
		  Show all Items available in ShoppingCart

Define Test Plan: By QA Team:  (Rule book) for Software Testing Team:
Test Strategy
Objective:Objectives captured from usecases
	Estimations and Delivery:
				Pre-conditions
				Timeline for testing:
	Resoruces required from Testing:
		Testers,----------------------------mannual Testing
		Testing Tools-----------------------Automation Testing Tool
		Test cases-------------------------plain documents,
   spreasheet,etc.




STLC Phases

There are following six major phases in every Software Testing Life Cycle Model (STLC Model):

	1.Requirement Analysis
	2.Test Planning
	3.Test case development
	4.Test Environment setup
	5.Test Execution
	6.Test Cycle closure


What is Entry and Exit Criteria in STLC?

Entry Criteria: 
		Entry Criteria gives the prerequisite items that must be completed before testing can begin.
Exit Criteria: 
		Exit Criteria defines the items that must be completed before testing can be concluded


1.Requirement Analysis
		
	Activities in Requirement Phase Testing
		1.Identify types of tests to be performed. 
		2.Gather details about testing priorities and focus.
		3.Prepare Requirement Traceability Matrix (RTM).
		4.Identify test environment details where testing is supposed to be carried out. 
		5.Automation feasibility analysis (if required).

	Deliverables of Requirement Phase Testing

		1.RTM (equirements Traceability Matrix)
			is a document that links requirements throughout the validation process. 
			The purpose of the Requirements Traceability Matrix is to ensure that all requirements defined for 
				a system are tested in the test protocols
		
		2.Automation feasibility report. (if applicable)

	
2.Test Planning
		
	Test Planning Activities
		1.Preparation of test plan/strategy document for various types of testing
		2.Test tool selection
		3.Test effort estimation
		4.Resource planning and determining roles and responsibilities.
		5.Training requirement
	
	Deliverables of Test Planning
		1.Test plan /strategy document.
		2.Effort estimation document.
	
3.Test case development

	Test Case Development Activities
		1.Create test cases, automation scripts (if applicable)
		2.Review and baseline test cases and scripts
		3.Create test data (If Test Environment is available)
	
	Deliverables of Test Case Development
		1.Test cases/scripts
		2.Test data	

4.Test Environment setup
	Test Environment Setup Activities
		1.Understand the required architecture, environment set-up and prepare hardware 
		   and software requirement list for the Test Environment.
		2.Setup test Environment and test data
		3.Perform smoke test on the build

	Deliverables of Test Environment Setup
		1.Environment ready with test data set up
		2.Smoke Test Results.

5.Test Execution
	Test Execution Activities
		1.Execute tests as per plan
		2.Document test results, and log defects for failed cases
		3.Map defects to test cases in RTM
		4.Retest the Defect fixes
		5.Track the defects to closure

	Deliverables of Test Execution
		1.Completed RTM with the execution status
		2.Test cases updated with results
		3.Defect reports


6.Test Cycle closure
	Test Cycle Closure Activities
		1.Evaluate cycle completion criteria based on Time, Test coverage, Cost,Software, Critical Business Objectives, Quality
		2.Prepare test metrics based on the above parameters.
		3.Document the learning out of the project
		4.Prepare Test closure report
		5.Qualitative and quantitative reporting of quality of the work product to the customer.
		6.Test result analysis to find out the defect distribution by type and severity.

	Deliverables of Test Cycle Closure
		1.Test Closure report
		2.Test metrics

Test Plan
A Test Plan is a detailed document that describes the test strategy, objectives, schedule, estimation, deliverables, and resources required to perform testing for a software product. Test Plan helps us determine the effort needed to validate the quality of the application under test. 
The test plan serves as a blueprint to conduct software testing activities as a defined process,which is minutely monitored and controlled by the test manager.

What is the Importance of Test Plan?
Follow the seven steps below to create a test plan as per IEEE 829
1.Analyze the product
2.Design the Test Strategy
3.Define the Test Objectives
4.Define Test Criteria
5.Resource Planning
6.Plan Test Environment
7.Schedule & Estimation
8.Determine Test Deliverables


Step 1) Analyze the product
	You should research clients and the end users to know their needs and expectations from the application
		Who will use the website?
		What is it used for?
		How will it work?
		What are software/ hardware the product uses?

Step 2) Develop Test Strategy
	A Test Strategy document, is a high-level document, which is usually developed by Test Manager. 
	This document defines:
		The project’s testing objectives and the means to achieve them
		Determines testing effort and costs

Step 3) Define Test Objective
	To define the test objectives, you should do 2 following steps
		1.List all the software features (functionality, performance, GUI…) which may need to test.
		2.Define the target or the goal of  the test based on  above features

What is test plan template?

TEST PLAN TEMPLATE is a detailed document that describes the test strategy, objectives, schedule, estimation and deliverables, and resources required for testing. Test Plan helps us determine the effort needed to validate the quality of the application under test.
The test plan serves as a blueprint to conduct software testing activities as a defined process which is minutely monitored and controlled by the test manager.Creating a Test Plan is mandatory to ensure success of your Software testing project.Help people outside the test team such as developers, business managers, customers understand the details of testing.Test Plan guides our thinking. It is like a rule book, which needs to be followed.Important aspects like test estimation, test scope, Test Strategy are documented in Test Plan, so it can be reviewed by Management Team and re-used for other projects.

____________________________________________________________________________________________________________________________________

What is a Test Case?
A TEST CASE is a set of actions executed to verify a particular feature or functionality of your software application. 
A Test Case contains test steps, test data, precondition, postcondition developed for specific test scenario to verify any requirement. 
The test case includes specific variables or conditions, using which a testing engineer can compare expected and actual results to determine whether a software product is functioning as per the requirements of the customer.
Test case:
	Test Case 1: Check the results on entering valid user Id and Password
	Test Case 2: Check the results on entering invalid user id and password
	Test case 3:Check the response when a user IS is empty and login buttong in presess..
you would need data

Test Case : 1
Description:  Check the results on entering valid user Id and Password
Test Steps:   1.Enter Email Address
	      2.Enter password
	      3.Click Sign In
Test Data:
	    Email: ravi.tambade@transflower.in
	    password: tfl@7867
Expected Result:
	   Login should be successfull
Actual Result:
	    Login was successful
Pass/Fail:
	   Pass

_________________________________________________________________________________________________________________________________

Test Case : 2
Description:  Check the results on entering invalid user id and password
Test Steps:   1.Enter  Invalid Email Address
	      2.Enter  Invalid password
	      3.Click Sign In
Test Data:
	    Email: ravi.jadhav@transflower.in
	    password: t56564
Expected Result:
	   Login should be falied
Actual Result:
	    Login should be falied
Pass/Fail:
	   passed
___________________________________________________________________________________________________________________________________

While drafting a test case to include the following information:
1.The description of what requirement is being tested
2.The explanation of how the system will be tested
3.The test setup like
	a version of an application under test, 
	software, 
	data files, 
	operating system, hardware, 
	security access, physical or logical date, 
	time of day, 
	prerequisites such as other tests and 
	any other setup information pertinent to the requirements being tested
4.Inputs and outputs or actions and expected results
5.Any proofs or attachments
6.Use active case language
7.Test Case should not be more than 15 steps
8.An automated test script is commented with inputs, purpose and expected results
9.The setup offers an alternative to pre-requisite tests
10.With other tests, it should be an incorrect business scenario order


While testing the web applications, one should consider the below mentioned template. 
The below mentioned checklist is almost applicable for all types of web applications depending on the business requirements.

The web application testing checklist consists of-

	1.Usability Testing
	2.Functional Testing
	3.Compatibility Testing
	4.Database Testing
	5.Security Testing
	6.Performance Testing

Example Usability Test Cases

1.Web page content should be correct without any spelling or grammatical errors
2.All fonts should be same as per the requirements.
3.All the text should be properly aligned.
4.All the error messages should be correct without any spelling or grammatical errors and the error message should match with the field label.
5.Tool tip text should be there for every field.
6.All the fields should be properly aligned.
7.Enough space should be provided between field labels, columns, rows, and error messages.
8.All the buttons should be in a standard format and size.
9.Home link should be there on every single page.
10.Disabled fields should be grayed out.
11.Check for broken links and images.
12.Confirmation message should be displayed for any kind of update and delete operation.
13.Check the site on different resolutions (640 x 480, 600×800 etc.?)
14.Check the end user can run the system without frustration.
15.Check the tab should work properly.
16.Scroll bar should appear only if required.
17.If there is an error message on submit, the information filled by the user should be there.
18.Title should display on each web page
19.All fields (Textbox, dropdown, radio button, etc) and buttons should be accessible by keyboard shortcuts and the user should be able to perform all operations by using keyboard.
20.Check if the dropdown data is not truncated due to the field size. Also, check whether the data is hardcoded or managed via administrator.


IDE  tool Support for Software Testing:
 Unit Testing:
	1.Create  a project to Test
	2.Create a unit Test project.
	3.Create Test Class.
	4.Create Test Method--------implementation for Test Case
	5.Build and Run Test.
	6.Fix your code and rerun  the test.
	7.Keep your fixing your code by performing repeated Test.
______________________________________________________________________________________________________________________________________

Automation Testing:
	Automation Testing Frameowrk
	Automation Testing Tool---------Selenium
	Automation Testing is done for Web Testing
_____________________________________________________________________________________________________________________________________

When to choose Automated Testing?

There are a number of scenarios when software test engineers choose automation testing. 

For instance, if they have a huge number of test cases that can be time consuming performed manually they would prefer test automation. 
In case of testing high priority features where they do not want to risk human errors, testing the same features again and again, running multiple test cases simultaneously on different systems, 
if the testing process is more complex and time consuming if done manually, the software test engineers choose test automation.

Most of the times, especially in large projects when testing is required with every release, certain types of testing including smoke test, sanity test, regression test, performance test, stress and load tests etc. are automated. While using an efficient test automation tool, testers also test the above mentioned as well as cross browser testing along with same features with different data sets, performance test and many more


How to choose the right tool for automation testing?

Before choosing an automation tool, you need to identify your requirements and ensure they align with the tool you select. The tool must be satisfying to your testing requirements, supporting the testing methods you would like to implement, suitable to your project environment and 
also technology and language that are used to build the application. One should always ensure that the tool is not very complex to understand and use as it becomes time consuming to go through all the training to learn how to operate.Although it highly depends on the kind of application, 
certain types of tests that can be automated are as follows:
1.Smoke test
2.Web test automation
3.Mobile testing
4.Sanity test
5.Regression test
6.Cross browser test automation
7.Web services test
8.Database testing
9.Big data testing
10.Various types of performance tests 
11.Functional test 
12.Integration test
13.Data driven test
14.Unit test. 

On the other hand, types of tests which should not be automated are exploratory test, UX test, UI test and API testing.

	
