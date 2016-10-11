#UseCase: 1

**Title:** Retrieve license and Vulnerability Information for requeseted software project
  
**Primary Actor:** Manager
   
**Goal in Context:** The Corporate Manager is able to retrieve license and vulnerability information  for a requested software project 
  
**Stakeholders:** Developer / Manager 
  
**Preconditions:** The Manger need to send request to project process to Receive the license and vulnerability information from the Policy Data store.
 
**Main Success Scenario:** Manager get the license and vulnerability information from software package & license information database.  
   
**Failed End Conditions:** Manager does not get the information from  software package & license information
  
**Trigger:** Manager request for software project license and vulnerability information. 

   
#UseCase: 2

**Title:** Request for Software Package License

**Primary Actor:** Developer

**Goal in Context:** Developer wants to get the license information of the submitted software package. 

**Stakeholders:** Developer / Manager 

**Preconditions:** There is some Software Package used by developer in a project. Software Package License service is running.

**Main Success Scenario:** Developer request for Software Package License is successfully accepted and developer obtains the license details. 

**Failed End Conditions:** No result found against software package.

**Trigger:** Developer request for Software Package License. 


#UseCase: 3

**Title:** Request Policy

**Primary Actor:** Developer

**Goal in Context:** Developer wants to get the information against some policy 

**Stakeholders:** Developer / Manager 

**Preconditions:** Policy request is submitted.

**Main Success Scenario:** Developer gets policy details  

**Failed End Conditions:** Policy information is not stored in the policy database.

**Trigger:** Developer requests a policy. 


