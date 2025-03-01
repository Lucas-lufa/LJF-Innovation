*Aaron: This is great, I like the structure that you've given and it's very clearly laid out. For the gap analysis I've never thought of literally doing a here's where we are, where we want to be set up for each. That said you have actually gone a little too much into detail if anything. But you have it so keep it! :D The solutions choices and comparisons are the "body" of this report. This is context and background stuff to set and refer to. Great work so far though!*

# Solutions report


## Executive summery

## Overview

The Alumni Project is a tool to facilitate community. This will be done through having a channel where past and present students can be in contact, network, organise events and participate. Thing that will flow from it meaningful work opportunities, mentoring and learning opportunities and cross discipline collaboration to counteract the ill effects of solo potentially creating innovation. We will start with a narrow scope of ICT but want to expand to all disciplines TAFE offers.

## Business Objectives (high level – Strategic plan?) 

### For all students

Networking Opportunities 
Have platform for students to connect with peers, alumni, and lectures beyond their course duration, to help professional and personal networking.


Streamline Communication 
A cohesive, easy to use that can be secure communication system. For students to find study groups, access mentorship opportunities, or stay updated on relevant information from NMTAFE.


Alumni Engagement
Have engagement from alumni, for those that are interested giving potential benefits for current students.
 

Giving Back 
Alumni involvement in volunteer or mentorship programs. This will help both parties get a deeper understanding if we are able to facilitate.


Secure Alumni Database
Accurate and complete alumni information to help with effective communication and engagement.

### For new students 

Schedule
Balancing coursework, extracurricular activities, and personal life without established routines or advice. 
 

Study Group Formation 
difficulty finding like-minded peers to form study groups for effective learning. 
 

Making Friends 
Struggling to build social connections and find a sense of belonging.

### Factually

Avenue for feedback
Has potential to get better quality feed back because people could report how things worked out after left but might suffer from small sample size.


Avenue for opportunity
I could be a better way to have opportunities disseminated from industry contact TAFE already has or from alumni.

## Existing software or considerations

The only solutions that is being employed are adhoc social media like linkedin or chat groups. Some ready made solutions are 
graduway https://gravyty.com/graduway/ ,
Personify https://personifycorp.com/ , 
hivebrite https://hivebrite.io/alumni-engagement-platform , 
almabase https://www.almabase.com/ ,

## Gap analysis

### For all students

Current State
Limited Networking Opportunities 
Students lack a dedicated platform to connect with peers, alumni, and lectures beyond their course duration, hindering professional and personal networking.  

Desired State
Networking Opportunities 
Have platform for students to connect with peers, alumni, and lectures beyond their course duration, to help professional and personal networking.


Current State
Disjointed Communication 
The current communication system is fragmented, making it difficult for students to find study groups, access mentorship opportunities, or stay updated on relevant information from NMTAFE. 

Desired State
Streamline Communication 
A cohesive, easy to use that can be secure communication system. For students to find study groups, access mentorship opportunities, or stay updated on relevant information from NMTAFE.


Current State
Limited Alumni Engagement 
These might be a low level of engagement from alumni, reducing the potential benefits for current students.

Desired State
Alumni Engagement
Have engagement from alumni, for those that are interested giving potential benefits for current students.


Current State
Difficulty Giving Back 
Barriers to alumni involvement in volunteer or mentorship programs. 

Desired State
Giving Back 
Alumni involvement in volunteer or mentorship programs. This will help both parties get a deeper understanding if we are able to facilitate.


Current State
Outdated Alumni Database 
inaccurate or incomplete alumni information hinders effective communication and engagement.  

Desired State
Secure Alumni Database
Accurate and complete alumni information to help with effective communication and engagement.

### For new students 

Current State
Time Management Struggles 

Desired State
Schedule
Balancing coursework, extracurricular activities, and personal life without established routines or advice. Maybe just linking in with what is there, an extra funnel into existing services.


Current State
Study Group Formation 
difficulty finding like-minded peers to form study groups for effective learning.

Desired State
Study Group Formation 
facilitate finding like-minded peers to form study groups for effective learning.


Current State
Making Friends 
Struggling to build social connections and find a sense of belonging.

Desired State
facilitate to build social connections and find a sense of belonging, while reducing the negative parts of socialising like bulling.


### Factually

Current State
Is good already with lecture culture and the TAFE intuition of soliciting feedback and accepting unsolicited feedback. 

Desired State
Avenue for feedback to feed into what is already there.
Has potential to get better quality feed back because people could report how things worked out after left but might suffer from small sample size.


Current State
can be patchy, I have heard of some people getting job placements and internship but not sure how common it is.

Desired State
Avenue for opportunity
I could be a better way to have opportunities disseminated from industry contact TAFE already has or from alumni.

### Strengths Weakness Opportunities Threats

#### Strengths

One place to go to find people in TAFE alumni.

#### Weakness

An extra thing to open.

#### Opportunities

Networking between members of the alumni.
Volunteering
Mentoring
Communication

#### Threats

Data honeypot
academic misconduct
Bullying
Staking

## Solutions

Alumni need to reach as many people as posable not just where the biggest audiences is on the same hand it needs to be usable not just working. Splitting the project in front, back and data. This should help the project be more maintainable and help it succeed in the long run at no extra effort except some planning. All three parts can be done with bespoke, a framework or with something off the shelf. Practically at our scale the front can be done bespoke or with a framework the back can be done with a framework or off the shelf and the data is really only off the shelf.

If we are having a client installed locally and not just web what can be do to make the user experience better? Not having to download user interface components, having post and feed history so there is something to look at if slow to load or offline, It could also have chat history, friends contact and details of groups that you are a member.

local install
ui components
feed or feeds history
posts history
chat history
shared data about groups and people. members and Friends or general?
documents

### Frontend

what is needed from the frontend
 To fit on desktop and mobile be performant
 the ui will change as we better understand what is needed for the ux
how can we do what is needed
A website, native client and framework cross platform.

 A web site that is mobile first or a progressive web application.
Having a mobile first web site or progressive web application will be the simplest way to have a frontend, no matter what we end with it will useful for testing the Backend.
It is quick and easy to make anything with html and css but to make something good is time consuming. If their device runs a browser will have access to Alumni. Problems can come with how different browsers implement internet specifications.
changing the ui will only be done once for each redesign.

 a native client for each platform.
can give the best results.
will require expertise in for each platform.
maintaining the different platforms and keeping them similar will take alot of work.

 a framework that dose cross platform.
frameworks have a style when it comes to ui completely different applications made with the same framework look similar.
changing the ui will only be done once for each redesign.

contrast
pick

The things we need from the frontend are to be cross platform, we want to reach as many people as posable. Easily prototyped, what we ultimately want is a great user experience the user interface (UI) will change as we learn more about how Alumni is used. There are three ways I see of achieving these requirements, One have a web interface with mobile first or a progressive web application, two have a native client for each platform, three use a framework that dose cross platform.

A website is easiest to get up and running, to get something really good can be time consuming. If changes need to be made to the UI only the cascading style sheets for each screen size is the only unique code the rest is shared so will be easy to maintain and update. For testing of the application programmable interface (API) a simple website will be needed, at least in the early stages before the UI is builded. If installation is require for a feature progressive web application (PWA) is a potential fix for this.

Building a native application for each platform has the potential of the best experience because it can be tailored to each platform and can take advantage of what they offer. Building each will take specific skill either alot of people, one per platform, or alot of time so a person can learn multiple. It will be hard to keep any UI changes synced between platforms after prototyped even with the appropriate people power and skill.

Using a framework that is cross platform with writing once will help considerably. Having the framework do the work of making applications native will mean that development and maintenance isn't effected by the amount of platforms supported. Also as we better understand how people use it we can improve the user experience (UX) by changing the UI and these changes will flow on to all versions. One of the down sides of
frameworks have a style and often things made with the same framework look similar but this might not matter.

From the three outlines I think going with a framework is the most balanced. A website frontend would be the easiest but might not be the most polished on mobile platforms. Having a native client on every platform would give the best results but would take alot of skill and work to build and maintain. Going with a framework will get the benefits of making native application without all the labor overhead and make a more polished user experience than a website alone.


### Backend

Laravel
build-in security.
fast launch time of applications.
session-based authorization and authentication.
Easy data management.
middleware.
routing.