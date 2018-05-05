## The Artists
From our humble beginnings as college freshman to our divine status as college juniors, we the artists have been working together to tackle extreme scenarios and homework questions. We are all Computer Engineering majors and plan to continue our studies further in the field of Software Engineering. Our team members along with our taglines are as follows:
* Barry Abe - Maui Local, fun-loving guy.
* Ky Ho - Mango lover, Love Live! enthusiast.
* Sean Teramae - Plays too much Hearthstone.

# Overview
Questboards is an application designed to further mobilize the able student body for short term 'Quests' that benefit both the community and a student's paycheck. Our initial thought was to create the application as a Quest system, similar to the video games that we all play. In our application, users, or adventurers, are able to place and take on Quests. These Quests are defined by and paid for by other users on the site. Quests would be an easy way to get quick tasks done.

# Application Found Here!
Questboards is deployed here: [QuestBoards](https://questboards.meteorapp.com)

# Guided Tour
1. When first landing on the QuestBoards Home Page, the user is greeted with a welcoming two option screen, where the user can either search for available Quests or create a listing. If the user is not logged in and tries to create a listing, they will be prompted to log in.
![Front Page](/doc/home2.PNG)

2. If the user chooses to search for an available Quest, they are taken to the Quest listings page, which gives a rundown of all available Quests and pending Quests. Pending Quests are waiting for the owner to select the user for the Quest. On this page, the user is able to click on a Quest to learn more details about the Quest.
![Listing](/doc/listing.PNG)

3. If the user chooses to create a Quest, they are taken to the Quest Create page. The Quest create page will then prompt the owner to post the appropriate Quest details.
![Create Quest](/doc/createQuest.png)

4. On the Quest info page, the user can see what the Quest entails. If the user chooses to, they can hit the request button at the bottom of the page to submit their candidacy for the Quest. If you are the Quest owner, you can change the details of the Quest by hitting the Edit Quest! button at the top of the page.
![Quest Info](/doc/questInfo.PNG)

## Milestone 3
This Milestone can be found here: [Github](https://github.com/the-artists/quest-boards/projects/3)
This Milestone started on April 24, 2018 and ended on May 4, 2018.
This Milestone mainly focused on adding the final bits of functionality to create a working application for assigning users to a Quest. Through this milestone, users are now able to request access for Quests and Quest progress is now tracked automatically.

#### Milestone 3 Feedback
* Good work setting up Quests, need more vector graphics.
* If I was using this site, I would want a 3rd party to oversee communications.
* How would the user be able to protest unpaid Quests?
* Adding more information to Profile could be useful.
* Support for notifications is a must.

## Initial User Study
*Names Hidden*
This study was conducted by surveying a group of friends that attend the University of Hawaii. A computer was given to them and we asked what they thought of the site. A summary is found below.
* Needs some work to find users for my Quest listing.
* I think it's good but could use improvements in the Quest information page.
* The user should be able to search for available Quests based on keyword.
* Policy page could be removed from the navbar and put into the footer.
* Good work on building the support for Quests but I need to be able to edit my profile.

## Developer Guide
### Installation

First, [install Meteor](https://www.meteor.com/install).

Second, [download a copy of QuestBoards](https://github.com/the-artists/quest-boards/archive/master.zip), or clone it using git.
  
Third, cd into the app/ directory and install libraries with:

```
$ meteor npm install
```

Fourth, run the system with:

```
$ meteor npm run start
```

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000).

### Modifying the System
For this project, the majority of custom pages lies under the imports/ directory. In the imports/ directory, the api/ folder holds the code necessary to populate the front-end website with appropriate data. The startup/ folder contains instructions on what to do when the server is first initialized. The ui/ folder holds the custom React components that were used to construct the application. 

To implement new test data, you can modify the config/settings.development.json file to prepare new test cases. Simply follow the already defined structure under defaultQuests.

## Goals
* Create a simple method for users to get paid to do short term jobs.
* Make it easier to delegate small, tedious tasks. 
* Connect users through job board listings (Quests).
* Define a status for jobs (open, pending, closed) to signify job availability. 
* Users can access their profile to see their associated quests.

## Future Goals
After implementing the basic functionality, here are ideas for more advanced features:

* Rating system for users in terms of reliability and job satisfaction.
* See previous job completion history
* Suggest other users for job
* Push notifications
* Venmo/Apple Pay support

## Milestone 2
This Milestone can be found here: [Github](https://github.com/the-artists/quest-boards/projects/2)
This Milestone started on April 12, 2018 and ended on April 24, 2018.

For Milestone 2, we focused on implementing the back-end and linking the data necessary for functionality on the front-end side. We continued to develop new front-end components during this time as well.

Screenshots of the template pages are found below:
## Milestone 1
This Milestone can be found here: [Github](https://github.com/the-artists/quest-boards/projects/1)
This Milestone started on April 3, 2018 and ended on April 12, 2018.

For Milestone 1, we focused on building the front-end templates to be filled later by our back-end database. These pages include the home page, the Quest create page, and the user profile page. 

Screenshots of the template pages are found below:

* [Home Page](https://questboards.meteorapp.com):
![Front Page](/doc/home.PNG)

* [User Page](https://questboards.meteorapp.com/profile):
![User Page](/doc/user.PNG)

* [Create Quest](https://questboards.meteorapp.com/add):
![Create Quest](/doc/createQuest.png)

* [Policy](https://questboards.meteorapp.com/policy):
![Policy Page](/doc/policy.PNG)

## Mockups
* Job Board, a listing board for all available quests:
![Front Page](/doc/Front_page.png)

* User Profile, profile page to show assigned quests and skills:
![User Page](/doc/User_Page.png)

* Job Create, page to create listing for quest. Should include pay, title, deadline, description, location, contact information, and skills/resources required:
![Create Job](/doc/Create_job.png)
