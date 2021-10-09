#Project Name:
  EmoBot (Mental Health Assistant)
  
#Project Owner:
  Khadeeja Gilani, Midhat Zahra 

##Roll Number:
  SP18-BSE-114

#Project Details:
##Description:
  EmoBot is an application created to provide users with a platform to share their mental health issues and get therapy and meditation recommendations according to that. User can have a conversation with the chatbot and share their concerns and get a solution after the bot predicts their mental health issue and mood etc. The user can also perform Cognitive Behavioural Therapies that the system provides. Furthermore, a user can track their mood history with daily and average statics visualized in the form of graphs. They can also view their health progress according to the therapy results and health tests. If there are users who have other severe mental health issues that our system cannot handle, the user is redirected to the locate therapist page to locate nearby therapists on google map to get professional help.

#Technology Stack:
  Python is used for back-end programming for training the chatbot and other machine learning algorithms used in providing recommendations.
  Flutter is used for user interface in front-end development.
  Firebase Firestore is used as a data store for our application.

#Deployment or Distribution Strategy:
  An android application is developed so it will be deployed on Google Play Store.

#Architecture:
  Our system comprises of eight modules. Chatbot module is developed on python by using deep learning model and an api is created (currently on localhost) to get the responses of user messages sent from the front-end as post requests. Mental health tests and Recommendations for meditations are also written in python using machine learning algorithms such as Collaborative and Content filtering. Mood Log and Health progress is displayed in the form of graphs and charts by using data visualization. Different therapies are provided by the chatbot on the chat or a separate user interface where the user can perform them. Google maps and places api is used to search nearby therapists according to the users' current location by displaying markers and list of nearby therapists in a specified radius.

#Target Users:
  Users with mental health issues such as depression and anxiety.
