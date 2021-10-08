# Student Van Tracking and Transportation System

## Project Owner
### Full Name
Muhammad Noor Ul Ain

### Roll Number
SP18-BSE-124

## Project Details
### Description
School Van Transportation and Tracking system is an android and web application. The purpose of the proposed app is to provide safe and secure transportation to the students. To  achieve this, the system introduces a proper attendance and tracking feature. When a student will get into the van, his/her attendance will be marked, and a notification will be  sent to his/her parent. Parents can also track the real time location of the van. A proper maintenance procedure will be implemented to ensure the good condition of the vehicle  and to avoid any unforeseen circumstances. 

### Technology Stack
  MEAN stack, Node.js , Firebase, Postman, Git, Kotlin (for android development)

### Deployment or Distribution Strategy
  - Play Store is be used to deploy android application.
  - Firebase is used to store the data of the applications. The reason is that firebase provide free cloud hosting with realtime database and authentication. Realtime database         helps the project in realtime tracking.
  - MEAN stack application is deployed on Heroku, the reason for that is that allows us to set environment variables very easily and it runs free of cost. 

### Architecture

Our system has 3 main components.
  - Mobile Application.
  - NodeJS Server
  - Firebase

The communication between these componenets is done through firebase. Both MEAN stack application and Android app uses firebase as a common point. NodeJS server uses Firebase Realtime Database URL as a REST endpoint. This is done through HTTPS. Firebase only responds to encrypted traffic so that data remains safe.
Mobile application uses firebase object to access firebase database.


### Target Users
The system provides services to students of schools, colleges and universities. It also targets parents who can track their child's location, and drivers who can see information of students to be picked and dropped. School transportation providers are also targeted.
