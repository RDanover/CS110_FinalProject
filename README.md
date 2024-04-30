# CS110 Final Project

110 Final Project Proposal
Rachel Danover, Ankita Ahluwalia, Krystal Pothilat

Project Idea:	
Rate My Study Spot at UCR: 
This website will allow users to browse various study spaces available on campus at UCR and review them based on factors such as cleanliness, quietness, capacity, food availability, and free wifi access. Users will be able to interact with other users via direct message to ask them questions about study spaces. Users will be rated based on the accuracy of their reviews by other users. 

Design Sketches:

![image](https://github.com/RDanover/CS110_FinalProject/assets/60625627/dff586a9-2edd-45ec-af42-88b4b2e2f498)


Task Allocation:
Front end development - Rachel Danover
Back end development - Ankita Ahluwalia and Krystal Pothilat
Database development - Ankita Ahluwalia and Krystal Pothilat

Team Meeting:
Team meetings will occur every Sunday from 12 - 3 pm on zoom, and we will meet every lab session in person Monday 3 - 5 pm. 

Profiling:
Users will be able to view their own profile in the settings tab and update their information there. Users will also be able to see their own accuracy rating in their profile. 

Users will also be able to view another person's profile by clicking their name on a review they have left. There the user will be able to either rate that user’s accuracy on a scale of 1-5 stars, or message them and ask them questions via direct message.

User Authentication and Authorization:
Users will be able to access the login page which will allow them to either sign in with an existing account, sign in with their google account, create a new account, or create a new account using their google account. 
A normal user will be able to change their own password, profile information, leave a review on a study space, leave a review about another user’s accuracy, and message another user. 

Social Network:
As mentioned in the profiling section users will be able to review another user’s accuracy on a scale of 1-5 stars, and be able to reach out to another user via direct message.

Rating and Commenting:
Users will be available to view all reviews for all locations. Users can respond to reviews through thumbs up/down reactions.
Users can leave their own reviews for each location. The criteria that they must rate for the location are cleanliness, quietness, and capacity. The total score (out of 5) will be calculated based on the scores for these attributes. Additionally, users can write their thoughts for the location in the review. 

Database:
The database will store the information for each location that can be reviewed. This includes location name, hours, phone number, and website.
The database will also store the reviews for each location. This includes date, cleanliness rating, quietness rating, capacity rating, overall rating, and written review.

Search and Recommendation System:
Users will be able to search through locations/reviews based on certain criteria. For locations, users can sort by overall rating, or alphabetical. They can also filter the locations by type (library, courtyard, academic building, etc), food availability, wifi availability, and overall rating.
 Users will be able to search through locations/reviews based on certain criteria. For reviews, users can sort by date (by oldest or by newest). They can also filter the reviews by rating. 
When viewing a certain location’s reviews, other study spots of similar type and rating will be recommended to the user.

Admin:
An admin user will be able to delete any user profile, change any user’s passwords, change any user’s profile information, delete/update reviews about study spaces, delete/update reviews about a user’s accuracy, and initialize/repopulate the database.

Architecture:
We will be using React, HTML5, JavaScript, and CSS3 for front-end, Node.js for back-end, and MongoDB for the database.


Tests:
We plan to have unit testing for each new feature created conducted by another member who did not implement the feature. 
We plan to have an integration test every week as a group to ensure everything is working properly. 

Ensuring Scalability and Security:
To ensure scalability we will accommodate hundreds of users.
To ensure scalability, we have to verify that we can add hundreds of data entries as well. 
To ensure security we will ensure we verify all user input to prevent cross site scripting or SQL injection attacks. 
