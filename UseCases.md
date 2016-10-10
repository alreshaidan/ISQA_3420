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

**Title:** Retrieve to checked for open sours Software components from NIST Vulnerability. 
 
**Primary Actor:** Developer. 

**Goal in Context:** To successes checked for open source Software components.

**Stakeholders:** Developer / Manager.

**Preconditions:** The Developer send request to checked for open source Software components to receive result from NIST Vulnerability DB.

**Main Success Scenario:** Developer get the software package Results from the NIST Vulnerability DB. 

**Failed End Conditions:** Developer not get the result from the NIST Vulnerability DB.

**Trigger:** Developer request for software package license.   


#UseCase: 3

**Title:** Determine the  Open Source Software to get  Refer policy. 

**Primary Actor:** Developer.

**Goal in Context:** Successes determine open source software. 

**Stakeholders:** Developer / Manager.

**Preconditions:** The developer send request to refer policy process to receive from the OSS Policy Datastore.

**Main Success Scenario:** Developer get the policy DB from the policy process by the OOS Policy Datastore.

**Failed End Conditions:** Developer not get the policy DB from the policy process by the OOS Policy Datastore.

**Trigger:** Developer request for open source software policy DB.
