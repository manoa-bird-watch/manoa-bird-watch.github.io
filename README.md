Software Engineering Project 2025 (ICS 314)

Project Title: Manoa Bird Watch

Our Github Organization and Repositories  
<https://github.com/orgs/manoa-bird-watch/repositories>  

Team Contract  
<https://github.com/manoa-bird-watch/manoa-bird-watch.github.io/blob/issue-09/teamcontract.md>

Members
- [Ace Reyes](https://github.com/Acezorey)
- [Alana Wesly](https://github.com/awesly)
- [Jeffrey Jian](https://github.com/jeffrey8193)
- [Chayanika Devi](https://github.com/Chayanika-Devi)

## Table of contents
1. [Deployment](#deployment)
2. [Project Proposal](#project-proposal)
3. [Overview](#overview)
4. [Approach](#approach)
5. [Features](#features)
6. [Use Case Ideas](#use-case-ideas)
7. [Beyond the Basics](#beyond-the-basics)

## Deployment
Here is the deployed application:
<https://m1-git-main-jeffrey8193s-projects.vercel.app/>

It currently features the landing page, which has a navbar with links to the sign up and sign in page, and below features some currently highlighted bird species that can be seen in Manoa.  
<img width="600px" style="border-radius: 10%;" class="rounded float-start pe-4" src="Images/manoa_bird_watch_M1.png">
<img width="600px" style="border-radius: 10%;" class="rounded float-start pe-4" src="Images/manoa_bird_watch_landing_page2_M1.png">
<img width="600px" style="border-radius: 10%;" class="rounded float-start pe-4" src="Images\manoa_bird_watch_sign_up_page_M1.png">
<img width="600px" style="border-radius: 10%;" class="rounded float-start pe-4" src="Images\manoa_bird_watch_sign_in_page_M1.png">


M1 Project and its issues can be seen here:  
<https://github.com/manoa-bird-watch/M1>  
<https://github.com/orgs/manoa-bird-watch/projects/1/views/1?layout=board>

M2 Project and its issues can be seen here:   
<https://github.com/orgs/manoa-bird-watch/projects/4>  
<https://github.com/orgs/manoa-bird-watch/projects/4/views/1>

## Design Plan for M1

- create mockups of each page 
- deploy the nextjs application template
- create the color blocked landing page 
- create the sign in / register page, which is linked in the navbar of the landing page
- create M2 project and add issues to it

## Design Plan for M2

- add four more pages:
  - birds of manoa page
  - report sightings page
  - list your sightings page
  - list all sightings page
- add user guide and developer guide to home page with updated screenshots of the pages

## User Guide 

(needs to be added still)


## Developer Guide

(needs to be added still)

## Project Proposal

<img width="600px" style="border-radius: 10%;" class="rounded float-start pe-4" src="Images\manoa_bird_watch_landing_page.png">
<img width="600px" style="border-radius: 10%;" class="rounded float-start pe-4" src="Images\manoa_bird_watch_login_page.png">
<img width="600px" style="border-radius: 10%;" class="rounded float-start pe-4" src="Images\manoa_bird_watch_report_sighting_page.png">
<img width="600px" style="border-radius: 10%;" class="rounded float-start pe-4" src="Images\manoa_bird_watch_your_sightings_page.png">

## Overview

_The problem:_ The Manoa campus is home to a diverse collection of plant and animal species, including many native to Hawaii. As a result, there are many avid bird watchers and people interested in where to find bird species, what time of day can you see these birds, and what bird species are you actually looking at. How can you find the bird you are looking for on campus reliably?

_The solution:_ Design a website to collect a list of birds and various information about them such as spotted locations, species and name, and what time of day and what part of the year can you spot them. Users can login and post information about where the birds have been spotted to better aid other bird watchers in finding them. 

## Approach

Users can create an account and update information about a bird species. Each bird species will have profile listing information about their name/species, location on campus, description, and the time of day and time of year they can be spotted on campus. Users can add information in the form of bird sightings, including location and date of the sighting. 

## Features

Our current idea is for this project to make use of 4 distinct pages: a main landing page displaying cards containing the information of different observed bird species, a login page where users can register and sign in, a “report sighting” page where users can add the birds that they have seen and the information they have of them (image, description, location etc…) to a database, and a “list sightings” page where users can see all of the birds they have seen previously, as well as add, delete, or edit past bird sightings.

Or, more simply:
- Landing page with all the birds
- User login page
- Report sighting page
- List sightings page

## Use case ideas

There are many possible use cases for this website. An initial one is, a new user going to the landing page, which is the home page, and making a new user account. Another use case is a returning user going to the landing page, which goes to the home page, signing in with their account, and navigating to the report sighting page to add information about a bird they have seen. Additionally, any user, with or without signing in, can browse the list of birds on the landing page, and a signed in user can navigate to the list sightings page and view and edit their past sightings. 

## Beyond the Basics

- Create a map that can be filtered by bird species. The map should show the bird species name, origin of the species whether it is migratory or Hawaiian bird once you click on the spotted location. 
- Add bird calls to each species
- A tracker displaying a user’s streak of how many days in a row they have reported a bird sighting, and a graph showing their rate of birds sighted over time.
