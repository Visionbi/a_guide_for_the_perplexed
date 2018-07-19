# System handover


Last but not least.
This is a sensitive and critical phase that needs to be carefully managed to make sure the customer gets all required 
tools and information that will enable him use and maintain the system after going live.
(This guide will not cover end-user training)

## Documentation
The purpose of documentation is to make sure the customer system owner gets a clear and full picture of the different models 
and the objects the system contains including the method they were implemented.
There are different approaches to document your software. One can manage it through detailed comments and explanations within 
the application code itself. Others might prefer to manage a standalone document for each business model.
A list of topics to be included:
•	Purpose
•	Background & business questions
•	General Assumptions
•	DWH Design (main information of each entity)
•	Data Flow Chart
•	Star Schema Chart 
•	Dependencies (internal and external)
•	Measures and attributes
•	Main and special capabilities

## Training
Holding a F2F training session/s will ensure high quality, focused and professional process. 
The training shall include detailed review of the system implementation, including:
•	Business model review (and the entities each model contain)
•	Solution architecture
•	Partitions
•	Loading process
•	Logging
•	Dashboard and reports review
The training session can lead to a walkthrough session that will include a code review. Make sure you are prepared to answer 
‘why’ questions and not just ‘how’.
It is preferred that you will upload your code to the customer source control system in order to have an alignment with 
internal solutions.

## Runbook
Writing a set of routines and operations that explain common recurring tasks will help you to find the optimal way 
to get the work done.
If you are not sure if you will remember to explain the customer how to do things 6 months from now or if there are many 
routines to follow , continue reading .
You can write a general checklist to cover daily operational tasks for example:
•	Check no alert emails or failures in the logs
•	Monitor system performances 
•	Make sure reports and dashboards are extracting data 
•	Etc.
You will write common failures and uncommon failures including potential fixing. How to recover from malfunctions . 
Do you need to run the process again or do you need to change something manually before running for the next time.
The runbook will include all the steps 1..5 till the problem is solved and will include links to technical information 
like user, passwords, connection strings etc.

## Infrastructure review
Going the last mile . Highly recommanded.
Infrastructure components to be mentioned during handover process , preferred with a DBA/System administrator.
•	Disk allocation 
•	Index fregmentation
• Review buckup & recovery procedures (Full/differential/transaction Log(Full Recover Mode))
• Data retention policy 
