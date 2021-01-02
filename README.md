# C-Users-Murilo-Desktop-Tech-CCT-Mikail-Web-data-base-CA-Web-Blog-App

Report:
The web application developed is a blog app that lets you create a post, edit a post, and delete a post. For a new post the title, image link and description are inputted. The data gets saved in a database and is validated by Schema before it is transformed to HTML for client-side consumption. There’s a home page where all blog posts can be seen and a new post page. An option of “Read More” is given for editing a post or viewing a blog post in detail.  
The web app is locally hosted and can run through the command line by going to the specified folder and entering “node app.js” to get the server started. MongoDB server has to be running at the same time to manipulate the data in various ways example creation and deletion.
Technologies Used:
Express: Web framework used with node for routing and make code simpler
Body Parser is used to get data out of the form and sends data into the request body, which is then parsed by the body parser.
Mongoose: It is a package used with npm that helps in interacting with MongoDB inside of our javascript file
Express Sanitizer: This module is used for sanitisation purposes during user input. 
SemanticUI: Used for styling for making the app visually appealing and responsive
MongoDB: Database used for storing the data 
