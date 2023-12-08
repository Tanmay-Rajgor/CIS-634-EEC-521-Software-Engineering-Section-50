# CIS-634-EEC-521-Software-Engineering-Section-50

# Live Website - Please go through the live website
https://chatrasahaya.org/

# Description
WARNING: This application contains security vulnerabilities. Run it only in a backed-up and sheltered environment (such as a VM with a recent snapshot and host-only networking) and at your own risk, escpecially if you enable some of the advanced options described below!

This software will help the Chatrasahaya to be more efficient in submitting of their requests such as money,food and other needs…and tracking of submission 
on the maps. It also sends the mails to the internal team to check the submissions quickly. The purpose of this project is to computerize all details 
regarding submissions from request us,Users can submit their required needs likes education,financial,Health…from the Request Us for Self /For Others 
Page by using some fields such as Name -- Full Name of the requester , Phone Number -- Phone/mobile Number of the Requester , Location -- The place of 
the request where books,chairs,tables are needed for the schools , Category-- Its was type of the request such as education,financial,
Health Description -- Its was the description/overview of the needs ,  Aaadhar Number -Its was unique identity number of the requester, 
Documents --- Proof of the documents needs to be uploaded here.

# Binaries and hosted versions
If you'd like to try Chatrasahaya but want to skip all of the cool software development stuff, use publicly hosted version, available at https://chatrasahaya.org/ . You will not be able to enable any of the advanced options and this site may not always be available, but it's the easiest way to get started


# Prereqiusites
Chatrasahaya has been developed using Eclipse and designed to run on Wordpress hosted, but since it's a relatively simple python wordrpress app, it should be pretty easy to port it to a different web application server. Here are out-of-the-box requirements:

- Wordpress hosted
- Gravity Forms to store the data
- Gradle 3.0 to build from command line


[Read more about importing Chatrasahaya into machine GitHub here](https://github.com/Tanmay-Rajgor/CIS-634-EEC-521-Software-Engineering-Section-50/tree/main)


# Advanced options
Chatrasahaya original design goals were to create an application that is easy to deploy, very stable and less dangerous (as far as vulnerable web apps go). However, these goals meant that certain attacks couldn’t be a part of it. Because of this, there are advanced user-configurable properties that can enable AltoroJ behaviors which are disabled by default.These enable extra functionality, new cool attacks and demos as well as optional behaviors.

Please see WEB-INF/app.properties file for more information on each property


# REST API
Chatrasahaya has a fairly extensive REST API, which is documented using Swagger. You can find out more about and interact with the provided REST services by clicking on the REST API link in the footer of almost every Chatrasahaya page.


#License
All files found in this project are licensed under the [Apache License 2.0](https://github.com/AppSecDev/AltoroJ/blob/master/LICENSE).
