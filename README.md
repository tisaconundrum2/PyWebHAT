# PyWebHAT
The Qt based PyHAT application but created to be ran in a web client/server environment

## Synopsis

This is a website/application based off of the Qt application that will be designed and ran on the users' machine.

The PyHAT application was designed in Qt, originally a C++ framework, but was boiled down and rebuilt for Python. This framework was a prime candidate because Python has many Machine learning algorithms that are available, so synthesizing the UI with Python Machine Learning is made more possible. 

The only issue with this are it's intrinsic limitations built into it. More specifically the software is harbored on the user's machine. I would like to de-couple the Application from the user's machine and utilize a complete web stack.

The plan is to build a front end Angular/Vue/React website that can be modeled after the original Qt application. All the while we will have python running on a more powerful server or cluster server that is ready to take requests from the website.

This decoupling would allow for faster analyzation of the data that tends to be used, while also bringing some of the popular aesthetics that comes with Web Design; something that the original Qt application sorely lacked.
