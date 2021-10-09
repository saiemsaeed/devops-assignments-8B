# Madadgar

## Project Owner
### Full Name
Namra Sheikh  

### Roll Number
SP18-BSE-097

## Project Details
### Description

Our system is a web application that will provide an opportunity to people who are seeking jobs.
The system is designed for people who are looking for service providers to get their work done in time. The system will allow service providers to provide services. Our system will provide direct communication between the customers and services without the inclusion of any third party. Our system is cost-effective and efficient. The system will manage both service provider and customer accounts. Customers can request service by posting a job. The system will generate a notification when the job is posted by a customer, or accepted by any service provider. When a customer provides feedback or rating to the service provider, the system sends a notification to the service provider. Customers can chat with service providers using this system. Admin receives notification when a complaint is filed by a customer in case of a scam. Moreover, there will be a question/answer portal, where customers can ask questions without actually hiring any service provider. The customer gets a new notification when the service provider provides an answer to his question. Customers can vote service provider’s answer. To ensure the authenticity of the service providers our system provides profile picture authentication. The system will allow the admin to respond to complaints by either blocking the account of the service provider or deleting it permanently. Admin can keep track of all registered users using this system. Admin can also view system statistics. 

The outcome of our project is a platform where service provider can provide services. Customers can easily hire service provider for their job to be done in time and at reasonable price.


### Technology Stack
  The tools and technologies used for developing this system are Visual studio code (VS code), Visio, MS Word, MongoDB, React, Express, Node.js. Incremental Software Process Model is used for the development of the project. In Incremental model, the system is divided into subsystems which will make it easier for our team to divide the workload and integrate it afterwards. The methodology we are following for this project is procedural as we are developing our website in react. Moreover, we are using functional components of react and also react is not an OOP based language.

### Deployment or Distribution Strategy
  The webiste will be deployed using Firebase Hosting and the REST API will be deployed at Heroku.

### Architecture
In this project, the architecture followed is Model-View-Controller (MVC) which is a software architecture widely used in the development of web applications. The architecture helps keep the code in manageable form. In MVC structure, the functionality is divided into 3 major parts. Each part is implemented and tested independently. 
It separates an application into the following components: 
* Models for handling data and business logic. It is responsible for holding the functions and variables that are involved with what it is representing. It functions more like a class in the OOP.
*	Controllers for handling the user interface and application by taking input from the user, sending it to the model to get the appropriate output and then sending it to the view to display the response to the user 
*	Views for handling graphical user interface objects and presentation. It will contain the markup, CSS, HTML amongst others used in the creation of the web page.

#### User Registration and login Management 
Service provider registration: The service provider will be able to register by providing his personal information, skills, experience, and certification if he claims to be a professional of the field. 
Customer Registration: In this module, the customer’s account will be created using required information such as name, address, location. 
Both the users will use their credential to login to the system.
#### Manage Users’ Account
 Add/remove Skills: Skills the service provider has can be added or removed. Update experience:  service provider can update experience in the profile. Disable Account: users can disable account according to their will. Change personal Information: Both type of users can update their personal information such as name, address, phone no. etc.
#### Manage Services
In this module, customer will post the service and notification will be sent to all nearby work-related service providers according to customer’s location by the customer such as budget and service type. After being notified of the service request, service provider will respond or consider the request and then it will be displayed to the customer. Then customer after viewing the ratings of the service provider will talk to provider using chat or call function of the system and fill a contract form and will hire him.
•	Posting a Job: The customer will be able to post a job request by entering the required information such as job title, description etc. a notification of the job will be sent to the service providers with related skills. Customer will be able to choose if he wants a work to be done physically or online.

•	Rating: once a job is complete the customer can rate the service provider and give feedback.

•	File Complaint: In case of any problem in work done by service provider or in case of fraud committed by service provider, customers can file a complaint about that service provider with proper reasoning and details. After proper investigation, service provider will pay the penalty
####	Question/Answer Portal
Customer can post a question on portal. Service provider can provide answer to customer’s question. Customer can vote service provider’s answer. Service provider can edit, delete his/her answer. Customer can search any question.
####	 Administration Controls
In this module all the feature and controls that an admin can have will be implemented. The administration will receive complaint. Respond to complaints. Restrict accounts based on complaints and can make a statistical analysis of how the website is performing.

Statistical Analysis: all the information about how the website is performing over a certain period of time can be view. The details related to the traffic on the website, can than further be specified to traffic per month, week or year. Number of new registrations, higher rated service providers.
####	In-App Chat:
When service provider accepts a job request, they can chat about the problem and the solution of the problem and any details related to the problem such the charges of the service, time duration, term and conditions of the job.
•	Message: Both type of users will be able send and receive messages over the internet if needed.
####	 Notification generation
Alerts related to job will be generated whenever:
•	Job is posted: the system will generate a notification that will be sent to the service providers with related skilled.
•	Job request is accepted: the system will generate a notification when a job is being responded to and send it to the person who posted the job.
•	Job offer is rejected: when a service provider declines an accepted job offer system notifies the customer. 
•	A complaint is registered: when a complaint is registered system alerts the administration.
•	A complaint is responded to: when administration responds to the complaints the system notifies the customer.
•	Answer is posted: The customer receives a notification when a service provider answers his question 
•	Answer is voted: The system notifies service provider when customer votes his answer.
####	Facial Unlock
The users will able to unlock the application using the mechanism of face detection. This will increase the security of the application. One the user has signed up he can change the unlock setting to facial unlock. Users’ web camera will be used to unlock the application.
####	Profile Picture Validation using AI
The system will check if the profile picture uploaded by the service provider is Valid:
Validation criteria:
•	It is a picture of a human being.
•	Eyes are visible and clear.
•	The picture is not a side pose.
•	The picture is not blur.
•	The picture is a close up of face.
•	The nose and the lips are visible.

### Target Users
 * Job seekers
 * Organizations' HR
 * Startup Owners
