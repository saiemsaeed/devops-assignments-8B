# Project Name
E-Control
## Project Owner
Muhammad Abdul Moeed
### Full Name
Muhammad Abdul Moeed

### Roll Number
SP18-BSE-074

## Project Details

The proposed system will allow the users to bring down their electricity bill by enabling them to monitor the electricity consumption of their appliances on a daily basis. It would show them a statistical analysis derived using the data gathered by the system to minimize the use of and controlling their electricity appliances. It would give users an insight on how much electricity is being consumed by each device and what measures to take to reduce their electricity bill. The app will also give tips and recommendations on how the user can manage electricity resources more efficiently. It will also use a prediction model to predict the total bill expected by the end of the month. 
 
This will result in the user having more control over their electricity consumption. Users will also be able to add more to their savings and will most likely reach their budget limit goal every month in the future.  

To  overcome the gas consumption problem, the system will also present logs and trends of geyser activity and will allow the user to switch the geyser on/off or control it’s temperature using the app. The temperature will also be automatically adjusted depending on the temperature outside detected using sensors. 

### Description
E-Control is an IoT based solution to resolve issues regarding the real-time monitoring of power useage. It also helps you control your gas geyser from mobile app and set schedules, 

### Technology Stack
We are developing TWO stand-alone systems, for tha we have developed two cross-platfrom applications using Flutter framework in dart language. 
    
- Firebase Auth is being used for authentication.
- Firebase storage to store media.
- Firebase CloudFirestore to store user-information.
- FCM for push notifications.

Back-end includes a NodeJS application used to deploy REST API which access the mongoDb Atlas
  - Sends PUSH notfification using Firebase Admin SDK.
  - Schedule tasks using Node Scheduler
  - Using Express to handle the routing and moogose for mongoDb Schema.

We are also developing two stand-alone IoT devices using ESP32.
- Using C++ and PlatformIO.
-  In that we have indivisual tasks running on indivisual kernal level threads on both cores of ESP32. 

  

### Deployment or Distribution Strategy
    NodeJs application is deployed on Heroku, the reason for that is that allows us to set environment variables very easily and it runs free of cost. 

    Firebase is hosting the Database to store user information, and MongoDb atlas to store real-time data because there is no limit to number of reads or rights in MongoDb Atlas. 

    Apple store and Playstore are to be used to deploy both the applications.

    Github is used as to host the repositories of all the modules because how Git allows us to do version controlling very easily.

  
### Architecture
    

  - Our system has to 4 main components. 
    - MongoDb Atlas
    - Firebase
    - Esp32 (Microcontroller)
    - Mobile App
    - NodeJs Server

    The interation between all these components is shown in the figure 


    ![Alt text](https://firebasestorage.googleapis.com/v0/b/travler-da284.appspot.com/o/Picture%201.png?alt=media&token=5584e881-5170-473a-93a7-69922cbb0d2e "Components Interaction")


    - Using HTTP protocols to access the REST Api from the microcontroller.
    - Using TCP socket to communicate between mobile app and microcontroller.  


  
 

### Target Users
Targeted user would be home owners and people who are really concerned about thier electricity bills or people who want to conserve energy in general. 
