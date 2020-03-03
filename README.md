# robin
We plan to build an Application Tracking System micro-service that will be used for analyzing and processing the in-house applications that we recieve. We will be using Python and Django backend to build the enitire system. 

It will consist of 2 major components:

# Form Builder Function in Python

We will have a form builder in our code that will be creating the form which directly feeds the data recieved to the evaluation model in real time. We will also have a user directory where the user has to create an account to log into and fill out the application for BUILD and come back and check the application status. We will be using the form-builder libraries provided in the Django framework to have a questionare that includes questions of various types. 

# Application Parsing and Evaluation 

The main component of the Application Tracking System is having a fairly simple Naturak Language Processing model parse through the long text answers from the applications and assigning a likely score to the application on how good a candidate is and provide some intelligent feedback. We plan to rank the application by this algortithm so it makes the grading and interview process much easier. 
