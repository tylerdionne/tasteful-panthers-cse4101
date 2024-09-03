## Tasteful Panthers: Food Recommendation at Dining Hall ##  
  
Team Members:   
Tyler Dionne (tdionne2021@my.fit.edu)   
Kendall Kelly (kelly2021@my.fit.edu)  
Braden Corkum (corkumb2013@my.fit.edu)    
  
Faculty Advisor:   
Philip Chan    
    
# First Semester  

# Goal and Motivation:  
The goal and motivation for this project is to remedy the pain of students not knowing what to eat at the campus dining hall.   
The users are unsure of what to eat when they enter the dining hall because of the fact that they lack confidence regarding the quality of their chosen meal and there is no current system in place to alleviate this pain.   

To solve this problem, our mobile application will allow users to see recommendations each and every day for the campus dining hall. This will lead to increased user satisfaction because of the fact that they will now be able to enter the campus dining hall with confidence on what they want to eat and the quality of the food.   
Given that the recommendation of the day will be based on other student reviews this will lead to an increased number of students having improved campus dining experience.  

# Approach (key features of the system):
There are five key features of the system which are as follows:
  
The diners can view personalized recommendations for each day. This feature will provide the user with a recommended meal of the day based on previous reviews they have left and/or the flavor profile the user built when creating their account. The recommendations will also be decided based on the reviews of other students that have similar flavor profiles. The purpose of this feature is to assist students in choosing a new meal to try each day. Creating personalized recommendations for each user encourages users to try new foods, improving their general experience in the dining hall and leading them to leave more reviews.      
  
The users can enter/view/search reviews. This feature will allow students to provide reviews on the campus dining hall meals each day and upload them to our mobile application where they will be processed in real time. This feature will also allow users to view/search through other students' reviews easily. In these reviews the user will be able to add stars, text, images, a link to a 30-second YouTube video, and tags. The stars will be out of five and are a way to rate how good or bad the user thought their meal was. The text will be used to describe how they felt about their meal and the images and videos will allow them to share what their food looked like. Lastly, the tags will allow for an easier experience when searching for a certain type of food. For example, a student may want to search for meals that are specifically good for studying or playing sports. The student will then be able to search for one of these tags and find all of the reviews that were marked with this specific tag. This feature is important because of the fact that the mobile app must have student reviews in order to make a recommendation of the day along with the fact that allowing the users to read and search other students reviews will increase the overall usability of the application.    
  
The user can be sent reminders via a GPS based notification system. This feature will use GPS location services on the user’s phone to know when they have entered the campus dining hall and notify them of two things: first the recommendation of the day and second a reminder to leave a review. This feature is important because it will remind the user of our mobile application when they enter the dining hall and also remind them 30 minutes after they have arrived to leave a review of their meal. Given that these notifications will be GPS based we will not bombard the user with notifications when they are not at the campus dining hall which will increase the chances of the user leaving the apps notifications on and using the recommendation/review features of our app when they are at the dining hall.  
  
The diners can participate in contests with a leader board. Each day there will be a poll where each student can guess which meal on the menu will have the highest rating tomorrow. The next day the meal with the highest rating will be revealed. There will also be top reviews of the week. There will be a theme for the week such as “good for studying” and the reviews eligible for the competition will need to be marked with this tag. At the end of the week the reviews will be judged by random users. The top three most liked reviews will be rewarded with some form of school merchandise. This feature is important because it keeps students interested as well as giving them a reason to leave more reviews. The reviews are so essential because they are what runs the entire system.  
  
The diners can suggest future meals. At the end of each week all users will be able to suggest a meal that they would like to see on the menu in the following week. The most popular meals may be added to the menu throughout that week and if they are, the staff will be able to comment on which day they will be making these meals. This will allow users to feel heard as well as encourages them to eat at the dining hall more. The more people that eat at the dining hall, the more people will leave reviews. This feature will contribute to the increase in reviews on the app, which will result in overall better quality of the app.   
  
The kitchen staff can search, view, and comment on reviews. This allows the staff to see what food is popular and which is not. By having a better idea of what their diners like they will be able to create a more appetizing menu in the future. In addition to this, staff is able to comment on any of the reviews they see. Commenting will allow staff to thank students for positive reviews and/or address any negative reviews. This feature is important because the kitchen staff cannot improve the menu or fix issues without seeing reviews and being able to comment allows the staff to build a good relationship with the diners.    
  
# Novel Features and Functionalities:  
A novel feature of our mobile application is the feedback system for kitchen staff. This is a novel feature because of the fact that this allows the kitchen staff to use the collected data (reviews) from students to make improvements.   
This feature will allow the kitchen staff to use the students' reviews to figure out the meals that students did not enjoy along with the meals that the students did enjoy so that they can make decisions for the next week accordingly. Therefore this feature is beneficial for both the students and the kitchen staff because it provides a way for the students to truly have a way of voicing their concerns with the campus dining hall along with a way for the kitchen staff to use that information to improve each week.  
    
# Algorithms and Tools:   
The first algorithm will be used to find people with similar profiles. We will be able to do this in two different ways. The first way being by their profile and the second being by their reviews. Say there are two people, one person likes sweet flavors and the other prefers spicy, these two people would not be a match. However, two people who both like spicy food would be a match. When comparing reviews we would look for if two people both reviewed the same dishes or very similar dishes. If two people both review a lot of dishes that revolve around chicken, they probably have similar tastes.   
  
The second algorithm will be used to determine what meal to suggest to an individual. We will do this by first finding someone who has similar taste and then comparing the meals we know both people have tried. For instance, say we have person one who has eaten and liked meals A, B, and C and we have person two who has eaten and liked meals B and C, but not A. Our algorithm will suggest that person two try meal A due to the similarities between the flavor profiles of person one and two.   
  
A useful tool we will use is Android Studio. None of the group members have an android phone, but the application will be an android app. We’ve chosen to remedy this by using the emulator that is a part of Android Studio. This emulator will be extremely useful when it comes to testing our application. 
  
We will also be learning to use Android SDK. This kit includes tools and libraries to make it easier to create android applications. Android SDK will be extremely useful when building this application, especially because none of our group members have done this before.   
    
Android ADB is a tool we will use to debug our application on the emulated device we will use from the command line. This tool will be extremely helpful during the testing process. 
We will need a backend framework to manage the server-side logic of the application. The backend framework will handle processing data, user requests, managing authentication, as well as handling interaction with the database. Spring Boot will most likely be used as it is in Java, but Django is another option and is in Python.
Databases will be used to store data, such as user/admin accounts, meal suggestions, reviews, and leaderboard scores. This manages the data while also making data easily retrievable. Some options for this are Firebase Firestore or MySQL.     
  
Location services are necessary for the GPS based notification system. We will need this for geofencing so we are able to tell when students are entering or leaving the dining hall. Two options for this are Google Play Services Location API or Android LocationManager.   
   
An API manager will be needed in order to design, test, and document communication between the application and backend server. This ensures that communication between the backend and the app is working smoothly. OpenAPI or Postman are good tools to use for this.  
    
A Cloud hosting service will allow us to use the backend server and database. This will ensure that the app is accessible and reliable without using physical servers. Heroku is a good service for beginners, however, we may need to use something like Google Cloud Platform for this task.  
    
# Technical Challenges:  
The first technical challenge will be understanding the Android Ecosystem. Android Studio is the most popular IDE for Android development and getting to understand the features, layout editor and emulator can be a technical challenge. A few of our team members have experience with Android emulation in applications such as Genymotion and Android Studio yet none of us are experienced with developing Android mobile applications in Android Studio.    
   
The second technical challenge will be learning Android SDK (Software Development Kit) and how to use it. Android SDK (Software Development Kit) is a collection of tools, libraries and resources provided by Google to help developers make Android applications. Another related tool that might pose a technical challenge is the Android ADB (Android Debug Bridge) which is a command line tool that allows you to debug and manage apps on real devices and emulated devices. Therefore learning these two tools may be challenging for our group given that some of us have little experience with ADB but no experience with Android SDK and both of these tools are essential to efficient mobile app development.  
  
The third technical challenge will be learning the programming languages that are used when developing Android applications. These languages include Java and Kotlin. Although all of our group members have experience coding in Java, none of our group members have any experience programming in Kotlin. In addition, although our group has experience coding in Java, learning the ins and outs of Android mobile application development in Java may pose a technical challenge.   
  
# Milestone 1 (Sep 30): Itemized Tasks:  
Compare and select technical tools for android app development environment, android app development language, libraries/modules for features in the app.   
Provide small “hello world” demo(s) to evaluate the tools for the environment, the language, and the libraries/modules.    
Resolve technical challenges 1, 2, and 3 by becoming more familiar with Android studio, Android SDK and ADB, and the language, Kotlin.   
Compare and select collaboration tools for software development, documents/presentations, communication, task calendar.  
Create Requirement Document  
Create Design Document  
Create Test Plan  

# Milestone 2 (Oct 28): Itemized Tasks:   
Implement, test, and demo diners enter/view reviews. These reviews will be stored either through replication or a centralized server. We will most likely use a centralized server.   
We will need the following in order to do this:  
Some type of backend framework such as Spring Boot in order to handle HTTP requests, process data, and communicate with the database. 
A database to store the reviews made by users  
A cloud hosting platform to host our backend framework and database.   
API management in order to ensure smooth communication between the application and backend server.   
Some type of authentication in order to ensure only authorized users can submit reviews. The purpose of doing this is to protect the integrity of the app. 
Implement, test, and demo diners searching reviews.  
Search by tags   
Implement, test, and demo kitchen staff search/view/comment on reviews.  
Search by tags  
Can comment on reviews, but cannot leave reviews.   
  
# Milestone 3 (Nov 25): Itemized Tasks:  
Implement, test, and demo personalized recommendations.  
First, consider likes and dislikes and then consider their existing reviews  
Then, match the user with other users with similar taste and compare their reviews.   
If person 1 likes meals A,B, and C and person 2 likes B and C but has not tried A, then suggest meal A.   
Implement, test, and demo GPS based notification system.  

We will need location services in order to determine where the user is.  
Possibly Android LocationManager or Google Play Services Location API  
Geofencing to define the boundaries of the specific location of the dining hall. Google Play Services can also be used for this.   
We will need a notification system to notify users before entering and after leaving the dining hall. Android NotificationManager can be used for this.   
Implement, test, and demo contests with a leader board.  

We need to implement the logic of the contest. There will be a theme for each week such as good for studying or good for working out. The more reviews, the more points you gain. The top 3 people with the most points will get some type of incentive such as school merch.   
A database to store the details of each contest.   

We will need real time data updates to automatically update the leaderboard. We could use Firebase RealTime Database for this.   
We will need a user interface in order to display the leaderboard.   
Implement, test, and demo suggesting future meals.   
A user interface will be needed in order to make it easier for users to suggest meals.   
A database to store all of the suggestions.   
An admin interface for kitchen staff to view the results.   
