# Project Name

E-Control

## Project Owners

Khadija Aman Khan
Muhammad Abdul Moeed

### Roll Number

SP18-BSE-065
SP18-BSE-074

## Project Details

### Description

E-Control is an energy monitoring and control cross-platform application. It consists of two main modules under the monitoring category; detection and prediction module. The detection module will use a machine learning algorithm to detect an electrical devices connected around the house. The prediction module will use a different machine learning algorithm that will be able to predict the next electricty bill. The controlling module, as the name suggests, will allow users to control certain devices around the house.

In addition, it also has a stand-alone cross-platform application for monitoring and control of gas geyser.

### Technology Stack

- Flutter framework (in Dart language) is being used to build the two stand-alone cross-platform mobile applications; one for electrcity and the other for geyser.
- MERN (MongoDB, Express, React, Node) stack will be used to develop the websites.
- Express along with NodeJS will also be used to create Rest API and manage its routing.
- MongoDB Atlas both will be used to store real-time electrcity data.
- C++ and Platform IO will be used to implement Micro-controller code.
- Tensorflow will be used to train the AI models being used for detection and prediction modules.
- Firebase Cloud Messaging (FCM) for push notifications.
- Firebase Auth for user authentication.
- Firebase Cloud Firestore will be used to store user information.

### Deployment or Distribution Strategy

- The two cross-platform applications will be deployed on Google Playstore and Apple Store so that it is available for users of both platforms.
- Firebase is hosting database to store user information.
- MongoDB Atlas is hosting real-time data storage as it allows unlimited writes and reads.
- Heroku is being used to host the NodeJS application becuase it is flexible, easy to use and is free of cost.
- For project version control purposes GitHub is being used to host the project repositories.
- Micro-controller code is deployed on Esp32 because it has integrated WiFi.

### Architecture

For the mobile applications, MVVM architecture is being followed consisting of Views (screen code using flutter), ViewModel (which consists of the data that will be displayed on the screen and also manages any state changes of the data) and Services (which has all the business logic). The flutter stacked architecture package, which is based on the MVVM architecture, is being used to properly divide the system to reflect the MVVM architecture.

As for the system as a whole, the main components include:

- Esp32 Micro-controller
- Mobile application
- NodeJS application
- Firebase
- MongoDB Atlas
- NodeJS Server

The micro-controller requests for resources from the NodeJS server Rest APIs using HTTP protocol. The micro-contoller is communicating with the mobile application using a TCP socket where both the components act as server and client. The illustration below we created for our FYP explains the overall interaction between all the components involved.

![Alt text](https://firebasestorage.googleapis.com/v0/b/travler-da284.appspot.com/o/Picture%201.png?alt=media&token=5584e881-5170-473a-93a7-69922cbb0d2e "System Architecture")

### Target Users

Target users include users who are interested in having more control over their energy consumption of their house. These are users who are looking to monitor their daily, weekly, monthly or yearly consumption and also being able to take action to control it.
