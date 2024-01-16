# Smart-Home-Monitoring-and-Management-System
## Business Overview:
Home Watching Services (HWS), owned by JP Lyons, offers a unique house watching service to monitor homes, especially during off-season periods when owners are away. Serving a community where many homes are occupied only during the summer, HWS ensures the safety and maintenance of these properties throughout the year.

## Innovative Technology Use:
HWS distinguishes itself by being the first in its sector to use sensor technology. Unlike traditional house watching services that require physical checks a few times a week, HWS's sensors provide 24/7 monitoring. These sensors are designed to detect various issues such as floods, leaks, and heating failures. Upon any sensor activation, an HWS employee promptly addresses the problem onsite.

## Service Model:
Clients are charged a monthly fee for continuous monitoring. Additional charges apply for extra services necessitated by the house calls, like flood clean-up or plumbing repairs.

## Expansion and Digitalization:
Recognizing the need for expansion, JP plans to extend services to more clients in the current town and neighboring areas. A key strategy for this growth is the development of a comprehensive online application to streamline business operations.

## Proposed Online System:

Client Onboarding: 
Allows potential clients to sign up, input their information, and request services online. After an initial property inspection and approval, clients are activated and billed monthly.
Sensor Integration and Notifications: The system receives alerts from sensors and notifies the on-call employee. Clients are also informed of any issues.

Issue Tracking: 
Clients can check the status of their issues online, with updates provided by the responding employees.
Billing and Administration: Monthly billing with the flexibility to adjust charges. Admin features include managing client accounts and employee roles.

Budget and Technical Challenges:
JP has set a $250,000 budget for the website's development. Challenges include ensuring effective integration of sensor technology with the new system and managing JP's availability due to his frequent field visits./

Project Development:
An upcoming analysis session with hired analysts will further define the design and functional aspects of the project.

### 1- Create a decomposition diagram of the business.
 
registration,
Monitoring,
Billing,
administration: (employee management, client management)
service

Registration:
•	Create account
•	Verify registration information
•	Notify user of successful registration
•	Deny registration request if information is incomplete or inaccurate
•	Send confirmation email to user   

Monitoring:
•	Collect data from sensors
•	Analyze data for anomalies or issues
•	Alert appropriate employee(s) of potential problems
•	Track progress of issue resolution
•	Generate reports on sensor data and issue status

Billing:
•	Generate invoice
•	Record payment
•	Adjust bill or credit account as necessary
•	Handle billing disputes and refunds
•	Send reminders for unpaid bills

Administration:
•	active/reactive account
•	change monthly bill fee 
•	add/remove employee

Service:
•	apply services
•	apply request
•	approve/disapprove


### 2-Create a BRD 
start:
Requirements document for <JP >
Date: 04/26/2023
By: Chen Liu
Revision History

Revision number	Date	Reason for revision	Revised by
1.0	04/26/2023	Initial Draft	

2.1 Scope statement : 
The purpose of this project is help JP Lyons to create an online platform that will allow potential clients to sign up for Home Watching Services (HWS).
The platform will coordinate the business by notifying HWS employees of sensor-triggered issues in clients' homes, 
enabling clients to monitor the status of their requests, and facilitating monthly billing. The project has a budget of $250,000.

1.	The system will allow users to register account and create their own profile. 
2.	The system will allow to connect sensor.
3.	The system will allow to add extra sensor as request.
4.	The system will allow terminating/stop sensor.
5.	The system will allow monitoring  7/24.
6.	The system will notify HWS employees when a sensor is triggered 
7.	The system will process monthly billing for clients 
8.	The system will allow clients to check the status of their requests. 
9.	The system will allow employees to add information on findings and actions taken to rectify. 
10.	The system will allow multiple payment options for clients.
11.	The system will send notifications to clients through email and/or text message.
12.	The system will allow clients to view their service request history.
13.	The system will allow clients to submit service requests.
14.	The system will allow employees to update service request status and add notes.
15.	The system will provide a search function for clients to find information about services and products. 

2.2	Out of scope: 
1.	The platform will not support cryptocurrency payments.
2.	The system will not integrate with social media platforms.
3.	The system will not have the ability to customize product recommendations based on customer behavior. 
4.	The system will not provide real-time analytics or reporting on property issues.

2.3 Goals: 
To provide a comprehensive property management solution that streamlines the property search, management, 
and service request processes for clients in a user-friendly and efficient manner.

2.4	Objectives: 
1.	Building a user-friendly and accessible online platform for clients to easily manage their properties, schedule visits, and request information and services.
2.	To provide reliable and efficient property monitoring and maintenance services to clients through sensor technology and proactive communication.
3.	establishing a secure and convenient payment system for clients to process transactions and manage their accounts.
4.	streamline internal processes and enhance employee productivity through a centralized dashboard for managing client properties and service requests.

2.5	Risks:
1.	Cost risk: As customer monitoring data continues to increase, plus historical data needs to be stored. So the cost of storing data will rise rapidly
2.	Schedule risk: JP's busy schedule may result in delays in making important decisions or providing feedback on project deliverables, leading to project delays.
3.	Technical risk: The technical person's concerns about connecting sensors to the new application may result in difficulties in implementing this feature,leading to delays or increased costs.
4.	Budget risk: JP's absence during important project discussions or decision-making sessions may lead to unplanned expenses or changes to the project scope, potentially increasing project costs beyond the allocated budget.

2.6	Constraints:  
1.	Regulatory compliance: The platform will need to comply with relevant laws and regulations governing data privacy, security, and financial transactions. Ensuring compliance not add additional complexity and cost to the project.  
2.	Budget constraint: The budget for building the site is unfixed at $250,000, but it’s better to keep around that amount.
3.	Time constraint: The project needs to be completed within a certain time frame to avoid losing potential clients or market opportunities. This project should not exceed 4 months.
4.	Scope constraint: The scope of the project needs to meet the requirements of the business while staying within the budget and time constraints. Any changes to the scope of the project must be approved by JP and the project team.

2.7	Decomposition diagram:


<img width="352" alt="image" src="https://github.com/chenliu521/Smart-Home-Monitoring-and-Management-System/assets/71107771/bafc0dad-15cb-4326-a9ec-166301ab714b">



2.8.1 Functional requirements


![image](https://github.com/chenliu521/Smart-Home-Monitoring-and-Management-System/assets/71107771/cba880b9-64c2-4486-a38c-e6bd1535b4e7)
  
2.8.2 Nonfunctional requirements

8.1.	Storage: 
8.1.1.	The system shall store all customer’s information and all transaction data in HWS Cloud

8.1.2.	The system must connect with a massive amount of storage platform.

8.1.3.	The system shall require encryption of all personal data

8.2.	response:
8.2.1.	The system shall respond quickly to user’s requests

8.2.2.	Ensure that all services, product search, page load and checkout processes are up and running even during peak periods

8.3.	Capacity:
8.3.1.	The system shall support volume of visitor over 310 million.

2.9  Stakeholders < JP Lyons >
2.10  Approvals < >



### 3-Create Activity Diagrams
<img width="333" alt="image" src="https://github.com/chenliu521/Smart-Home-Monitoring-and-Management-System/assets/71107771/236ed431-b4ab-4d81-bb1b-4dca16c79430">

<img width="468" alt="image" src="https://github.com/chenliu521/Smart-Home-Monitoring-and-Management-System/assets/71107771/7032be73-9c04-4fcd-937f-a286379615c2">

### 4- Create a data model for the two process flows you have created
Create a Crow's feet diagram


### 5- Create Wireframes for the two processes.

<img width="468" alt="image" src="https://github.com/chenliu521/Smart-Home-Monitoring-and-Management-System/assets/71107771/f7c30f99-5b8c-41ee-829e-fb350566daee">

## step:

![image](https://github.com/chenliu521/Smart-Home-Monitoring-and-Management-System/assets/71107771/d1a3987e-ced5-479a-8203-85101377b9a4)

