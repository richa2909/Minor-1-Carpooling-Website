# Minor-Project-1--Carpooling-Website
August-November 2014

Team members (Alphabetically) :
Mridul B. Mittal, Richa Raje Yadav and Shashwat Naulakha

Mentor:
Mr. R.K. Yadav

Technologies used:
php, javaScript, html, css

Description:
This is a Social networking based website aiming to implement a carpool system, named DTUkonnect, i.e., DTU being the name of our college, connecting the students to our college in a greener way.
The website provides basic functionalities like creating an account, activation email, viewing a profile of a user, viewing the available carpools, sending requests to join/quit/cancel request to the carpool. The user can also create/delete their own carpool. Each user gets notified if a person sends a request or accepts/declines their request. A user also gets notified if the carpool he is currently a member of gets deleted.
AJAX has been used for a more dynamic end user experience and also to reduce the payload between client-server.

To launch the website:
1. Extract the folder to 'C:\wamp\www' folder.
2. Start wampserver(windows) or xampp(ubuntu).
3. Go to phpMyadmin and create a new database with the name 'carpool'.
4. Run the file tables.php to create the tables in the database.
5. Go to localhost/<foldername>/signup.php to use the website.
6. Server setting should be changed accordingly to make the mail function run in signup.php, simply remove the comments from that section if the server is configured. (commented initially)
