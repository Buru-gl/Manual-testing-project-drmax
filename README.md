# Final Project for Manual Testing - IT Factory

Hello! My name is M. Buruiană and I will present a project for manual testing, part of the manual testing course at IT Factory Academy.  

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test: https://www.drmax.ro/

API Documentation: *N/A*

The final project will include: [**Testing section**](https://github.com/Buru-gl/Manual-testing-project-drmax#1-testing-section)

Tools used: Jira [Atlassian](https://www.atlassian.com/software/jira), for Jira we use [Zephyr](https://marketplace.atlassian.com/apps/1014681/zephyr-squad-test-management-for-jira?tab=overview&hosting=cloud)

# Functional specifications

-> [functional specification](https://github.com/Buru-gl/Manual-testing-project-drmax/blob/main/Functional_specifications_drmax.pdf)


# 1 Testing section

## 1.1 Test Planning

The Test Plan is designed to describe all the details of testing the modules: "Login with a created account", "Register a new account", "Revalidate email address", "Search filters", "Select products and checkout", "Check additional information provided by the site" in the online shop of the drmax website. 

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

#### 1.1.1 Roles assigned to the project and persons allocated
  * Product owner: IT Factory
  * Project manager: IT Factory - Gabriela Radulescu
  * QA Tester: M. Buruiana

#### 1.1.2 Entry criteria defined
 - To ensure testing has been provided and made available to testers: Approved test plan, Access to relevant documentation for the software product, Test environments prepared (installation, software configuration, database, etc.), Access to systems and functionalities (accounts, permissions). [entry criteria](https://github.com/Buru-gl/Manual-testing-project-drmax/blob/main/Conditii_de_testare_test_case.png);
 -  functional business specifications are defined;
 -  esting environment is up and running;
 -  smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing).

#### 1.1.3 Exit criteria defined
 - all planned test cases were executed;
 - 70% of the tests passed;
 - no critical issues/bugs have open status (all unresolved bugs have low priority and severity from the point of view of software functionality).

#### 1.1.4 Test scope

* __Tests in scope:__ All features of the "Login" module that have been defined in the requirements and technical specifications, for the www.drmax.ro page, must be tested.
                      Other functionalities specific to web pages launched online, such as functional tests, GUI tests, etc.
* __Tests not in scope:__ Out-of-scope tests: compatibility tests with multiple operating systems (other than Windows), existing previously implemented functionality such as stress, performance, security tests. Only 
                      web pages will be tested, no mobile apps are developed. Automated testing is out of scope. 

#### 1.1.5 Risks detected

Project and product risks, materialised in the risk matrix, were identified at the planning stage. [matricea de risc](https://github.com/Buru-gl/Manual-testing-project-drmax/blob/main/Jira_matricea_de_risc-drmax.jpg).
  
#### 1.1.6 Evaluating entry criteria

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue. 

## 1.2 Test Monitoring and Control

It will be done by generating periodic reports that reflect the current status of the test.
Executions By Date
![Test_metrix_by_date](https://github.com/Buru-gl/Manual-testing-project-drmax/assets/125501132/0274c81c-fce4-4898-89cd-3f51530263a9)
![Test Executions By Test Cycle](https://github.com/Buru-gl/Manual-testing-project-drmax/assets/125501132/383580cc-58de-4862-9608-e0e05b035ad3)

## 1.3 Test Analysis

The testing process will be executed based on the above requirements for the "Login" module. The following test conditions were found: [test conditions](https://github.com/Buru-gl/Manual-testing-project-drmax/blob/main/Conditii_de_testare_test_case.png)

## 1.4 Test Design

Functional test cases were created in Zephyr Squad. Based on the specification analysis, the test design techniques used to generate the test cases are: Functional Testing and Non-functional Testing, as the site goes beyond the "Beta Testing" stage and is used in real world conditions, we use the concept of "happy flow" using Positive Testing and Negative Testing respectively.         
***Test case:***
![Test_case-titlu](https://github.com/Buru-gl/Manual-testing-project-drmax/assets/125501132/f4768b93-7794-40d4-9361-9553bb3b4905)

**Test cases:**
The test cases with steps can be viewed here: [JIRA test case](https://github.com/Buru-gl/Manual-testing-project-drmax/blob/main/Test_case_Jira.pdf)

## 1.5 Test Implementation

- Checked if we have everything we need to start executing tests?
- Test environment is up and running: (https://www.drmax.ro).

## 1.6 Test Execution

* The tests will be run on some of the most popular browsers: Chrome, Mozilla Firefox, Microsoft Edge, Apple Safari.
* If time allows, we will extend the tests to other browsers such as Tor, Opera, Brave;
* Test cases are executed on the created test Cycle summary: [cycle_summary_execution.pdf](https://github.com/Buru-gl/Manual-testing-project-drmax/blob/main/Summary_test_case_Jira.png)
* Bugs have been created based on the failed tests. The complete bug reports can be found here: [created_bugs.pdf](https://github.com/Buru-gl/Manual-testing-project-drmax/blob/main/Bug_Jira.pdf)
  ![Bug`s JIRA title](https://github.com/Buru-gl/Manual-testing-project-drmax/assets/125501132/07c8bcbd-51bd-410c-b67e-3caafc751c42)
* The test execution graph was generated in JIRA, the final report shows: [test completion report](https://github.com/Buru-gl/Manual-testing-project-drmax/blob/main/Chart_JIRA_raport.png)
  ![Test execution chart proiect TM-1](https://github.com/Buru-gl/Manual-testing-project-drmax/assets/125501132/b74521d2-931e-4088-a729-6eb6ea04486a)
  
## 1.7 Test Completion

* Exit criteria was evaluated and passed
* The traceability matrix was generated and can be found here: [Traceability_matrix.csv](https://github.com/Buru-gl/Manual-testing-project-drmax/blob/main/Forward%20Traceability.png)
* Test execution chart was generated: [test execution chart](https://github.com/Buru-gl/Manual-testing-project-drmax/blob/main/Chart_JIRA_raport.png)
* The cases tested generally worked well, but there are a few issues that need to be adjusted to provide an optimal end-user experience.
* Following the testing we have recommended fixing those found to ensure a loss-free user experience, financial loss or loss of potential customers.
  [Conclusions](https://github.com/Buru-gl/Manual-testing-project-drmax/blob/main/Conclusions_drmax.png)![Conclusions_drmax](https://github.com/Buru-gl/Manual-testing-project-drmax/assets/125501132/c60900be-7c03-4880-b3d5-40dd1e2d8338)

  


