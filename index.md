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
* [Application design](#application-design)
  * [Directory structure](#directory-structure)
  * [Import conventions](#import-conventions)
  * [Naming conventions](#naming-conventions)
  * [Data model](#data-model)
  * [CSS](#css)
  * [Routing](#routing)
  * [Authentication](#authentication)
  * [Authorization](#authorization)
  * [Configuration](#configuration)
  * [Quality Assurance](#quality-assurance)
    * [ESLint](#eslint)
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
<img width="1651" alt="uhvibe_edit-profile_page" src="https://user-images.githubusercontent.com/23148470/33931645-b2ab5a9e-df94-11e7-8896-b07eefa4ada1.png">

### User Profile

The user profile page allows the user to view their current profile information.
<img width="1650" alt="uhvibe_user-profile_page" src="https://user-images.githubusercontent.com/23148470/33931537-646ba1ea-df94-11e7-9430-85e77e571155.png">

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

# Application Design

## Directory structure

The top-level directory structure of UHvibe contains:

```
app/        # holds the application source files for Meteor
config/     # holds settings.development.json, a configuration file
.gitignore  # don't commit IntelliJ project files, node_modules, and settings.production.json
```

This directory structure allows us to separate the configuration files in config/ directory from the actial appp files in the app/ directory.

The app/ directory has this top-level structure:

```
client/
  lib/           # holds Semantic UI files.
  head.html      # the <head>, the meta data
  main.js        # import all the client-side html and js files. 

imports/
  api/           # Define collection processing code (client + server side)
    base/
    interest/
    message/
    profile/
  startup/       # Define code to run when system starts up (client-only, server-only)
    client/        
    server/        
  ui/
    components/  # templates that appear inside a page template.
    layouts/     # Layouts contain common elements to all pages (i.e. menubar and footer)
    pages/       # Pages are navigated to by FlowRouter routes.
    stylesheets/ # CSS customizations, if any.

node_modules/    # managed by Meteor

private/
  database/      # holds the JSON file used to initialize the database on startup.

public/          
  images/        # holds static images for landing page and predefined sample users.
  
server/
   main.js       # import all the server-side js files.
```

## Import conventions

All application code exists in the imports/ directory. Our method uses client/main.js and server/main.js to import the code appropriate for the client and server in an appropriate order.

In this method, every imports/ subdirectory containing any Javascript or HTML files has a top-level index.js file that is responsible for importing all files in its associated directory.   

Then, client/main.js and server/main.js are responsible for importing all the directories containing code they need. Here is the contents of client/main.js:

```
import '/imports/startup/client';
import '/imports/ui/components/form-controls';
import '/imports/ui/components/directory';
import '/imports/ui/components/user';
import '/imports/ui/components/landing';
import '/imports/ui/layouts/directory';
import '/imports/ui/layouts/landing';
import '/imports/ui/layouts/shared';
import '/imports/ui/layouts/user';
import '/imports/ui/pages/filter';
import '/imports/ui/pages/landing';
import '/imports/ui/pages/user';
import '/imports/ui/pages/learnmore';
import '/imports/ui/pages/messages';
import '/imports/ui/pages/profile';
import '/imports/ui/stylesheets/style.css';
import '/imports/api/base';
import '/imports/api/profile';
import '/imports/api/interest';
import '/imports/api/message'
```

Here is the contents of server/main.js:

```
import '/imports/startup/server';
import '/imports/api/base';
import '/imports/api/profile';
import '/imports/api/interest';
import '/imports/api/message'; 
```

All lines invoke the index.js file in the specified directory except for style.css

We use this approach to make it simple to understand what code is loaded and in what order, and to simplify debugging when some code or templates do not appear to be loaded.  In our approach, there are only two places to look for top-level imports: the main.js files in client/ and server/, and the index.js files in import subdirectories. 

Note that this two-level import structure ensures that all code and templates are loaded, but does not ensure that the symbols needed in a given file are accessible.  So, for example, a symbol bound to a collection still needs to be imported into any file that references it. 
 
## Naming conventions

This system adopts the following naming conventions:

  * Files and directories are named in all lowercase, with words separated by hyphens. Example: accounts-config.js
  * "Global" Javascript variables (such as collections) are capitalized. Example: Profiles.
  * Other Javascript variables are camel-case. Example: collectionList.
  * Templates representing pages are capitalized, with words separated by underscores. Example: Directory_Page. The files for this template are lower case, with hyphens rather than underscore. Example: directory-page.html, directory-page.js.
  * Routes to pages are named the same as their corresponding page. Example: Landing_Page.

## Data model

The UHvibe data model is implemented by three Javascript classes: [InterestCollection](https://github.com/UHvibe/UHvibe/blob/master/app/imports/api/interest/InterestCollection.js), [MessageCollection](https://github.com/UHvibe/UHvibe/tree/master/app/imports/api/message), and [ProfileCollection](https://github.com/UHvibe/UHvibe/blob/master/app/imports/api/profile/ProfileCollection.js). Both of these classes encapsulate a MongoDB collection with the same name and export a single variable (Interests, Message, Profiles)that provides access to that collection. 

Any part of the system that manipulates the UHvibe data model imports the Interests, Messages, or Profiles variable, and invokes methods of that class to get or set data.

There are many common operations on MongoDB collections. To simplify the implementation, the InterestCollection, MessageCollection, and ProfileCollection classes inherit from the [BaseCollection](https://github.com/UHvibe/UHvibe/blob/master/app/imports/api/base/BaseCollection.js) class.

The [BaseUtilities](https://github.com/UHvibe/UHvibe/blob/master/app/imports/api/base/BaseUtilities.js) file contains functions that operate across both classes. 

## CSS

The application uses the [Semantic UI](http://semantic-ui.com/) CSS framework. To learn more about the Semantic UI theme integration with Meteor, see [Semantic-UI-Meteor](https://github.com/Semantic-Org/Semantic-UI-Meteor).

The Semantic UI theme files are located in [app/client/lib/semantic-ui](https://github.com/ics-software-engineering/meteor-application-template/tree/master/app/client/lib/semantic-ui) directory. Because they are located in the client/ directory and not the imports/ directory, they do not need to be explicitly imported to be loaded. (Meteor automatically loads all files into the client that are located in the client/ directory). 

Note that the user pages contain a menu fixed to the top of the page, and thus the body element needs to have padding attached to it.  However, the landing page does not have a menu, and thus no padding should be attached to the body element on that page. To accomplish this, the [router](https://github.com/UHvibe/UHvibe/blob/master/app/imports/startup/client/router.js) uses "triggers" to add an remove the appropriate classes from the body element when a page is visited and then left by the user. 

## Routing

For display and navigation among its four pages, the application uses [Flow Router](https://github.com/kadirahq/flow-router).

Routing is defined in [imports/startup/client/router.js](https://github.com/ics-software-engineering/meteor-application-template/blob/master/app/imports/startup/client/router.js).

UHvibe defines the following routes:

  * The `/` route goes to the public landing page.
  * The `/learnmore` route goes to the public learn more page
  * The `/<user>/createProfile` route goes to the create profile page associated with `<user>`, which is the UH account name.
  * The `/<user>/editProfile` route goes to the create profile page associated with `<user>`, which is the UH account name.
  * The `/<user>/profile` route goes to the user profile page associated with `<user>`, which is the UH account name.
  * The `/<user>/search` route goes to the search page, which contains user profiles, associated with `<user>`, which is the UH account name.
  * The `/<user>/messages` route goes to the messages page associated with `<user>`, which is the UH account name.
  * The `/<user>/messages/readMessage/<messageID>` route goes to the read message page associated with `<user>`, which is the UH account name, and `<messageID>`, which is the specfic and unique id of each message.
  * The `/<user>/messages/sendMessage/<messageID>` route goes to the send message page associated with `<user>`, which is the UH account name, and `<messageID>`, which is the specfic and unique id of each message.

## Authentication

For authentication, the application uses the University of Hawaii CAS test server, and follows the approach shown in [meteor-example-uh-cas](http://ics-software-engineering.github.io/meteor-example-uh-cas/).

When the application is run, the CAS configuration information must be present in a configuration file such as  [config/settings.development.json](https://github.com/ics-software-engineering/meteor-application-template/blob/master/config/settings.development.json). 

Anyone with a UH account can login and use UHvibe to create a profile. 

## Authorization

The landing and learn more pages have a public access.

The create profile, edit profile, user profile, search, and message pages require authorization: you must be logged in (i.e. authenticated) through the UH test CAS server, and the authenticated username returned by CAS must match the username specified in the URL.  So, for example, only the authenticated user `testuser` can access the pages `http://localhost:3000/testuser/createProfile` and etc.

To prevent people from accessing pages they are not authorized to visit, template-based authorization is used following the recommendations in [Implementing Auth Logic and Permissions](https://kadira.io/academy/meteor-routing-guide/content/implementing-auth-logic-and-permissions). 

The application implements template-based authorization using an If_Authorized template, defined in [If_Authorized.html](https://github.com/UHvibe/UHvibe/blob/master/app/imports/ui/layouts/user/if-authorized.html) and [If_Authorized.js](https://github.com/UHvibe/UHvibe/blob/master/app/imports/ui/layouts/user/if-authorized.js).

## Configuration

The [config](https://github.com/UHvibe/UHvibe/tree/master/config) directory is intended to hold settings files.  The repository contains one file: [config/settings.development.json](https://github.com/UHvibe/UHvibe/blob/master/config/settings.development.json).

The [.gitignore](https://github.com/UHvibe/UHvibe/blob/master/.gitignore) file prevents a file named settings.production.json from being committed to the repository. So, if you are deploying the application, you can put settings in a file named settings.production.json and it will not be committed.

UHvibe checks on startup to see if it has an empty database in [initialize-database.js](https://github.com/UHvibe/UHvibe/blob/master/app/imports/startup/server/initialize-database.js), and if so, loads the file specified in the configuration file, such as [settings.development.json](https://github.com/UHvibe/UHvibe/blob/master/config/settings.development.json).  For development purposes, a sample initialization for this database is in [initial-collection-data.json](https://github.com/UHvibe/UHvibe/blob/master/app/private/database/initial-collection-data.json).

## Quality Assurance

### ESLint

UHvibe includes a [.eslintrc](https://github.com/UHvibe/UHvibe/blob/master/app/.eslintrc) file to define the coding style adhered to in this application. You can invoke ESLint from the command line as follows:

```
meteor npm run lint
```

ESLint should run without generating any errors.  

It's significantly easier to do development with ESLint integrated directly into your IDE (such as IntelliJ).

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
