techON

Supervisor

### Full Name

TAQI RAZA JAFFREY

### Roll Number

SP18-BSE-127

## Project Details

### Description

techON is basically a web application which aims to make every teacher in the world searchable in their local area and online and to make sure that every student gets a suitable teacher as soon as possible when required. Especially in Covid like situation, there is a need of such platform where students can easily have access to teachers as students have been facing a lot of difficulty in understanding several subjects and topics in online group lectures. techON will provide that platform and will have two main users, Students and Teachers from all over the world. Students and teachers will be able to connect with each other through the chat system present within the website. Students will be able to pay directly to the teachers within the system. Only student and teacher are involved in deciding the terms, work to be done and the payment method. techON will also provide the Location service, through which students will be able to locate teachers nearby or in a specific area Teachers will also have a rating graph, which will be the result of the feedback and ratings provided by the students.A feature of web analytics will be present depicting the graphical visualization of the performance of teachers and various other factors. Based on the feedback and reviews of the students, each teacher will have a graphical representation of their performance.

### Technology Stack


| Technology    | Second Header    |
| ------------- | -------------    |
|mongodb        | Database         |
|Angular        | Web Front-end    |
|NodeJs         | Backend          |
|ExpressJs      | Backend framework|

### Deployment or Distribution Strategy

Our system is deployed heroku both frontend and the backend.


### Architecture

System Architecture is basically a conceptual model that defines the structure, behavior and view of the system. It is formal representation of the system and provide infrastructure for the system. There is different architecture followed. 

techON will follow Client server architecture model at higher level. The upper layer in Server call database layer which will have all models that map to database. Next layer is service layer which hold all mean functionality. After that have controller layer which took request from client and delegate it to service layer. In parallel of these layers have DTOS (Data Transform Object) layer which proper map data from database.

DTOS gave only required data to controller which requested by client. Client architecture is a web-based application which will be used to interact with the backend and database.




### Target Users

Tergeted users will be the student and teacher.
For teacher, they can offer their services as a teacher and can get hired by the student.
For Student, they can hire student teacher of any subject in which they are having difficulties.