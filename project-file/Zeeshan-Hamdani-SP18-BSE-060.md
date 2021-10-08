
# CMMI V2.0 AUTOMATION

## NESCOM
### Full Name
Zeeshan Ali Hamdani

### Roll Number
SP18- SE-060

## Project Details
### Description
 This project is an industrial project. This project is a project management software based on the 2018 version of CMMI v2.0.
 CMMI v1.1 was first released in 2002, and upon its introduction many companies strived to achieve different levels of CMMI. These levels describe how managed and streamline are the process of an organization. CMMI consists of 5 levels: Initial, Defined, Quantitatively, Managed and Optimizing. With increase in each level, the organization moves a step towards high degree of satisfaction, efficiency and effectiveness. 

CMMI has also gone through many changes similar to how the trends in project management have changed as well. Following CMMI v1.1 (in 2002), a sequel was released in 2006 label as CMMI v1.2, then CMMI v1.3 in 2010 and then comes the latest version of CMMI, CMMI v2.0 released in March 2018.

Whilst being a beneficial PI (Process Improvement) standard, there are no CMMI v2.0 project management tools at hand. This project provides a proprietary solution for NESCOM, that will implement some of the most important knowledge areas from CMMI v2.0.
The list of knowledge areas is as follows:
* Planning
* Estimating
* Monitor & Control 
* Process Asset Development 
* Configuration Management 
* Supplier Agreement Management 
* Technical Solution 
* Product Integration 
* Requirement Development Management 
* Verification & Validation
*  Peer Reviews.


### Technology Stack
  
  This project is being built with MERN Stack, therefore, it uses Javascript and ES6. 
  
 Abbreviation | Technology
------------- | -------------
M             | MongoDB
E             | ExpressJS
R             | ReactJS
N             | NodeJS

Tools
* Visual Studio Code
* GitHub
* Postman
* MongoDB Compass
* Microsoft Office
  * Word
  * Visio
  * Project
  * Powerpoint
  * Excel



### Deployment or Distribution Strategy
  
  The system will be deployed on the organizations intranet through a series of nodes and routes with port forwarding to allow interdepartmental access to the system. 
  The system lacks online capabilities due to security concerns posed by our stakeholder NESCOM.

  

### Architecture
 This project utilizes the N-tier architecture which is used most commonly with web applications because of its ability to decompose the application into logical and physical layers.

 In this case N=3 so, the layers are:
* Presentation Layer
* Application Layer
*  Data Layer

 Each layer holds a specific responsibility and contains interfaces to communicate with the subsequent layer. The data flow between the layers is bi-directional, which means data can move back and forth between different layers to fulfil a request.
 
This architecture is also highly scalable since we can add additional application servers to the application layer. Due to the usage of Node.js for application layer, the single application server itself can cater to many requests at once.
 
Since N-tier architecture is based on separation of concerns and modularity, the coupling between
 client and the server is low, and therefore, the system is easier to test, correct, maintain, and extend.
 
In this project, the application layer fetches data from the database and returns it as JSON. The use of JSON, nowadays, makes our application layer highly interoperable, allowing this web system to be replicated as mobile applications as well using nothing but the same application server.


### Target Users
 * Project Managers
    * Goals
        * To be able to check on Project progress.
        * Keep the budget and schedule under surveillance
        * Be able to communicate with other members   

 * Developers
    * Goals
        * Be able to view projects they are currently working on.
        * Be able to open/close issues related to a bug in the project
        * Be able to to communicate with other team members.
        * Be able to observe task completed task and pending tasks.

 * Quality Analysts / Tester
    * Goals
        * Audit the software quality
        * Report any bugs
        * Communicate with feature developer and owner.



<h2>Submission by</h2>


 Name  | Roll Number
-----  | -----------
ZEESHAN ALI HAMDANI | SP18-BSE-060
