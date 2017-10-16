# My Hiking Journal

#### Java unit team project for Epicodus, August 2017

#### By Esti Shay, Maria Thomas, Ryan Nunez, and Paul Guevarra

## Description

Hiking journal that allows for noting trails the user has hiked or wants to hike, and create a journal entry with notes about the trail. Incorporates widgets from REI's Hiking Project: https://www.hikingproject.com



## Setup/Installation Requirements

* Clone the repo
* Install Handlebars/Mustache plugin
* Run App.java

## Specifications

### User Class
| Description                                        | Input                                       | Output              |
| -------------------------------------------------- | -------------------------------------------:| ------------------: |
| Create a new team object | team details | add new team to list |
|  create user object and assign an ID  |  user details  |  assign ID number  |
|  search member by ID number  |  ID# 1  |  User Ryan  |
|  get a list of all users created  |  get all users  |  Ryan, Esti, Maria, Paul  |
|  update changes to a user name  |  ID# 1 "Ryan"  to "Kim"  |  ID# "Kim"  |
|  delete user by id  |  delete ID# 2 Paul  |  Users list: ID# 1 Ryan, ID# 3 Esti  |
|  delete all users  |  delete all users  |  no users found  |



### Journal Class
| Description                                        | Input                                       | Output              |
| -------------------------------------------------- | -------------------------------------------:| ------------------: |
|  create journal entry object and assign an ID  |  first journal entry details  |  assign ID#1 to journal entry object  |
|  search journal by ID number  |  ID# 2  |  journal entry #2  |
|  get a list of all journals created  |  get all journals  |  Journal #1, Journal #2, Journal #3  |
|  find journal entry by trail ID property  |  trail ID#3  |  journal #6 trail ID#3 "Details"  |
|  find journal entry by trail and user properties  |  trail ID# 3, user ID# 5  |  User ID# 5 Trail ID#3 Notes: "details"  |
|  update journal entry properties  |  "new content"  |  notes: the journey was "new content".  |
|  delete journal by id  |  delete journal entry ID# 2  |  all journals list: ID# 1, ID# 3  |
|  delete journal by trail ID#  |  trail ID#2  |  all journals list:  Journal ID# 1 Trail ID# 3, Journal ID# 2 Trail ID# 1, Journal ID# 4 Trail ID# 1,  |
|  delete all journals  |  delete all journals  |  no journals found  |


### Trail Class
| Description                                        | Input                                       | Output              |
| -------------------------------------------------- | -------------------------------------------:| ------------------: |
|  create trail entry object and assign an ID  |  first trail entry details  |  assign ID#1 to trail entry object  |
|  search trail by ID number  |  ID# 2  |  trail entry #2  |
|  get a list of all trails created  |  get all trails  |  trail #1, trail #2, trail #3  |
|  update trail entry properties  |  "new content"  |  location: "new content"  |
|  delete trail by id  |  delete trail entry ID# 2  |  all trails list: ID# 1, ID# 3  |

## Design
![Homepage screenshot](/src/main/resources/public/images/971HikeHomepage.jpg "Hompage")

![Find a trail screenshot](/src/main/resources/public/images/971HikeAddPage.jpg "Add a new trail to your trail diary, screenshot")

![Surprise Me screenshot](/src/main/resources/public/images/971HikeSurpriseMeAddPage.jpg "Random trail generator version of the add trail page")

![Trail list screenshot](/src/main/resources/public/images/971HikeTrailListPage.jpg "List of your saved trails")

![Trail diary screenshot](/src/main/resources/public/images/971HikeTrailLogPage.jpg "Example trail diary with all the user's data and reviews")


## Technologies Used

Java, Spark, SQL, H2, JSON, GSON, written in IntelliJ

### License

Licensed under GPL

Copyright &copy; 2017 Esti Shay, Maria Thomas, Ryan Nunez, and Paul Guevarra
