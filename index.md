# Table of Contents

* [About UHvibe](#about-uhvibe)
* [User Guide](#user-guide)
  * [Landing Page](#landing-page)
  * [Learn More](#learn-more)
  * [Login](#login)
  * [Create Profile](#create-profile)
  * [Edit Profile](#edit-profile)
  * [User Profile](#user-profile)
  * [Search](#search)
  * [Messages](#messages)
* [Installation](#installation)
* [Development History](#development-history)
  * [Milestone 1](#milestone-1)
  * [Milestone 2](#milestone-2)
* [Feedback](#feedback)
* [Contact Us](#contact-us)
  
# About UHvibe

University of Hawaii has 10 campuses and additional educational and research facilities across the State of Hawaii. Thus, the community is very large and diverse. Unfortunately, there are very little ways to find and connect with others based on their music 'vibe'. UHvibe offers a way to overcome these issues.

[UHvibe](http://uhvibe.meteorapp.com/) is a Meteor application that is designed to help the University of Hawaii community find and connect with others based on their music interests and skills. 

# User Guide

### Landing Page

The user can get information on the web-app by clicking on 'Learn More' of the navigation bar or the user can log in by clicking on the 'LOGIN' button of the navigation bar.
<img width="1632" alt="uhvibe_landing_page" src="https://user-images.githubusercontent.com/23148470/33913696-fbd222c6-df3e-11e7-8fd5-3ff55974cb1f.png">

### Learn More

The user can get information on 'What is the purpose of this app?', 'Why use this app?', and the general features that the app has. If the user/visitor is interested in using the app, they can click on the 'LOGIN' button at the bottom of the page.
<img width="1631" alt="uhvibe_learn-more_page_1" src="https://user-images.githubusercontent.com/23148470/33913719-10efb524-df3f-11e7-8eb3-47395eb5d4f5.png">

<img width="1628" alt="uhvibe_learn-more_page_2" src="https://user-images.githubusercontent.com/23148470/33913725-1cedf0f2-df3f-11e7-9ac3-ea71152e6e4d.png">

<img width="1617" alt="uhvibe_learn-more_page_3" src="https://user-images.githubusercontent.com/23148470/33913733-2671ec32-df3f-11e7-930f-f9de42c3bff2.png">

<img width="1607" alt="uhvibe_learn-more_page_4" src="https://user-images.githubusercontent.com/23148470/33913741-31359c18-df3f-11e7-9e64-b8d819480bf0.png">

### Login

After clicking on the 'LOGIN' button, the user is presented with login page, where they can enter their University of Hawaii username and password.
<img width="1631" alt="uhvibe_login_page" src="https://user-images.githubusercontent.com/23148470/33913764-48316bb8-df3f-11e7-9cf7-0fa5e94d4839.png">

### Create Profile

The user can input their information about themselves and their music interests/skills to allow other users to recognize them in the 'Search' page.
<img width="1625" alt="uhvibe_create-profile_page" src="https://user-images.githubusercontent.com/23148470/33913807-6e3bf51c-df3f-11e7-81a2-0fcfb3fa4fbf.png">

### Edit Profile

If the user decides to change any of their information, they have the option of editing their profile.
<img width="1620" alt="uhvibe_edit-profile_page" src="https://user-images.githubusercontent.com/23148470/33913843-93e54250-df3f-11e7-837a-becf06841cf7.png">

### User Profile

The user profile page allows the user to view their current profile information.
<img width="1624" alt="uhvibe_user-profile_page" src="https://user-images.githubusercontent.com/23148470/33913875-b45a3194-df3f-11e7-8854-2ae6bee03730.png">

### Search

The search page shows all the user profiles. The user has the option of filtering music genre interests to show specific user profiles. There is also an option to message specific users using the messaging feature.
<img width="1625" alt="uhvibe_search-profile_page" src="https://user-images.githubusercontent.com/23148470/33913888-bfec4af6-df3f-11e7-8733-ba301f8d84d3.png">

### Messages

The user is able to view both their received messages and their sent messages. Every message has a 'Read' option, that allows the user to see the contents of the message. New messages are indicated by the 'New' keyword and users are notified of new messages in the navigation bar (a red dot appears next to 'Messages' when you have a new message). Users will also be notified of any unfinished sent messages, which will be indicated by the 'Draft' keyword.
<img width="1622" alt="uhvibe_messages_page" src="https://user-images.githubusercontent.com/23148470/33913919-df9aab7c-df3f-11e7-8be2-55b18ab46f03.png">

<img width="1623" alt="uhvibe_sent-messages_page" src="https://user-images.githubusercontent.com/23148470/33913933-ecedf194-df3f-11e7-9e7b-89090ba962ee.png">

When the user is finished reading their message, they have the option of going back to the mailbox, replying to the message, or deleting the message. If the user clicks on the 'Reply' button, it will bring the user to the 'Send-Message' page, which allows the user to write their message and send it. If the user clicks on the 'Delete' button, a 'confirmation' alert will appear to confirm if the user does, in fact, want to delete the message.
<img width="1619" alt="uhvibe_read-message_page" src="https://user-images.githubusercontent.com/23148470/33913955-f8f8f7fe-df3f-11e7-9338-840dcbcea2d9.png">

<img width="1624" alt="uhvibe_send-message_page" src="https://user-images.githubusercontent.com/23148470/33913961-02a84cbe-df40-11e7-8ddf-61a5308b9f81.png">

# Installation

First, [install Meteor](https://www.meteor.com/install).

Second, [download a copy of UHvibe](https://github.com/UHvibe/UHvibe/archive/master.zip), or clone it using git.
  
Third, cd into the app/ directory and install libraries with:

```
$ meteor npm install
```

Fourth, run the system with:

```
$ meteor npm run start
```

If done correctly, the application will appear at [http://localhost:3000](http://localhost:3000). If you have an account on the UH test CAS server, you can login. 

The UHvibe files were made using an Integrated Developement Environment called IntelliJ IDEA. The files can be modified using your text-editor of choice.

# Development History
### Milestone 1
Milestone 1 started on November 7, 2017 and ended on November 22, 2017.

The goal of this milestone was to create mockup pages of our app. 

Mockup Pages include: 
* Landing Page
* Learn More Page
* Get Started Page
* Profile Form Page
* Search Page

The issues done in Milestone 1 can be seen in [UHvibe Github Project Milestone 1](https://github.com/UHvibe/UHvibe/projects/1). 

<img width="666" alt="ms1-issues-final" src="https://user-images.githubusercontent.com/23148470/33162957-35cd079e-cfd0-11e7-964d-b469eb82e76a.png">

Each issue was implemented in its own branch and was merged into the master branch.

<img width="1186" alt="ms1-network" src="https://user-images.githubusercontent.com/23148470/33163001-5d7b80d6-cfd0-11e7-8190-b7c7505b5895.png">

The issues that are planned in Milestone 2 can be seen in [UHvibe Github Project Milestone 2](https://github.com/UHvibe/UHvibe/projects/2).

### Milestone 2
Milestone started on November 23, 2017 and ended on December 7, 2017.

The goal of this milestone was to continue to increase the functionality and the overall quality of our app.

The issues done in Milestone 2 can be seen in [UHvibe Github Project Milestone 2](https://github.com/UHvibe/UHvibe/projects/2).

# Feedback
### Feedback 1 by C.B.

**Good**:

-The design looks great.

-All the basic functions are available.

-The app was simple to navigate.

**Bad/Improvements**:

-You could add more customization in the user's profile

-Show the whole conversation (the message chain)

-On the homepage, you can have notifications of messages or possibly some other reason, such as an event that is happening in Hawaii that might interest you.

-Create groups and allow users to possibly comment and send puclic messages within the group

**Overall**:

-Expected something bland, but it was cool.

### Feedback 2 by A.E.

**Good**:

-The color choice for the design is really good.

-The various functions are great.

**Bad/Improvements**:

-Maybe add some slack-like channels for a group of users

-Could have users follow or add other users (a friend system)

**Overall**:

-Overall, it was really good. I didn't expect it to be that good. 

#### Feedback 3 by A.O.

Awesome design, especially the front page. I like how they implemented filters and email contact functions and also really like the simple design for profile :)

#### Feedback 4 by Y.C.

- It's cool how only UH students can use the app.

- It's nice how it allows students to make new friends with similar interests.

- The design is nice, everything is organized nicely.

- It would be a good platform for new UH students who want to meet new friends.

#### Feedback 5 by J.C.

**Good**:

-Nice Design

-Nice layout, the functionalities make sense. 

**Bad/Improvements**:

-When I search for people, it would be nice if we can search by input.

-It is a little too much work to cross out the interests to search for people. 

**Overall**:

-Overall, I thought the app was very well thought and created considering that it is a project for school.  

# Contact Us
* Mai Abe: maiabe@hawaii.edu
* Darlene Agbayani: darlene4@hawaii.edu
* Jun Okabe: okabej3@hawaii.edu
