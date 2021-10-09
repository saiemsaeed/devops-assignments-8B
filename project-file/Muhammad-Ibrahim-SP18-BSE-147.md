Project Name CMMI Automation V2.0

Project Owner NESCOM

Full Name Muhammad Ibrahim

Roll Number SP18-BSE-147

Project Details

Description This project is an industrial project given to us by nescom. This project will allow the organization to improve the quality of their product. It combines project management, customer relationship (CRM) and reporting into an all-in-one solution.This software is the improved version of the existing CMMI V1.3 in which agile was introduced into its workflow to improve performance. In this project we are required to implement 12 knownledge areas of cmmi out of 24. These areas are Peer Reviews, Requirement Development Management, Technical Solution, Verification & Validation, Product Integration and Process Quality Assurance, Planning, Estimating, Monitor and Control, Process Asset Development, Configuration Management, Supplier Agreement Management.

Technology Stack This project will be built using MongoDB, Express Js, React Js, Node Js (MERN) Stack.

Tools VS Code GitHub Mongo Compass Postman MS Office Deployment or Distribution Strategy Due to security issues imposed by the Nescom, this software will be deployed on the intranet of the organization by using nodes and routes.

Architecture This project utilizes the N-tier architecture which is used most commonly with web applications because of its ability to decompose the application into logical and physical layers Each layer holds a specific responsibility and contains interfaces to communicate with the subsequent layer. The data flow between the layers is bi-directional, which means data can move back and forth between different layers to fulfil a request. This architecture is also highly scalable since we can add additional application servers to the application layer. Due to the usage of Node.js for application layer, the single application server itself can cater to many requests at once. Since N-tier architecture is based on separation of concerns and modularity, the coupling between client and the server is low, and therefore, the system is easier to test, correct, maintain, and extend. In this project, the application layer fetches data from the database and returns it as JSON. The use of JSON, nowadays, makes our application layer highly interoperable, allowing this web system to be replicated as mobile applications as well using nothing but the same application server

Target Users Admin will use this software to create a project template and assign project manager. Admin would also be able to add user. Project Manager will use this software to view the progress of different project that are assigned to him. He would be able to assign the task to team members and resolve issues if there are any. Team leader will use this software to manage his team members and help them in their tasks and queries. Developer will use this software to view his task and complete them within given time. Tester will use this software to test the documents and report a bug if found.
