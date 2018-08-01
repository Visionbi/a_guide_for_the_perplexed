**Development**
=================
Software development is the process of computer programming, documenting, testing, 
and bug fixing involved in creating and maintaining applications and frameworks resulting in a software product

*Source to target*
------------------
The BI software development process starts with the source to target document (S2T). 
The purpose of this document is to map source system fields (from files or DB  tables ) to the fields of
a target system, in our case dim/ fact tables in the data warehouse / data mart. 
Here is some other important information that the S2T document should include:
  - Business logic required in order to create fields.
  - Loading frequency for the mapping described by the document.
  - What should be the "join" statement in order to get the desired dataset.
  - Data types of both the source and target fields.
  - Any conversion logic that is applied to convert between data types.
  - Any applicable business rules.

*Design of reports*
-------------------
A high quality BI report design is crucial for success in every BI implementation..
Bad design may lead to confusion and mislead BI end users or result in bad business decisions. 
Well designed BI reports and dashboards can help a company reveal unusual patterns in their data and make important decisions.
3 key questions need to be answered while designing BI reports: 

**who** - the first answer will be who is your target audience: 
- business users, and/or
- management users, and/or
- board of directors
	
**what** - the fundamentals of the reports are the metrics and KPIs.
	 Via interviews you will find out what metrics and KPIs are currently in use to monitor the organization business processes 

**how** - the last question that will be answered will be how to present the data and metrics. 
For example, which diagram/ chart will be easier to understand and will present the information in the right context. 

Based on the answers the next step will be creating a mockup containing all key information 
and relevant charts and get a sign off on it from the stakeholder/clients of the reports. 

*Performing code reviews*
-------------------------
Code Review is systematic and intended to perform a check on a developer code searching for mistakes, bugs, 
inefficiency or lack of use of best practises.
Code review is done in order to improve the overall quality of code written in the project
and to help the developers to learn from each other's mistakes - without blaming!. 
It is very important to take in mind and reserve time from the beginning to perform  code reviews.
Code review can be done by several people:
- Peer developer
- PM
- Other PM
- Architect 

*Recurring team meetings*
-------------------------
In order to establish a work routine, recurring team meetings are a must. 
When a project is at the work-in-process state it is recommended  to have a daily team meeting where all members can update their status on current task and/or ask for guidance and/or raise flags regarding the progress of their tasks.
weekly team meetings are the place to share concepts, define the agenda for development ,perform design reviews 
and connect all team members to the "big" picture of the project.

*On-going documentation*
------------------------
It is highly important to maintain and keep the project documentation up to date. 
Any new columns , features or other functionality added to the project must be updated. 
If possible it is recommended to use tools that will automate documentation straight for code. 
Another possibility is to extend logging in the project and use logs as documentation.
  
