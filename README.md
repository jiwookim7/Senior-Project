﻿# Project Name

WorldStrides Full Stack Application.

Link: https://grand-crumble-8aac30.netlify.app

## Project summary

There are several regions throughout the United States that are run by y different regional directors. However, the regional director cannot be at every event. We need staff memebers to replace this issue. The problem involves creating a system that can automate the process of assigning staff to events in as efficient a way as possible, while maintaining ease of maintenance and ease of use of the system.
In order to solve this problem, my team will create a full stack web application that can match staff members to events. One of the main objectives is to create a system that is easy to maintain after it is finished. The client does not want to need to employ a software engineer to keep the application running. Also, the system should be easy to use. It can be difficult to get staff members to fill out online forms, so any forms should be easy, quick, clear, and even fun.

The client wants to have an application that automates what he already does manually. Therefore, it will need to take input from staff members that act as parameters to match them with events. The main challenge is to automate the decision making that increases the efficiency of these
event placements. It will be necessary for our algorithm to detect when the same staff member is able to attend several events in one day or one week that are in close proximity to each other.

The application will have a streamlined decision and it will be easy to interact with. The forms will be kept minimal, but will still have options that make it engaging and enjoyable, like the option to enter preferences. The goal is to make filling out the staff availability forms an exciting experience, rather than a chore.
In order to keep it easy to maintain, the interaction required after the application is deployed will be kept to a minimum.


### One-sentence description of the project

Create a full stack web application that can match staff members to events and easy to maintable for clients.


### Additional information about the project

Our program mainly focuses on clients or stakeholders who are employees from WorldStrides. This program will help clients and stakeholders to search the available events and organize the schedule visually so that clients and stakeholders can communicate more effectively from our
program. The main request of our program is that we are going to help new employees to check their schedules visually, instead of having a conversation. Our clients and stakeholders can write the schedule and share it to other employees as well. Our algorithm will help narrow down
which school events are available or unavailable in our program so that users can communicate who is taking school events visually. Moreover, by using graph theory to match staff to events and times more efficiently. Lastly, we can save all these events in the database; and we can archive the history of school events as well.


## Installation
### Prerequisites

Web server: Node.js.
Application server: APIs.
Database : MongoDB.
Open source software: Git.

### Add-ons


Configuration: To make the program function to the user's liking, we will be implementing add event, add employess, and restricted access for information security.
Event: We will be implementing event of deleting and editing so that user can flexibly change based on their schudle. Also, we will give option to pick available event so that they can select vacancy seat in school event.
Mechanism: We will be using MongoDB to accept connections from clients and processes database actions from them. Also, we will be using React to make our webpage more prettier and Node.js to support data streaming and allowing to create both readable and writeable data streams.
API: It will be able to allow two applications to talk to each other. In our project, we will be able to communicate between website of Worldstrides and our project website.
Packaging: We will package this into two files server and client. 
Management: We will manage activities, planning, coordinating, measuring, monitoring, controlling, and reporting.






### Installation Steps

The user does not need to install anything on their machine. They only need to be able to access a popular web browser like Google Chrome, Safari, or Firefox. 
If you are going to develop the project more, you will need to:
1. Install Node.js at https://nodejs.org/en/
2. Install a text editor like Visual Studio Code (https://code.visualstudio.com/)


## Functionality

1. Navigate to the website (once it has been deployed).
2. Create a profile by clicking on Create Profile.
3. Create an event by clicking on Create Event.
4. View the Staff List by going to the homepage.
5. View the Event List page.
6. Update or delete profiles.
7. Update or delete events.
8. Create an account with a certain access level.
9. Allow users to edit their own account.
10. Match staff members to events based on availability.
11. Password restriction.
12. Upload events from a .csv file.
13. Match staff members to events based on state.
14. Select a priority ranking for staff assignments.
15. Navigate to different pages using dropdown lists in the navigation bar. 

## Known Problems

There are sometime problems with connecting to the server, which is usually related to the MongoDB Network Access settings. These can be changed by going to the MongoDB account linked with the web application.


## Contributing

TODO: Leave the steps below if you want others to contribute to your project.

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Additional Documentation

TODO: Provide links to additional documentation that may exist in the repo, e.g.,
   * [sprint_1_report.md] https://github.com/WSUCptSCapstone-Fall2022Spring2023/worldstrides-fullstackapp/blob/master/sprint_1_report.md
   * [sprint_2_report.md] https://github.com/WSUCptSCapstone-Fall2022Spring2023/worldstrides-fullstackapp/blob/master/sprint_2_report.md
   * [sprint_3_report.md] https://github.com/WSUCptSCapstone-Fall2022Spring2023/worldstrides-fullstackapp/blob/master/sprint_3_report.md
   * [sprint_1_Spring_report.md] https://github.com/WSUCptSCapstone-Fall2022Spring2023/worldstrides-fullstackapp/blob/master/sprint_1_Spring_report.md
   * [sprint_2_Spring_report.md] https://github.com/WSUCptSCapstone-Fall2022Spring2023/worldstrides-fullstackapp/blob/master/sprint_2_Spring_report.md
   * [Sprint1_Demo.md] https://github.com/WSUCptSCapstone-Fall2022Spring2023/worldstrides-fullstackapp/blob/master/sprint_1_report.md
   * [Sprint2_Demo.md] https://github.com/WSUCptSCapstone-Fall2022Spring2023/worldstrides-fullstackapp/blob/master/Sprint2_Demo.md
   * [Sprint3_Demo.md] https://github.com/WSUCptSCapstone-Fall2022Spring2023/worldstrides-fullstackapp/blob/master/Sprint3_Demo.md
   * [Sprint1_Spring_Demo.md] https://github.com/WSUCptSCapstone-Fall2022Spring2023/worldstrides-fullstackapp/blob/master/Sprint2_Spring_Demo.md

## License
MIT License

Copyright (c) 2022 WorldStrides

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
