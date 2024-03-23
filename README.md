[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/0wrsx4Jb)
# Topic : Barter System
Project Summary:
The aim of this project is to create a web application that enables users to trade goods and services without any payments. The application will use the MERN stack (MongoDB, Express.js, React.js, Node.js) and will have a user-friendly interface and a secure database.

Project Complexity:
This project is moderately complex as it involves developing both front-end and back-end functionalities, as well as integrating with external APIs for authentication. The project will also require testing and debugging to ensure quality and performance.

Project Features:
The main features of the application are:
User registration and login using email or social media accounts
User profile creation and editing
Goods and services listing and browsing
Haves and needs matching and filtering
Trade negotiation and confirmation
Trade feedback and rating
Loops creation and joining for group trading and chatting

APIs to be used - (subject to change/add)
Authentication 
JSON Web Token - JWT and express middleware or AuthO
Cloudinery - upload images on cloud
Mail gun - email receipts
PayOrders - paypal and stripe
Maps - Google Map
Twilio Programmable Chat
Deploy on MongoDb


## Team members: 
1. Ritvik Paramkusham
2. Vraj Reshamdalal
3. Ishita Janwale
4. Preksha Yadav

## Milestones:
- M1 - Story1, Story 2
- M2 - Story3, Story 4
- M3 - Story5, Story 6


## User Stories:

1. Story 1: As a user I should be able to register/ login.

    Acceptance Criteria : 

    - Users should be able to register themselves 

    - Users should be able to verify themselves using Email/Mobile Phone

    - Registered user should be able to login themselves using a valid password, email 


    Priority: High

2. Story 2: After logging in a user should see a landing page where they will be able to  enter their respective  haves and/or needs.

    Acceptance Criteria:

    - Must create a navbar for user to navigate through the applications
    - User must be able to successfully enter haves
    - User must be able to successfully enter needs


    Priority: High

3. Story 3 : After logging in a user should be able to see the feeds, where all the haves and needs will be displayed.

    Acceptance Criteria:
    - Users must be able to see latest haves and needs

    - Users must be able to see past haves and needs.

    Priority : Medium

3. Story 4:
    Creating loops - 
    A user(admin) with a have/need will be able to create a loop. Loop is a group where admin will be able to accept users to join for trade in. A loop can have different status
    - Open - users can be join 
    - Committed - when a trade in is about to happen - users cannot join anymore
    - Closed - trade in is completed
    
    Acceptance Criteria:

    Priority : High


5. Story 5 : View User Profile and read notifications in Inbox

    Acceptance Criteria:
    - A user must be able to see his/her profile page and edit it.
    - A user must get notifications
    - A user must be able to reply to the messages in Inbox.
    - A user must be able to log out of the web application

    
    Priority: Mediums	


6. Story 6: Bug fixes and Enhancements

    Acceptance Criteria:
    - Identified bugs must be fixed
    - U/UX can be enhanced as required

    Priority: Low

## Assigning stories to team members :
- Ishita : Story 1
- Ritvik : Story 2
- Vraj : Story 3
- Preksha : Story 4
- Ishita and Ritvik : Story 5
- Vraj and Preksha : Story 6

## Domain Model :

![Domain Model](images/diagram-domain-driven.jpeg)
